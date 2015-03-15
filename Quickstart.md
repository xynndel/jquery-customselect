# Introduction #

## 4 easy steps: ##
  1. Include jQuery.js in your page
  1. Include jquery.customselect.js in your page
  1. Style
  1. Let the script to it's magic

# Details #
  1. Include jQuery.js in your page, preferredly right before the closing body-Tag. Minimum Version required is jQuery 1.4.
  1. Include jquery.customselect.js in your page
```
<script type="text/javascript" src="/path/to/jquery-1.4.2.min.js"></script>
<script type="text/javascript" src="jquery.customselect.js"></script>
```
  1. Use CSS to style the new selectbox, see [Examples](Examples.md) for styling basics
  1. Let the script to its magic
```
<script type="text/javascript">
$(document).ready(function(){
    $('select').customSelect();
});
</script>
```