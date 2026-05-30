## 整体规划

参考 Stanford CS229 的机器学习框架：机器学习是一套从数据中学习规律的技术，主线包括监督学习、无监督学习、学习理论、强化学习和应用实践；本仓库还特别放入了 PCA/SVD/QR、树模型、推荐系统、Attention 和 YouTube 推荐论文精读。

```text
机器学习 = 用数据训练可泛化的预测、表示和决策系统
│
├── 这门课要解决的问题
│   ├── 怎样从已有样本预测未知样本？
│   │   └── 用监督学习、损失函数和优化方法学习输入到输出的映射
│   ├── 没有标签时怎样发现结构？
│   │   └── 用降维、聚类、表示学习从数据中提取隐藏模式
│   └── 模型怎样进入真实业务？
│       └── 用推荐、CTR、排序、A/B Test 和误差分析连接算法与效果
│
├── 工具一  数学与表示基础
│   ├── PCA / SVD          从矩阵分解理解降维和主方向
│   ├── QR 与最小二乘      理解线性模型背后的投影问题
│   └── LLL 与子空间视角   补充更深的线性代数工具
│
├── 工具二  经典模型与学习理论
│   ├── 基础概念           明确样本、特征、标签、目标函数
│   ├── 树模型与随机森林   用分裂、集成处理非线性关系
│   └── 泛化与调参         关注过拟合、偏差方差和模型选择
│
├── 工具三  推荐与广告系统
│   ├── BPR 与推荐建模     从用户行为学习偏好排序
│   ├── CTR 预估           把点击概率建成可优化目标
│   └── Learning to Rank   把搜索、广告、推荐统一到排序问题
│
└── 工具四  深度模型与论文精读
    ├── Attention / Transformer  理解序列建模的新结构
    ├── YouTube Recommendations  学习候选生成与排序两阶段架构
    └── 书单与项目材料           把理论、论文和业务实践连起来
```

<!-- Author : Dongsheng Deng & Liam Huang-->
<!-- Program Email: elegantlatex2e@gmail.com -->

[Homepage](https://elegantlatex.org/) | [Github](https://github.com/ElegantLaTeX/ElegantBook) | [CTAN](https://ctan.org/pkg/elegantbook) | [Download](https://github.com/ElegantLaTeX/ElegantBook/releases) | [Wiki](https://github.com/ElegantLaTeX/ElegantBook/wiki) | [Weibo](https://weibo.com/elegantlatex)

![License](https://img.shields.io/ctan/l/elegantbook.svg) ![CTAN Version](https://img.shields.io/ctan/v/elegantbook.svg) ![Github Version](https://img.shields.io/github/release/ElegantLaTeX/ElegantBook.svg) ![Repo Size](https://img.shields.io/github/repo-size/ElegantLaTeX/ElegantBook.svg)

---

# ElegantBook 优美的 LaTeX 书籍模板

ElegantBook 是为 LaTeX 书籍写作而设计的模板，由 [Dongsheng Deng](https://ddswhu.me/) 和 [Liam Huang](https://liam.page/) 创立，模板创立的初衷是方便我们自己做笔记 :smile:。如果你有其他问题、建议或者报告 bug，可以提交 issues 或者给我们发邮件：elegantlatex2e@gmail.com。QQ 用户交流群：692108391，欢迎加入。

## 重要提示

**重要提示**：ElegantLaTeX 项目 **不接受** 任何非预授权的提交（pull requests）！

## 致谢

特别感谢 [sikouhjw](https://github.com/sikouhjw) 和 [syvshc](https://github.com/syvshc) 长期以来对于 Github 上 issue 的快速回应，以及各个社区论坛对于 ElegantLaTeX 相关问题的回复。
特别感谢 ChinaTeX 以及 [LaTeX 工作室](http://www.latexstudio.net/)对于本系列模板的大力宣传与推广。

如果你喜欢我们的模板，你可以在 Github 上收藏我们的模板。

## 协议

本模板发布遵循 LaTeX 项目公共许可证 1.3 c 或更高版本。如果是衍生作品，请务必加入协议声明和模板信息（github、CTAN 地址）。

## 衍生作

+ [ElegantBookdown](https://github.com/XiangyunHuang/ElegantBookdown)：[XiangyunHuang](https://github.com/XiangyunHuang) 开发并维护的基于 ElegantBook 的 Bookdown 模板。
+ [bookdownplus](https://github.com/pzhaonet/bookdownplus)：应网友要求，[pzhaonet](https://github.com/pzhaonet) 在 bookdownplus 收录了 ElegantPaper 模板，并为 Mac 做了字体适配。
+ [PanBook](https://github.com/annProg/PanBook)：[annProg](https://github.com/annProg) 开发并维护的基于 Markdown 写作的工作流，收录了 ElegantBook 和 ElegantPaper 模板。
