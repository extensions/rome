# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > yield > function-name-generator-method`

### `ast`

```javascript
JSRoot {
	body: [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "A"
				loc: SourceLocation es2015/yield/function-name-generator-method/input.js 1:6-1:7 (A)
			}
			meta: JSClassHead {
				body: [
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "yield"
								loc: SourceLocation es2015/yield/function-name-generator-method/input.js 2:3-2:8 (yield)
							}
							loc: SourceLocation es2015/yield/function-name-generator-method/input.js 2:3-2:8
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation es2015/yield/function-name-generator-method/input.js 2:2-2:8
							start: Position 2:2
						}
						body: JSBlockStatement {
							body: []
							directives: []
							loc: SourceLocation es2015/yield/function-name-generator-method/input.js 2:11-2:13
						}
						head: JSFunctionHead {
							async: false
							generator: true
							hasHoistedVars: false
							params: []
							loc: SourceLocation es2015/yield/function-name-generator-method/input.js 2:8-2:10
						}
						loc: SourceLocation es2015/yield/function-name-generator-method/input.js 2:2-2:13
					}
				]
				loc: SourceLocation es2015/yield/function-name-generator-method/input.js 1:0-3:1
			}
			loc: SourceLocation es2015/yield/function-name-generator-method/input.js 1:0-3:1
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<es2015/yield/function-name-generator-method/input.js>
	loc: SourceLocation es2015/yield/function-name-generator-method/input.js 1:0-3:1
}
```

### `diagnostics`

```

```
