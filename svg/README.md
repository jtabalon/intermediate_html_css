# SVG

## What are SVG's?
- scalable image format
- easily scale to any size and retain quality without increasing filesize
- you can change properties through CSS and JavaScript

Most often used for:
- Icons
- Graphs
- Large, Simple Images
- Patterned Backgrounds
- Applying effects to other elements via SVG filters

## Vector Graphics vs Raster Graphics

### Vector Graphics
- defined by math
- no pixel grid
- formulas for different shapes and lines... because of these formulas provides scalability with no effect on quality or size of file

### Raster Graphics
- detail limited to size of pixel grid
- the larger the grid the bigger the file size

## Scalable Vector Graphics (Continued)

### SVG Benefits
SVG's are defined using Extensible Markup Language (XML).
- SVG's are human readable:

``` html
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100">
    <rect x=0 y=0 width=100 height=50 />
    <circle class="svg-circle" cx="50" cy="50" r="10"/>
</svg>
```

XML is designed to be interoperable with HTML, so you cna put code in the HTML file and display images out of the box.

### SVG Drawbacks
SVG's are inefficient at complex images because they need to be written in XML.