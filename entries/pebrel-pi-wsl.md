# pebrel-pi-wsl

让 WSL 下的 Pi 通过 hook 向 Pebrel 同步会话和任务状态，并支持任务完成通知。

Use Pi hooks in WSL to show session and task status in Pebrel, including task completion notifications.

**作者 / Author:** [VauntlekV](https://github.com/VauntlekV) · **版本 / Version:** [0.1.0](https://github.com/VauntlekV/pebrel-pi-wsl/tree/v0.1.0) · **许可 / License:** GPL-3.0-only

[源码 / Source](https://github.com/VauntlekV/pebrel-pi-wsl) · [使用说明 / Documentation](https://github.com/VauntlekV/pebrel-pi-wsl/blob/v0.1.0/README.md)

## 安装 / Install

启用 Pebrel 的 AI hook，在 Pebrel 的 WSL 终端执行：

Enable AI hooks in Pebrel, then run in its WSL terminal:

```sh
pi install git:github.com/VauntlekV/pebrel-pi-wsl@v0.1.0
```

启动 Pi 即可。Pi 已运行时，任务结束后执行 `/reload`。

Start Pi, or use `/reload` after a running task ends.

作者实测 / Author-tested: Pebrel 2.1.1 · Pi 1.0.0 · Debian WSL2.
