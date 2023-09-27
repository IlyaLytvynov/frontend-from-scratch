# Box Model and Flexbox Practice Solutions

```css
/* 1. Display Properties */
.blockDiv {
    display: block;
    background-color: #FF5733; /* Example color */
}

.inlineBlockDiv {
    display: inline-block;
    background-color: #33FF57; /* Example color */
}

.inlineDiv {
    display: inline;
    background-color: #5733FF; /* Example color */
}

/* 2. Padding & Margin */
.paddedMarginDiv {
    width: 100px;
    height: 100px;
    padding: 20px;
    margin: 30px;
    background-color: #FF33A1; /* Example color */
}

/* 3. Box-sizing Property */
.boxSizingDiv {
    width: 100px;
    height: 100px;
    padding: 20px;
    box-sizing: border-box;
    background-color: #A133FF; /* Example color */
}

/* 4. Collapsing Margins */
.collapsingDiv1, .collapsingDiv2 {
    margin-top: 15px;
    margin-bottom: 15px;
    background-color: #FFA133; /* Example color for the first div */
}

.collapsingDiv2 {
    background-color: #33FFF6; /* Example color for the second div */
}

/* 5. Flex Container */
.flexContainer {
    display: flex;
    background-color: #FF6533; /* Example color */
}

.flexItem {
    width: 50px;
    height: 50px;
    background-color: #6533FF; /* Example color for child divs */
    margin: 5px;
}

/* 6. Justify-content */
.justifiedFlexContainer {
    display: flex;
    justify-content: space-between;
    background-color: #33FF65; /* Example color */
}

/* 7. Align-items */
.centerAlignedFlexContainer {
    display: flex;
    height: 200px; /* This height is set to observe the centering */
    align-items: center;
    background-color: #FF3365; /* Example color */
}

/* 8. Flex Direction */
.columnFlexContainer {
    display: flex;
    flex-direction: column;
    background-color: #65FF33; /* Example color */
}

/* 9. Flex-grow, Flex-shrink, and Flex-basis */
.flexContainerForGrow {
    display: flex;
    background-color: #6533FF; /* Example color */
}

.growingDiv {
    flex-grow: 2;
    background-color: #33FFA1; /* Example color */
}

/* For experimentation with flex-shrink and flex-basis, you might need specific container sizes or additional properties. */

/* 10. Wrapping Flex Items */
.wrappingFlexContainer {
    display: flex;
    flex-wrap: wrap;
    width: 150px; /* This width is set to observe the wrapping */
    background-color: #A1FF33; /* Example color */
}

.wrappingItem {
    width: 50px;
    height: 50px;
    background-color: #FF33F6; /* Example color */
    margin: 5px;
}
