### refers to

- [grid](https://developer.mozilla.org/en-US/docs/Web/CSS/grid)


### words:

- gutter 槽
- fr fraction 部分  
- rectangular  矩形的
- . period


### index
- what is grid layout?
- creating your grid in css
- - defining a grid
  - flexible grids with fr unit
  - gaps between tracks
  - repeating track listings
  - the implicit and explicit grid
  - the minmax() function
  - as many columns as will fit
- line-based placement
- positioning with grid-template-areas
- a css grid, grid framework


### usage
container:

- grid
- - grid-auto-columns
- - grid-auto-flow
- - grid-auto-rows
- - grid-template-areas
- - grid-template-columns
- - grid-template-rows
- - grid-column-gap
- - grid-row-gap
- - column-gap
- - row-gap
- grid-gap (gap)
- - grid--row-gap
  - grid-column-gap
- grid-column
- - grid-column-start
  - grid-column-end
- grid-row
- - grid-row-start
  - grid-row-end


### example
```css
grid-template-coloumns: 200px 200px 200px;   
grid-template-columns: 1fr 1fr 1fr
grid-template-columns: repeat(3, 1fr)
grid-auto-rows: 100px;
grid-auto-rows: minmax(100px, auto)
grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
grid-template-areas: {
    "header header ."
    "sidebar . content"
    ". footer footer"
}
header {
	grid-area: header
}
```


fr: represents one fraction of the available space in the grid container.

 The fr unit distributes space in proportion 比例,available space not all space. Therefore if one of your tracks has something large inside it , there will be less free space to share out.

 

