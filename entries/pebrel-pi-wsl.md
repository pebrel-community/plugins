# pebrel-pi-wsl

| Item | Value |
| --- | --- |
| Author | [VauntlekV](https://github.com/VauntlekV) |
| Source | [VauntlekV/pebrel-pi-wsl](https://github.com/VauntlekV/pebrel-pi-wsl) |
| Listed version | `0.1.0` / [`v0.1.0`](https://github.com/VauntlekV/pebrel-pi-wsl/tree/v0.1.0) |
| Pinned revision | [`1ebea7a9d033515bfc3766b6dc4ac0bdce613f06`](https://github.com/VauntlekV/pebrel-pi-wsl/tree/1ebea7a9d033515bfc3766b6dc4ac0bdce613f06) |
| License | GPL-3.0-only |
| Category | Pi / WSL integration extension |
| Runs in | Pi's extension runtime, inside WSL |

## What it does

The extension subscribes to Pi session, agent, and tool lifecycle events. It
reports session identity and task status through Pebrel's authenticated OSC
hook channel; Pebrel owns the terminal state and notification behavior.

The entry is installed by Pi's package manager. It is not a `plugin.toml`
package for Pebrel's current `plugin check/run` command, and this listing does
not change Pebrel's source or add an execution engine to the application.

## Install

Enable AI hooks in Pebrel, then run inside its WSL terminal:

```sh
pi install git:github.com/VauntlekV/pebrel-pi-wsl@v0.1.0
```

Start Pi, or use `/reload` after a running task ends. For configuration and
removal, follow the [author's versioned README](https://github.com/VauntlekV/pebrel-pi-wsl/blob/v0.1.0/README.md).

## Compatibility and review

The author reports testing Pebrel 2.1.1, Pi 1.0.0, and Debian WSL2. Package
metadata declares Node.js >=22.19.0. Other versions and platforms are not
established by this listing.

Community review on 2026-10-02 checked repository metadata, GPL license and
NOTICE, the Pi entry source, and the version tag's target revision. No third-party
code was installed or executed during this review, and the author's runtime
claim has not been independently reproduced by the community.

## 中文

这是 **VauntlekV 编写的 Pi 扩展**，安装在 WSL 中的 Pi 里，通过 Pebrel 现有
的认证 OSC 通道同步会话、任务运行与完成状态。它不修改 Pebrel 源码，
也不是 Pebrel 当前 `plugin check/run` 使用的 `plugin.toml` 插件包。

安装前启用 Pebrel 的 AI hook，在 Pebrel 的 WSL 终端执行上面的 `pi install`
命令。作者声明实测 Pebrel 2.1.1、Pi 1.0.0、Debian WSL2；工坊已核对来源、
入口、许可和版本，但尚未独立运行验证，不将作者声明扩大为跨平台兼容保证。

该扩展保留作者的仓库、版本和 GPL-3.0-only 许可。通用 WSL hook 安装及传输
能力仍属于 Pebrel 主项目的职责；这份社区登记不替代主项目的基础支持。
