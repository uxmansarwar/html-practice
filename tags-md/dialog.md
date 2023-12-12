# HTML &lt;dialog&gt; Tag

### Represents a dialog box or a window.



## Table of content


| Properties            | Values                                                               |
|---------------------|----------------------------------------------------------------------|
| Name                | dialog tag                                                |
| Tag                 | &lt;dialog&gt;&lt;/dialog&gt;                                            |
| Is Paired Tag       | Yes                                                  |
| Is Block-Level Tag  | No                                |
| Included in HTML5   | Yes     |
| Tag Type            | Interactive, used for creating a dialog or popup     |
| Deprecated in HTML5 | No     |


## Default Styling


-	Default **Font-Size:** N/A (not applicable)
-	Default **Font-Family:** N/A (not applicable)
-	Default **Font-Weight:** N/A (not applicable)


<br>
<br>

## Example #1
### Use the &lt;dialog&gt; tag to create a dialog box with content.
```html
<dialog open>
  <p>This is a dialog box content.</p>
  <button>Close</button>
</dialog>
``` 
<br>
<br>

## Example #2
### You can interact with the dialog using JavaScript, such as opening or closing it.
```html
<script>
  var dialog = document.querySelector('dialog');
  dialog.showModal();
</script>
``` 
<br>
<br>

