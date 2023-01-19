# Foundations / CSS Foundations Knowledge Checks

## 4.1 CSS Foundations

1. What are the main differences between external, internal, and inline CSS?

    External CSS is a CSS file linked to an HTML file.

    Internal CSS is CSS embedded using the `<style>` element.

    Inline CSS is CSS using `<style>=...` directly within an identifier.

2. What is the syntax for class and ID selectors?

    Class: `class = sample` in HTML, `.sample` in CSS.

    ID: `ID = sample` in HTML, #sample` in CSS.

3. How would you apply a single rule to two different selectors?

    Chaining: `.selector-one, .selector-two {}`

4. Given an element that has an id of title and a class of primary, how would you use both attributes for a single rule?

    `.primary#title {}`

5. What does the descendant combinator do?

    Select only elements of the latter selector that also have an ancestor of the previous selector.

6. Between a rule that uses one class selector and a rule that uses three type selectors, which rule has the higher specificity?

    One class selector

## 4.2 Inspecting HTML And CSS

1. How do you select a specific element on your page with your browser’s developer tools?

    Right click > Inspect Element

2. What does a strikethrough in a CSS element mean in your browser’s developer tools?

    The style rule has been superceded by another rule.

3. How do you change CSS in real time on specific elements of a web page with your browser’s developer tools?

    Inspect Element > Styles tab

## 4.3 The Box Model

1. From inside to outside, what is the order of box-model properties?

    Padding, border, margin

2. What does the box-sizing CSS property do?

    Sets the total size of the element to `width` and turns all other spacing inwards

3. What is the difference between the standard and alternative box model?

    Whether `box-sizing` is used

4. Would you use margin or padding to create more space between 2 elements?

    Margin

5. Would you use margin or padding to create more space between the contents of an element and its border?

    Padding

6. Would you use margin or padding if you wanted two elements to overlap each other?

    Margin

## Block and Inline

1. What is the difference between a block element and an inline element?

    Block elements are placed on a new line. Vertical margin is respected.

    Inline elements are placed on the current line. Vertical margin is not respected.

2. What is the difference between an inline element and an inline-block element?

    Inline-block elements are on the same line, but their margin is respected.

3. Is an h1 block or inline?

    Block

4. Is button block or inline?

    Inline

5. Is div block or inline?

    Block

6. Is span block or inline?

    Inline