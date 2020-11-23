# A design system for more efficient development

## Motivation

I often end up spending too much of my developing time in considerations regarding things like font sizes, line heights, palettes etc. Furthermore, I've found that every time I use some kind of design system which is defined in advance, the design ends up looking much more consistent and better.

In order to speed up and improve the styling process of any project I've created this `default-styles.css` stylesheet.

## Systems and Reset

The `default-styles.css` stylesheet includes design systems for the following aspects of CSS:

1. Font weight
2. Font weight
3. Line height
4. Colors
5. Margin
6. Padding
7. Breakpoints
8. Width
9. Height
10. Box shadows
11. Border radius
12. Border width
13. Opacity

In addition to the above mentioned systems, I've incorporated a **CSS reset** based on [Richard Clark's HTML5 reset](http://html5doctor.com/html-5-reset-stylesheet/) and a **Box Model** based on [the Universal Box Sizing with Inheritance](https://css-tricks.com/box-sizing/#universal-box-sizing-with-inheritance).

## The color system

The coloring system is based on 14 different color palettes. Each palette is divided into three parts: _primary_, _neutral_ and _supporting_. Furthermore, each color in the palettes come in 10 different variations. The reason why is that you probably need more colors than you might think - a color palette needs to be comprehensive in order to create those small nuances that makes the design beautiful.

To use a palette, simply comment out all the palettes you don't need an only import the one you're going to use.

## Browser support

Since the design system is based on CSS variables. One thing to note is that CSS variables [lack native IE support](https://caniuse.com/css-variables). However, the [css-vars-ponyfill](https://jhildenbiddle.github.io/css-vars-ponyfill/#/)
