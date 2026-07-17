# sshsocket

在 Debian/Ubuntu 新服务器的 root 会话中一键修改 SSH 端口：

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/SYNY0/sshsocket/main/sshsocket)
```

脚本不使用 `sudo`，请先以 root 身份登录服务器后执行。运行前请先在云安全组放行你准备使用的新 SSH 端口。
