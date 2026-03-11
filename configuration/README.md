# Custom Configuration: Top-Tier AI Models

> Configure WorkBuddy to use top-tier AI models from multiple vendors through EvoLink API

**Language:** English | [简体中文](README.zh-CN.md)

[← Back to main README](../README.md)

---

## Overview

WorkBuddy supports custom AI model integration through `models.json` configuration files. By connecting to **EvoLink API**, you get access to top-tier models from OpenAI, Google, ByteDance, Moonshot, and more — all through a single API key.

> CodeBuddy uses the same configuration method. This guide applies to both.

## Prerequisites

1. Log in to [EvoLink Console](https://evolink.ai/dashboard)
2. Navigate to API Keys → Click "Create New Key"
3. Copy the generated key (starts with `sk-`)

## Configuration

### 1. Locate Configuration File

| Tool | Path |
| :--- | :--- |
| **WorkBuddy** (macOS/Linux) | `~/.workbuddy/models.json` |
| **WorkBuddy** (Windows) | `C:\Users\<username>\.workbuddy\models.json` |
| **CodeBuddy** (macOS/Linux) | `~/.codebuddy/models.json` |
| **CodeBuddy** (Windows) | `C:\Users\<username>\.codebuddy\models.json` |

> Project-level config (`<project-root>/.workbuddy/models.json`) takes priority over user-level config.

### 2. Add Model Configuration

```json
{
  "models": [
    {
      "id": "evolink/auto",
      "name": "Evolink Auto (Smart Routing)",
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

> ⚠️ Replace `sk-your-api-key-here` with your actual EvoLink API Key.

### 3. Save and Restart

The tool auto-detects config changes and reloads (1-second debounce delay).

---

## Available Models

### GPT Series

| Model ID | Display Name |
| :--- | :--- |
| `gpt-5.4` | Evolink GPT-5.4 |
| `gpt-5.2` | Evolink GPT-5.2 |
| `gpt-5.1` | Evolink GPT-5.1 |
| `gpt-5.1-chat` | Evolink GPT-5.1 Chat |
| `gpt-5.1-thinking` | Evolink GPT-5.1 Thinking |

### Gemini Series

| Model ID | Display Name |
| :--- | :--- |
| `gemini-2.5-pro` | Evolink Gemini 2.5 Pro |
| `gemini-2.5-flash` | Evolink Gemini 2.5 Flash |
| `gemini-3-pro-preview` | Evolink Gemini 3.0 Pro |
| `gemini-3-flash-preview` | Evolink Gemini 3.0 Flash |

### Doubao Seed 2.0 Series

| Model ID | Display Name |
| :--- | :--- |
| `doubao-seed-2.0-pro` | Evolink Doubao Seed 2.0 Pro |
| `doubao-seed-2.0-mini` | Evolink Doubao Seed 2.0 Mini |
| `doubao-seed-2.0-lite` | Evolink Doubao Seed 2.0 Lite |
| `doubao-seed-2.0-code` | Evolink Doubao Seed 2.0 Code |

### Kimi K2 Series

| Model ID | Display Name |
| :--- | :--- |
| `kimi-k2-thinking` | Evolink Kimi K2 Thinking |
| `kimi-k2-thinking-turbo` | Evolink Kimi K2 Thinking Turbo |

---

## Evolink Auto: Smart Routing

Select `evolink/auto` to let EvoLink automatically pick the best model for each request.

**How it works:**
- Analyzes request content and selects the most suitable model
- Prioritizes cost-effective models while ensuring quality
- Distributes requests across models for stability
- Returns the actual model name used in the response

---

## Limit Visible Models

Use `availableModels` to control which models appear in the dropdown:

```json
{
  "models": [
    // ... model configurations
  ],
  "availableModels": [
    "evolink/auto",
    "gpt-5.4",
    "doubao-seed-2.0-mini"
  ]
}
```

---

## FAQ

**Where is the configuration file?**
See the path table above. User-level config applies globally; project-level config overrides it per project.

**Config not working?**
1. Validate JSON format
2. Confirm API Key is correct
3. Restart the application

**Which models are supported?**
EvoLink supports models from OpenAI, Anthropic, Google, ByteDance, Moonshot, and more. See [Model List](https://evolink.ai/models).

**Is the API Key secure?**
Stored locally only. Not uploaded to the cloud. Set file permissions to restrict access.

---

## Links

- [EvoLink Console](https://evolink.ai/dashboard)
- [EvoLink API Documentation](https://docs.evolink.ai/en/api-manual)
- [CodeBuddy Official Documentation](https://www.codebuddy.cn/docs)
- [Full Model List](https://evolink.ai/models)
