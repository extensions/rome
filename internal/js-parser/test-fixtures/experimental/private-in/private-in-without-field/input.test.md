# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > private-in > private-in-without-field`

### `ast`

```javascript
JSRoot {
	body: [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "Foo"
				loc: SourceLocation experimental/private-in/private-in-without-field/input.js 1:6-1:9 (Foo)
			}
			meta: JSClassHead {
				body: [
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "test"
								loc: SourceLocation experimental/private-in/private-in-without-field/input.js 2:2-2:6 (test)
							}
							loc: SourceLocation experimental/private-in/private-in-without-field/input.js 2:2-2:6
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation experimental/private-in/private-in-without-field/input.js 2:2-2:6
							start: Position 2:2
						}
						body: JSBlockStatement {
							body: [
								JSExpressionStatement {
									expression: JSReferenceIdentifier {
										name: "INVALID_PLACEHOLDER"
										loc: SourceLocation experimental/private-in/private-in-without-field/input.js 3:4-3:5
									}
									loc: SourceLocation experimental/private-in/private-in-without-field/input.js 3:4-3:5
								}
								JSExpressionStatement {
									expression: JSBinaryExpression {
										operator: "in"
										left: JSReferenceIdentifier {
											name: "x"
											loc: SourceLocation experimental/private-in/private-in-without-field/input.js 3:5-3:6 (x)
										}
										right: JSObjectExpression {
											properties: []
											loc: SourceLocation experimental/private-in/private-in-without-field/input.js 3:10-3:12
										}
										loc: SourceLocation experimental/private-in/private-in-without-field/input.js 3:5-3:12
									}
									loc: SourceLocation experimental/private-in/private-in-without-field/input.js 3:5-3:13
								}
							]
							directives: []
							loc: SourceLocation experimental/private-in/private-in-without-field/input.js 2:9-4:3
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: []
							loc: SourceLocation experimental/private-in/private-in-without-field/input.js 2:6-2:8
						}
						loc: SourceLocation experimental/private-in/private-in-without-field/input.js 2:2-4:3
					}
				]
				loc: SourceLocation experimental/private-in/private-in-without-field/input.js 1:0-5:1
			}
			loc: SourceLocation experimental/private-in/private-in-without-field/input.js 1:0-5:1
		}
	]
	comments: []
	corrupt: true
	diagnostics: [
		{
			origins: [{entity: "ParserCore<js>"}]
			description: {advice: [], category: ["parse"], categoryValue: "js", message: [RAW_MARKUP {value: "Unknown start to an "}, "statement expression"]}
			location: {
				language: "js"
				path: UIDPath<experimental/private-in/private-in-without-field/input.js>
				end: Position 3:4
				start: Position 3:4
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<experimental/private-in/private-in-without-field/input.js>
	loc: SourceLocation experimental/private-in/private-in-without-field/input.js 1:0-6:0
}
```

### `diagnostics`

```

 experimental/private-in/private-in-without-field/input.js:3:4 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unknown start to an statement expression

    1 │ class Foo {
    2 │   test() {
  > 3 │     #x in {};
      │     ^
    4 │   }
    5 │ }


```
