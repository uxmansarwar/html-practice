# HTML &lt;map&gt; Tag

### Defines an image map, associating areas of the image with specific hyperlinks or other actions.



## Table of content


| Properties            | Values                                                               |
|---------------------|----------------------------------------------------------------------|
| Name                | map tag                                                |
| Tag                 | &lt;map&gt;&lt;/map&gt;                                            |
| Is Paired Tag       | Yes                                                  |
| Is Block-Level Tag  | No                                |
| Included in HTML5   | No     |
| Tag Type            | Image map element tag     |
| Deprecated in HTML5 | No     |


## Default Styling


-	Default **Font-Size:** Browser-dependent, typically inherits from the surrounding text.
-	Default **Font-Family:** Browser-dependent, typically inherits from the surrounding text.
-	Default **Font-Weight:** Browser-dependent, typically inherits from the surrounding text.


<br>
<br>

## Example #1
### You can use the &lt;map&gt; tag along with &lt;area&gt; tags to create an image map.
```html
<img src="planets.jpg" usemap="#planetmap" alt="Planets">
<map name="planetmap">
  <area shape="rect" coords="34,44,270,350" href="sun.html" alt="Sun">
  <!-- Other areas go here -->
</map>
``` 
<br>
<br>

