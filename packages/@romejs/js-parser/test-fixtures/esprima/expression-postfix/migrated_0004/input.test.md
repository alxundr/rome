# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > expression-postfix > migrated_0004`

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
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 12
      line: 2
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
          column: 11
          index: 11
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: UpdateExpression {
        operator: '++'
        prefix: false
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 11
            index: 11
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        argument: ReferenceIdentifier {
          name: 'arguments'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 9
              index: 9
              line: 1
            }
            start: Object {
              column: 0
              index: 0
              line: 1
            }
          }
        }
      }
    }
  ]
}
```
