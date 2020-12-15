# CSS GRID Intro.
## Notes on Grid Lecture 
* Flex Box is for one row and one column.
* FYI `text-align: center;` great for centering text within box.

### Grid 
* To activate grid we need to set `display: grid;` in our container
* Grid Template Columns = grid-template-columns: %;
* Grid Template Rows = grid-template-rows: %;
* Example: `grid-template-columns: 15% 60% 25%;`
* Example: `grid-template-rows: 15% 35% 35% 15%;`

### Grid Lines 
* Lines between rows and columns.
* grid-row: 1/2; tells us we are making the container stretch from row line 1 / 2. 
* grid-row: lines run vertically up and down.
* grid-column: 1/4; tells the container to stretch from column line 1/4.
* grid-column: lines run horizontally left to right.
* `See style.css file for example.` 

# Display Flex - Media Query - Lecture Notes
* For images to be flexible when sizes vary.
* `flex-wrap: wrap;` is one way of accomplishing this.
* `@media query`
* In the brackets we can apply a set of `rules.`
* To add columns we would have to adjust the HTML and wrap the items in `sections.`

### Media Query
```javascript
@media( max-width: 1200 px) {
    .square{
        background-color: red;
    }

    .container {
        flex-direction: column;
    }
}
```
 












