# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > regression > issue-321-failing`

```javascript
Program {
  comments: Array []
  corrupt: true
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 65
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        advice: Array []
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Unexpected token, expected ,'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 33
          index: 33
          line: 1
        }
        start: Object {
          column: 27
          index: 27
          line: 1
        }
      }
    }
  ]
  body: Array [
    VariableDeclarationStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 33
          index: 33
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: VariableDeclaration {
        kind: 'const'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 33
            index: 33
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        declarations: Array [
          VariableDeclarator {
            id: BindingIdentifier {
              name: 'fn'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 33
                  index: 33
                  line: 1
                }
                start: Object {
                  column: 6
                  index: 6
                  line: 1
                }
              }
              meta: PatternMeta {
                definite: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 33
                    index: 33
                    line: 1
                  }
                  start: Object {
                    column: 6
                    index: 6
                    line: 1
                  }
                }
                typeAnnotation: FlowFunctionTypeAnnotation {
                  rest: undefined
                  typeParameters: undefined
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 33
                      index: 33
                      line: 1
                    }
                    start: Object {
                      column: 10
                      index: 10
                      line: 1
                    }
                  }
                  returnType: FlowGenericTypeAnnotation {
                    id: ReferenceIdentifier {
                      name: 'Object'
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 33
                          index: 33
                          line: 1
                        }
                        start: Object {
                          column: 27
                          index: 27
                          line: 1
                        }
                      }
                    }
                    typeParameters: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 33
                        index: 33
                        line: 1
                      }
                      start: Object {
                        column: 27
                        index: 27
                        line: 1
                      }
                    }
                  }
                  params: Array [
                    FlowFunctionTypeParam {
                      name: undefined
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 19
                          index: 19
                          line: 1
                        }
                        start: Object {
                          column: 12
                          index: 12
                          line: 1
                        }
                      }
                      meta: PatternMeta {
                        optional: false
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 19
                            index: 19
                            line: 1
                          }
                          start: Object {
                            column: 12
                            index: 12
                            line: 1
                          }
                        }
                        typeAnnotation: FlowGenericTypeAnnotation {
                          id: ReferenceIdentifier {
                            name: 'Object'
                            loc: Object {
                              filename: 'input.js'
                              end: Object {
                                column: 18
                                index: 18
                                line: 1
                              }
                              start: Object {
                                column: 12
                                index: 12
                                line: 1
                              }
                            }
                          }
                          typeParameters: undefined
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 18
                              index: 18
                              line: 1
                            }
                            start: Object {
                              column: 12
                              index: 12
                              line: 1
                            }
                          }
                        }
                      }
                    }
                    FlowFunctionTypeParam {
                      name: undefined
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 26
                          index: 26
                          line: 1
                        }
                        start: Object {
                          column: 20
                          index: 20
                          line: 1
                        }
                      }
                      meta: PatternMeta {
                        optional: false
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 26
                            index: 26
                            line: 1
                          }
                          start: Object {
                            column: 20
                            index: 20
                            line: 1
                          }
                        }
                        typeAnnotation: FlowGenericTypeAnnotation {
                          id: ReferenceIdentifier {
                            name: 'Object'
                            loc: Object {
                              filename: 'input.js'
                              end: Object {
                                column: 26
                                index: 26
                                line: 1
                              }
                              start: Object {
                                column: 20
                                index: 20
                                line: 1
                              }
                            }
                          }
                          typeParameters: undefined
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 26
                              index: 26
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
                    }
                  ]
                }
              }
            }
            init: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 33
                index: 33
                line: 1
              }
              start: Object {
                column: 6
                index: 6
                line: 1
              }
            }
          }
        ]
      }
    }
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 35
          index: 35
          line: 1
        }
        start: Object {
          column: 34
          index: 34
          line: 1
        }
      }
      expression: ReferenceIdentifier {
        name: 'INVALID_PLACEHOLDER'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 35
            index: 35
            line: 1
          }
          start: Object {
            column: 34
            index: 34
            line: 1
          }
        }
      }
    }
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 38
          index: 38
          line: 1
        }
        start: Object {
          column: 36
          index: 36
          line: 1
        }
      }
      expression: ReferenceIdentifier {
        name: 'INVALID_PLACEHOLDER'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 38
            index: 38
            line: 1
          }
          start: Object {
            column: 36
            index: 36
            line: 1
          }
        }
      }
    }
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 57
          index: 57
          line: 1
        }
        start: Object {
          column: 39
          index: 39
          line: 1
        }
      }
      expression: UnaryExpression {
        operator: 'void'
        prefix: true
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 57
            index: 57
            line: 1
          }
          start: Object {
            column: 39
            index: 39
            line: 1
          }
        }
        argument: CallExpression {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 57
              index: 57
              line: 1
            }
            start: Object {
              column: 44
              index: 44
              line: 1
            }
          }
          callee: ReferenceIdentifier {
            name: 'INVALID_PLACEHOLDER'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 45
                index: 45
                line: 1
              }
              start: Object {
                column: 44
                index: 44
                line: 1
              }
            }
          }
          arguments: Array [
            ReferenceIdentifier {
              name: 'o1'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 50
                  index: 50
                  line: 1
                }
                start: Object {
                  column: 48
                  index: 48
                  line: 1
                }
              }
            }
            ReferenceIdentifier {
              name: 'o2'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 54
                  index: 54
                  line: 1
                }
                start: Object {
                  column: 52
                  index: 52
                  line: 1
                }
              }
            }
          ]
        }
      }
    }
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 60
          index: 60
          line: 1
        }
        start: Object {
          column: 58
          index: 58
          line: 1
        }
      }
      expression: ReferenceIdentifier {
        name: 'INVALID_PLACEHOLDER'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 60
            index: 60
            line: 1
          }
          start: Object {
            column: 58
            index: 58
            line: 1
          }
        }
      }
    }
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 64
          index: 64
          line: 1
        }
        start: Object {
          column: 61
          index: 61
          line: 1
        }
      }
      expression: ReferenceIdentifier {
        name: 'o1'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 63
            index: 63
            line: 1
          }
          start: Object {
            column: 61
            index: 61
            line: 1
          }
        }
      }
    }
  ]
}
```
