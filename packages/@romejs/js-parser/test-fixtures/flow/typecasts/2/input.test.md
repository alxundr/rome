# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > typecasts > 2`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
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
      column: 50
      index: 50
      line: 1
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 50
          index: 50
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: FlowTypeCastExpression {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 49
            index: 49
            line: 1
          }
          start: Object {
            column: 1
            index: 1
            line: 1
          }
        }
        typeAnnotation: FlowObjectTypeAnnotation {
          exact: false
          inexact: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 49
              index: 49
              line: 1
            }
            start: Object {
              column: 23
              index: 23
              line: 1
            }
          }
          properties: Array [
            FlowObjectTypeProperty {
              kind: 'init'
              key: Identifier {
                name: 'xxx'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 27
                    index: 27
                    line: 1
                  }
                  start: Object {
                    column: 24
                    index: 24
                    line: 1
                  }
                }
              }
              value: NumberKeywordTypeAnnotation {
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 35
                    index: 35
                    line: 1
                  }
                  start: Object {
                    column: 29
                    index: 29
                    line: 1
                  }
                }
              }
              optional: false
              proto: false
              static: false
              variance: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 35
                  index: 35
                  line: 1
                }
                start: Object {
                  column: 24
                  index: 24
                  line: 1
                }
              }
            }
            FlowObjectTypeProperty {
              kind: 'init'
              key: Identifier {
                name: 'yyy'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 40
                    index: 40
                    line: 1
                  }
                  start: Object {
                    column: 37
                    index: 37
                    line: 1
                  }
                }
              }
              value: StringKeywordTypeAnnotation {
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 48
                    index: 48
                    line: 1
                  }
                  start: Object {
                    column: 42
                    index: 42
                    line: 1
                  }
                }
              }
              optional: false
              proto: false
              static: false
              variance: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 48
                  index: 48
                  line: 1
                }
                start: Object {
                  column: 37
                  index: 37
                  line: 1
                }
              }
            }
          ]
        }
        expression: ObjectExpression {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 21
              index: 21
              line: 1
            }
            start: Object {
              column: 1
              index: 1
              line: 1
            }
          }
          properties: Array [
            ObjectProperty {
              key: StaticPropertyKey {
                value: Identifier {
                  name: 'xxx'
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 5
                      index: 5
                      line: 1
                    }
                    start: Object {
                      column: 2
                      index: 2
                      line: 1
                    }
                  }
                }
                variance: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 5
                    index: 5
                    line: 1
                  }
                  start: Object {
                    column: 2
                    index: 2
                    line: 1
                  }
                }
              }
              value: NumericLiteral {
                value: 0
                format: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 8
                    index: 8
                    line: 1
                  }
                  start: Object {
                    column: 7
                    index: 7
                    line: 1
                  }
                }
              }
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 8
                  index: 8
                  line: 1
                }
                start: Object {
                  column: 2
                  index: 2
                  line: 1
                }
              }
            }
            ObjectProperty {
              key: StaticPropertyKey {
                value: Identifier {
                  name: 'yyy'
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 13
                      index: 13
                      line: 1
                    }
                    start: Object {
                      column: 10
                      index: 10
                      line: 1
                    }
                  }
                }
                variance: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 13
                    index: 13
                    line: 1
                  }
                  start: Object {
                    column: 10
                    index: 10
                    line: 1
                  }
                }
              }
              value: StringLiteral {
                value: 'hey'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 20
                    index: 20
                    line: 1
                  }
                  start: Object {
                    column: 15
                    index: 15
                    line: 1
                  }
                }
              }
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 20
                  index: 20
                  line: 1
                }
                start: Object {
                  column: 10
                  index: 10
                  line: 1
                }
              }
            }
          ]
        }
      }
    }
  ]
}
```
