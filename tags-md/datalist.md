# HTML &lt;datalist&gt; Tag

### Contains a set of &lt;option&gt; elements that represent the permissible or suggested options available to users.



## Table of content


| Properties            | Values                                                               |
|---------------------|----------------------------------------------------------------------|
| Name                | datalist tag                                                |
| Tag                 | &lt;datalist&gt;&lt;/datalist&gt;                                            |
| Is Paired Tag       | Yes                                                  |
| Is Block-Level Tag  | No                                |
| Included in HTML5   | Yes     |
| Tag Type            | Interactive, used for providing a predefined list of options     |
| Deprecated in HTML5 | No     |


## Default Styling


-	Default **Font-Size:** N/A (not applicable)
-	Default **Font-Family:** N/A (not applicable)
-	Default **Font-Weight:** N/A (not applicable)


<br>
<br>

## Example #1
### Use the &lt;datalist&gt; tag to define a list of options for an input element.
```html
<label for="browser">Choose a browser:</label>
<input list="browsers" id="browser" name="browser"/>
<datalist id="browsers">
  <option value="Chrome">
  <option value="Firefox">
  <option value="Safari">
  <option value="Edge">
  <option value="Opera">
</datalist>
``` 
<br>
<br>

