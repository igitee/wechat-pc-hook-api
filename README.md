# Wechat Hook TO Restful API

这个项目的目的是要把微信pc端所有hook变成restful api   
完全公开免费!!!   
谢Hezone的教程   
https://study.163.com/course/courseMain.htm?courseId=1006486010   
目前项目代码和结构非常简陋, 我打算功能比较完善时再重构一下

我用的pc微信的版本是2.6.7.40, 如果版本不同的话需要自己找到call的基址, 方法在Hezone的教程里有

### 使用方法
注入Debug文件夹里的WechatDllCpp.dll到微信进程, http服务自动开启
地址的127.0.0.1:2019

1. 发消息api(目前只有这个, 功能会慢慢添加)   
127.0.0.1:2019/send   
```
{
    "wxid" : "微信id"
    "msg"  : "要发的信息"
}
```
--------
### PS

2019/4/12    
抱歉大家等这么久, 我一直有心更新代码, 不过对反编译很不在行,
我也在学习, 我在从基础开始学, 比较忙但是没有放弃, 我也希望
能很快出下个功能, 不过可能大家还得等一段时间, 我相信我掌握
反编译后会比较快的开发接下来的功能, 让大家用到最方便和可靠
的微信API, 感谢给我留言的朋友给我的支持, 谢谢！

