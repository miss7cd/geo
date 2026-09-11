## 工作空间目录结构及作用

GEO-WORK/
├── README.md              # 工作空间说明文档（本文件）
├── RULE.md                # 工作空间规则文档：存放本工作空间的执行约束与规范（如「不依赖工作空间外部的记忆」），所有执行须遵守
├── templates/             # 通用模板存放目录（文章/报告等可复用模板）
├── report/                # 工作空间级汇总与总报告目录
│   ├── RP-{YYYY-MM-DD}.html   # 每日报告（可本地预览）
│   └── knowledge.md           # 知识库评估
└── T-{企业名称}-{核心词}/   # 各 GEO项目目录（每个公司一个，按目录规范命名）
    ├── config.json        # 项目配置：项目元数据与检测问句配置
    ├── knowledge/         # 知识库：产品介绍、企业资料、案例等知识文档
    ├── report/            # 该项目检测报告与运营报告
    ├── article/           
    ├──── {YYYY-MM-DD}/    # 文章：命名规则 ART-{媒体}-{question}.md
    ├── data/              # 检测数据：从飞书拉取、用于数据分析的检测数据
    ├──── {YYYY-MM-DD}/       # 按检测日期归档的检测记录（含 {platform}-{questions.id}.json）
    └── resource/          # 资源/素材

