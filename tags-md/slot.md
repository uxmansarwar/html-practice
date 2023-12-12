# HTML &lt;slot&gt; Tag

### Represents a placeholder inside a shadow tree where the content of the shadow host (parent) will be inserted.



## Table of content


| Properties            | Values                                                               |
|---------------------|----------------------------------------------------------------------|
| Name                | slot tag                                                |
| Tag                 | &lt;slot&gt;&lt;/slot&gt;                                            |
| Is Paired Tag       | Yes                                                  |
| Is Block-Level Tag  | No                                |
| Included in HTML5   | Yes     |
| Tag Type            | Shadow DOM tag     |
| Deprecated in HTML5 | No     |


## Default Styling


-	Default **Font-Size:** Browser-dependent, typically inherits from the surrounding text.
-	Default **Font-Family:** Browser-dependent, typically inherits from the surrounding text.
-	Default **Font-Weight:** Browser-dependent, typically inherits from the surrounding text.


<br>
<br>

## Example #1
### The &lt;slot&gt; tag is used within a Shadow DOM to define where the content from the host should be inserted.
```html
<div id="container">
  <p>Regular DOM content outside the shadow tree.</p>
  <shadow></shadow>
</div>
``` 
<br>
<br>

