# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `comments > regression > 11469`

### `ast`

```javascript
JSRoot {
	body: [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "A"
				loc: SourceLocation comments/regression/11469/input.js 1:6-1:7 (A)
			}
			meta: JSClassHead {
				body: [
					JSClassMethod {
						kind: "method"
						trailingComments: ["1"]
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "test"
								loc: SourceLocation comments/regression/11469/input.js 2:2-2:6 (test)
							}
							loc: SourceLocation comments/regression/11469/input.js 2:2-2:6
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation comments/regression/11469/input.js 2:2-2:6
							start: Position 2:2
						}
						body: JSBlockStatement {
							body: []
							directives: []
							innerComments: ["0"]
							loc: SourceLocation comments/regression/11469/input.js 2:9-4:3
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: []
							loc: SourceLocation comments/regression/11469/input.js 2:6-2:8
						}
						loc: SourceLocation comments/regression/11469/input.js 2:2-4:3
					}
				]
				loc: SourceLocation comments/regression/11469/input.js 1:0-7:1
			}
			loc: SourceLocation comments/regression/11469/input.js 1:0-7:1
		}
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "B"
				loc: SourceLocation comments/regression/11469/input.js 9:6-9:7 (B)
			}
			meta: JSClassHead {
				body: [
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "test"
								loc: SourceLocation comments/regression/11469/input.js 10:2-10:6 (test)
							}
							loc: SourceLocation comments/regression/11469/input.js 10:2-10:6
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation comments/regression/11469/input.js 10:2-10:6
							start: Position 10:2
						}
						body: JSBlockStatement {
							body: []
							directives: []
							innerComments: ["2"]
							trailingComments: []
							loc: SourceLocation comments/regression/11469/input.js 10:9-12:3
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: []
							loc: SourceLocation comments/regression/11469/input.js 10:6-10:8
						}
						loc: SourceLocation comments/regression/11469/input.js 10:2-12:3
					}
				]
				loc: SourceLocation comments/regression/11469/input.js 9:0-13:1
			}
			loc: SourceLocation comments/regression/11469/input.js 9:0-13:1
		}
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "C"
				loc: SourceLocation comments/regression/11469/input.js 15:6-15:7 (C)
			}
			meta: JSClassHead {
				body: [
					JSClassMethod {
						kind: "method"
						trailingComments: ["3"]
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "test"
								loc: SourceLocation comments/regression/11469/input.js 16:2-16:6 (test)
							}
							loc: SourceLocation comments/regression/11469/input.js 16:2-16:6
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation comments/regression/11469/input.js 16:2-16:6
							start: Position 16:2
						}
						body: JSBlockStatement {
							body: []
							directives: []
							loc: SourceLocation comments/regression/11469/input.js 16:9-16:11
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: []
							loc: SourceLocation comments/regression/11469/input.js 16:6-16:8
						}
						loc: SourceLocation comments/regression/11469/input.js 16:2-16:11
					}
				]
				loc: SourceLocation comments/regression/11469/input.js 15:0-18:1
			}
			loc: SourceLocation comments/regression/11469/input.js 15:0-18:1
		}
	]
	comments: [
		CommentLine {
			id: "0"
			value: " this.member = 'value';"
			loc: SourceLocation comments/regression/11469/input.js 3:4-3:29
		}
		CommentBlock {
			id: "1"
			value: " Trailing comment "
			loc: SourceLocation comments/regression/11469/input.js 6:2-6:24
		}
		CommentLine {
			id: "2"
			value: " this.member = 'value';"
			loc: SourceLocation comments/regression/11469/input.js 11:4-11:29
		}
		CommentLine {
			id: "3"
			value: " this.member = 'value';"
			loc: SourceLocation comments/regression/11469/input.js 17:2-17:27
		}
	]
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<comments/regression/11469/input.js>
	loc: SourceLocation comments/regression/11469/input.js 1:0-19:0
}
```

### `diagnostics`

```

```
