# HTML &lt;!doctype&gt; Tag

### Specifies the document type and version of HTML being used. Usually found at the beginning of an HTML document.


## Imported Things
| #   | **Aspect**                       | **Description**                                                |
| --- | ---------------------------------| -------------------------------------------------------------- |
| 1   | **Definition:**                  | Specifies the document type and version of HTML being used.    |
| 2   | **Purpose:**                     | Ensures the web browser renders the HTML document correctly.   |
| 3   | **Compatibility Mode:**          | Influences the browser's rendering mode for backward compatibility. |
| 4   | **Document Validation:**         | Helps validate HTML code against specified Document Type Definitions (DTD). |
| 5   | **XHTML Transition:**            | Used to transition from HTML to XHTML, signaling a stricter syntax. |
| 6   | **Placement:**                   | Typically placed at the very beginning of an HTML document.    |
| 7   | **Document Version Information:**| Indicates the HTML version and helps browsers interpret the code accordingly. |



## Table of content
| Properties            | Values                                                               |
|---------------------|----------------------------------------------------------------------|
| Name                | doctype tag                                                |
| Tag                 | &lt;!doctype&gt;                                            |
| Is Paired Tag       | No                                                  |
| Is Block-Level Tag  | No                                |
| Included in HTML5   | No     |
| Tag Type            | Document Structure     |
| Deprecated in HTML5 | No     |


## Default Styling


-	Default **Font-Size:** N/A
-	Default **Font-Family:** N/A
-	Default **Font-Weight:** N/A


<br>
<br>


## Example #1
### XHTML 1.0 Frameset:
```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Frameset//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-frameset.dtd">
``` 

<br>
<br>

## Example #2
### HTML 4.01 Strict:
```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
``` 
<br>
<br>

## Example #3
### HTML 4.01 Transitional:
```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
``` 
<br>
<br>

## Example #4
### HTML 4.01 Frameset:
```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/frameset.dtd">
``` 
<br>
<br>

## Example #5
### XHTML 1.0 Strict:
```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
``` 
<br>
<br>

## Example #6
### XHTML 1.0 Transitional:
```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
``` 

<br>
<br>


#### However, with HTML5, the doctype declaration is simplified to &lt;!DOCTYPE html&gt;, making it easier for developers to specify the HTML version without needing to remember different doctype declarations for various versions.


## Example #7
### Declare the HTML document type at the beginning of your HTML file.
```html
<!DOCTYPE html>
``` 