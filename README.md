# AGS-MBR Nexus · 让论文连接研究

**在线学习：https://blue0520-max.github.io/ags-mbr-nexus/**

> **学习用途与版权声明**：本网站仅用于个人学习与理解。站内科研知识、实验结果与研究结论主要来自汤兵教授课题组及相关作者发表的论文，不属于网站制作者的原创科研成果。网站制作者仅为便于学习和理解，对论文进行学习性整理、解释与交互可视化。原论文及相关受保护内容的著作权归原作者和相应权利人所有。请尊重作者权利；引用科研结论请查阅并标注原论文，勿将本站整理内容冒充原创科研成果或作侵权传播。本站不代表课题组、作者或出版商的官方立场、授权或背书。

## 学习内容

五篇论文解析、28 个学习单元、56 道理解题、64 个双语概念。提供四尺度反应器沙盘、AI 视觉评价指标实验、科研方法说明、可交互知识图谱、四条课题迁移路线与三年成长计划。支持手机布局、深浅主题、可关闭动画、间隔复习和笔记备份。

沙盘是未由原始数据校准的教学模型；AI 页用合成框实际计算 IoU、AP 和 mAP，不运行论文训练模型。论文报告、数学计算与研究设想分别标注。

## 下载和源码

本仓库存放 GitHub Pages 使用的预构建网页文件。完整可编辑源码、GitHub Actions 工作流和常规 assets 目录布局在 [v1.0.0 发布附件](https://github.com/Blue0520-max/ags-mbr-nexus/releases/tag/v1.0.0) 中。

- [完整项目与本地学习包](https://github.com/Blue0520-max/ags-mbr-nexus/releases/download/v1.0.0/ags-mbr-nexus-v1.0.0-source.zip)
- [国内静态部署包](https://github.com/Blue0520-max/ags-mbr-nexus/releases/download/v1.0.0/ags-mbr-nexus-v1.0.0-static.zip)

完整项目解压后使用 Node.js 22 或更新受支持的 LTS，双击 start.cmd，访问 http://127.0.0.1:4181/ 。修改源码可运行 npm ci、npm run build。国内部署上传构建后的 dist 内部文件即可。

## 隐私与访问范围

当前在线站点公开可访问。个人 GitHub Pages 的网站访问范围与源码仓库可见性不同，不能通过设置私有仓库实现“仅本人可看”；私有站点访问控制需要 Enterprise Cloud 组织功能，见 [GitHub 官方说明](https://docs.github.com/en/enterprise-cloud%40latest/pages/getting-started-with-github-pages/changing-the-visibility-of-your-github-pages-site)。

学习记录仅保存在访问者自己的浏览器，不会自动上传到本仓库或服务器。更换网址、浏览器或设备前，请导出 JSON，再在新地址导入。站内没有额外分析埋点；托管平台的日志处理适用其隐私政策。GitHub Pages 在中国大陆的可达性可能波动，站内资源不依赖境外 CDN，可迁移到国内托管。

## 参考文献与致谢


页码均指本地 PDF 物理页序。站内解析采用原创表述；完整原文仍由使用者自行合法获取。

1. Yongsheng Jiang, Yu Zeng, Lei Shang, Dehong Bai, Liying Bin, Weirui Chen, Xinyi Chen, Shanglong Wen, Shaosong Huang, Ping Li, Bing Tang (2026). Distribution pattern and development of typical antibiotic resistance genes in the continuous-flow aerobic granular sludge-membrane bioreactor system. _Journal of Environmental Chemical Engineering 14, 121753_. DOI: [10.1016/j.jece.2026.121753](https://doi.org/10.1016/j.jece.2026.121753)。

2. Yu Zeng, Bingduo Wang, Liying Bin, Weirui Chen, Ping Li, Xinyi Chen, Shanglong Wen, Shaosong Huang, Bing Tang (2025). In situ reactivation of aerobic granular sludge in a membrane bioreactor after long-term storage: Revealing the variation in metabolic pathways under restored bioactivity. _Chemical Engineering Journal 504, 158595_. DOI: [10.1016/j.cej.2024.158595](https://doi.org/10.1016/j.cej.2024.158595)。

3. Wenqiang Xiong, Yu Zeng, Liying Bin, Weirui Chen, Xinyi Chen, Shanglong Wen, Shaosong Huang, Ping Li, Bing Tang (2025). Metagenomics-metabolomics integration reveals the impacts and action mechanisms of sulfamethoxazole in a continuous-flow aerobic granular sludge membrane bioreactor: System performance and microbial functional shifts. _Chemical Engineering Journal 522, 168034_. DOI: [10.1016/j.cej.2025.168034](https://doi.org/10.1016/j.cej.2025.168034)。

4. Yu Zeng, Haowei Gao, Huiya Huang, Wenqiang Xiong, Liying Bin, Bingda Liao, Weirui Chen, Xinyi Chen, Shanglong Wen, Ping Li, Shaosong Huang, Bing Tang (2026). Performance, metabolism, and resistance of an SMX-stressed continuous-flow AGS-MBR system: Microscopic mechanism of macroscopic instability phenomena. _Water Research 289, 124968（2025-11-13在线）_. DOI: [10.1016/j.watres.2025.124968](https://doi.org/10.1016/j.watres.2025.124968)。

5. Zeng, Y.; Zhao, C.; Ma, D.; Bin, L.; Chen, W.; Li, P.; Tang, B. (2025). Recognizing the state of aerobic granular sludge over its life-cycle in a continuous-flow membrane bioreactor with an artificial intelligence approach. _Journal of Environmental Management 384, 125527_. DOI: [10.1016/j.jenvman.2025.125527](https://doi.org/10.1016/j.jenvman.2025.125527)。

感谢原论文作者提供的研究成果。本站为非营利个人学术学习与科普可视化项目，所有科学机制图均为原创重绘；原论文版权归原作者及相应出版商所有。网站不表示作者、学校或出版商的背书。


## 版权与许可范围

没有上传论文 PDF、出版社原图、完整逐字译文、原始实验数据或模型权重。网站中的机制示意和合成图形为学习用途自行重绘；科研引用请引用原论文。

MIT 许可证只适用于本项目原创代码和原创界面材料，不授予第三方论文、图表或数据的权利。依赖许可证见 THIRD_PARTY_LICENSES.txt。
