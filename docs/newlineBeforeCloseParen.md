# newlineBeforeCloseParen

Decides whether to place close-parenthesis `)` of sub-queries on a separate line.

## Options

- `true` (default) adds newline before close-parenthesis.
- `false` no newline.

Caveats:

This option is ignored when `indentStyle: "tabularLeft"` or `"tabularRight"` is used.

### newlineBeforeCloseParen: true

```
SELECT
  *
FROM
  (
    SELECT
      *
    FROM
      my_table
  );
```

### newlineBeforeCloseParen: false

```
SELECT
  *
FROM
  (
    SELECT
      *
    FROM
      my_table );
```
