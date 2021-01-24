# lotServer


## 用户安装
### 常规自动安装
```
bash <(wget --no-check-certificate -qO- https://github.com/LotIndex/lotServer/raw/master/Install.sh) install
```

### 指定内核安装
```
bash <(wget --no-check-certificate -qO- https://github.com/LotIndex/lotServer/raw/master/Install.sh) install <Kernel Version>
```

## 完全卸载
```
bash <(wget --no-check-certificate -qO- https://github.com/LotIndex/lotServer/raw/master/Install.sh) uninstall
```

## 例子：更换内核相关
### Debian/Unbuntu 自动更换内核 (必须，运行后需重启)
```
bash <(wget --no-check-certificate -qO- wget https://git.io/Kernel.sh)
```
### CentOS用户如遇内核不能匹配, 请参照以下示例
 > 使用锐速安装脚本,得知不能匹配到内核.  
 通过 uname -r 查看到的版本号为 2.6.32-642.el6.x86_64 ,  
 去查看锐速版本库发现有个内核版本很接近 2.6.32-573.1.1.el6.x86_64 .  
 执行安装命令:  
```
bash <(wget --no-check-certificate -qO-  https://git.io/lotServerInstall.sh) install 2.6.32-573.1.1.el6.x86_64
```
 > 锐速安装脚本就会强制安装内核版本为 2.6.32-573.1.1.el6.x86_64 的锐速.  
 安装命令中的 2.6.32-573.1.1.el6.x86_64 可自行更改.  
 启动锐速  
 如果启动成功，恭喜你!  
 如果启动失败，请重复 2-5 步骤!  
 不要害怕失败,安装失败并不会影响系统运行.
***
***
## 命令行使用方法
- 启动命令 /appex/bin/lotServer.sh start
- 停止加速 /appex/bin/lotServer.sh stop
- 状态查询 /appex/bin/lotServer.sh status
- 重新启动 /appex/bin/lotServer.sh restart
- 查看网络数据（需安装bc命令：yum -y install bc） /appex/bin/lotServer.sh stats

## 许可证生成 -->[萌咖 API接口](https://moeclub.org/api)  
### 如果无法生成许可证,可能API正在被无聊的人攻击.

## [常见问答](https://github.com/MoeClub/lotServer/wiki)     

## [更新历史](http://download.appexnetworks.com.cn/releaseNotes/)     

  
