# Spreadsheet Styling with CSS

A simple CSS example for formatting spreadsheet-style tables. Customize text colors, text styles, and cell alignment to make data clear and easy to read.

## Features

- Text and background colors
- Bold, italic, and other text styles
- Horizontal and vertical cell alignment
- Cell padding and borders

## Example

```html
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Quarterly Report</td>
      <td>Complete</td>
    </tr>
  </tbody>
</table>
th {
  color: #ffffff;
  background-color: #2563eb;
  font-weight: bold;
  text-align: center;
  vertical-align: middle;
}

td {
  color: #1f2937;
  text-align: left;
  vertical-align: top;
  padding: 8px 12px;
  border: 1px solid #d1d5db;
}

Save the CSS in a stylesheet and link it to the HTML page containing the table.
