# npm-build-scripts

学习用 NPM scripts 打包


# 补充

## git 使用
报错:
`remote: Permission to (远端git文件地址) denied to (git用户名)`

原因:
mac电脑存储了github先前访问的密码,每次push的时候都会读取这个本地用户名及密码(采用 https 而非 ssh),导致账号和密码授权没有通过,所以才被github denied.

解决方案:
打开 钥匙串访问
Finder ----> 应用程序 ---->实用工具 ---->钥匙串访问
或
直接搜索 钥匙串访问 ---> 打开
找到 github.com 的 密码记录 ---> 修改用户名和密码 或 直接右键 删除