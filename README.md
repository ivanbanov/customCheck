# customCheck
Custom chekcbox and radio button (CSS3 / jQuery)

## Live Demo
* <a href="http://ivanbanov.github.com/customCheck/custom-css3.html" target="_blank">pure CSS3</a>
* <a href="http://ivanbanov.github.com/customCheck/custom-jquery.html" target="_blank">plugin jQuery</a>

## Features
* Two options of usage: pure CSS3 or jquery plugin
* Responsive custom bullets
* No need images, customCheck use [Font-Awesome](http://fortawesome.github.io/Font-Awesome/) for style of bullets
* pure CSS3 support: for the time being just webkit browsers (FF [bug](https://bugzilla.mozilla.org/show_bug.cgi?id=557306))
* plugin jQuery support: IE8+ and modern browsers

## Installation
Add to your project the jQuery and the customCheck script.
```
<script src="path/jquery.js"></script>
<script src="path/jquery.customCheck.js"></script>
```

## Usage
```
$('input:radio, input:checkbox').customCheck({
	onCheck: function(),
	onUncheck: function()
});
```

## Methods
### Check
__check__, __uncheck__ or __toggleCheck__ check state of element.
```
$(element).customCheck('check');
```

### Disabled
__enable__, __disable__ or __toggle__ enable state of element.
```
$(element).customCheck('enable');
$(element).customCheck('disable');
$(element).customCheck('toggleEnable');
```

### Update
Update the actual states of element.
```
$(element).customCheck('update');
```

### Destroy
Remove styles and bind events of element
```
$(element).customCheck('destroy');
```
