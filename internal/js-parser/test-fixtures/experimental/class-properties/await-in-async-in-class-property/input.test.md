# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > class-properties > await-in-async-in-class-property`

### `ast`

```javascript
JSRoot {
	body: [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "C"
				loc: SourceLocation experimental/class-properties/await-in-async-in-class-property/input.js 1:6-1:7 (C)
			}
			meta: JSClassHead {
				body: [
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "p"
								loc: SourceLocation experimental/class-properties/await-in-async-in-class-property/input.js 2:2-2:3 (p)
							}
							loc: SourceLocation experimental/class-properties/await-in-async-in-class-property/input.js 2:2-2:3
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation experimental/class-properties/await-in-async-in-class-property/input.js 2:2-2:3
							start: Position 2:2
						}
						value: JSArrowFunctionExpression {
							body: JSAwaitExpression {
								argument: JSUnaryExpression {
									operator: "+"
									prefix: true
									argument: JSNumericLiteral {
										value: 42
										loc: SourceLocation experimental/class-properties/await-in-async-in-class-property/input.js 2:26-2:28
									}
									loc: SourceLocation experimental/class-properties/await-in-async-in-class-property/input.js 2:24-2:28
								}
								loc: SourceLocation experimental/class-properties/await-in-async-in-class-property/input.js 2:18-2:28
							}
							head: JSFunctionHead {
								async: true
								hasHoistedVars: false
								params: []
								loc: SourceLocation experimental/class-properties/await-in-async-in-class-property/input.js 2:6-2:17
							}
							loc: SourceLocation experimental/class-properties/await-in-async-in-class-property/input.js 2:6-2:28
						}
						loc: SourceLocation experimental/class-properties/await-in-async-in-class-property/input.js 2:2-2:29
					}
				]
				loc: SourceLocation experimental/class-properties/await-in-async-in-class-property/input.js 1:0-3:1
			}
			loc: SourceLocation experimental/class-properties/await-in-async-in-class-property/input.js 1:0-3:1
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<experimental/class-properties/await-in-async-in-class-property/input.js>
	loc: SourceLocation experimental/class-properties/await-in-async-in-class-property/input.js 1:0-4:0
}
```

### `diagnostics`

```

```
