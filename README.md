# Padavan 固件自定义修改并全自动编译

直接 Fork 修改好之后点击 Star 按钮即可开始自动编译 ( 自己点击 Star 才会运行 请不要重复点击 点一次运行一次 ) 

点击 [Actions](https://github.com/TurBoTse/Padavan-NG-Build/actions) 按钮查看项目运行状态 编译好的固件也在里面 

源码使用 [本人的 Padavan-NG 源码库](https://github.com/TurBoTse/padavan-ng.git)



用户名: admin

登录密码: admin

IP地址: 192.168.2.1

WiFi名称: 2G: Padavan 5G: Padavan_5G

WiFi密码: 1234567890

如要修改请编辑 [public.sh](https://github.com/TurBoTse/Padavan-Build/blob/main/public/public.sh) 宽带账号和密码 默认AP模式 打开桥接 超频 集成插件等更多请参考[PSG1218.sh](https://github.com/TurBoTse/Padavan-Build/blob/main/public/PSG1218.sh)

启用和禁用插件也可以修改 *.config 放在 [public](https://github.com/TurBoTse/Padavan-NG-Build/tree/main/public) 或  [padavan/config](https://github.com/TurBoTse/Padavan-NG-Build/blob/main/padavan/config)

自定义优先执行 [public](https://github.com/TurBoTse/Padavan-NG-Build/tree/main/public) 公共文件夹下的然后再执行各个源码库对应的文件夹  例如:  [padavan/config](https://github.com/TurBoTse/Padavan-NG-Build/blob/main/padavan/config)    [padavan/scripts](https://github.com/TurBoTse/Padavan-NG-Build/blob/main/padavan/scripts)
