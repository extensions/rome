# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > interface > generic`

### `ast`

```javascript
JSRoot {
	body: [
		TSInterfaceDeclaration {
			id: JSBindingIdentifier {
				name: "I"
				loc: SourceLocation typescript/interface/generic/input.ts 1:10-1:11 (I)
			}
			body: TSInterfaceBody {
				body: []
				loc: SourceLocation typescript/interface/generic/input.ts 1:46-1:48
			}
			typeParameters: TSTypeParameterDeclaration {
				params: [
					TSTypeParameter {
						name: "T"
						constraint: TSObjectKeywordTypeAnnotation {
							loc: SourceLocation typescript/interface/generic/input.ts 1:22-1:28
						}
						default: TSObjectTypeAnnotation {
							members: [
								TSPropertySignature {
									declare: false
									optional: false
									readonly: false
									key: JSStaticPropertyKey {
										value: JSIdentifier {
											name: "x"
											loc: SourceLocation typescript/interface/generic/input.ts 1:33-1:34 (x)
										}
										loc: SourceLocation typescript/interface/generic/input.ts 1:33-1:34
									}
									typeAnnotation: TSNumberKeywordTypeAnnotation {
										loc: SourceLocation typescript/interface/generic/input.ts 1:36-1:42
									}
									loc: SourceLocation typescript/interface/generic/input.ts 1:33-1:42
								}
							]
							loc: SourceLocation typescript/interface/generic/input.ts 1:31-1:44
						}
						loc: SourceLocation typescript/interface/generic/input.ts 1:12-1:44
					}
				]
				loc: SourceLocation typescript/interface/generic/input.ts 1:11-1:45
			}
			loc: SourceLocation typescript/interface/generic/input.ts 1:0-1:48
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "module"
	syntax: ["ts"]
	path: UIDPath<typescript/interface/generic/input.ts>
	loc: SourceLocation typescript/interface/generic/input.ts 1:0-2:0
}
```

### `diagnostics`

```

```
