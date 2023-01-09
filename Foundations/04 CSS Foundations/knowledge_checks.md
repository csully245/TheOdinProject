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