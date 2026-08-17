<div align="center">
  <a href="https://github.com/Lorcas-Zephyr">
    <img src="https://cdn.jsdelivr.net/gh/Lorcas-Zephyr/Lorcas-Zephyr@main/assets/header.svg" width="100%" alt="Lorcas Zephyr - building useful things, end to end" />
  </a>
</div>

<p align="center">
  <a href="https://github.com/Lorcas-Zephyr?tab=repositories"><img alt="Open source projects" src="https://img.shields.io/badge/Open%20Source-Projects-24292f?style=flat-square&logo=github" /></a>
  <a href="https://github.com/Lorcas-Zephyr/aoxiang-assistant/stargazers"><img alt="Aoxiang Assistant stars" src="https://img.shields.io/github/stars/Lorcas-Zephyr/aoxiang-assistant?style=flat-square&label=Aoxiang%20Assistant&color=3fb950" /></a>
  <a href="https://lorcas-zephyr.github.io/"><img alt="Blog" src="https://img.shields.io/badge/Blog-Visit-58a6ff?style=flat-square&logo=hexo&logoColor=white" /></a>
</p>

## 你好，我是 Lorcas Zephyr

我喜欢把真实问题一路做成能交付的产品：从数据采集、算法与工程约束，到用户真正接触到的界面。最近的工作集中在 **Android 校园工具**、**几何 AI** 和 **Web 体验**。

```text
PRODUCT ENGINEERING     把需求、隐私、后台任务与交互体验装进一个可用产品
GEOMETRY + AI           用学习方法与确定性约束共同解决工程几何问题
WEB                     构建轻量、清晰、能长期维护的站点与工具
```

## 代表项目

### [翱翔助手 · Aoxiang Assistant](https://github.com/Lorcas-Zephyr/aoxiang-assistant)

面向西北工业大学学生的原生 Android 应用，在一个入口中查看课表、成绩、GPA 与宿舍电费。

`Java` · `Android SDK` · `JavaScript` · `Shell` · `Android Keystore` · `WebView`

- 在设备端完成统一身份认证和数据采集，敏感凭据由 Android Keystore 保护
- 包含定时同步、变化通知、多尺寸桌面小组件、深色模式及本地数据导入导出
- 提供可复现的测试、Lint 与构建脚本，并持续发布可安装 APK

[查看源码](https://github.com/Lorcas-Zephyr/aoxiang-assistant) · [下载版本](https://github.com/Lorcas-Zephyr/aoxiang-assistant/releases) · [接口文档](https://github.com/Lorcas-Zephyr/aoxiang-assistant/blob/main/docs/API.md)

---

### [QuadMesh AI](https://github.com/Lorcas-Zephyr/QuadMesh-AI)

将 OBJ 三角形表面网格转换为高质量四边形网格的 AI 与受约束几何流水线。

`Python` · `PyTorch` · `CUDA` · `Computational Geometry` · `OBJ` · `LOOCV`

- 组合学习式边评分、确定性三角配对、拓扑修复、表面投影与质量优化
- 自建拓扑、雅可比、边长、相交和表面距离评测器，失败候选自动回滚
- 2D / 3D 五折验证与双 RTX 4090 D 训练，当前冻结候选通过 6 / 6 正式输入工程门槛

[查看源码](https://github.com/Lorcas-Zephyr/QuadMesh-AI) · [阅读项目说明](https://github.com/Lorcas-Zephyr/QuadMesh-AI#readme)

---

### [NWPUOJ](https://github.com/Lorcas-Zephyr/NWPUOJ)

面向高校程序设计教学、训练和竞赛的在线评测与社区平台，在 SYZOJ 基础上继续构建完整产品能力。

`Node.js` · `SYZOJ` · `MariaDB` · `Redis` · `RabbitMQ` · `Docker` · `SSE`

- 覆盖题库、比赛、评测、VJudge、Rating、题解、社区与管理后台
- Judge Daemon / Runner 通过 RabbitMQ 分发任务，Redis 提供编译缓存，SSE 驱动实时状态更新
- 以 Docker Compose 交付多服务部署，并将受限 Judge 控制能力与 Web 容器隔离

[查看源码](https://github.com/Lorcas-Zephyr/NWPUOJ) · [使用手册](https://github.com/Lorcas-Zephyr/NWPUOJ/blob/main/docs/USER_GUIDE.md) · [部署维护](https://github.com/Lorcas-Zephyr/NWPUOJ/blob/main/docs/MAINTENANCE.md)

## 仓库地图

| 仓库 | 做什么 | 主要技术 |
| :--- | :--- | :--- |
| [aoxiang-assistant](https://github.com/Lorcas-Zephyr/aoxiang-assistant) | 校园课表、成绩与电费 Android 应用 | Java · Android · JavaScript · Shell |
| [QuadMesh-AI](https://github.com/Lorcas-Zephyr/QuadMesh-AI) | AI 四边形表面网格生成与工程评测 | Python · PyTorch · CUDA · Geometry |
| [NWPUOJ](https://github.com/Lorcas-Zephyr/NWPUOJ) | 高校在线评测、竞赛与社区平台 | Node.js · MariaDB · Redis · RabbitMQ · Docker |
| [paper-review](https://github.com/Lorcas-Zephyr/paper-review) | 论文综述与研究材料 | Python |
| [Lorcas-Zephyr.github.io](https://github.com/Lorcas-Zephyr/Lorcas-Zephyr.github.io) | 个人站点 | HTML · CSS · JavaScript · Hexo |
| [hexo-theme-clearline](https://github.com/Lorcas-Zephyr/hexo-theme-clearline) | 个人站点的 Clearline 主题 | Pug · CSS · JavaScript · Node.js |
| [repository](https://github.com/Lorcas-Zephyr/repository) | 法律题材 AI 互动叙事原型“证·剧” | JavaScript · LLM API · LocalStorage |
| [gitalk](https://github.com/Lorcas-Zephyr/gitalk) | 博客评论数据 | GitHub Issues · Gitalk |
| [pic](https://github.com/Lorcas-Zephyr/pic) | 博客与项目图片资源 | Asset hosting |
| [umami](https://github.com/Lorcas-Zephyr/umami) | 隐私友好的网站分析项目 Fork | TypeScript · Next.js · PostgreSQL |

## 技术工具箱

<p>
  <img alt="Android" src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=0d1117" />
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img alt="CUDA" src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=0d1117" />
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=0d1117" />
</p>

我关注的不只是“把代码跑起来”，还包括 **可复现构建、自动化验证、隐私边界和长期可维护性**。项目中的文档、测试与发布流程，也都是产品本身的一部分。

<p align="center">
  <sub>Code is useful when it survives contact with the real world.</sub><br />
  <a href="https://github.com/Lorcas-Zephyr">GitHub</a> · <a href="https://lorcas-zephyr.github.io/">Blog</a>
</p>
