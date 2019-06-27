### frps-onekey
此脚本根据[clangcn/onekey-install-shell](https://github.com/clangcn/onekey-install-shell/tree/master/frps)脚本制作，感谢`Clang`大大
##### 版本
```
脚本版本：19.06.27

frps版本：0.27.0
```
##### 操作
```bash
# 安装
wget --no-check-certificate https://raw.githubusercontent.com/jakehu/frp/master/frps-onekey/install-frps.sh -O ./install-frps.sh
chmod 700 ./install-frps.sh
./install-frps.sh install

# 卸载
./install-frps.sh uninstall

# 更新
./install-frps.sh update

# 管理
frps {start|stop|restart|status|config|version}
```
### frpc-docker

##### 版本
```
脚本版本：19.06.27

frps版本：0.27.0
```
#### 操作
```bash
# 使用
docker run -d --restart always -v /data/frpc.ini:/frp/frpc.ini jakehu/frpc-docker
```