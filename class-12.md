# sumary class 12 

## Chart in javascript
it's amethod to display data instead of table. the chart is more clear than table. there is three type of charts, which are par chart, pie chart and line chart. 
we use with chart `<canvas>`, which has two attributes hight and width. canvas tag is like img tag. The `<canvas>` element has a method called getContext(), used to obtain the rendering context and its drawing functions. we are using functions to draw rectangle, path, arc and line. for change color we use two properties fillStyle and strokeStyle. Also, we can do line style by using several properties.



**you can draw rectangle on the canvas by using three functions:**
1. fillRect(x, y, width, height)
2. strokeRect(x, y, width, height)
3. clearRect(x, y, width, height) making it full transparent

**drawing function for path:**
1. beginPath()
2. closePath()
3. stroke()
4. fill()

**line style:**
1. getLineDash()
2. setLineDash(segments)
3. lineDashOffset = value

**for text:**
1. fillText(text, x, y [, maxWidth])
2. strokeText(text, x, y [, maxWidth])
3. measureText()

