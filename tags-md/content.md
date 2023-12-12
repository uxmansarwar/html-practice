# HTML &lt;content&gt; Tag

### Represents the shadow DOM content insertion point in a shadow tree.



## Table of content


| Properties            | Values                                                               |
|---------------------|----------------------------------------------------------------------|
| Name                | content tag                                                |
| Tag                 | &lt;content&gt;&lt;/content&gt;                                            |
| Is Paired Tag       | Yes                                                  |
| Is Block-Level Tag  | No                                |
| Included in HTML5   | Yes     |
| Tag Type            | Obsolete     |
| Deprecated in HTML5 | Yes     |


## Default Styling


-	Default **Font-Size:** N/A (not applicable)
-	Default **Font-Family:** N/A (not applicable)
-	Default **Font-Weight:** N/A (not applicable)


<br>
<br>

## Example #1
### The &lt;content&gt; tag was used in the shadow DOM to define insertion points for distributed content.
```html
<shadow-root>
  <content select="p"></content>
</shadow-root>
``` 
<br>
<br>

## Example #2
### The &lt;content&gt; tag is deprecated in HTML5. Use the &lt;slot&gt; element instead.
```html
<shadow-root>
  <slot name="p"></slot>
</shadow-root>
``` 
<br>
<br>

