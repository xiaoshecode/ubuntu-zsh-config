# ubuntu-zsh-config 维护说明

Ubuntu、Oh My Zsh、终端主题和 Conda 初始化脚本。

- 上游：https://github.com/yihuai-gao/ubuntu-config
- 在线文档：https://xiaoshecode.github.io/xiaoshecode/repos/ubuntu-zsh-config/
- 检查日期：2026-10-30

## 环境与使用

- 仅在待配置的 Ubuntu 环境使用；先阅读脚本会修改的系统包与用户配置。

使用/检查入口（需先满足依赖条件）：

- `bash -n setup_ubuntu.sh`
- `bash -n install_oh_my_zsh.sh`

## 目录职责

- setup_ubuntu.sh — 系统初始化
- install_oh_my_zsh.sh / config_oh_my_zsh.sh — Shell 配置
- install_conda.sh — Conda 安装
- p10k.zsh — 主题配置

## 本次整理

- 新增维护文档和在线文档入口，补全用途、目录、使用路径及验证边界。

## 检查记录

- **仓库目录与入口盘点**（passed）：检查 Git 索引中的 13 个路径、README 和项目配置；不等于功能验收。
- **完整构建与端到端运行**（not_run）：未执行安装脚本或修改本机 shell、系统包与用户配置；Ubuntu 实机安装尚待验证。

## 验证边界与待办

- 未执行安装脚本或修改本机 shell、系统包与用户配置；Ubuntu 实机安装尚待验证。

## 后续维护约定

保留上游许可证与作者信息。沿用现有模块边界和格式配置；修复功能时同步最小回归验证。依赖或接口变更需写明迁移步骤，避免仅为目录美观搬动公开入口。
