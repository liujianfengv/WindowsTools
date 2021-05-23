<div align='center'><font size = '70'>Cmder</div>

Windows下的一款命令行工具，界面简洁，可以使用一些常用的Linux命令。官网链接 [Cmder](https://cmder.net)
### 配置步骤
- 添加cmder.exe到环境变量
- 管理员身份启动cmder,输入命令```Cmder.exe /REGISTER ALL```将cmder添加至右键菜单
- 将Cmder默认的命令提示符"λ"改为"\$"，在cmder\\vendor中的clink.lua内```local lambda = "$"``` 将"λ"替换成"\$";
  或cmder\\vendor\\git-for-windows\\etc\\profile.d\\git-prompt.sh内``` PS1="$PS1"'λ ' ``` 将"λ"替换成"\$";
- cmder\\config\\user_profile.sh 配置启动命令
- cmder\\vendor\\conemu-maximus5\\ConEmu.xml 配置文件