# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-class > migrated_0019`

### `ast`

```javascript
JSRoot {
	body: [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "A"
				loc: SourceLocation esprima/es2015-class/migrated_0019/input.js 1:6-1:7 (A)
			}
			meta: JSClassHead {
				body: [
					JSClassMethod {
						kind: "constructor"
						key: JSStaticPropertyKey {
							value: JSStringLiteral {
								value: "constructor"
								loc: SourceLocation esprima/es2015-class/migrated_0019/input.js 1:9-1:22
							}
							loc: SourceLocation esprima/es2015-class/migrated_0019/input.js 1:9-1:22
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation esprima/es2015-class/migrated_0019/input.js 1:9-1:22
							start: Position 1:9
						}
						body: JSBlockStatement {
							body: []
							directives: []
							loc: SourceLocation esprima/es2015-class/migrated_0019/input.js 1:24-1:26
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: []
							loc: SourceLocation esprima/es2015-class/migrated_0019/input.js 1:22-1:24
						}
						loc: SourceLocation esprima/es2015-class/migrated_0019/input.js 1:9-1:26
					}
					JSClassMethod {
						kind: "constructor"
						key: JSComputedPropertyKey {
							value: JSStringLiteral {
								value: "constructor"
								loc: SourceLocation esprima/es2015-class/migrated_0019/input.js 1:28-1:41
							}
							loc: SourceLocation esprima/es2015-class/migrated_0019/input.js 1:27-1:42
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation esprima/es2015-class/migrated_0019/input.js 1:27-1:42
							start: Position 1:27
						}
						body: JSBlockStatement {
							body: []
							directives: []
							loc: SourceLocation esprima/es2015-class/migrated_0019/input.js 1:44-1:46
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: []
							loc: SourceLocation esprima/es2015-class/migrated_0019/input.js 1:42-1:44
						}
						loc: SourceLocation esprima/es2015-class/migrated_0019/input.js 1:27-1:46
					}
				]
				loc: SourceLocation esprima/es2015-class/migrated_0019/input.js 1:0-1:47
			}
			loc: SourceLocation esprima/es2015-class/migrated_0019/input.js 1:0-1:47
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
				message: RAW_MARKUP {value: "Duplicate constructor in the same class"}
			}
			location: {
				language: "js"
				path: UIDPath<esprima/es2015-class/migrated_0019/input.js>
				end: Position 1:42
				start: Position 1:27
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<esprima/es2015-class/migrated_0019/input.js>
	loc: SourceLocation esprima/es2015-class/migrated_0019/input.js 1:0-2:0
}
```

### `diagnostics`

```

 esprima/es2015-class/migrated_0019/input.js:1:27 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Duplicate constructor in the same class

    class A {"constructor"(){} ["constructor"](){}}
                               ^^^^^^^^^^^^^^^


```
