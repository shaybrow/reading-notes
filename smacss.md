# SMACSS and Responsive Web Design

[Back to Main Page](README.md)

## Responsive Web Design

In order to accomodate both mobile devices and computers websites need to be built out to support both using RWD

### Flexible Layouts

- broken down into 3 parts: flexible layouts, media queries and flexible media

- don't use fixed measurements

- using `target/context = result` we can determine percentages to keep the size of elements relatively the same across different screen sizes

### Media Queries

- allow you to specify different syles for different browsers and devices

- provide us the ability to determine presentation based on what sort of viewport our user is using

- if no media type is included rules will default to all

### Mobile FIrst

- use styles primarily targeted to smaller views then rules for adding styles as the viewports get larger

### Viewport

- `viewport` is a meta tag that allows us to define the scale, width or height of the viewport

- you will need to create specific rules if you're including media on your website as it will not scale automatically

## Floats

- a positioning property used to allow text to flow around the element

- can be used to create a web layout top to bottom

### Clear

- if an element has the clear property it will move down onto the next line despite the float