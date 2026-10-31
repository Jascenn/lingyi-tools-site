# Lingyi App Watch Site

`Lingyi App Watch` 的独立产品站点。

当前线上地址：

- `https://watch.lingyi.tools`

## 项目定位

这个仓库只负责对外展示页面，不承载本地监控逻辑。

- 独立站点：产品介绍、截图、Release 入口
- 独立域名入口：`watch.lingyi.tools`
- 独立于本地监控项目：`local-software-update-monitor`

## 当前结构

- `index.html`: 首页
- `404.html`: Pages 兜底跳转
- `_headers`: 基础安全响应头
- `assets/`: 截图等静态资源

## 迭代方式

后续统一按 GitHub 流程更新：

1. 从 `main` 拉新分支
2. 在分支上修改页面
3. 发 Pull Request
4. 合并到 `main`
5. 合并到 `main` 后由 Cloudflare Pages 原生从 GitHub 拉取并自动部署

## 发布说明

当前 Pages 项目：

- `lingyi-tools`

当前子域名：

- `watch.lingyi.tools`

## 备注

当前仓库保留 GitHub Actions 只做基础校验。

真正的线上部署由 Cloudflare Pages 的 Git 集成完成。

建议后续把当前使用的全局 API Key 替换成单独的 Cloudflare API Token，并逐步清理这次过渡期留下的 Secret。

## 治理

- 修改前请阅读 [CONTRIBUTING.md](CONTRIBUTING.md)
- 页面数据与外部请求说明见 [PRIVACY.md](PRIVACY.md)
- 安全问题请按 [SECURITY.md](SECURITY.md) 私下报告
