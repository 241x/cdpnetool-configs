# CDPNETOOL Configs Share

社区共享的 cdpnetool 配置文件仓库。

## 简介

[cdpnetool](https://github.com/241x/cdpnetool) 是一款基于 Chrome DevTools Protocol 的网络请求拦截与修改工具。

本仓库用于汇集社区用户分享的配置文件，方便大家直接使用。

## 可用配置

| 配置文件 | 适用网站/场景 | 功能描述 | 贡献者 |
|---------|-------------|---------|--------|
| [cors-enable.json](configs/cors-enable.json) | 所有网站 | 允许跨域请求，解决浏览器同源策略限制 | - |

## 使用配置

1. 下载本仓库中的 `.json` 配置文件
2. 在 cdpnetool 中点击「导入配置」
3. 选择下载的配置文件即可使用

## 贡献配置

欢迎通过 Pull Request 分享你的配置！

### 提交步骤

1. Fork 本仓库
2. 将你的配置文件放入 `configs/` 目录
3. 按规范命名文件：`网站-功能描述.json`（如 `bilibili-ad-block.json`）
4. 提交 PR，简要说明配置的作用和适用场景

### 配置要求

- 配置文件需为有效的 JSON 格式
- 建议注明适用的网站或场景
- 不包含敏感信息

## 目录结构

```
configs/          # 配置文件存放目录
```

## 许可证

与 cdpnetool 保持一致：GPL-3.0