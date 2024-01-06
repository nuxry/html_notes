# Colspan: Column Spanning

definition to be added...

উদাহরনঃ
```html
<body>

  <table border="1">
    <caption>Table with Colspan</caption>
    <tr>
      <th>Header 1</th>
      <th>Header 2</th>
      <th colspan="2">Header 3 (spanning 2 columns)</th>
    </tr>
    <tr>
      <td>Row 1, Cell 1</td>
      <td>Row 1, Cell 2</td>
      <td colspan="2">Row 1, Cell 3 (spanning 2 columns)</td>
    </tr>
    <tr>
      <td>Row 2, Cell 1</td>
      <td>Row 2, Cell 2</td>
      <td>Row 2, Cell 3</td>
      <td>Row 2, Cell 4</td>
    </tr>
  </table>

</body>
```

আউটপুটঃ 

<body>
  <table border="1">
    <caption>Table with Colspan</caption>
    <tr>
      <th>Header 1</th>
      <th>Header 2</th>
      <th colspan="2">Header 3 (spanning 2 columns)</th>
    </tr>
    <tr>
      <td>Row 1, Cell 1</td>
      <td>Row 1, Cell 2</td>
      <td colspan="2">Row 1, Cell 3 (spanning 2 columns)</td>
    </tr>
    <tr>
      <td>Row 2, Cell 1</td>
      <td>Row 2, Cell 2</td>
      <td>Row 2, Cell 3</td>
      <td>Row 2, Cell 4</td>
    </tr>
  </table>
</body>