# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/codec-js-regexp/index.test.ts --update-snapshots` to update.

## `parses escape characters correctly`

### `0`

```javascript
{
	diagnostics: []
	expression: JSRegExpSubExpression {
		body: [
			JSRegExpCharacter {
				value: "f"
				loc: SourceLocation unknown 1:0-1:1
			}
			JSRegExpGroupCapture {
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharacter {
							value: "o"
							loc: SourceLocation unknown 1:2-1:3
						}
					]
					loc: SourceLocation unknown 1:2-1:3
				}
				loc: SourceLocation unknown 1:1-1:4
			}
			JSRegExpNumericBackReference {
				value: 1
				loc: SourceLocation unknown 1:4-1:6
			}
		]
		loc: SourceLocation unknown 1:0-1:6
	}
}
```

### `1`

```javascript
{
	diagnostics: []
	expression: JSRegExpSubExpression {
		body: [
			JSRegExpCharacter {
				value: "f"
				loc: SourceLocation unknown 1:0-1:1
			}
			JSRegExpGroupCapture {
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharacter {
							value: "o"
							loc: SourceLocation unknown 1:2-1:3
						}
					]
					loc: SourceLocation unknown 1:2-1:3
				}
				loc: SourceLocation unknown 1:1-1:4
			}
			JSRegExpCharacter {
				value: "\0"
				loc: SourceLocation unknown 1:4-1:6
			}
		]
		loc: SourceLocation unknown 1:0-1:6
	}
}
```

### `2`

```javascript
{
	diagnostics: []
	expression: JSRegExpSubExpression {
		body: [
			JSRegExpCharacter {
				value: "f"
				loc: SourceLocation unknown 1:0-1:1
			}
			JSRegExpGroupCapture {
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharacter {
							value: "a"
							loc: SourceLocation unknown 1:2-1:3
						}
					]
					loc: SourceLocation unknown 1:2-1:3
				}
				loc: SourceLocation unknown 1:1-1:4
			}
			JSRegExpGroupCapture {
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharacter {
							value: "b"
							loc: SourceLocation unknown 1:5-1:6
						}
					]
					loc: SourceLocation unknown 1:5-1:6
				}
				loc: SourceLocation unknown 1:4-1:7
			}
			JSRegExpGroupCapture {
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharacter {
							value: "c"
							loc: SourceLocation unknown 1:8-1:9
						}
					]
					loc: SourceLocation unknown 1:8-1:9
				}
				loc: SourceLocation unknown 1:7-1:10
			}
			JSRegExpGroupCapture {
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharacter {
							value: "d"
							loc: SourceLocation unknown 1:11-1:12
						}
					]
					loc: SourceLocation unknown 1:11-1:12
				}
				loc: SourceLocation unknown 1:10-1:13
			}
			JSRegExpGroupCapture {
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharacter {
							value: "e"
							loc: SourceLocation unknown 1:14-1:15
						}
					]
					loc: SourceLocation unknown 1:14-1:15
				}
				loc: SourceLocation unknown 1:13-1:16
			}
			JSRegExpGroupCapture {
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharacter {
							value: "f"
							loc: SourceLocation unknown 1:17-1:18
						}
					]
					loc: SourceLocation unknown 1:17-1:18
				}
				loc: SourceLocation unknown 1:16-1:19
			}
			JSRegExpGroupCapture {
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharacter {
							value: "g"
							loc: SourceLocation unknown 1:20-1:21
						}
					]
					loc: SourceLocation unknown 1:20-1:21
				}
				loc: SourceLocation unknown 1:19-1:22
			}
			JSRegExpGroupCapture {
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharacter {
							value: "h"
							loc: SourceLocation unknown 1:23-1:24
						}
					]
					loc: SourceLocation unknown 1:23-1:24
				}
				loc: SourceLocation unknown 1:22-1:25
			}
			JSRegExpGroupCapture {
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharacter {
							value: "i"
							loc: SourceLocation unknown 1:26-1:27
						}
					]
					loc: SourceLocation unknown 1:26-1:27
				}
				loc: SourceLocation unknown 1:25-1:28
			}
			JSRegExpGroupCapture {
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharacter {
							value: "j"
							loc: SourceLocation unknown 1:29-1:30
						}
					]
					loc: SourceLocation unknown 1:29-1:30
				}
				loc: SourceLocation unknown 1:28-1:31
			}
			JSRegExpGroupCapture {
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharacter {
							value: "k"
							loc: SourceLocation unknown 1:32-1:33
						}
					]
					loc: SourceLocation unknown 1:32-1:33
				}
				loc: SourceLocation unknown 1:31-1:34
			}
			JSRegExpNumericBackReference {
				value: 11
				loc: SourceLocation unknown 1:34-1:37
			}
		]
		loc: SourceLocation unknown 1:0-1:37
	}
}
```

### `3`

```javascript
{
	diagnostics: []
	expression: JSRegExpSubExpression {
		body: [
			JSRegExpCharacter {
				value: "f"
				loc: SourceLocation unknown 1:0-1:1
			}
			JSRegExpGroupCapture {
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharacter {
							value: "a"
							loc: SourceLocation unknown 1:2-1:3
						}
					]
					loc: SourceLocation unknown 1:2-1:3
				}
				loc: SourceLocation unknown 1:1-1:4
			}
			JSRegExpCharacter {
				value: "\x02"
				loc: SourceLocation unknown 1:4-1:6
			}
		]
		loc: SourceLocation unknown 1:0-1:6
	}
}
```

### `4`

```javascript
{
	diagnostics: []
	expression: JSRegExpSubExpression {
		body: [
			JSRegExpCharacter {
				value: "f"
				loc: SourceLocation unknown 1:0-1:1
			}
			JSRegExpGroupCapture {
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharacter {
							value: "a"
							loc: SourceLocation unknown 1:2-1:3
						}
					]
					loc: SourceLocation unknown 1:2-1:3
				}
				loc: SourceLocation unknown 1:1-1:4
			}
			JSRegExpNumericBackReference {
				value: 2
				loc: SourceLocation unknown 1:4-1:6
			}
		]
		loc: SourceLocation unknown 1:0-1:6
	}
}
```

### `5`

```javascript
{
	diagnostics: []
	expression: JSRegExpSubExpression {
		body: [
			JSRegExpCharacter {
				value: "f"
				loc: SourceLocation unknown 1:0-1:1
			}
			JSRegExpGroupNonCapture {
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharacter {
							value: "a"
							loc: SourceLocation unknown 1:4-1:5
						}
					]
					loc: SourceLocation unknown 1:4-1:5
				}
				loc: SourceLocation unknown 1:1-1:6
			}
			JSRegExpCharacter {
				value: "\x01"
				loc: SourceLocation unknown 1:6-1:8
			}
		]
		loc: SourceLocation unknown 1:0-1:8
	}
}
```

### `6`

```javascript
{
	diagnostics: []
	expression: JSRegExpSubExpression {
		body: [
			JSRegExpQuantified {
				lazy: false
				min: 1
				target: JSRegExpCharSet {
					body: [
						JSRegExpCharSetRange {
							end: JSRegExpCharacter {
								value: "\u04ff"
								loc: SourceLocation unknown 1:3-1:4
							}
							loc: SourceLocation unknown 1:1-1:4
							start: JSRegExpCharacter {
								value: "\u0400"
								loc: SourceLocation unknown 1:1-1:2
							}
						}
					]
					invert: false
					loc: SourceLocation unknown 1:0-1:5
				}
				loc: SourceLocation unknown 1:0-1:6
			}
			JSRegExpCharacter {
				value: "\0"
				loc: SourceLocation unknown 1:6-1:8
			}
		]
		loc: SourceLocation unknown 1:0-1:8
	}
}
```

### `7`

```javascript
{
	diagnostics: []
	expression: JSRegExpSubExpression {
		body: [
			JSRegExpGroupCapture {
				name: "quote"
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharSet {
							body: [
								JSRegExpCharacter {
									value: "'"
									loc: SourceLocation unknown 1:10-1:11
								}
								JSRegExpCharacter {
									value: "\""
									loc: SourceLocation unknown 1:11-1:12
								}
							]
							invert: false
							loc: SourceLocation unknown 1:9-1:13
						}
					]
					loc: SourceLocation unknown 1:9-1:13
				}
				loc: SourceLocation unknown 1:0-1:14
			}
			JSRegExpNamedBackReference {
				name: "quote"
				loc: SourceLocation unknown 1:14-1:23
			}
		]
		loc: SourceLocation unknown 1:0-1:23
	}
}
```

### `8`

```javascript
{
	diagnostics: []
	expression: JSRegExpSubExpression {
		body: [
			JSRegExpGroupCapture {
				name: "quote"
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharSet {
							body: [
								JSRegExpCharacter {
									value: "'"
									loc: SourceLocation unknown 1:10-1:11
								}
								JSRegExpCharacter {
									value: "\""
									loc: SourceLocation unknown 1:11-1:12
								}
							]
							invert: false
							loc: SourceLocation unknown 1:9-1:13
						}
						JSRegExpNamedBackReference {
							name: "quote"
							loc: SourceLocation unknown 1:13-1:22
						}
					]
					loc: SourceLocation unknown 1:9-1:22
				}
				loc: SourceLocation unknown 1:0-1:22
			}
		]
		loc: SourceLocation unknown 1:0-1:22
	}
}
```

### `9`

```javascript
{
	diagnostics: []
	expression: JSRegExpSubExpression {
		body: [
			JSRegExpCharacter {
				value: "k"
				loc: SourceLocation unknown 1:0-1:2
			}
			JSRegExpCharacter {
				value: "<"
				loc: SourceLocation unknown 1:2-1:3
			}
			JSRegExpCharacter {
				value: "q"
				loc: SourceLocation unknown 1:3-1:4
			}
			JSRegExpCharacter {
				value: "u"
				loc: SourceLocation unknown 1:4-1:5
			}
			JSRegExpCharacter {
				value: "o"
				loc: SourceLocation unknown 1:5-1:6
			}
			JSRegExpCharacter {
				value: "t"
				loc: SourceLocation unknown 1:6-1:7
			}
			JSRegExpCharacter {
				value: "e"
				loc: SourceLocation unknown 1:7-1:8
			}
			JSRegExpCharacter {
				value: ">"
				loc: SourceLocation unknown 1:8-1:9
			}
		]
		loc: SourceLocation unknown 1:0-1:9
	}
}
```

### `10`

```javascript
{
	diagnostics: [
		{
			origins: [{entity: "ParserCore<regex>"}]
			description: {
				advice: []
				category: ["parse"]
				categoryValue: "regex"
				message: RAW_MARKUP {value: "Invalid named capture referenced"}
			}
			location: {
				language: "regex"
				sourceText: "<quote>\\k<quote>"
				path: UIDPath<unknown>
				end: Position 1:16
				start: Position 1:16
			}
		}
	]
	expression: JSRegExpSubExpression {
		body: [
			JSRegExpCharacter {
				value: "<"
				loc: SourceLocation unknown 1:0-1:1
			}
			JSRegExpCharacter {
				value: "q"
				loc: SourceLocation unknown 1:1-1:2
			}
			JSRegExpCharacter {
				value: "u"
				loc: SourceLocation unknown 1:2-1:3
			}
			JSRegExpCharacter {
				value: "o"
				loc: SourceLocation unknown 1:3-1:4
			}
			JSRegExpCharacter {
				value: "t"
				loc: SourceLocation unknown 1:4-1:5
			}
			JSRegExpCharacter {
				value: "e"
				loc: SourceLocation unknown 1:5-1:6
			}
			JSRegExpCharacter {
				value: ">"
				loc: SourceLocation unknown 1:6-1:7
			}
			JSRegExpNamedBackReference {
				name: "quote"
				loc: SourceLocation unknown 1:7-1:16
			}
		]
		loc: SourceLocation unknown 1:0-1:16
	}
}
```

### `11`

```javascript
{
	diagnostics: [
		{
			origins: [{entity: "ParserCore<regex>"}]
			description: {
				advice: []
				category: ["parse"]
				categoryValue: "regex"
				message: RAW_MARKUP {value: "Unclosed named capture"}
			}
			location: {
				language: "regex"
				sourceText: "(?<quote>['\"])\\k<quote"
				path: UIDPath<unknown>
				end: Position 1:22
				start: Position 1:22
			}
		}
	]
	expression: JSRegExpSubExpression {
		body: [
			JSRegExpGroupCapture {
				name: "quote"
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharSet {
							body: [
								JSRegExpCharacter {
									value: "'"
									loc: SourceLocation unknown 1:10-1:11
								}
								JSRegExpCharacter {
									value: "\""
									loc: SourceLocation unknown 1:11-1:12
								}
							]
							invert: false
							loc: SourceLocation unknown 1:9-1:13
						}
					]
					loc: SourceLocation unknown 1:9-1:13
				}
				loc: SourceLocation unknown 1:0-1:14
			}
			JSRegExpNamedBackReference {
				name: "quote"
				loc: SourceLocation unknown 1:14-1:22
			}
		]
		loc: SourceLocation unknown 1:0-1:22
	}
}
```

## `verify the parser recognizes nodes correctly`

### `0`

```javascript
{
	diagnostics: [
		{
			origins: [{entity: "ParserCore<regex>"}]
			description: {
				advice: []
				category: ["parse"]
				categoryValue: "regex"
				message: RAW_MARKUP {value: "Duplicate capture group name"}
			}
			location: {
				language: "regex"
				sourceText: "(?<test>)(?<test>)"
				path: UIDPath<unknown>
				end: Position 1:9
				start: Position 1:9
			}
		}
	]
	expression: JSRegExpSubExpression {
		body: [
			JSRegExpGroupCapture {
				name: "test"
				expression: JSRegExpSubExpression {
					body: []
					loc: SourceLocation unknown 1:8-1:8
				}
				loc: SourceLocation unknown 1:0-1:9
			}
			JSRegExpGroupCapture {
				name: "test"
				expression: JSRegExpSubExpression {
					body: []
					loc: SourceLocation unknown 1:17-1:17
				}
				loc: SourceLocation unknown 1:9-1:17
			}
		]
		loc: SourceLocation unknown 1:0-1:17
	}
}
```

### `1`

```javascript
{
	diagnostics: []
	expression: JSRegExpSubExpression {
		body: [
			JSRegExpCharacter {
				value: "t"
				loc: SourceLocation unknown 1:0-1:1
			}
			JSRegExpCharacter {
				value: "e"
				loc: SourceLocation unknown 1:1-1:2
			}
			JSRegExpCharacter {
				value: "s"
				loc: SourceLocation unknown 1:2-1:3
			}
			JSRegExpCharacter {
				value: "t"
				loc: SourceLocation unknown 1:3-1:4
			}
			JSRegExpCharacter {
				value: "\n"
				loc: SourceLocation unknown 1:4-1:7
			}
		]
		loc: SourceLocation unknown 1:0-1:7
	}
}
```