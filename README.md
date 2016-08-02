# portfolio
Will be my new website focused on speed

# useful links:
**basic html5 template tutorial:** https://www.sitepoint.com/a-basic-html5-template/

# steps to implement lazyload with pure javascript:

**1. onLoad function:**
http://stackoverflow.com/a/9899701
```javascript
// self executing function here
(function() {
   // your page initialization code here
   // the DOM will be available here

})();
```

**2. search elements by tag:**
http://stackoverflow.com/a/25657360
```javascript
var form = document.forms[0];
```

**3. set attribute:**
http://www.w3schools.com/jsref/met_element_setattribute.asp
```javascript
document.getElementsByTagName("H1")[0].setAttribute("class", "democlass");
```