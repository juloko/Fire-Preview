# Fire review
#### The idea it's provide a Live Preview for Firebase users that serve the hosting by functions application. In another words users of command: `firebase serve`
 
 
### Great Achievals:
-  Watch some required files
-  Update the page if files has changed;
-  Timed.

### What you need to do:
-  Install the lib on your webpage;
```html
<script src="https://cdn.jsdelivr.net/npm/axios/dist/axios.min.js"></script>
```

-  Declare the files that you keep watching;
```js
const dinamicPath = [
    "index.html",
    "js/main/lightNews.js",
    "/css/style.css"];
```

-  Define time to update the page.
```js
const  timeUpdate = 1000;`
```

-  Call Fire Preview.
```js
firePreview(dinamicPath,timeUpdate);
```

 
