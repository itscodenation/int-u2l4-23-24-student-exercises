# Lesson 2.4: Class Attributes

## 🎯 Objectives
- Understand and use class attributes in HTML and CSS to style specific elements.
- Differentiate between tag selectors and class selectors.


## Table of Contents
- [Key Concepts](#key-concepts)
  - [Class Attributes](#class-attributes)
  - [CSS Specificity](#css-specificity)
  - [Steps to Using Class Attributes](#steps-to-using-class-attributes)
- [Error Spotting](#error-spotting)

## Key Concepts

### Class Attributes
- **Definition**: Class attributes enable you to apply styles to specific HTML elements, rather than all elements of the same type.
- **Syntax**: `<tag class="classname">content</tag>`
- **CSS Selector**: To apply styles, use a period before the class name in your CSS file: 
  ```css
  .classname { property: value; }
  ```

### CSS Specificity
- **Definition**: Specificity determines which CSS rules are applied to an element when there are conflicting styles.
- **Order of Precedence**: 
  1. Inline styling
  2. IDs
  3. Class, attributes & pseudo-classes
  4. Elements & pseudo-elements

### Steps to Using Class Attributes
1. **HTML**: Decide which tags to style differently and add a class attribute with a meaningful name.
2. **CSS**: Write the styling rules using the class selector.
3. **Example**: 
  ```html
  <p class="highlight">Important text</p>
  ```
  ```css
  .highlight { background-color: yellow; }
  ```

## Error Spotting
- **Case Sensitivity**: Class names are case-sensitive; make sure to match the exact case in both HTML and CSS.

<br>

Happy coding!