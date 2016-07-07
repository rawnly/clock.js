#Usage
Include this file 
```html
<script src=".../path/to/clock.js"> </script>
```
then to create a new clock use this: 
```JavaScript
//yourJsFile.js

var clock = new Clock(); //define clock

//set clock element
clock.new('#myClock') //'.class' or '#id' or 'tagname'
```
###Hex Clock
Clock.js generate an hex code based on actual hour for example `13:36:12` is `#133612` you can simpy do this with `clock.setBackground();` and `clock.setColor();` also like `clock.new();` you can change the selector to classes, id or other tagnames.

##Dependencies
Clock.js need [jQuery](https://github.com/jquery/jquery) to works, snippet below:

```html
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.0.0/jquery.min.js"></script>
```
