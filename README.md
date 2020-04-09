# N1JiSho（N1辞書）

> 本人于2020.3.1开始学习日语，计划于2021.9.1前考得N1证书

> 如果有时间考虑出一个日语学习APP，估将知识点设计成数据库表的形式

---

## references

- cjkRuby：https://biebu.xin/demo/2017-08-28-cjk-ruby

```js
function cjkRuby(str) {
    return str.replace(/\{([^{}()]+)\}\(([^{}()]+)\)/g, function(match, $1, $2) {
        return '<ruby>' + $1 + '<rt>' + $2 + '</rt></ruby>'
    });
}
```
