# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > class-private-names-duplicated > instance-get-static-set`

### `ast`

```javascript
JSRoot {
	body: [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "A"
				loc: SourceLocation experimental/class-private-names-duplicated/instance-get-static-set/input.js 1:6-1:7 (A)
			}
			meta: JSClassHead {
				body: [
					JSClassPrivateMethod {
						kind: "get"
						key: JSPrivateName {
							id: JSIdentifier {
								name: "x"
								loc: SourceLocation experimental/class-private-names-duplicated/instance-get-static-set/input.js 2:7-2:8 (x)
							}
							loc: SourceLocation experimental/class-private-names-duplicated/instance-get-static-set/input.js 2:6-2:8
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation experimental/class-private-names-duplicated/instance-get-static-set/input.js 2:2-2:8
							start: Position 2:2
						}
						body: JSBlockStatement {
							body: []
							directives: []
							loc: SourceLocation experimental/class-private-names-duplicated/instance-get-static-set/input.js 2:11-2:13
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: []
							loc: SourceLocation experimental/class-private-names-duplicated/instance-get-static-set/input.js 2:8-2:10
						}
						loc: SourceLocation experimental/class-private-names-duplicated/instance-get-static-set/input.js 2:2-2:13
					}
					JSClassPrivateMethod {
						kind: "set"
						key: JSPrivateName {
							id: JSIdentifier {
								name: "x"
								loc: SourceLocation experimental/class-private-names-duplicated/instance-get-static-set/input.js 3:14-3:15 (x)
							}
							loc: SourceLocation experimental/class-private-names-duplicated/instance-get-static-set/input.js 3:13-3:15
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: true
							loc: SourceLocation experimental/class-private-names-duplicated/instance-get-static-set/input.js 3:2-3:15
							start: Position 3:2
						}
						body: JSBlockStatement {
							body: []
							directives: []
							loc: SourceLocation experimental/class-private-names-duplicated/instance-get-static-set/input.js 3:19-3:21
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: [
								JSBindingIdentifier {
									name: "_"
									meta: JSPatternMeta {
										loc: SourceLocation experimental/class-private-names-duplicated/instance-get-static-set/input.js 3:16-3:17
									}
									loc: SourceLocation experimental/class-private-names-duplicated/instance-get-static-set/input.js 3:16-3:17 (_)
								}
							]
							loc: SourceLocation experimental/class-private-names-duplicated/instance-get-static-set/input.js 3:15-3:18
						}
						loc: SourceLocation experimental/class-private-names-duplicated/instance-get-static-set/input.js 3:2-3:21
					}
				]
				loc: SourceLocation experimental/class-private-names-duplicated/instance-get-static-set/input.js 1:0-4:1
			}
			loc: SourceLocation experimental/class-private-names-duplicated/instance-get-static-set/input.js 1:0-4:1
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<experimental/class-private-names-duplicated/instance-get-static-set/input.js>
	loc: SourceLocation experimental/class-private-names-duplicated/instance-get-static-set/input.js 1:0-4:1
}
```

### `diagnostics`

```

```
