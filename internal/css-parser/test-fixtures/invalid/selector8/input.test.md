# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/css-parser/index.test.ts --update-snapshots` to update.

## `invalid > selector8`

### `ast`

```javascript
CSSRoot {
	body: [
		CSSRule {
			prelude: [
				CSSSelector {
					patterns: []
					loc: SourceLocation invalid/selector8/input.css 1:0-1:6
				}
			]
			block: CSSBlock {
				value: []
				startingTokenValue: "{"
				loc: SourceLocation invalid/selector8/input.css 1:6-3:1
			}
			loc: SourceLocation invalid/selector8/input.css 1:0-3:1
		}
	]
	comments: []
	corrupt: false
	diagnostics: [
		{
			origins: [{entity: "ParserCore<css>"}]
			description: {
				advice: []
				category: ["parse"]
				categoryValue: "css"
				message: RAW_MARKUP {value: "Expected the use of an identifier after <emphasis>#</emphasis>."}
			}
			location: {
				language: "css"
				path: UIDPath<invalid/selector8/input.css>
				end: Position 1:5
				start: Position 1:0
			}
		}
	]
	path: UIDPath<invalid/selector8/input.css>
	loc: SourceLocation invalid/selector8/input.css 1:0-3:1
}
```

### `diagnostics`

```

 invalid/selector8/input.css:1 parse(css) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Expected the use of an identifier after #.

  > 1 │ #1234 {
      │ ^^^^^
    2 │
    3 │ }


```
