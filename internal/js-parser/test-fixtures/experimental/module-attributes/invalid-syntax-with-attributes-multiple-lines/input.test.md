# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > module-attributes > invalid-syntax-with-attributes-multiple-lines`

### `ast`

```javascript
JSRoot {
	body: [
		JSImportDeclaration {
			namedSpecifiers: []
			source: JSStringLiteral {
				value: "x"
				loc: SourceLocation experimental/module-attributes/invalid-syntax-with-attributes-multiple-lines/input.js 1:7-1:10
			}
			loc: SourceLocation experimental/module-attributes/invalid-syntax-with-attributes-multiple-lines/input.js 1:0-1:10
		}
		JSWithStatement {
			body: JSExpressionStatement {
				expression: JSReferenceIdentifier {
					name: "INVALID_PLACEHOLDER"
					loc: SourceLocation experimental/module-attributes/invalid-syntax-with-attributes-multiple-lines/input.js 2:4-2:5
				}
				loc: SourceLocation experimental/module-attributes/invalid-syntax-with-attributes-multiple-lines/input.js 2:4-2:5
			}
			object: JSReferenceIdentifier {
				name: "type"
				loc: SourceLocation experimental/module-attributes/invalid-syntax-with-attributes-multiple-lines/input.js 2:0-2:4 (type)
			}
			loc: SourceLocation experimental/module-attributes/invalid-syntax-with-attributes-multiple-lines/input.js 1:11-2:5
		}
		JSExpressionStatement {
			expression: JSStringLiteral {
				value: "json"
				loc: SourceLocation experimental/module-attributes/invalid-syntax-with-attributes-multiple-lines/input.js 2:6-2:12
			}
			loc: SourceLocation experimental/module-attributes/invalid-syntax-with-attributes-multiple-lines/input.js 2:6-2:12
		}
	]
	comments: []
	corrupt: true
	diagnostics: [
		{
			origins: [{entity: "ParserCore<js>"}]
			description: {
				advice: []
				category: ["parse"]
				categoryValue: "js"
				message: RAW_MARKUP {value: "Expected a semicolon or a line terminator"}
			}
			location: {
				language: "js"
				path: UIDPath<experimental/module-attributes/invalid-syntax-with-attributes-multiple-lines/input.js>
				end: Position 1:11
				start: Position 1:11
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<experimental/module-attributes/invalid-syntax-with-attributes-multiple-lines/input.js>
	loc: SourceLocation experimental/module-attributes/invalid-syntax-with-attributes-multiple-lines/input.js 1:0-3:0
}
```

### `diagnostics`

```

 experimental/module-attributes/invalid-syntax-with-attributes-multiple-lines/input.js:1:11
parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Expected a semicolon or a line terminator

  > 1 │ import "x" with
      │            ^
    2 │ type: "json"


```
