# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 438`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			expression: JSReferenceIdentifier {
				name: "INVALID_PLACEHOLDER"
				loc: SourceLocation core/uncategorised/438/input.js 2:0-2:1
			}
			loc: SourceLocation core/uncategorised/438/input.js 2:0-2:1
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
				path: UIDPath<core/uncategorised/438/input.js>
				end: Position 2:0
				start: Position 2:0
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<core/uncategorised/438/input.js>
	loc: SourceLocation core/uncategorised/438/input.js 1:0-2:1
}
```

### `diagnostics`

```

 core/uncategorised/438/input.js:2 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unknown start to an statement expression

    ]
    ^


```
