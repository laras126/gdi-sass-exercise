# GDI Sass Workshop

Hello, hello! This is a repository containing a static HTML and CSS website. Your task is to turn it into a Sass project.

### To Set Started

1. [Install Sass](http://sass-lang.com/install) and download this repository
2. Create a new folder called `scss/` to house your Sass files
3. Move `style.css` file to your `scss` directory and rename it `style.scss`
4. In the command line, `cd` into the project folder (not `css/` or `scss/`)
5. Run `sass --watch scss:css`
6. Proceed to the challenges below!

### Challenges

1. Separate out everything in `style.scss` into partials and import them
2. Create files for variables and mixins
3. Figure out which values can be variables and create variables for them (e.g. colors, device sizes, font sizes, and more!)
4. Use nesting to consolidate up the `.nav` styles and the pseudoclasses in the `.btn` and `a` selectors
5. Move the styles in the media query to inside the relevant selectors
6. Use color functions to adjust link hover styles
7. Create a button mixin
8. Add another style of button using the mixin

#### Bonus

1. Use the [Sass random](https://blog.codepen.io/2013/08/26/random-function-in-sass/) function
2. Add another parameter to the button mixin
3. Add a footer menu to the site, referencing the formatting of the top nav
4. Create a mixin for adding hover transitions of varying speeds
5. Create a sizing scale for typography, [like this](https://github.com/laras126/yuling-theme/blob/ls-tweaks/assets/scss/utils/_variables.scss#L68) one
6. Play around with the [Simple Sassy Starter](https://github.com/laras126/simple-sassy-starter)
