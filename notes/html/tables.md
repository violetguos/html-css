


1.  When should you use tables?
- mark up structured tabular data
- A long time ago, tables were used to structure pages instead of CSS. Don't do that...

2. What is the structure of a table?
- table
- table row
- table data
- table header
- table caption


3. What are the special tags that dictate certain parts of a table, e.g. headers or captions?
```
<table>
  <caption>Design and Front-End Development Books</caption>
  <tr> <!--row-->
    <th scope="col">Item</th>
    <th scope="col">Availability</th>
   
  </tr>
  <tr>
    <td>Don&#8217;t Make Me Think by Steve Krug</td>
    <td>In Stock</td>
  
  </tr>
  
  <!-- more rows with tr -->
</table>
```

4. How can you combine cells in a table?
- use `border-collapse: collapse` css property
- customize the html tag, e.g. `<th scope="col" colspan="2">Item</th>`

5. Why do you need to be careful about your padding and borders in tables?
- The `border-spacing` property works only when the `border-collapse` property value is `separate`
6. How do you align text within cells in a table?
- `text-align` css property: move text horizontally
- `vertical-align`: works only with inline and table-cell elements, NOT  block, inline-block, etc
