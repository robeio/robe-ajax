## robe-ajax

### Motivation
 
 Ajax library exported from jquery

 
#### installitation

```ssh
npm install robe-ajax
```

#### usage 

Javascript : 

```javascript

var jajax = require("robe-ajax");

// call jajax.ajax like $.ajax

jajax.ajax(
  url: "script.php",
  method: "POST",
  data: { id : menuId },
  dataType: "html"
);

```


ES6 : 

```javascript

import jajax from "robe-ajax";

// call jajax.ajax like $.ajax

jajax.ajax(
  url: "script.php",
  method: "POST",
  data: { id : menuId },
  dataType: "html"
);

```


More information : http://api.jquery.com/jquery.ajax/