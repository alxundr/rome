# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > type-parameter-declaration > reserved-word-class-name-failure`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'flow'
    'jsx'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 24
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
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Unexpected keyword delete'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 20
          index: 20
          line: 1
        }
        start: Object {
          column: 14
          index: 14
          line: 1
        }
      }
    }
  ]
  body: Array [
    FlowDeclareClass {
      id: BindingIdentifier {
        name: 'delete'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 20
            index: 20
            line: 1
          }
          start: Object {
            column: 14
            index: 14
            line: 1
          }
        }
      }
      extends: Array []
      implements: Array []
      mixins: Array []
      typeParameters: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 23
          index: 23
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      body: FlowObjectTypeAnnotation {
        exact: false
        inexact: undefined
        properties: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 23
            index: 23
            line: 1
          }
          start: Object {
            column: 21
            index: 21
            line: 1
          }
        }
      }
    }
  ]
}
```
