## 雷神加速器自动暂停工具

### 特性

- 退出游戏时自动暂停加速器
- 电脑关机时自动暂停加速器
- 长时间没有运行游戏时暂停加速器(每1小时检测一次)


### 使用说明

#### 填写config.toml
- 将雷神账号密码填写在username,password
- 将需要监听的游戏进程名(不要.exe)填写在games, 以英文逗号分隔(默认监听pubg，盗贼之海。)
- 将需要启动的应用程序填写在[start_with], (默认启动雷神加速器和steam)

#### 启动
- 启动leigodhelper.exe 
- leigodhelper.exe 会自动启动雷神加速器，steam等应用程序
- 可以将leigodhelper.exe 调整为以管理员权限运行
