# 智能体协议研究库

Agent Protocols Research Library

## 简介

本研究库汇集了关于主流AI智能体商业/支付协议的深度调研报告，包括：

1. **ACP** (Agent Commerce Protocol) - OpenAI + Stripe
2. **UCP** (Universal Commerce Protocol) - Google
3. **AP2** (Agent Payments Protocol) - Google
4. **x402** - Coinbase
5. **MCP** (Model Context Protocol) - Anthropic
6. **A2A** (Agent2Agent Protocol) - Google
7. **ANP** (Agent Network Protocol) - 开源社区
8. **MPP** (Machine Payments Protocol) - Stripe + Paradigm
9. **对比分析** - 协议全景对比

## 本地部署

### 方式一：Python HTTP 服务器（推荐）

```bash
# 进入项目目录
cd agent-protocols-research

# Python 3
python -m http.server 8080

# 或 Python 2
python -m SimpleHTTPServer 8080
```

然后访问 http://localhost:8080

### 方式二：Node.js http-server

```bash
# 安装 http-server
npm install -g http-server

# 启动服务器
http-server -p 8080
```

### 方式三：VS Code Live Server

安装 VS Code 的 Live Server 插件，右键点击 `index.html` 选择 "Open with Live Server"

## 文件结构

```
agent-protocols-research/
├── index.html          # 网站主页
├── README.md           # 本文件
├── 01-acp.md          # ACP协议调研报告
├── 02-ucp.md          # UCP协议调研报告
├── 03-ap2.md          # AP2协议调研报告
├── 04-x402.md         # x402协议调研报告
├── 05-mcp.md          # MCP协议调研报告
├── 06-a2a.md          # A2A协议调研报告
├── 07-anp.md          # ANP协议调研报告
├── 08-comparison.md   # 协议对比分析
└── 09-mpp.md          # MPP协议调研报告
```

## 使用说明

1. 启动本地服务器后，访问 http://localhost:8080
2. 点击左侧导航栏中的报告文件查看内容
3. 支持 Markdown 渲染、代码高亮、表格显示

## 技术栈

- 前端：原生 HTML + Tailwind CSS
- Markdown 渲染：marked.js
- 代码高亮：highlight.js
- 图标：Heroicons

## 参考资源

- [MCP Specification](https://modelcontextprotocol.io/specification/)
- [A2A GitHub](https://github.com/a2aproject/A2A)
- [UCP Developer Guide](https://developers.google.com/merchant/ucp)
- [AP2 Documentation](https://ap2lab.com/docs/)
- [x402 Website](https://www.x402.org/)
- [ANP White Paper](https://w3c-cg.github.io/ai-agent-protocol/)
- [MPP GitHub](https://github.com/tempoxyz/mpp-specs)

## 许可证

本研究库内容仅供学习研究使用。

---

*最后更新: 2026年3月*
