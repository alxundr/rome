# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > type-alias > plain`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.ts'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array ['ts']
  loc: Object {
    filename: 'input.ts'
    end: Object {
      column: 0
      index: 17
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    TypeAliasTypeAnnotation {
      id: BindingIdentifier {
        name: 'T'
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 6
            index: 6
            line: 1
          }
          start: Object {
            column: 5
            index: 5
            line: 1
          }
        }
      }
      typeParameters: undefined
      loc: Object {
        filename: 'input.ts'
        end: Object {
          column: 16
          index: 16
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      right: NumberKeywordTypeAnnotation {
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 15
            index: 15
            line: 1
          }
          start: Object {
            column: 9
            index: 9
            line: 1
          }
        }
      }
    }
  ]
}
```
