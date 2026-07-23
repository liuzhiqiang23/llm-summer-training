# 大模型部署与应用 — 暑期实训资料

> 2026 暑期大模型实训课程全套资料，涵盖教材课件、实验任务书、学习笔记和综合实验报告。

## 目录结构

```
├── 教材课件/       # 5 份 PDF 课件
│   ├── 01.Ai大模型技术基础.pdf
│   ├── 02.Linux操作系统基础.pdf
│   ├── 03.大模型本地部署.pdf
│   ├── 04.大模型接口调用.pdf
│   └── 05.容器技术基础.pdf
├── 实验任务书/     # 2 份实验任务书
│   ├── 大模型部署与应用实验任务书.pdf
│   └── RockyLinux基础操作实验任务书.pdf
├── 实验报告/       # 1 份综合实验报告
│   └── 大模型部署与应用综合实验报告.docx
├── 学习笔记/       # 2 份课程笔记
│   ├── AI大模型技术基础-学习笔记.docx
│   └── Linux操作系统基础-学习笔记.docx
└── 操作指南/       # 1 份工具指南
    └── LM_Studio_详细操作指南.docx
```

## 实验内容

1. **llama.cpp 量化部署** — 源码编译、GGUF 转换、Q8_0/Q4_K_M/Q2_K 量化、服务部署
2. **Cherry Studio 提示词工程** — LM Studio GPU 加速、角色设定/少样本/思维链/格式约束
3. **Python API 流式对话** — OpenAI 兼容 API、多轮记忆、跨后端适配
4. **MCP 协议与 Skill 配置** — MCP 六大原语、@cherry/fetch + @cherry/memory
5. **Docker 容器化部署** — Rocky Linux Docker CE、LLM 推理容器、GPU 访问

## 环境

- Windows 11 + Rocky Linux 虚拟机
- Python 3.x / openai / python-docx
- llama.cpp / LM Studio / Cherry Studio / Docker CE
- DeepSeek API
