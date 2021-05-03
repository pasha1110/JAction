# JAction
JAction is a javascript library for simple DOM manipulation and ajax

# Instalation

Installation can only be done using cdn, because this library is not yet available on npm. Here is the CDN link:

```html
<script src="https://cdn.jsdelivr.net/gh/pasha1110/JAction@1.0.0/src/original/JAction.js"></script>
``` 

compressed version

```html
<script src="https://cdn.jsdelivr.net/gh/pasha1110/JAction@1.0.0/src/compressed/JAction.min.js"></script>
``` 

## Size comparison with several other javascript libraries.

<small>original: </small>
---------------------------
| library        | size   |
| -------------- | ------ |
| jQuery(3.6.0)  | 282 KB |
| Dojo(1.10.4)   | 598 KB |
| w3js           | 13 KB  |
| JAction(1.0.0) | 12 KB  |
<br>
compressed:

<!-- --------------------------- -->
| library        | size   |
| -------------- | ------ |
| jQuery(3.6.0)  | 87.4KB |
| Dojo(1.10.4)   | 155 KB |
| w3js           | 13 KB  |
| JAction(1.0.0) | 11 KB  |

# Usage

Very easy to use! Check out the code below.
_see index.html for example_
``` javascript
// with ALIAS (jct)
jct._ method here_

// without ALAIAS (jct)
// this is recommended when you want to add a new method
JAction._ method here_
```


# JAction Method

* setHTML   
    to set html content on an element. If you only want to set text, it is recommended to use setText

    Example:
    ```javascript
    //set H! tag html contentjct
    jct.setHTML("h1","<b>Hello from JAction!</b>")
    ```

* setText   
    to set text content on an element. If you want to set html, use setHTML

    Example:
    ```javascript
    //set H1 tag text content
    jct.setText("h1","Hello from JAction!")
    ```
* setAttr <br>
    to set attributes to the html element
    to set attributes to the html element,
    This function has 3 parameters, namely:
    1. Target: Select HTML element
    2. attribute name
    3. attribute value

    Example: 
    ```javascript
    //setAttr to h1 element
    jct.setAttr("h1","class","red")
    ```