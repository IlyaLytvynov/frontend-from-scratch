# CSS Practice Solutions

```css
/* 1. Tag Selector */
p {
    color: blue;
}

/* 2. Class Selector */
.highlight {
    background-color: yellow;
}

/* 3. Multiple Class Selectors */
.alert.warning {
    color: red;
}

/* 4. ID Selector */
#header {
    font-size: 24px;
}

/* 5. Attribute Selector */
a[target="_blank"] {
    text-decoration: underline;
}

/* 6. Descendant Selector */
.container p {
    color: green;
}

/* 7. Pseudo-class Selector */
button:hover {
    background-color: grey;
}

/* 8. Grouping Selectors */
h1, h2, h3 {
    color: brown;
}

/* 9. Child Selector */
ul > li {
    border: 1px dashed black;
}

/* 10. Adjacent Sibling Selector */
h2 + p {
    font-style: italic;
}
