# Cross-Domain
各种跨域解决办法。

## 同源策略
    协议，域名，端口号必须一致： 同域
    跨域限制(同源策略)：cookie，storage，
                    dom-->所以可以通过iframe去解决跨域
                    ajaxy也不支持跨域

## 实现跨域
    1.jsonp
    2.cros
    3.postMessage
    4.document.domian(解决子域和父域之间限制)
    5.window.name
    6.localion.hash
    7.http-proxy(代理)
    8.nginx
    9.websocket 
