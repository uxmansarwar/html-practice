# HTML &lt;output&gt; Tag

### Represents the result of a calculation or user action in a form.



## Table of content


| Properties            | Values                                                               |
|---------------------|----------------------------------------------------------------------|
| Name                | output tag                                                |
| Tag                 | &lt;output&gt;&lt;/output&gt;                                            |
| Is Paired Tag       | Yes                                                  |
| Is Block-Level Tag  | No                                |
| Included in HTML5   | Yes     |
| Tag Type            | Form-related tag     |
| Deprecated in HTML5 | No     |


## Default Styling


-	Default **Font-Size:** Not Applicable
-	Default **Font-Family:** Not Applicable
-	Default **Font-Weight:** Not Applicable


<br>
<br>

## Example #1
### You can use the &lt;output&gt; tag to display the result of a calculation within a form.
```html
<form oninput="result.value=parseInt(a.value)+parseInt(b.value)">
  <input type="range" id="a" value="50">+
  <input type="number" id="b" value="50">
  =<output name="result" for="a b">100</output>
</form>
``` 
<br>
<br>

