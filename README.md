# foundation-dynamic-tables

Designed to enable **easier reading of tables on mobile devices**, this simple bit of code displays a table which, under a particular screen size, displays the information vertically rather than horizontally and places the header text next to each item.

**Larger screen table appearance**
<img src="https://github.com/akavy/foundation-dynamic-tables/blob/master/LargeTable.png" alt="Large view of table" />

**Mobile screen table appearance**
NOTE: Red colouring is just for effect .. see the notes in the file.
<img src="https://github.com/akavy/foundation-dynamic-tables/blob/master/MobileViewTable.png" alt="Mobile view of table" />

The styling system utilises the [Zurb Foundation Sites](http://foundation.zurb.com) styling framework (version 6.2.3).

There are a couple of additional styles at the top of the code to demonstrate the ability to customise the information based on whether it is a horizontal or vertical table.

This code has repeating header `<span>` statements for each table cell, so that **it will work without the use of Javascript**. However you can vastly reduce the amount and maintainability of your code by adding some Javascript which adds the header labels automatically.

# License

This code is published under the MIT License. Hopefully you will find it useful.

Happy coding :)

Jonathan @ akavy
[jonathan@akavy.com](mailto:jonathan@akavy.com)
