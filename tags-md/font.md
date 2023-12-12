# HTML &lt;font&gt; Tag

### Defines the font, color, and size of text within its container.



## Table of content


| Properties            | Values                                                               |
|---------------------|----------------------------------------------------------------------|
| Name                | font tag                                                |
| Tag                 | &lt;font&gt;&lt;/font&gt;                                            |
| Is Paired Tag       | Yes                                                  |
| Is Block-Level Tag  | No                                |
| Included in HTML5   | No     |
| Tag Type            | Text formatting tag     |
| Deprecated in HTML5 | Yes     |


## Default Styling


-	Default **Font-Size:** Browser-dependent, set by the deprecated attributes (size attribute, CSS should be used instead).
-	Default **Font-Family:** Browser-dependent, set by the deprecated attributes (face attribute, CSS should be used instead).
-	Default **Font-Weight:** Browser-dependent, set by the deprecated attributes (weight attribute, CSS should be used instead).


<br>
<br>

## Example #1
### Use the &lt;font&gt; tag to define font-related styles for text within its container.
```html
<font size="4" color="red">This is red, size 4 text.</font>
``` 
<br>
<br>

## Example #2
### Use CSS to achieve font styling instead of the deprecated &lt;font&gt; tag.
```html
<style>
  .styled-text {
    color: red;
    font-size: 18px;
    font-weight: bold;
  }
</style>
<span class="styled-text">This is red, size 18, bold text.</span>
``` 
<br>
<br>

