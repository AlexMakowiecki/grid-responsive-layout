# Grid Responsive Layout - Scistream
## Details
A website with scientific articles, only made to practice CSS Grid. 
The concepts learned were:
### Grid container
  - **display:grid** to assign an element as a grid container. 
  - **grid-template-columns** to assign the number and the width of the grid
  - **grid-template-rows** to assign the number and the height of the rows. Normally not used
  - **fr unit** when you want the grid columns/rows to take and share all the space of the container
    - 1 fr = 1 fraction, so if you want a column to take more, you can increase the fraction count. 
  - **grid-template** to assign both rows and columns
    * Rows first, then columns, separated by a diagonal bar:  `rows-width / columns-width`
  - **gap**, **row-gap**, **column-gap** to assign the gap/space between grid items
  - **grid-auto-rows** to assign the height of the implicit rows.
  - **grid-auto-flow:dense** to make the grid-container move the grid-items freely, trying to be as compact as possible.
    - Only recommended for image gallery, since it moves the items without respecting the order of the HTML document affecting, for example, the keyboard accessibility
### Grid item
  - **grid-column** and **grid-row** to assign the column and row of the grid item
  - **span** to make a grid item expand and take the number of columns or rows assigned
    * used in **grid-column** and **grid-row**
  - **line assign**: assign the beginning and ending line that you want the grid item to take.
    * used in **grid-column** and **grid-row** using a diagonal line to separate begin and end.
    * for reference, a grid with 12 columns, will have 13 lines
### Grid area
  - **grid-template-area** to write the grid layout explicitly
  - **grid-area** to assign an area name to a grid item, used in the grid-template-area property.
  - **blank spaces** using pointers (*.*) to write empty grid-items in the grid-template-area property. 
  - use of grid-area and blank spaces to make the website layout, simulating the use of margin and padding. 
### CSS functions
  - **repeat(count, value)** to repeat a value a 'count' times
    - used in grid-template when you have many columns or rows of the same value
  - **minmax(min, max)** to define a min and a max for a property
    - with width:minmax() the item will maintain the min width until remaining space appears on the website.  
## About Scrimba

At Scrimba our goal is to create the best possible coding school at the cost of a gym membership! 💜
If we succeed with this, it will give anyone who wants to become a software developer a realistic shot at succeeding, regardless of where they live and the size of their wallets 🎉
The Frontend Developer Career Path aims to teach you everything you need to become a Junior Developer, or you could take a deep-dive with one of our advanced courses 🚀

- [Our courses](https://scrimba.com/allcourses)
- [The Frontend Career Path](https://scrimba.com/learn/frontend)
- [Become a Scrimba Pro member](https://scrimba.com/pricing)

Happy Coding!
