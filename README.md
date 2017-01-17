# Alpha v 1.0.0
Alpha is a LAYOUT Framework for CSS while maintaining vertical rhythm and progressive typography styles.

Alpha is based on **FLEXBOX**. This makes it not much backward compatible. So, i suggest you to add a polyfill for older browser (I.E). 

It is based on **12-COL** Grid. The Number of columns in a row show always sum to 12. If the sum of columns is greater than 12 ( >12) then the grid will collapse or overflows.

**Note** : Vertical rhythm is based on default font-family provided. 

## INFO
* Base font-size: 16px or 1em.
* Line-height: 24px or 1.5em; (i.e. font-size * 1.5).
* You can change the default vertical rhythm anytime later by editing the css file. 
* Body text is based on Wider sans-serif whereas headings are based on narrower serif.

## LINKS 
Documentation - will be updated soon

[Live Demo](http://codepen.io/Pothula/pen/bgwmvj/?editors=1100)

## CSS CLASSES 
* xs  - For device with 4-inch and less. (Eg: div class="xs-12")
* s   - For device above 4-inch. (Eg: div class="xs-12 s-12")
* m   - For Phablets and Tablets (Portrait). (Eg: div class="xs-12 s-12 m-6")
* l   - For Tablets (Landscape) and Desktop. (Eg: div class="xs-12 s-12 m-6 l-4")
* xl  - For Desktop > 1200px. (Eg: div class="xs-12 s-12 m-6 l-4 xl-4")
* xxl - For Desktop > 1800px. (Eg: div class="xs-12 s-12 m-6 l-4 xl-4 xxl-3")

## USAGE

1. Include meta tag for viewport.
2. In the body section **main** is the parent tag for all the elements.
3. Create a div with class row for containing column.
4. Now create any block element and add desired classes (eg: div class="xs-12 s-6 m-4 l-4 xl-4 xxl-4" ).
5. **Advanced usage** - You can nest a column class in another column.
