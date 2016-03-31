## simplefooter
Simply make the footer at the bottom of the page... Easy, right?
### Installation:
**This requires JQUERY to run**
First, paste in the following **UNDER THE JQUERY SCRIPT TAG!!!!**:
```html
<script src="https://raw.githubusercontent.com/AAIDev/simplefooter/master/sf.js"></script>
```
Now, paste in the following into the body element.  Replace "footer" with the id of the footer element, and you can change the debug from true or false.
```html
onload='function simpleFooter(/*footer id*/ "footer", /*debug*/ false)'
```
You should have something like this now:
```html
<body onload='function simpleFooter(/*footer id*/ "footer", /*debug*/ false)'>
<div id='text'>text<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>mor text</div>
<div id='footer'>something, copyright, this got the worlds best webpage award, more propaganda, actually got participation award(s)</div>
</body>
```
and...
#### THE FOOTER IS ON THE BOTTOM!!!
