# Nepali Date Picker

### Install:

Using Bower: 
``` bash
$ bower install datepicker-nepali --save`
```

### How do I use it?
- First include to page css and js files
``` html
<!-- this should go after your </body> -->
<script type="text/javascript" src="jquery.min.js"></script>
<script type="text/javascript" src="dist/jquery.nepaliDatePicker.min.js"></script>
<link rel="stylesheet" href="dist/nepaliDatePicker.min.css">
```
- Html
``` html
<input type="text" value="" name="date" class="date-picker">
```
- Javascript
``` javascript
$(".date-picker").nepaliDatePicker({
      dateFormat: "%D, %M %d, %y",
      closeOnDateSelect: true,
      minDate : "सोम, जेठ १०, २०७३",
      maxDate : "मंगल, जेठ ३२, २०७३"
  });
```

## Buliding from source

### Installing dependencies
``` bash
$ bower install

$ npm install

#if you already install grunt dependencies
$ grunt update
```
 
 ### Minifying javascript & css
 ``` bash
 $ grunt compress
 ```
 
 ### Testing calender Functions
  ``` bash
  $ grunt test
  ```
 
 
