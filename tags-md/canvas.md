# HTML &lt;canvas&gt; Tag

### Defines an area for drawing graphics using JavaScript.



## Table of content


| Properties            | Values                                                               |
|---------------------|----------------------------------------------------------------------|
| Name                | canvas tag                                                |
| Tag                 | &lt;canvas&gt;&lt;/canvas&gt;                                            |
| Is Paired Tag       | Yes                                                  |
| Is Block-Level Tag  | No                                |
| Included in HTML5   | Yes     |
| Tag Type            | Graphic tag     |
| Deprecated in HTML5 | No     |


## Default Styling


-	Default **Font-Size:** N/A (inline element)
-	Default **Font-Family:** N/A (inline element)
-	Default **Font-Weight:** N/A (inline element)


<br>
<br>

## Example #1
### Create a basic canvas element for drawing graphics.
```html
<canvas id="myCanvas" width="200" height="100"></canvas>
``` 
<br>
<br>

## Example #2
### Use JavaScript to draw on the canvas.
```html
var canvas = document.getElementById('myCanvas');
var context = canvas.getContext('2d');
context.fillRect(0, 0, 200, 100);
``` 
<br>
<br>

