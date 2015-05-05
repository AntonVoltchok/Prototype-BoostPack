# Prototype BoostPack
### Responsive Rapid Prototyping Helpers - No Dependencies

I noticed Ionic as well as a few other mobile front-end frameworks 
had some basic helper classes which I liked a lot, so I decided to add 
in a few more which have no dependencies.

The idea is this would help in an Agile environment where
changes are continuous and unpredictable. The layout would be done 
mostly in HTML with helper classes. This way when changes happen
instead of searching through a bunch of css, most layout changes
could instead be done quickly and easily by making a few class changes in HTML while still keeping the HTML relatively semantic.

* _layout.scss : basic layout helper classes
* _simplegrid : extremely minimal grid setup from Graham Miller, as simple as it gets
* _mixins : so far some basic SCSS media queries
* _reset : Eric Meyer's reset
* _variables : a few example classes
* _type : a few example classes
* _components : if basic prototype all components can go here, if complex, split it up ex: buttons, etc...

Next I'm planning on adding some javascript helper functions and expanding on the css helpers while keeping 
everything as minimal as possible.
