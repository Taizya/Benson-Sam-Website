## TODO

**Always make sure the content in the section is horizontally and vertically centered**
**Do not run any npm commands**
**Always use em for sizing in css**

- Make the following changes in the @src/pages/index.astro

1. Modify the css of the why-choose-us section to work in the same way the value-proposition section works in the
   @src/pages/about.astro. Don't use the class used by value-proposition just extrapulate the styles and use a more fitting
   class for the why-choose-us section or if possible extrapulate the stles and edit the ImageBackgroundSection so that it
   can support the same styling for heading text that have been used in the value-proposition section so that the styles are not
   duplicated everywhere it is used. If you implement this correctly it should allow me to remove the styles in the about.astro
   that are duplicating this effect and not have any issues.
   The goal is to allow sections in any page using the ImageBackgroundSection layout to have the same styling for text headings
   that are currently being used in the value-proposition section of the about.astro
