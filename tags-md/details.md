# HTML &lt;details&gt; Tag

### Represents a disclosure widget from which the user can obtain additional information or controls.



## Table of content


| Properties            | Values                                                               |
|---------------------|----------------------------------------------------------------------|
| Name                | details tag                                                |
| Tag                 | &lt;details&gt;&lt;/details&gt;                                            |
| Is Paired Tag       | Yes                                                  |
| Is Block-Level Tag  | Yes                                |
| Included in HTML5   | Yes     |
| Tag Type            | Interactive, used for creating a disclosure widget     |
| Deprecated in HTML5 | No     |


## Default Styling


-	Default **Font-Size:** N/A (not applicable)
-	Default **Font-Family:** N/A (not applicable)
-	Default **Font-Weight:** N/A (not applicable)


<br>
<br>

## Example #1
### Use the &lt;details&gt; tag to create a disclosure widget with nested content.
```html
<details>
  <summary>Click to view details</summary>
  <p>Additional information goes here.</p>
</details>
``` 
<br>
<br>

## Example #2
### You can nest details elements to create hierarchical disclosure widgets.
```html
<details>
  <summary>Outer Details</summary>
  <p>Outer details content.</p>
  <details>
    <summary>Inner Details</summary>
    <p>Inner details content.</p>
  </details>
</details>
``` 
<br>
<br>

