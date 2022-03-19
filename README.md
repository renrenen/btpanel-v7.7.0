# btpanel-v7.7.0
btpanel-v7.7.0-backup  官方原版v7.7.0版本面板备份

**Centos/Ubuntu/Debian安装命令 独立运行环境（py3.7）**

```Bash
curl -sSO https://raw.githubusercontent.com/779776787/btpanel-v7.7.0/main/install/install_panel.sh && bash install_panel.sh
```

去除账号绑定:
```Bash
echo "{\"uid\":1000,\"username\":\"admin\",\"serverid\":\"xxx\"}" > /www/server/panel/data/userInfo.json
```
