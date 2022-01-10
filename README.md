# parcel-template-basic
This repository is basic template of Front-End WEB Developing Progress  

### index.html
***
totally basic index.html file
<br>
### package.json
---
```json
 "scripts": {
    "dev": "parcel index.html",
    "build": "parcel build index.html"
  },
```
with `npm run dev` command, I can easily run my local server
<br />
### static
---
```json
 "devDependencies": {
...
"parcel-plugin-static-files-copy": "^2.6.0",
...
},
"staticFiles": {
    "staticPath": "static"
  },
```
by this method, I can include my external filese such as favicon, images, or some other else.
<br />

### scss
---
```json
 "sass": "^1.47.0"
```
```scss
$color--black: #000;
$color--white: #fff;

body {
  background-color: $color--black;
  h1 {
    color: $color--white;
    display: flex;
  }
}
```
using SCSS to make CSS easier way
