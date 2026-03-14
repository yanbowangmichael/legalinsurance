香港保险产品深度分析工具 | Hong Kong Insurance Analytics Tool
       
🏆 基于2025年最新分红实现率数据的交互式保险分析工具
完全离线可用 | 实时收益计算 | 多维度产品对比
English Version | 中文说明
 
📸 预览截图
1. 收益计算器
Calculator 实时计算保单现金价值与IRR，支持调整分红实现率假设
2. 产品对比
Comparison 四大保险公司产品全方位对比
3. 情景模拟
Scenario 乐观/基准/悲观三种情景下的收益预测
4. 公司分析
Company 2025年最新分红实现率数据与雷达图分析
 
✨ 核心功能
🧮 智能收益计算器
•	实时计算：输入年缴保费、缴费年期、持有年期，即时显示预期收益
•	分红实现率模拟：60%-120%可调滑块，查看不同假设下的收益变化
•	四家公司对比：友邦(AIA)、保诚(Prudential)、永明(Sunlife)、宏利(Manulife)
•	保证/非保证分析：清晰展示保证部分与非保证部分的占比
📊 多维度产品对比
对比维度	说明
分红实现率	2025年最新周年红利/终期红利数据
IRR收益	10年/20年/30年/50年预期收益率
保证占比	保证现金价值占总价值的比例
货币选择	支持的保单货币种类
投资风格	固定收益vs权益类资产配置
特色功能	各公司产品的独特优势
🎯 情景模拟分析
•	乐观情景：分红实现率110-120%，经济复苏假设
•	基准情景：分红实现率90-100%，平稳运行假设
•	悲观情景：分红实现率60-80%，市场低迷假设
📚 专业知识库
•	分红实现率、复归红利、终期红利等专业术语解释
•	2025年香港保监局GN16新规解读
•	分红平滑机制原理说明
•	各保险公司官方查询链接
 
🚀 快速开始
在线使用
本地使用
方法1：直接下载（推荐）
1.	下载 index.html 文件
2.	双击文件在浏览器中打开
3.	无需安装，无需网络（离线版）
方法2：克隆仓库
# 直接在浏览器中打开 index.html
方法3：部署到自有服务器
# 复制文件到Web服务器目录
# 或上传到Nginx/Apache服务器
 
📊 数据来源
2025年分红实现率数据
保险公司	周年红利	归原红利	终期红利	数据来源
友邦 AIA	89%	92%	102%	官网

保诚	80%	81%	78%	官网

永明	83%	95%	84%	永明香港官网
宏利	77%	-	107%	官网

⚠️ 免责声明：本工具数据仅供参考，实际产品信息以保险公司官方披露为准。投资有风险，投保需谨慎。
 
🛠️ 技术栈
•	前端框架：原生 HTML5 + CSS3 + JavaScript（零依赖）
•	图表库：原生 SVG / Chart.js（在线版）
•	响应式设计：支持桌面端、平板、手机
•	浏览器兼容：Chrome, Firefox, Safari, Edge 最新版本
项目结构
hk-insurance-tool/
├── index.html              # 主文件（完全离线版）
├── online-version.html     # 在线版（Chart.js图表）
├── README.md               # 本文件
├── LICENSE                 # MIT许可证
├── screenshots/            # 预览截图
│   ├── calculator.png
│   ├── comparison.png
│   ├── scenario.png
│   └── company.png
└── docs/                   # 文档
    ├── data-sources.md     # 数据来源说明
    └── changelog.md        # 更新日志
 
📝 使用指南
1. 计算预期收益
1.	选择”收益计算器”标签
2.	输入年缴保费（如：10,000美元）
3.	选择缴费年期（5年/10年/20年）
4.	调整分红实现率滑块（建议：友邦90%，保诚70%，永明95%）
5.	选择持有年期（10年/20年/30年/50年）
6.	点击保险公司按钮切换不同公司
7.	查看实时计算结果与现金价值增长表
2. 对比不同产品
1.	切换到”产品对比”标签
2.	查看四大公司的详细对比表格
3.	重点关注分红实现率、IRR、保证占比等核心指标
3. 情景分析
1.	进入”情景模拟”标签
2.	查看乐观/基准/悲观三种情景下的IRR预测
3.	根据自身风险承受能力选择参考情景
 
🔄 更新日志
v1.0.0 (2025-03-14)
•	✅ 初始版本发布
•	✅ 集成2025年最新分红实现率数据
•	✅ 实现四家公司产品对比功能
•	✅ 添加情景模拟分析器
•	✅ 支持完全离线使用
计划功能
•	☐ 添加更多保险公司（万通、富卫等）
•	☐ 历史分红实现率趋势图
•	☐ 保费融资计算器
•	☐ 多货币汇率转换
•	☐ PDF报告导出功能
 
🤝 贡献指南
欢迎提交Issue和Pull Request！
提交Issue
•	🐛 Bug报告：描述问题、复现步骤、期望结果
•	💡 功能建议：描述新功能、使用场景
•	📊 数据更新：提供最新的分红实现率数据来源
开发流程
1.	Fork 本仓库
2.	创建功能分支 (git checkout -b feature/AmazingFeature)
3.	提交更改 (git commit -m 'Add some AmazingFeature')
4.	推送到分支 (git push origin feature/AmazingFeature)
5.	打开 Pull Request
 
📄 许可证
本项目采用 MIT 许可证 - 详见 LICENSE 文件
MIT License

Copyright (c) 2025 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
 
⚠️ 免责声明
1.	数据准确性：本工具数据来源于公开渠道，力求准确但不保证100%无误，请以保险公司官方披露为准。
2.	投资建议：本工具仅供参考学习，不构成任何投资建议或产品推荐。
3.	风险提示：保险产品收益具有不确定性，过往业绩不代表未来表现，投资有风险，投保需谨慎。
4.	责任限制：作者不对因使用本工具而产生的任何直接或间接损失承担责任。
 
📞 联系我们
•	📧 邮箱：yanxu07020713@gmail.com
•	🐙 GitHub Issues：提交问题
 
🙏 致谢
•	数据来源：香港保险业联会、各保险公司官网
•	设计灵感：香港金融管理局公开资料
•	开源社区：感谢所有贡献者的支持
 
⭐ 如果这个项目对您有帮助，请给个Star支持一下！
Made with ❤️ in Hong Kong
 
English Version
Overview
A comprehensive offline-ready analytics tool for Hong Kong insurance products, featuring real-time IRR calculations, multi-dimensional product comparisons, and scenario analysis based on 2025 latest fulfillment ratio data.
Key Features
•	💰 Smart Calculator: Real-time cash value and IRR calculation with adjustable fulfillment ratio assumptions
•	📊 Product Comparison: Side-by-side comparison of AIA, Prudential, Sunlife, and Manulife products

•	🎯 Scenario Analysis: Optimistic, baseline, and pessimistic scenario modeling
•	📚 Knowledge Base: Insurance terminology explanations and regulatory updates
•	🔒 Fully Offline: Works without internet connection
Quick Start
git clone https://github.com/yourusername/hk-insurance-tool.git
open index.html  # or double-click the file
Data Sources
All data is sourced from official insurance company disclosures and the Hong Kong Federation of Insurers as of March 2025.
 
中文说明 | Back to Top
