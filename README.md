# Red v 1.0.1
Red is a LAYOUT Framework for CSS based on **FLEXBOX** Property.

This makes it unsuitable for browser which does not support **FLEXBOX**.. So, i suggest you to add a polyfill for older browser (I.E). 

It is based on **12-COL** Grid. The Number of columns in a row show always sum to 12. If the sum of columns is greater than 12 ( >12) then the grid will collapse or overflows.

## LINKS 
Documentation - will be updated soon

[Live Demo](http://codepen.io/Pothula/pen/bgwmvj/?editors=1100)

## CSS CLASSES 
* col-xs-*   - For device with 4-inch and less. (Eg: div class="col-xs-12")
* col-sm-*   - For device above 4-inch. (Eg: div class="col-xs-12 col-sm-12")
* col-md-*   - For Phablets and Tablets (Portrait). (Eg: div class="col-xs-12 col-sm-12 col-md-6")
* col-lg-*   - For Tablets (Landscape) and Desktop. (Eg: div class="col-xs-12 col-sm-12 col-md-6 col-lg-4")
* col-xl-*   - For Desktop > 1200px. (Eg: div class="col-xs-12 col-sm-12 col-md-6 col-lg-4 col-xl-4")
* col-xxl-*  - For Desktop > 1800px. (Eg: div class="col-xs-12 col-sm-12 col-md-6 col-lg-4 col-xl-4 col-xxl-3")

## USAGE

1. Include meta tag for viewport.
2. In the body section create **main** tag and append all the elements except nav and footer.
3. Create a div with class **.row** for containing column.
4. Now create any block element inside **.row** and add desired classes (eg: div class="xs-12 s-6 m-4 l-4 xl-4 xxl-4" ).
5. **Advanced usage** - You can nest a column class in another column.
