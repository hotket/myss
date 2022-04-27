

```shell
yum -y install wget &&
wget -N --no-check-certificate https://raw.githubusercontent.com/lizhongnian/ss-panel-v3-mod-node-connect/master/ss-panel-v3-mod-node-connect.sh &&
chmod +x ss-panel-v3-mod-node-connect.sh &&
bash ss-panel-v3-mod-node-connect.sh
```

按提示选择1（webapi对接）或2（数据库对接）
然后输入相应的参数，回车执行，等待脚本安装完毕重启vps后即可成功
