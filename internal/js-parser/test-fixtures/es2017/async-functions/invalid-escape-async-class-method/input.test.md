# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2017 > async-functions > invalid-escape-async-class-method`

### `ast`

```javascript
JSRoot {
	body: [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "X"
				loc: SourceLocation es2017/async-functions/invalid-escape-async-class-method/input.js 1:6-1:7 (X)
			}
			meta: JSClassHead {
				body: [
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "x"
								loc: SourceLocation es2017/async-functions/invalid-escape-async-class-method/input.js 1:21-1:22 (x)
							}
							loc: SourceLocation es2017/async-functions/invalid-escape-async-class-method/input.js 1:21-1:22
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation es2017/async-functions/invalid-escape-async-class-method/input.js 1:10-1:22
							start: Position 1:10
						}
						body: JSBlockStatement {
							body: [
								JSExpressionStatement {
									expression: JSAwaitExpression {
										argument: JSReferenceIdentifier {
											name: "x"
											loc: SourceLocation es2017/async-functions/invalid-escape-async-class-method/input.js 1:33-1:34 (x)
										}
										loc: SourceLocation es2017/async-functions/invalid-escape-async-class-method/input.js 1:27-1:34
									}
									loc: SourceLocation es2017/async-functions/invalid-escape-async-class-method/input.js 1:27-1:34
								}
							]
							directives: []
							loc: SourceLocation es2017/async-functions/invalid-escape-async-class-method/input.js 1:25-1:36
						}
						head: JSFunctionHead {
							async: true
							generator: false
							hasHoistedVars: false
							params: []
							loc: SourceLocation es2017/async-functions/invalid-escape-async-class-method/input.js 1:22-1:24
						}
						loc: SourceLocation es2017/async-functions/invalid-escape-async-class-method/input.js 1:10-1:36
					}
				]
				loc: SourceLocation es2017/async-functions/invalid-escape-async-class-method/input.js 1:0-1:38
			}
			loc: SourceLocation es2017/async-functions/invalid-escape-async-class-method/input.js 1:0-1:38
		}
	]
	comments: []
	corrupt: false
	diagnostics: [
		{
			origins: [{entity: "ParserCore<js>"}]
			description: {
				advice: []
				category: ["parse"]
				categoryValue: "js"
				message: [RAW_MARKUP {value: "<emphasis>"}, "async", RAW_MARKUP {value: "</emphasis> can't contain a unicode escape"}]
			}
			location: {
				language: "js"
				path: UIDPath<es2017/async-functions/invalid-escape-async-class-method/input.js>
				end: Position 1:10
				start: Position 1:10
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<es2017/async-functions/invalid-escape-async-class-method/input.js>
	loc: SourceLocation es2017/async-functions/invalid-escape-async-class-method/input.js 1:0-2:0
}
```

### `diagnostics`

```

 es2017/async-functions/invalid-escape-async-class-method/input.js:1:10 parse(js) ━━━━━━━━━━━━━━━━━━

  ✖ async can't contain a unicode escape

    class X { \u0061sync x() { await x } }
              ^


```
