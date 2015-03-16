# jQuery custom styled checkbox #

## About plugin ##
_A replacement for the standard checkbox that allows you to change the look of checkbox elements in your page._

### Features ###
  * only inline elements used, just like default checkoxes
  * cross-browser look and feel (tested in IE6, IE7, IE8, Firefox and Chrome engines)
  * work with radio buttons too
  * supports inline and jQuery attached click events
  * supports "label hovering": when you point over parent label element, it will highlight its checkbox (thanks to Eugene for the idea)
  * dynamic skin changing
  * adds new checkbox events "check", "uncheck", "disable", "enable", ready to use in jQuery.bind() method



### What it does? ###
[View demonstration](http://widowmaker.kiev.ua/checkbox/)

[![](http://widowmaker.kiev.ua/checkbox/screenshot.png)](http://widowmaker.kiev.ua/checkbox/)

### How to wrap checkbox? ###
Just launch following code:
```
  $('input[type=checkbox]').checkbox();
```

### **Configuration: ###
Plugin has following configuration options:**

**cls:** checkbox wrapper class (default: jquery-checkbox)

**empty:** path/filename of "empty"(1x1 transparent) image (default: empty.png)

#### Example: ####
```
$('input[type=checkbox]').checkbox({
  cls:'jquery-safari-checkbox',
  empty: 'http://www.yoursite.com/images/empty.gif'
});
```

## Сompatibility: ##

  * jQuery v1.2.x
  * FireFox 2.0.0.x
  * Internet Explorer 6/7
  * Opera 9
  * Safari for Windows (should work on Safari 2.0+ for Mac)

## Feedback ##
[Please write you feedback here!](http://groups.google.com/group/jquery-checkbox/browse_thread/thread/7f1e16c209369ce6)