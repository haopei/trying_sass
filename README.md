# First Experiment with SASS

This experiment follows the [Sass Basics](http://sass-lang.com/guide) guide.

### Project Structure
The source `.scss` files are stored inside `/src/scss`, while the public distribution files are inside `/dist/styles`. The `$ sass --watch` is used to bridge the two directories.

### How to Run
1. Open project directory and run this on the terminal: `$ sass --watch /src/scss/main.scss:dist/styles/main.css`
2. Write scss inside `/src/scss/main.scss` and see the generated CSS code within `dist/styles/main.css`.

### Featured Experiments
This experiment explored the following Sass features:
1. Variables
2. Nesting
3. Partials, using `@import` directive.
4. Mixins, using `@import` directive.
5. Extend, using `@extend` directive.
6. Mathematical Operators

See `/src/scss/main.scss` for additional comments.
