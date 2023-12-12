# HTML &lt;form&gt; Tag

### Represents an HTML form, used for collecting user input.



## Table of content


| Properties            | Values                                                               |
|---------------------|----------------------------------------------------------------------|
| Name                | form tag                                                |
| Tag                 | &lt;form&gt;&lt;/form&gt;                                            |
| Is Paired Tag       | Yes                                                  |
| Is Block-Level Tag  | Yes                                |
| Included in HTML5   | No     |
| Tag Type            | Form tag     |
| Deprecated in HTML5 | No     |


## Default Styling


-	Default **Font-Size:** Browser-dependent, typically inherits from the surrounding text.
-	Default **Font-Family:** Browser-dependent, typically inherits from the surrounding text.
-	Default **Font-Weight:** Browser-dependent, typically inherits from the surrounding text.


<br>
<br>

## Example #1
### Use the &lt;form&gt; tag to create an HTML form for user input.
```html
<form action="/submit" method="post">
  <!-- Form elements go here -->
  <input type="text" name="username" placeholder="Username">
  <input type="password" name="password" placeholder="Password">
  <button type="submit">Submit</button>
</form>
``` 
<br>
<br>

## Example #2
### Apply CSS styles to enhance the appearance of the form.
```html
<style>
  form {
    border: 1px solid #ccc;
    padding: 10px;
  }
</style>
<form action="/submit" method="post">
  <!-- Form elements go here -->
  <input type="text" name="username" placeholder="Username">
  <input type="password" name="password" placeholder="Password">
  <button type="submit">Submit</button>
</form>
``` 
<br>
<br>

