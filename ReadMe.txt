GitHub读取资源文件


目的：直接获取我上传到GitHub上的代码，而不是打开那个代码所在的页面。

解决
这样写：https://raw.githubusercontent.com/:owner/:repo/master/:path

例子：
https://github.com/freeket/htgames/blob/master/config/config.json
https://raw.githubusercontent.com/freeket/htgames/master/config/config.json

https://github.com/freeket/htgames/blob/master/config/native_ad.png
https://raw.githubusercontent.com/freeket/htgames/master/config/native_ad.png