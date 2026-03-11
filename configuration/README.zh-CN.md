# 自定义配置：顶级 AI 模型

> 通过 EvoLink API 为 WorkBuddy 配置多厂商顶级 AI 模型

**语言:** [English](README.md) | 简体中文

[← 返回主 README](../README.zh-CN.md)

---

## 概述

WorkBuddy 支持通过 `models.json` 配置文件接入自定义 AI 模型。连接 **EvoLink API** 后，你可以通过一个 API Key 使用 OpenAI、Google、字节跳动、月之暗面等多家厂商的顶级模型。

> CodeBuddy 使用相同的配置方式，本指南同时适用。

## 前置条件

1. 登录 [EvoLink 控制台](https://evolink.ai/dashboard)
2. 进入 API Keys → 点击「创建新密钥」
3. 复制生成的密钥（以 `sk-` 开头）

## 配置步骤

### 1. 找到配置文件

| 工具 | 路径 |
| :--- | :--- |
| **WorkBuddy** (macOS/Linux) | `~/.workbuddy/models.json` |
| **WorkBuddy** (Windows) | `C:\Users\<用户名>\.workbuddy\models.json` |
| **CodeBuddy** (macOS/Linux) | `~/.codebuddy/models.json` |
| **CodeBuddy** (Windows) | `C:\Users\<用户名>\.codebuddy\models.json` |

> 项目级配置（`<项目根目录>/.workbuddy/models.json`）优先级高于用户级配置。

### 2. 添加模型配置

```json
{
  "models": [
    {
      "id": "evolink/auto",
      "name": "Evolink Auto (智能路由)",
      "vendor": "Evolink",
      "apiKey": "sk-your-api-key-here",
      "url": "https://direct.evolink.ai/v1/chat/completions",
      "supportsToolCall": true,
      "supportsImages": true
    },
    {
      "id": "gpt-5.4",
      "name": "Evolink GPT-5.4",
      "vendor": "OpenAI",
      "apiKey": "sk-your-api-key-here",
      "url": "https://direct.evolink.ai/v1/chat/completions",
      "supportsToolCall": true,
      "supportsImages": true
    },
    {
      "id": "doubao-seed-2.0-mini",
      "name": "Evolink Doubao Seed 2.0 Mini",
      "vendor": "ByteDance",
      "apiKey": "sk-your-api-key-here",
      "url": "https://direct.evolink.ai/v1/chat/completions",
      "supportsToolCall": true,
      "supportsImages": true
    }
  ]
}
```

> ⚠️ 请将 `sk-your-api-key-here` 替换为你的 EvoLink API Key。

### 3. 保存并重启

工具会自动检测配置变更并重新加载（1 秒防抖延迟）。

---

## 可用模型

### GPT 系列

| 模型 ID | 显示名称 |
| :--- | :--- |
| `gpt-5.4` | Evolink GPT-5.4 |
| `gpt-5.2` | Evolink GPT-5.2 |
| `gpt-5.1` | Evolink GPT-5.1 |
| `gpt-5.1-chat` | Evolink GPT-5.1 Chat |
| `gpt-5.1-thinking` | Evolink GPT-5.1 Thinking |

### Gemini 系列

| 模型 ID | 显示名称 |
| :--- | :--- |
| `gemini-2.5-pro` | Evolink Gemini 2.5 Pro |
| `gemini-2.5-flash` | Evolink Gemini 2.5 Flash |
| `gemini-3-pro-preview` | Evolink Gemini 3.0 Pro |
| `gemini-3-flash-preview` | Evolink Gemini 3.0 Flash |

### 豆包 Seed 2.0 系列

| 模型 ID | 显示名称 |
| :--- | :--- |
| `doubao-seed-2.0-pro` | Evolink Doubao Seed 2.0 Pro |
| `doubao-seed-2.0-mini` | Evolink Doubao Seed 2.0 Mini |
| `doubao-seed-2.0-lite` | Evolink Doubao Seed 2.0 Lite |
| `doubao-seed-2.0-code` | Evolink Doubao Seed 2.0 Code |

### Kimi K2 系列

| 模型 ID | 显示名称 |
| :--- | :--- |
| `kimi-k2-thinking` | Evolink Kimi K2 Thinking |
| `kimi-k2-thinking-turbo` | Evolink Kimi K2 Thinking Turbo |

---

## Evolink Auto：智能路由

选择 `evolink/auto`，让 EvoLink 自动为每次请求匹配最佳模型。

**工作原理：**
- 分析请求内容，自动选择最合适的模型
- 在保证质量的前提下优先使用性价比最高的模型
- 在多个模型之间分发请求，提升系统稳定性
- 响应中返回实际使用的模型名称

---

## 限制可见模型

使用 `availableModels` 控制下拉菜单中显示哪些模型：

```json
{
  "models": [
    // ... 模型配置
  ],
  "availableModels": [
    "evolink/auto",
    "gpt-5.4",
    "doubao-seed-2.0-mini"
  ]
}
```

---

## 常见问题

**配置文件在哪里？**
参见上方路径表。用户级配置全局生效，项目级配置覆盖用户级。

**配置不生效？**
1. 检查 JSON 格式是否正确
2. 确认 API Key 是否正确
3. 重启应用

**支持哪些模型？**
EvoLink 支持 OpenAI、Anthropic、Google、字节跳动、月之暗面等多家厂商的模型。查看 [模型列表](https://evolink.ai/models)。

**API Key 安全吗？**
仅存储在本地，不会上传到云端。建议设置文件权限防止未授权访问。

---

## 相关链接

- [EvoLink 控制台](https://evolink.ai/dashboard)
- [EvoLink API 文档](https://docs.evolink.ai/en/api-manual)
- [CodeBuddy 官方文档](https://www.codebuddy.cn/docs)
- [完整模型列表](https://evolink.ai/models)
