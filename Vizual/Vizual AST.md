
Three main classes:
- expressions
- statements
- declarations

Expression is a tree of:
- ident
- bacisLit
- funcLit
- compositeLit
- parenExpr
- unaryExpr
- binaryExpr

Type is a tree of:
- arrayType
- funcType

---
## Counter AST

``` yaml
block:
	style:
		color
		border
		borderColor
		rounded
	align:
		padding
		margin
		dir
		main
		cross
		wrap?
		reverse?
	logic:
		showIf
		loopFor
		onClick
		onHover


page:
	name: Counter
	state:
		- count:
			  type: number
			  val: 0
	align:
		dir: col
		cross: center
	children:
		- text:
			val:
				ident: count
		- block:
			children:
				- block:
					logic:
						
					children:
						- text:
							val: +
				- comp:
					type: button
					text: +
					action: funcLit
```

``` TypeScript
interface Block {
	
}
```