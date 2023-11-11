
**Applying Styles to Specific Elements:**

When you want to style a specific `<h1>` element, you can use an ID attribute to uniquely identify that element. Here's a detailed explanation of this process:

1. **Adding ID Attribute:**
    
    - In your HTML file, add an `id` attribute to the `<h1>` element you want to style. For example:
        
```html
- - `<h1 id="header-one">Chapter One</h1>`
```

        
        
- **Creating an ID Rule in CSS:**
    
    - In your CSS file, create a rule for the specific ID. Use the hash symbol (`#`) followed by the ID name (`header-one`) as the selector.
        
```css
1. - `#header-one {   color: green; }`
```
        


        
2. **Applying the Rule:**
    
    - Save the CSS file, and you'll notice that the text for the `<h1>` element with the ID `header-one` turns green.
3. **Understanding CSS Precedence and Specificity:**
    
    - CSS follows rules of precedence and specificity when applying styles.
    - In this case, the ID selector (`#header-one`) is more specific than the HTML type selector (`h1`), so the styles defined for the ID take precedence.
4. **CSS Specificity:**
    
    - Specificity is a measure of how specific a selector is. IDs have higher specificity than class selectors, and class selectors have higher specificity than element type selectors.
    - When conflicts arise, the browser applies the styles based on specificity.

**Example:**

```html

`<!-- HTML --> <!DOCTYPE html> <html lang="en">
<head>  
<meta charset="UTF-8">   
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<link rel="stylesheet" href="style.css">   
<title>CSS Styling</title> 
</head>
<body>  
<h1 id="header-one">Chapter One</h1>  
<h1>Title of Another Chapter</h1> 
</body> 
</html>`
```

```css

`/* CSS - style.css */ h1 {   color: blue;   background-color: gray; }  #header-one {   color: green; }`
```



In this example, the first CSS rule (`h1` selector) sets styles for all `<h1>` elements. The second rule (`#header-one` selector) sets specific styles for the `<h1>` element with the ID `header-one`. The ID rule takes precedence due to its high