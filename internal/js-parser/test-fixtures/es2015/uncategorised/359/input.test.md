# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 359`

### `ast`

```javascript
JSRoot {
	body: [
		JSVariableDeclarationStatement {
			declaration: JSVariableDeclaration {
				kind: "const"
				declarations: [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "await"
							loc: SourceLocation es2015/uncategorised/359/input.js 1:6-1:11 (await)
						}
						init: JSCallExpression {
							arguments: []
							callee: JSReferenceIdentifier {
								name: "foo"
								loc: SourceLocation es2015/uncategorised/359/input.js 1:14-1:17 (foo)
							}
							loc: SourceLocation es2015/uncategorised/359/input.js 1:14-1:19
						}
						loc: SourceLocation es2015/uncategorised/359/input.js 1:6-1:19
					}
				]
				loc: SourceLocation es2015/uncategorised/359/input.js 1:0-1:20
			}
			loc: SourceLocation es2015/uncategorised/359/input.js 1:0-1:20
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<es2015/uncategorised/359/input.js>
	loc: SourceLocation es2015/uncategorised/359/input.js 1:0-2:0
}
```

### `diagnostics`

```

```
