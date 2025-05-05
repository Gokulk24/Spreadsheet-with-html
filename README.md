# Spreadsheet-with-html
<!DOCTYPE html>
<html>
<head>
  <title>Simple Spreadsheet</title>
  <style>
    table {
      border-collapse: collapse;
    }
    td, th {
      border: 1px solid #ccc;
      padding: 10px;
      min-width: 80px;
      text-align: center;
    }
    td[contenteditable="true"] {
      background-color: #f9f9f9;
    }
  </style>
</head>
<body>
  <h2>Simple Spreadsheet</h2>
  <table id="spreadsheet">
    <thead>
      <tr>
        <th></th>
