# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > class-private-names-duplicated > static-field-static-method`

### `ast`

```javascript
JSRoot {
	body: [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "A"
				loc: SourceLocation experimental/class-private-names-duplicated/static-field-static-method/input.js 1:6-1:7 (A)
			}
			meta: JSClassHead {
				body: [
					JSClassPrivateProperty {
						key: JSPrivateName {
							id: JSIdentifier {
								name: "x"
								loc: SourceLocation experimental/class-private-names-duplicated/static-field-static-method/input.js 2:10-2:11 (x)
							}
							loc: SourceLocation experimental/class-private-names-duplicated/static-field-static-method/input.js 2:9-2:11
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: true
							loc: SourceLocation experimental/class-private-names-duplicated/static-field-static-method/input.js 2:2-2:11
							start: Position 2:2
						}
						value: JSNumericLiteral {
							value: 0
							loc: SourceLocation experimental/class-private-names-duplicated/static-field-static-method/input.js 2:14-2:15
						}
						loc: SourceLocation experimental/class-private-names-duplicated/static-field-static-method/input.js 2:2-2:16
					}
					JSClassPrivateMethod {
						kind: "method"
						key: JSPrivateName {
							id: JSIdentifier {
								name: "x"
								loc: SourceLocation experimental/class-private-names-duplicated/static-field-static-method/input.js 3:10-3:11 (x)
							}
							loc: SourceLocation experimental/class-private-names-duplicated/static-field-static-method/input.js 3:9-3:11
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: true
							loc: SourceLocation experimental/class-private-names-duplicated/static-field-static-method/input.js 3:2-3:11
							start: Position 3:2
						}
						body: JSBlockStatement {
							body: []
							directives: []
							loc: SourceLocation experimental/class-private-names-duplicated/static-field-static-method/input.js 3:14-3:16
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: []
							loc: SourceLocation experimental/class-private-names-duplicated/static-field-static-method/input.js 3:11-3:13
						}
						loc: SourceLocation experimental/class-private-names-duplicated/static-field-static-method/input.js 3:2-3:16
					}
				]
				loc: SourceLocation experimental/class-private-names-duplicated/static-field-static-method/input.js 1:0-4:1
			}
			loc: SourceLocation experimental/class-private-names-duplicated/static-field-static-method/input.js 1:0-4:1
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<experimental/class-private-names-duplicated/static-field-static-method/input.js>
	loc: SourceLocation experimental/class-private-names-duplicated/static-field-static-method/input.js 1:0-4:1
}
```

### `diagnostics`

```

```
