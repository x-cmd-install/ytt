# ytt

[English version](./README.md)

YAML templating tool that works on YAML structure instead of text

[![x-cmd/install — ytt Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/ytt.svg?lang=zh)](https://x-cmd.com/install/ytt)

## 安装

```sh
x install ytt
```

## 代码洞察

合计: **92,365** 行代码（覆盖前 5 种语言、共 **708** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 79,164 | 16,470 | 13,074 | 429 |
| JavaScript | 8,226 | 1,024 | 1,059 | 2 |
| Yaml | 4,264 | 1,141 | 693 | 263 |
| Css | 478 | 50 | 68 | 2 |
| Sh | 129 | 25 | 53 | 12 |

## OpenSSF Scorecard 评分

总评分: **6.5 / 10**

评分最低的几项:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Pinned-Dependencies** (3/10) — dependency not pinned by hash detected -- score normalized to 3
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected

## 源代码

- **上游仓库**: <https://github.com/carvel-dev/ytt>
- **官网**: <https://carvel.dev/ytt>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.55.4` (2026-10-19)
- **最近提交**: 2026-10-30
- **Release 含资产**: 10 个

## 流行度

- **Star**: 1,885 · **Fork**: 169 · **开放 issue**: 546 · **贡献者**: 86

## 累计统计

- **发布数**: 106 · **已合并 PR**: 365 · **开放 PR**: 13 · **已关闭 issue**: 400 · **开放 issue**: 146 · **提交数**: 1351

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-01 | 1 | 7 | 1 | 0 | 1 | 12 |
| last60d | 2026-09-01 | 2 | 11 | 3 | 0 | 2 | 18 |
| 90d | 2026-08-02 | 3 | 15 | 6 | 2 | 2 | 26 |
| last180d | 2026-05-04 | 5 | 23 | 9 | 2 | 2 | 35 |
| 360d | 2025-11-05 | 10 | 33 | 10 | 5 | 4 | 43 |
| last720d | 2024-11-10 | 14 | 48 | 10 | 13 | 7 | 105 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [checksums.txt](https://github.com/carvel-dev/ytt/releases/download/v0.55.4/checksums.txt) | 590 B | `other` |
| [checksums.txt.pem](https://github.com/carvel-dev/ytt/releases/download/v0.55.4/checksums.txt.pem) | 3.1 KiB | `other` |
| [checksums.txt.sig](https://github.com/carvel-dev/ytt/releases/download/v0.55.4/checksums.txt.sig) | 96 B | `other` |
| [ytt-darwin-amd64](https://github.com/carvel-dev/ytt/releases/download/v0.55.4/ytt-darwin-amd64) | 17.5 MiB | `native/darwin/x64` |
| [ytt-darwin-arm64](https://github.com/carvel-dev/ytt/releases/download/v0.55.4/ytt-darwin-arm64) | 16.5 MiB | `native/darwin/arm64` |
| [ytt-linux-amd64](https://github.com/carvel-dev/ytt/releases/download/v0.55.4/ytt-linux-amd64) | 17.1 MiB | `native/linux/x64` |
| [ytt-linux-arm64](https://github.com/carvel-dev/ytt/releases/download/v0.55.4/ytt-linux-arm64) | 16.0 MiB | `native/linux/arm64` |
| [ytt-linux-riscv64](https://github.com/carvel-dev/ytt/releases/download/v0.55.4/ytt-linux-riscv64) | 15.7 MiB | `native/linux/riscv64` |
| [ytt-windows-amd64.exe](https://github.com/carvel-dev/ytt/releases/download/v0.55.4/ytt-windows-amd64.exe) | 17.4 MiB | `native/win/x64` |
| [ytt-windows-arm64.exe](https://github.com/carvel-dev/ytt/releases/download/v0.55.4/ytt-windows-arm64.exe) | 16.0 MiB | `native/win/arm64` |

## 发行版状态

在 [repology.org](https://repology.org/project/ytt) 上共有 **56** 个发行版报告此项目。**8** 个 ✅ 已是最新上游版本，**7** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Homebrew | `0.55.4` | ✅ latest |
| Nix unstable | `0.55.4` | ✅ latest |
| Alpine edge | `0.52.1` | ⚠️ outdated |

## 改进这些数据

ytt 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `ytt` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/ytt.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/261031.yml` · 2026-10-31T06:22:19Z._
