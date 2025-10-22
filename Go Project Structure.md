https://medium.com/@smart_byte_labs/organize-like-a-pro-a-simple-guide-to-go-project-folder-structures-e85e9c1769c2

``` shell
go mod init github.com/MakariiSlupskyi/simple-crud

```


## Domain-Driven Design

```
project  
├── cmd # Command-related files  
│   └── app # Application entry point  
│       └── main.go # Main application logic  
├── internal # Internal codebase  
│   ├── user # Domain 'user'  
│   │   ├── handler.go # User-specific handler  
│   │   ├── service.go # User-specific service  
│   │   ├── repository.go # User-specific repository  
│   │   └── user.go # User model  
│   └── product # Domain 'product'  
│       ├── handler.go # Product-specific handler  
│       ├── service.go # Product-specific service  
│       └── repository.go # Product-specific repository  
├── pkg # Shared utilities  
├── configs # Configuration files  
├── go.mod # Go module definition  
└── go.sum # Go module checksum file
```

---

## Modular Structure

Best for microservices

```
project/  
├── user_module/ # User module  
│   ├── handler/ # Handlers for user-related requests  
│   ├── service/ # Business logic for user operations  
│   ├── repository/ # Data access layer for user data  
│   ├── user.go # User model definition  
│   ├── go.mod # User module Go module definition  
│   └── go.sum # User module Go module checksum file  
├── product_module/ # Product module  
│   ├── handler/ # Handlers for product-related requests  
│   ├── service/ # Business logic for product operations  
│   ├── repository/ # Data access layer for product data  
│   ├── product.go # Product model definition  
│   ├── go.mod # Product module Go module definition  
│   └── go.sum # Product module Go module checksum file  
├── api_gateway/ # API gateway to manage different services  
│   ├── main.go # Main entry point for API gateway  
│   ├── go.mod # API gateway Go module definition  
│   └── go.sum # API gateway Go module checksum file  
└── configs/ # Shared configuration files
```
