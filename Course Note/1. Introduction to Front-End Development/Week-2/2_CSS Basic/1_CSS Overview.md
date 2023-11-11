**CSS Overview:**

- CSS (Cascading Style Sheets) is a styling language that complements HTML by defining how HTML elements should be displayed on the web page.

**Elements of a CSS Rule:**

1. **Selector:**
    
    - The selector specifies the HTML element or elements to which the style will be applied.
    - Examples:
    ```css
    h1 {
  color: blue;
  background-color: gray;
}
```

        - `h1`: Targets all `<h1>` (heading one) elements.
        - `.class`: Targets all elements with a specific class.
        - `#id`: Targets a specific element with a unique ID.


1. **Declaration Block:**
    
    - The declaration block is enclosed in curly brackets `{}` and contains style declarations.
    - Example:
        
        css

```css
h1 {
  color: blue;
  background-color: gray;
}
```
        

- - `h1 {   color: blue;   background-color: gray; }`
        
- **Declaration:**
    
    - A declaration consists of a property and its corresponding value, separated by a colon.
    - Ends with a semicolon.
    - Example:
        
        css

```css
color: blue;
```
        . - `color: blue;`
        
2. **Property:**
    
    - Describes the specific aspect of the element to be styled.
    - Examples: `color`, `font-size`, `margin`, `background-color`.
3. **Value:**
    
    - Specifies the value of the property.
    - Example: `blue`, `16px`, `10%`, `#F0F0F0`.

**Applying CSS Rules:**

- CSS rules are applied based on selectors, determining which HTML elements will receive the specified styles.
- Selectors can be broad, affecting multiple elements, or specific to target individual elements.

**CSS Precedence and Specificity:**

- CSS rules may conflict, and the browser uses precedence and specificity to determine which rule takes effect.
- Specificity is based on the type of selector (ID, class, element type).

**Pro Tip - Live Preview in VS Code:**

- The Live Preview extension in Visual Studio Code allows you to see real-time updates to your HTML and CSS without manually refreshing the browser.