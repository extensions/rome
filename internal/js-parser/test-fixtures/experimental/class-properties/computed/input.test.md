# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > class-properties > computed`

### `ast`

```javascript
JSRoot {
	body: [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "Foo"
				loc: SourceLocation experimental/class-properties/computed/input.js 1:6-1:9 (Foo)
			}
			meta: JSClassHead {
				body: [
					JSClassProperty {
						key: JSComputedPropertyKey {
							value: JSReferenceIdentifier {
								name: "x"
								loc: SourceLocation experimental/class-properties/computed/input.js 2:3-2:4 (x)
							}
							loc: SourceLocation experimental/class-properties/computed/input.js 2:2-2:5
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation experimental/class-properties/computed/input.js 2:2-2:5
							start: Position 2:2
						}
						loc: SourceLocation experimental/class-properties/computed/input.js 2:2-2:5
					}
					JSClassProperty {
						key: JSComputedPropertyKey {
							value: JSStringLiteral {
								value: "y"
								loc: SourceLocation experimental/class-properties/computed/input.js 3:3-3:6
							}
							loc: SourceLocation experimental/class-properties/computed/input.js 3:2-3:7
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation experimental/class-properties/computed/input.js 3:2-3:7
							start: Position 3:2
						}
						loc: SourceLocation experimental/class-properties/computed/input.js 3:2-3:7
					}
				]
				loc: SourceLocation experimental/class-properties/computed/input.js 1:0-4:1
			}
			loc: SourceLocation experimental/class-properties/computed/input.js 1:0-4:1
		}
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "Foo2"
				loc: SourceLocation experimental/class-properties/computed/input.js 6:6-6:10 (Foo2)
			}
			meta: JSClassHead {
				body: [
					JSClassProperty {
						key: JSComputedPropertyKey {
							value: JSReferenceIdentifier {
								name: "p"
								loc: SourceLocation experimental/class-properties/computed/input.js 7:3-7:4 (p)
							}
							loc: SourceLocation experimental/class-properties/computed/input.js 7:2-7:5
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation experimental/class-properties/computed/input.js 7:2-7:5
							start: Position 7:2
						}
						loc: SourceLocation experimental/class-properties/computed/input.js 7:2-7:5
					}
					JSClassMethod {
						kind: "method"
						key: JSComputedPropertyKey {
							value: JSReferenceIdentifier {
								name: "m"
								loc: SourceLocation experimental/class-properties/computed/input.js 8:3-8:4 (m)
							}
							loc: SourceLocation experimental/class-properties/computed/input.js 8:2-8:5
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation experimental/class-properties/computed/input.js 8:2-8:5
							start: Position 8:2
						}
						body: JSBlockStatement {
							body: []
							directives: []
							loc: SourceLocation experimental/class-properties/computed/input.js 8:9-8:11
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: []
							loc: SourceLocation experimental/class-properties/computed/input.js 8:6-8:8
						}
						loc: SourceLocation experimental/class-properties/computed/input.js 8:2-8:11
					}
				]
				loc: SourceLocation experimental/class-properties/computed/input.js 6:0-9:1
			}
			loc: SourceLocation experimental/class-properties/computed/input.js 6:0-9:1
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<experimental/class-properties/computed/input.js>
	loc: SourceLocation experimental/class-properties/computed/input.js 1:0-10:0
}
```

### `diagnostics`

```

```
