## robe-jajax

### Motivation
 
 Ajax library exported from jquery

 
#### installitation

```ssh
npm install jajax
```

#### usage 

Javascript : 

```javascript

var jajax = require("jajax");

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

import jajax from "jajax";

// call jajax.ajax like $.ajax

jajax.ajax(
  url: "script.php",
  method: "POST",
  data: { id : menuId },
  dataType: "html"
);

```


More information : http://api.jquery.com/jquery.ajax/