<div name="head">

# this documentation is in progress!

# JAction

JAction is a javascript library for simple DOM manipulation and ajax
</div>

<div name="menu">

# Menu
* [Home](#Head)
* [Menu](#menu)
* [Installation](#installation)
* [Size Comparison](#size_comparison)
  * [original](#original)
  * [compressed](#compressed)


* [Usage](#usage)
* [JAction method](#jaction_method)
   * [setText](#settext)
   <!-- * [setEventAll](#seteventall) -->
   * [setHTML](#sethtml)
   * [setHTMLAll](#sethtmlall)
   * [setAttr](#setattr)
   <!-- * [setAttrAll](#setattrall)
   * [setEvent](#setevent)
   * [setEventAll](#seteventall) -->

<br>

</div>

<div name="Installation">

# Instalation

Installation can only be done using cdn, because this library is not yet available on npm. Here is the CDN link:

```html
<script src="https://cdn.jsdelivr.net/gh/pasha1110/JAction/src/original/JAction.js"></script>
``` 

compressed version(recommended):

```html
<script src="https://cdn.jsdelivr.net/gh/pasha1110/JAction/src/compressed/JAction.min.js"></script>
``` 

and, place the script in the head tag

</div>

<br>
<div name="size_comparison">

## Size comparison with several other javascript libraries.

<small>original</small>
---------------------------
| library        | size   |
| -------------- | ------ |
| jQuery(3.6.0)  | 282 KB |
| Dojo(1.10.4)   | 598 KB |
| JAction(1.1.0) | 13 KB  |
<br>
compressed:

<!-- --------------------------- -->
| library        | size   |
| -------------- | ------ |
| jQuery(3.6.0)  | 87.4KB |
| Dojo(1.10.4)   | 155 KB |
| JAction(1.1.0) | 12 KB  |

</div>

<div name="usage">

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


</div>

<span name="jaction_method">

# JAction Method

</span>

<div name="sethtml">

* setHTML   
    to set html content on an element. If you only want to set text, it is recommended to use setText
    This function has 2 parameters, namely: 
    1. target
    2. html content

    Example:
    ```javascript
    //set H! tag html contentjct
    jct.setHTML("h1","<b>Hello from JAction!</b>")
    ```

</div>

<div name="sethtmlall">

* setHTMLAll 
     to set the html content, but to all selected html elements
     This function has several parameters: 
     
     1. Target
     2. Html code

     Example:
     ```javascript
     jct.setHTMLAll ("h1","Hello From JAction")
     ```

</div>

<div name="settext">

* setText   
    to set text content on an element. If you want to set html, use setHTML

    Example:
    ```javascript
    //set H1 tag text content
    jct.setText("h1","Hello from JAction!")
    ```

</div>


* setTextAll
    to set text content on an element but for all selected elements. If you want to set html, use setHTMLAll

    Example:
    ```javascript
    //set H1 tag text content
    jct.setText("h1","Hello from JAction!")
    ```

</div>


<div name="setattr">

* setAttr <br>
    to set attributes to the html element
    This function has 3 parameters, namely:
    1. Target: Select HTML element
    2. attribute name
    3. attribute value

    Example: 
    ```javascript
    //setAttr to h1 element
    jct.setAttr("h1","class","red")
    ```

</div>