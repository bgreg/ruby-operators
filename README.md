This is a fork of Anil's nice little site showing ruby operators in flash card format. 

Paste this into the console:

```
var jq = document.createElement('script');
jq.src = "//ajax.googleapis.com/ajax/libs/jquery/1/jquery.min.js";
document.getElementsByTagName('head')[0].appendChild(jq);

// ... give time for script to load, then type.
jQuery.noConflict();

// don't show the operator names on page load
$('div.operator_name').hide();

// Click the page header div to show/hide the operators
$(".page-header").click(function(){$('div.operator_name').toggle();});
```

Now you won't see the names until you click.  


ruby-operators
==============
Simple app to show different Ruby operators with their funny names.


Contribute
==========
Edit [operators.json](https://github.com/anildigital/ruby-operators/blob/master/public/config/operators.json) and send pull request.
