# frp ![CI](https://github.com/Mabeple/frpc/workflows/CI/badge.svg)

[FRP_VERSION](https://github.com/fatedier/frp/releases)

变量: `version`

构建: `docker bulid -t mabeple/frpc`

```
docker run -d --name=frpc -e ${version} --restart=always -v /root/frpc/frpc.ini:/frp/frpc.ini stilleshan/frpc
```