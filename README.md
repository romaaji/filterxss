### On Browser

Shim mode (reference file `test/test.html`):

```html
<script src="https://rawgit.com/leizongmin/js-xss/master/dist/xss.js"></script>
<script>
// apply function filterXSS in the same way
var html = filterXSS('<script>alert("xss");</scr' + 'ipt>');
alert(html);
</script>
```
