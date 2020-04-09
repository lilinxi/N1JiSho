# N1JiSho

- cjkRuby：https://biebu.xin/demo/2017-08-28-cjk-ruby

```js
function cjkRuby(str) {
    return str.replace(/\{([^{}()]+)\}\(([^{}()]+)\)/g, function(match, $1, $2) {
        return '<ruby>' + $1 + '<rt>' + $2 + '</rt></ruby>'
    });
}
```