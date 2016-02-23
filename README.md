##手机YY Api Bridge
---
> 手机YY客户端 web端调用原生api必备组件

###安装方法
    cnpm i @yy/yy-bridge --save

###使用方法
    let YYApi = require('@yy/yy-bridge') //CMD
    import YYApi from '@yy/yy-bridge' //ES6
    
    let isLogined = YYApi.invokeClientMethod('data', 'isLogined') //获取用户登录状态
    YYApi.invokeClientMethod('ui', 'goto', {'uri': 'yymobile://Login/Login'}); //跳转到登录界面
    
### 适用客户端
* iOS
* Android


