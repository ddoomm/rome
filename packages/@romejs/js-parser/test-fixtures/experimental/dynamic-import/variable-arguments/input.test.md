# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > dynamic-import > variable-arguments`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 0
			index: 67
			line: 3
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 30
					index: 30
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "const"
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 30
						index: 30
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "testVarible"
							loc: Object {
								filename: "input.js"
								identifierName: "testVarible"
								end: Object {
									column: 17
									index: 17
									line: 1
								}
								start: Object {
									column: 6
									index: 6
									line: 1
								}
							}
						}
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 29
								index: 29
								line: 1
							}
							start: Object {
								column: 6
								index: 6
								line: 1
							}
						}
						init: JSStringLiteral {
							value: "test.js"
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 29
									index: 29
									line: 1
								}
								start: Object {
									column: 20
									index: 20
									line: 1
								}
							}
						}
					}
				]
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 35
					index: 66
					line: 2
				}
				start: Object {
					column: 0
					index: 31
					line: 2
				}
			}
			expression: JSCallExpression {
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 34
						index: 65
						line: 2
					}
					start: Object {
						column: 0
						index: 31
						line: 2
					}
				}
				arguments: Array [
					JSArrowFunctionExpression {
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 33
								index: 64
								line: 2
							}
							start: Object {
								column: 25
								index: 56
								line: 2
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 33
									index: 64
									line: 2
								}
								start: Object {
									column: 31
									index: 62
									line: 2
								}
							}
						}
						head: JSFunctionHead {
							async: false
							hasHoistedVars: false
							params: Array []
							rest: undefined
							returnType: undefined
							thisType: undefined
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 30
									index: 61
									line: 2
								}
								start: Object {
									column: 25
									index: 56
									line: 2
								}
							}
						}
					}
				]
				callee: JSMemberExpression {
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 24
							index: 55
							line: 2
						}
						start: Object {
							column: 0
							index: 31
							line: 2
						}
					}
					object: JSImportCall {
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 19
								index: 50
								line: 2
							}
							start: Object {
								column: 6
								index: 37
								line: 2
							}
						}
						argument: JSReferenceIdentifier {
							name: "testVarible"
							loc: Object {
								filename: "input.js"
								identifierName: "testVarible"
								end: Object {
									column: 18
									index: 49
									line: 2
								}
								start: Object {
									column: 7
									index: 38
									line: 2
								}
							}
						}
					}
					property: JSStaticMemberProperty {
						value: JSIdentifier {
							name: "then"
							loc: Object {
								filename: "input.js"
								identifierName: "then"
								end: Object {
									column: 24
									index: 55
									line: 2
								}
								start: Object {
									column: 20
									index: 51
									line: 2
								}
							}
						}
						loc: Object {
							filename: "input.js"
							identifierName: "then"
							end: Object {
								column: 24
								index: 55
								line: 2
							}
							start: Object {
								column: 20
								index: 51
								line: 2
							}
						}
					}
				}
			}
		}
	]
}
```
