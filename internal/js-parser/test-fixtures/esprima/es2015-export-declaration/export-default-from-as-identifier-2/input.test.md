# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-export-declaration > export-default-from-as-identifier-2`

### `ast`

```javascript
JSRoot {
	body: [
		JSExportDefaultDeclaration {
			declaration: JSCallExpression {
				arguments: [
					JSReferenceIdentifier {
						name: "bar"
						loc: SourceLocation esprima/es2015-export-declaration/export-default-from-as-identifier-2/input.js 1:21-1:24 (bar)
					}
				]
				callee: JSReferenceIdentifier {
					name: "from"
					loc: SourceLocation esprima/es2015-export-declaration/export-default-from-as-identifier-2/input.js 1:15-1:19 (from)
				}
				loc: SourceLocation esprima/es2015-export-declaration/export-default-from-as-identifier-2/input.js 1:15-1:25
			}
			loc: SourceLocation esprima/es2015-export-declaration/export-default-from-as-identifier-2/input.js 1:0-1:26
		}
	]
	comments: []
	corrupt: false
	diagnostics: [
		{
			origins: [{entity: "ParserCore<js>"}]
			description: {
				advice: [
					log {
						category: "info"
						text: RAW_MARKUP {value: "Change the extension to <emphasis>.mjs</emphasis> to turn this file into a module"}
					}
					log {
						category: "info"
						text: RAW_MARKUP {value: "Add <emphasis>\"type\": \"module\"</emphasis> to your <filelink emphasis target=\"<dim>undefined</dim>\" />"}
					}
				]
				category: ["parse"]
				categoryValue: "js"
				message: RAW_MARKUP {value: "<emphasis>import</emphasis> and <emphasis>export</emphasis> can only appear in a module"}
			}
			location: {
				language: "js"
				path: UIDPath<esprima/es2015-export-declaration/export-default-from-as-identifier-2/input.js>
				end: Position 1:26
				start: Position 1:0
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<esprima/es2015-export-declaration/export-default-from-as-identifier-2/input.js>
	loc: SourceLocation esprima/es2015-export-declaration/export-default-from-as-identifier-2/input.js 1:0-2:0
}
```

### `diagnostics`

```

 esprima/es2015-export-declaration/export-default-from-as-identifier-2/input.js:1 parse(js) ━━━━━━━━

  ✖ import and export can only appear in a module

    export default from (bar);
    ^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Change the extension to .mjs to turn this file into a module

  ℹ Add "type": "module" to your <dim>undefined</dim>


```
