# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-export-declaration > export-default-expression`

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
  syntax: Array []
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
  body: Array [
    ExportDefaultDeclaration {
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
      declaration: BinaryExpression {
        operator: '+'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 21
            index: 21
            line: 1
          }
          start: Object {
            column: 16
            index: 16
            line: 1
          }
        }
        left: NumericLiteral {
          value: 1
          format: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 17
              index: 17
              line: 1
            }
            start: Object {
              column: 16
              index: 16
              line: 1
            }
          }
        }
        right: NumericLiteral {
          value: 2
          format: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 21
              index: 21
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
```