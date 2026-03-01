# 全球主要大模型公司与代表模型（速览）

> 生成时间：2026-03-01（Asia/Shanghai）
> 
> 说明：本报告为行业速览，按生态影响力与公开产品线整理，非穷尽名单。模型版本迭代快，建议以各公司官方文档/发布页为准。

## 1) 美国与欧洲主要公司

### OpenAI
- GPT 系列（如 GPT-4.x、GPT-4o、o 系列推理模型）
- 多模态能力（文本/图像/语音相关）

### Anthropic
- Claude 系列（如 Opus / Sonnet / Haiku 分层）
- Claude Code（开发者工作流生态）

### Google DeepMind / Google
- Gemini 系列（Nano / Pro / Ultra 及后续迭代）
- 面向代码、多模态与 Agent 工作流的衍生能力

### Meta
- Llama 系列（Llama 2/3/3.x）
- 偏开源权重与社区生态

### xAI
- Grok 系列（Grok-1/1.5/2 及后续）

### Cohere
- Command 系列（企业文本与 RAG 场景）
- Embed / Rerank（企业检索常用）

### Mistral AI（法国）
- Mistral 7B、Mixtral、Mistral Large、Codestral

### AI21 Labs（以色列）
- Jurassic / Jamba 等

## 2) 中国主要公司

### 阿里云（通义）
- Qwen（通义千问）系列（通用/代码/数学/视觉等）

### 百度（文心）
- ERNIE（文心）系列

### 字节跳动（豆包）
- 豆包系列（通用、多模态、语音等方向）

### 腾讯（混元）
- 混元系列（通用与行业版）

### 华为（盘古）
- 盘古系列（行业/政企/科研方向）

### 智谱 AI
- GLM / ChatGLM 系列

### 月之暗面（Moonshot AI）
- Kimi 系列（长上下文能力突出）

### 百川智能
- Baichuan 系列

### MiniMax
- abab / MiniMax 系列（文本、语音、视频能力）

### 零一万物（01.AI）
- Yi 系列

### 科大讯飞
- 星火认知大模型系列

### 商汤（SenseTime）
- SenseNova（日日新）系列

## 3) 云厂商与企业生态模型

### Amazon AWS
- Titan 系列（Bedrock 生态）

### IBM
- Granite 系列（企业/代码方向）

### NVIDIA
- Nemotron 及 NIM 推理生态

## 4) 选型建议（简版）

- **通用能力优先**：OpenAI / Anthropic / Google
- **开源与私有化部署**：Meta Llama / Mistral / Qwen / Yi
- **企业检索与知识库**：Cohere（Embed/Rerank）+ 任一主流生成模型
- **中文场景**：Qwen / ERNIE / GLM / Kimi / Hunyuan（按任务评测）
- **代码场景**：Claude 系列、GPT 系列、Codestral、Qwen-Coder（按基准实测）

## 5) 风险与注意事项

1. 模型命名与版本更新很快，需定期复核。  
2. 不同榜单结论差异很大，建议以你真实任务做 A/B 测试。  
3. 生产落地除了模型质量，还要看：成本、延迟、可用区、合规、数据治理、工具链。

---

如需，我可以继续产出：
- 按“代码能力/中文能力/成本”三维对比表（Markdown 表格）
- 私有化部署建议（按显存预算：24GB/48GB/80GB+）
- 适合你团队的 2~3 套技术栈组合方案
