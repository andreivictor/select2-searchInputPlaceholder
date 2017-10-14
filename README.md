# Select2 - 'searchInputPlaceholder' option

Extends Select2 v4 plugin by adding an option to set a placeholder for the 'search' input field.


## Demo ##

Demo available on [JsFiddle](http://jsfiddle.net/3k9xfdxo/). 


## Usage ##
Initialize the select2 plugin with the `searchInputPlaceholder` option. 

```javascript
$("input").autocomplete({
    // options 
    searchInputPlaceholder: 'My custom placeholder...'
});
```

## Setup ##

Include the script after Select2 main javascript file:
```html
<script src="select2.js"></script>
<script src="select2-searchInputPlaceholder.js"></script>
