Date: 2080/07/11
By: [Saroz Pokhrel](https://www.sarozpokhrel.com.np)

**HTML Tables**:

HTML tables are used to neatly organize data in rows and columns. They provide an effective way to present information, such as price lists, schedules, or specifications, making it easy for users to read and understand the content. In this video, you'll learn how to create a simple HTML table for displaying prices using table tags.

**Structure of an HTML Table**:

1. `<table>`: The `<table>` tag is used to define the entire table.
    
2. `<tr>`: The `<tr>` tag is used to create rows within the table. Each row contains table data.
    
3. `<td>`: The `<td>` tag defines individual table data cells within a row. It contains the actual content, such as dish names and prices.
    
4. `<th>`: The `<th>` tag is used to create table header cells, which provide column headings. It is typically placed in the first row of the table.
    

**Creating an HTML Table**:

1. Start with the `<table>` tag to define the table.
2. Add `<tr>` tags to create table rows. You'll have one row for each item you want to display.
3. Inside each row, add `<td>` tags to define the content of the table cells. Include the dish name and price in separate cells.
4. To add column headers, use `<tr>` for the header row and `<th>` for header cells. Include headers like "Dish" and "Price."

Here's an example of an HTML table with headers and two rows:

html

`<table>     <tr>         <th>Dish</th>         <th>Price</th>     </tr>     <tr>         <td>Falafel</td>         <td>$10</td>     </tr>     <tr>         <td>Pasta Salad</td>         <td>$12</td>     </tr> </table>`

**Styling the Table**:

To improve the visual appearance of the table, you can use CSS. In the video, a one-pixel border is added to the table to create a visual separation between cells. You can use the `<style>` tag within the HTML document to apply basic styling, but it's more common to define styles in a separate CSS file for better organization and maintainability.

Tables are a fundamental part of HTML for presenting structured data, and they can be styled in various ways to match the design of your website. As you progress in web development, you'll learn more about advanced table styling and CSS best practices.