# Hysteria-script

Hysteria 一键脚本，支持IPv4、IPv6 VPS

> 注意⚠：部分VPS提供商会对使用Hysteria的VPS实行封号等处理策略，请谨慎部署和使用！

## 使用方法

```shell
wget -N https://raw.githubusercontents.com/Misaka-blog/Hysteria-script/master/hysteria.sh && bash hysteria.sh
```

快捷方式 `bash hysteria.sh`

## 脚本预览

![image](https://user-images.githubusercontent.com/96560028/167280089-e1754f00-c33f-4c71-a877-39c81596c6bd.png)

## 客户端连接教程

1. 在 Hysteria 的 [Release 页面](https://github.com/HyNetwork/hysteria/releases)，根据自己的架构下载对应的程序

![image](https://user-images.githubusercontent.com/96560028/167276169-c24e2db7-7e39-45dc-aba9-127f1a48f01a.png)

2. 把脚本生成的 `client.json` 和 Hysteria 主程序放到同一目录下

![image](https://user-images.githubusercontent.com/96560028/167276200-f4e3cbd5-ce26-481b-9a55-cd159a92385d.png)

3. 打开命令行，输入以下命令（以Windows为例）

```bat
.\hysteria-tun-windows-6.0-amd64.exe -c client.json client
```

4. 如图所示，即可代表 Hysteria 客户端已成功运行。**切记不能直接关闭！！！**

![image](https://user-images.githubusercontent.com/96560028/167276127-2a2f7693-3d08-4a1e-a5ba-8031a8a4c4b2.png)

5. 在 V2rayN 上添加一个 Socks5 节点，然后使用 V2rayN 连接

![image](https://user-images.githubusercontent.com/96560028/167276239-9d4b9fbf-8b97-43ea-8313-96ad05ead039.png)

## 参考资料

Hysteria：https://github.com/HyNetwork/hysteria

YouTube 不良林：https://www.youtube.com/watch?v=pMe_oErfLWQ

## Stargazers over time

[![Stargazers over time](https://starchart.cc/Misaka-blog/Hysteria-script.svg)](https://starchart.cc/Misaka-blog/Hysteria-script)
