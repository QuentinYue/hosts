<center>
![img][image]
</center>

<br>

**使用本项目之前，请先阅读此 README 及下方的许可协议**

----------


## 更新 hosts
* 下面介绍的操作均可能覆盖现有 hosts ，进行操作前请先确认是否需要备份。

* 若更新 hosts 未立即生效，请重置网络：
  - 在系统设置内开关网络
  - 启用禁用飞行模式
  - 重启系统


### Windows 配置
用文本编辑器（如`Notepad++`）打开文件：

    C:\Windows\System32\drivers\etc\hosts

将 [hosts][rawhosts] 全部内容复制到上述文件内并保存

> 注意：如果遇到无法保存，请右键文件hosts并找到“属性” -> “安全”，然后选择你登陆的用户名，最后点击编辑，勾选“写入”即可。

### Linux 配置
将 [hosts][rawhosts] 全部内容复制到`/etc/hosts`中并保存。

### Mac OS 配置
将 [hosts][rawhosts] 全部内容复制到 `/etc/hosts`中并保存。

### Android 配置
将 [hosts][rawhosts] 全部内容复制到 `/etc/hosts`中并保存。

### iOS 配置
将 [hosts][rawhosts] 全部内容复制到 `/etc/hosts`中并保存。

----------


## 更多
如有问题，请开 [Issue][issue] 反馈。

----------


## LICENSE
- 本项目的所有代码除另有说明外，均按照 [MIT License][license] 发布。
- 请在遵守当地相关法律法规的前提下使用本项目。

----------

【完】

[rawhosts]:https://raw.githubusercontent.com/linuxcer/hosts/master/hosts
[issue]:https://github.com/linuxcer/hosts/issues
[license]:https://github.com/linuxcer/hosts/blob/master/LICENSE
[image]:https://github.com/linuxcer/hosts/blob/master/hosts.png?raw=true

