# Lesson hightlights

- **A decorative image should not have an alt text:** If an image is a decorative image, it doesn't need to have an alt, it can be an empty string the alt. This indicates that is a decorative image.
- **The font size should be in REM:** Using REM instead of pixels let the browser adjust the font size based on the user browser preferences. If you put un pixels, that will override the browser size adjustment. It's important for accesbility.
- **Usage of CSS primitives and semantic variables:** Is very useful to have primitive variables like --clr-brown-600 and use those variables to create more semantic variables like --background-main: var(--clr-brown-600). This is a good approach to let the developer find easy the variables that should use in each use case. And it has to be avoid to use primitives en the implementation of the page.

## Important terms

- **BEM:** CSS naming convention
