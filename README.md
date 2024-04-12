# EMCM

Even More Console methods.

## Instalation

```bash
npm install emcm
```

## Usage

### Table

You can get a table by using the `Table` class.

```javascript
const table = new Table()
table.addRow('This is the key', 'This is the value')

console.log(table.toString())
// output:
// ┌────────────────┬──────────────────┐
// │key             │value             │
// ├────────────────┼──────────────────┤
// │This is the key │This is the value │
// └────────────────┴──────────────────┘
```