# assets

这些 SVG 是**从第三方服务取下来固化在本仓的副本**，不是手写的。

## 为什么固化

2026-09-03 `github-readme-activity-graph.vercel.app` 返回 `HTTP 402
DEPLOYMENT_DISABLED`（作者的 Vercel 部署被停），profile 首屏挂了一张破图。
⚠ **这个位置是简历的落点** —— 六份简历都写着 `GitHub：github.com/alertform`，
HR 点进来第一屏就是这个 README。破图直接被面试官看到。

那张图已删除。剩下的两个第三方依赖（打字动画与徽章）同样是别人的免费服务，
**同一种死法随时会重演**，所以取下来放进本仓，改由 GitHub 自己的
raw.githubusercontent 提供。三份都是自包含的（只有 XML 命名空间声明，
无任何外部资源拉取），渲染结果与线上服务逐字节一致。

## 各文件的原始生成地址（要改内容就改这里的参数再重新取）

**typing.svg** — DenverCoder1/readme-typing-svg，SMIL 动画，四句循环：

```
https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=21&duration=2600&pause=700&color=CC785C&center=true&vCenter=true&width=640&height=44&lines=AI-native+tooling;Unreal+Engine+gameplay;Robot+learning;Motion-capture+data+pipelines
```

**badge-portfolio.svg** — shields.io 静态徽章：

```
https://img.shields.io/badge/Portfolio%20%C2%B7%20Blog-CC785C?style=for-the-badge&logo=vercel&logoColor=F0EEE6&labelColor=191919
```

**badge-repos.svg** — shields.io 静态徽章：

```
https://img.shields.io/badge/Repositories-191919?style=for-the-badge&logo=github&logoColor=F0EEE6&labelColor=191919
```

## 更新方法

```bash
curl -s '<上面对应的地址>' -o assets/<文件名>.svg
```

⚠ 改完把 README.md 里引用的 `?v=N` 递增一位，否则 GitHub 的 camo 代理会继续用缓存。

## 不在此列

`snake.svg` / `snake-light.svg` 在 `output` 分支，由 GitHub Actions 自动生成，
本来就是自建的，不受第三方停机影响。
