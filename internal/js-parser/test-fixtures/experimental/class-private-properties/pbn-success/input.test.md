# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > class-private-properties > pbn-success`

### `ast`

```javascript
JSRoot {
	body: [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "Point"
				loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 1:6-1:11 (Point)
			}
			meta: JSClassHead {
				body: [
					JSClassPrivateProperty {
						key: JSPrivateName {
							id: JSIdentifier {
								name: "x"
								loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 2:3-2:4 (x)
							}
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 2:2-2:4
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 2:2-2:4
							start: Position 2:2
						}
						value: JSNumericLiteral {
							value: 1
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 2:7-2:8
						}
						loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 2:2-2:9
					}
					JSClassPrivateProperty {
						key: JSPrivateName {
							id: JSIdentifier {
								name: "y"
								loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 3:3-3:4 (y)
							}
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 3:2-3:4
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 3:2-3:4
							start: Position 3:2
						}
						value: JSNumericLiteral {
							value: 2
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 3:7-3:8
						}
						loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 3:2-3:9
					}
					JSClassMethod {
						kind: "constructor"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "constructor"
								loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 5:2-5:13 (constructor)
							}
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 5:2-5:13
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 5:2-5:13
							start: Position 5:2
						}
						body: JSBlockStatement {
							body: [
								JSExpressionStatement {
									expression: JSAssignmentExpression {
										operator: "="
										left: JSMemberExpression {
											object: JSThisExpression {
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 6:4-6:8
											}
											property: JSStaticMemberProperty {
												value: JSPrivateName {
													id: JSIdentifier {
														name: "x"
														loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 6:10-6:11 (x)
													}
													loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 6:9-6:11
												}
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 6:9-6:11
											}
											loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 6:4-6:11
										}
										right: JSUnaryExpression {
											operator: "+"
											prefix: true
											argument: JSReferenceIdentifier {
												name: "x"
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 6:15-6:16 (x)
											}
											loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 6:14-6:16
										}
										loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 6:4-6:16
									}
									loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 6:4-6:17
								}
								JSExpressionStatement {
									expression: JSAssignmentExpression {
										operator: "="
										left: JSMemberExpression {
											object: JSThisExpression {
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 7:4-7:8
											}
											property: JSStaticMemberProperty {
												value: JSPrivateName {
													id: JSIdentifier {
														name: "y"
														loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 7:10-7:11 (y)
													}
													loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 7:9-7:11
												}
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 7:9-7:11
											}
											loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 7:4-7:11
										}
										right: JSUnaryExpression {
											operator: "+"
											prefix: true
											argument: JSReferenceIdentifier {
												name: "y"
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 7:15-7:16 (y)
											}
											loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 7:14-7:16
										}
										loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 7:4-7:16
									}
									loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 7:4-7:17
								}
							]
							directives: []
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 5:28-8:3
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: [
								JSBindingAssignmentPattern {
									left: JSBindingIdentifier {
										name: "x"
										meta: JSPatternMeta {
											loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 5:14-5:15
										}
										loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 5:14-5:15 (x)
									}
									right: JSNumericLiteral {
										value: 0
										loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 5:18-5:19
									}
									loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 5:14-5:19
								}
								JSBindingAssignmentPattern {
									left: JSBindingIdentifier {
										name: "y"
										meta: JSPatternMeta {
											loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 5:21-5:22
										}
										loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 5:21-5:22 (y)
									}
									right: JSNumericLiteral {
										value: 0
										loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 5:25-5:26
									}
									loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 5:21-5:26
								}
							]
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 5:13-5:27
						}
						loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 5:2-8:3
					}
					JSClassMethod {
						kind: "get"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "x"
								loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 10:6-10:7 (x)
							}
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 10:6-10:7
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 10:2-10:7
							start: Position 10:2
						}
						body: JSBlockStatement {
							body: [
								JSReturnStatement {
									argument: JSMemberExpression {
										object: JSThisExpression {
											loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 10:19-10:23
										}
										property: JSStaticMemberProperty {
											value: JSPrivateName {
												id: JSIdentifier {
													name: "x"
													loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 10:25-10:26 (x)
												}
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 10:24-10:26
											}
											loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 10:24-10:26
										}
										loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 10:19-10:26
									}
									loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 10:12-10:26
								}
							]
							directives: []
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 10:10-10:28
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: []
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 10:7-10:9
						}
						loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 10:2-10:28
					}
					JSClassMethod {
						kind: "set"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "x"
								loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 11:6-11:7 (x)
							}
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 11:6-11:7
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 11:2-11:7
							start: Position 11:2
						}
						body: JSBlockStatement {
							body: [
								JSExpressionStatement {
									expression: JSAssignmentExpression {
										operator: "="
										left: JSMemberExpression {
											object: JSThisExpression {
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 11:17-11:21
											}
											property: JSStaticMemberProperty {
												value: JSPrivateName {
													id: JSIdentifier {
														name: "x"
														loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 11:23-11:24 (x)
													}
													loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 11:22-11:24
												}
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 11:22-11:24
											}
											loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 11:17-11:24
										}
										right: JSUnaryExpression {
											operator: "+"
											prefix: true
											argument: JSReferenceIdentifier {
												name: "value"
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 11:28-11:33 (value)
											}
											loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 11:27-11:33
										}
										loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 11:17-11:33
									}
									loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 11:17-11:33
								}
							]
							directives: []
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 11:15-11:35
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: [
								JSBindingIdentifier {
									name: "value"
									meta: JSPatternMeta {
										loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 11:8-11:13
									}
									loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 11:8-11:13 (value)
								}
							]
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 11:7-11:14
						}
						loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 11:2-11:35
					}
					JSClassMethod {
						kind: "get"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "y"
								loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 13:6-13:7 (y)
							}
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 13:6-13:7
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 13:2-13:7
							start: Position 13:2
						}
						body: JSBlockStatement {
							body: [
								JSReturnStatement {
									argument: JSMemberExpression {
										object: JSThisExpression {
											loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 13:19-13:23
										}
										property: JSStaticMemberProperty {
											value: JSPrivateName {
												id: JSIdentifier {
													name: "y"
													loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 13:25-13:26 (y)
												}
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 13:24-13:26
											}
											loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 13:24-13:26
										}
										loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 13:19-13:26
									}
									loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 13:12-13:26
								}
							]
							directives: []
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 13:10-13:28
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: []
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 13:7-13:9
						}
						loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 13:2-13:28
					}
					JSClassMethod {
						kind: "set"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "y"
								loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 14:6-14:7 (y)
							}
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 14:6-14:7
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 14:2-14:7
							start: Position 14:2
						}
						body: JSBlockStatement {
							body: [
								JSExpressionStatement {
									expression: JSAssignmentExpression {
										operator: "="
										left: JSMemberExpression {
											object: JSThisExpression {
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 14:17-14:21
											}
											property: JSStaticMemberProperty {
												value: JSPrivateName {
													id: JSIdentifier {
														name: "y"
														loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 14:23-14:24 (y)
													}
													loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 14:22-14:24
												}
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 14:22-14:24
											}
											loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 14:17-14:24
										}
										right: JSUnaryExpression {
											operator: "+"
											prefix: true
											argument: JSReferenceIdentifier {
												name: "value"
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 14:28-14:33 (value)
											}
											loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 14:27-14:33
										}
										loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 14:17-14:33
									}
									loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 14:17-14:33
								}
							]
							directives: []
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 14:15-14:35
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: [
								JSBindingIdentifier {
									name: "value"
									meta: JSPatternMeta {
										loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 14:8-14:13
									}
									loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 14:8-14:13 (value)
								}
							]
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 14:7-14:14
						}
						loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 14:2-14:35
					}
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "equals"
								loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:2-16:8 (equals)
							}
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:2-16:8
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:2-16:8
							start: Position 16:2
						}
						body: JSBlockStatement {
							body: [
								JSReturnStatement {
									argument: JSLogicalExpression {
										operator: "&&"
										left: JSBinaryExpression {
											operator: "==="
											left: JSMemberExpression {
												object: JSThisExpression {
													loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:21-16:25
												}
												property: JSStaticMemberProperty {
													value: JSPrivateName {
														id: JSIdentifier {
															name: "x"
															loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:27-16:28 (x)
														}
														loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:26-16:28
													}
													loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:26-16:28
												}
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:21-16:28
											}
											right: JSMemberExpression {
												object: JSReferenceIdentifier {
													name: "p"
													loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:33-16:34 (p)
												}
												property: JSStaticMemberProperty {
													value: JSPrivateName {
														id: JSIdentifier {
															name: "x"
															loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:36-16:37 (x)
														}
														loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:35-16:37
													}
													loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:35-16:37
												}
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:33-16:37
											}
											loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:21-16:37
										}
										right: JSBinaryExpression {
											operator: "==="
											left: JSMemberExpression {
												object: JSThisExpression {
													loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:41-16:45
												}
												property: JSStaticMemberProperty {
													value: JSPrivateName {
														id: JSIdentifier {
															name: "y"
															loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:47-16:48 (y)
														}
														loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:46-16:48
													}
													loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:46-16:48
												}
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:41-16:48
											}
											right: JSMemberExpression {
												object: JSReferenceIdentifier {
													name: "p"
													loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:53-16:54 (p)
												}
												property: JSStaticMemberProperty {
													value: JSPrivateName {
														id: JSIdentifier {
															name: "y"
															loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:56-16:57 (y)
														}
														loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:55-16:57
													}
													loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:55-16:57
												}
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:53-16:57
											}
											loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:41-16:57
										}
										loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:21-16:57
									}
									loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:14-16:57
								}
							]
							directives: []
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:12-16:59
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: [
								JSBindingIdentifier {
									name: "p"
									meta: JSPatternMeta {
										loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:9-16:10
									}
									loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:9-16:10 (p)
								}
							]
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:8-16:11
						}
						loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 16:2-16:59
					}
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "toString"
								loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:2-18:10 (toString)
							}
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:2-18:10
						}
						meta: JSClassPropertyMeta {
							abstract: false
							declare: false
							optional: false
							readonly: false
							static: false
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:2-18:10
							start: Position 18:2
						}
						body: JSBlockStatement {
							body: [
								JSReturnStatement {
									argument: JSTemplateLiteral {
										expressions: [
											JSMemberExpression {
												object: JSThisExpression {
													loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:32-18:36
												}
												property: JSStaticMemberProperty {
													value: JSPrivateName {
														id: JSIdentifier {
															name: "x"
															loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:38-18:39 (x)
														}
														loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:37-18:39
													}
													loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:37-18:39
												}
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:32-18:39
											}
											JSMemberExpression {
												object: JSThisExpression {
													loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:45-18:49
												}
												property: JSStaticMemberProperty {
													value: JSPrivateName {
														id: JSIdentifier {
															name: "y"
															loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:51-18:52 (y)
														}
														loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:50-18:52
													}
													loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:50-18:52
												}
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:45-18:52
											}
										]
										quasis: [
											JSTemplateElement {
												cooked: "Point<"
												raw: "Point<"
												tail: false
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:23-18:29
											}
											JSTemplateElement {
												cooked: ","
												raw: ","
												tail: false
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:41-18:42
											}
											JSTemplateElement {
												cooked: ">"
												raw: ">"
												tail: true
												loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:54-18:55
											}
										]
										loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:22-18:56
									}
									loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:15-18:56
								}
							]
							directives: []
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:13-18:58
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: []
							loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:10-18:12
						}
						loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 18:2-18:58
					}
				]
				loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 1:0-19:1
			}
			loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 1:0-19:1
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<experimental/class-private-properties/pbn-success/input.js>
	loc: SourceLocation experimental/class-private-properties/pbn-success/input.js 1:0-20:0
}
```

### `diagnostics`

```

```
