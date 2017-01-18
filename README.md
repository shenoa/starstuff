# Starstuff

Here's a quick rundown of my decisions on the exercise.

## html

The html is pretty self explanatory. I included a title and meta description I thought matched the content and would be appropriate for SEO purposes. I used html5 tags to define the structure in a way that would be easy to create css styles matching the layout. Minimal classes kept the code on the lean side, but would need to be extended if this content was added to a more complex layout. I added a few role attributes, as I'm currently researching ARIA compatibility with the intention to implement them more frequently as a matter of routine.

## CSS

Sass is a huge time saver, and my preferred method of generating CSS. I used a reset which allowed me to have a more consistent layout without having to accommodate browser differences in default page rendering. With CSS, layout choices can vary greatly depending on what type of backwards compatibility the project requires. Since only recent browser versions were within scope, I decided to use flexbox for the layout. This is actually an area I don't have as much experience with, so I was happy to be able to implement the layout in that manner.

Most of the rest of the CSS is fairly straight-forward. When architecting a larger site, I usually break the css into Sass partials for ease of maintenance, but that wasn't sensible for a small demo project.

## Mobile

Had there been more mobile layouts to consider than just a single break point, I would have opted for a more sophisticated way of handling of media queries. The tablet sizes seem to render either the mobile or the desktop version in an acceptable way.

## In Summary

Many thanks for taking the time to review my application. I hope to meet you in person soon!
