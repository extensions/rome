# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > class > invalid-escape-static`

### `ast`

```javascript
JSRoot {
	body: [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "X"
				loc: SourceLocation es2015/class/invalid-escape-static/input.js 1:6-1:7 (X)
			}
			meta: JSClassHead {
				body: [
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "y"
								loc: SourceLocation es2015/class/invalid-escape-static/input.js 1:22-1:23 (y)
							}
							loc: SourceLocation es2015/class/invalid-escape-static/input.js 1:22-1:23
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: true
							loc: SourceLocation es2015/class/invalid-escape-static/input.js 1:10-1:23
							start: Position 1:10
						}
						body: JSBlockStatement {
							body: []
							directives: []
							loc: SourceLocation es2015/class/invalid-escape-static/input.js 1:26-1:28
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: []
							loc: SourceLocation es2015/class/invalid-escape-static/input.js 1:23-1:25
						}
						loc: SourceLocation es2015/class/invalid-escape-static/input.js 1:10-1:28
					}
				]
				loc: SourceLocation es2015/class/invalid-escape-static/input.js 1:0-1:30
			}
			loc: SourceLocation es2015/class/invalid-escape-static/input.js 1:0-1:30
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
				message: [RAW_MARKUP {value: "<emphasis>"}, "static", RAW_MARKUP {value: "</emphasis> can't contain a unicode escape"}]
			}
			location: {
				language: "js"
				path: UIDPath<es2015/class/invalid-escape-static/input.js>
				end: Position 1:12
				start: Position 1:12
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<es2015/class/invalid-escape-static/input.js>
	loc: SourceLocation es2015/class/invalid-escape-static/input.js 1:0-2:0
}
```

### `diagnostics`

```

 es2015/class/invalid-escape-static/input.js:1:12 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ static can't contain a unicode escape

    class X { st\u0061tic y() {} }
                ^


```
