# 智能聊天助手

基于 Deepseek 大模型的智能聊天助手，使用 Streamlit 构建。

## 功能特性

- 🤖 友好的 AI 聊天界面
- 💬 流式响应，实时显示
- 📝 对话历史记录
- 🚀 基于 deepseek-v4-flash 模型

## 环境要求

- Python 3.8+

## 安装步骤

1. 克隆仓库到本地
```bash
git clone <你的仓库地址>
cd chatbox
```

2. 安装依赖
```bash
pip install -r requirements.txt
```

3. 配置环境变量
   
   创建 `.env` 文件（如果不存在），添加你的 API 密钥：
```
OPENAI_API_KEY=你的Deepseek_API密钥
```

4. 运行应用
```bash
streamlit run chatbox2.py
```

## 使用说明

1. 在浏览器中打开 http://localhost:8501
2. 在输入框中输入你的问题
3. AI 会实时回复你的问题

## 注意事项

- 确保你的 `.env` 文件中有有效的 `OPENAI_API_KEY`
- `.env` 文件已包含在 `.gitignore` 中，不会上传到 GitHub
- 你需要从 Deepseek 官网获取 API 密钥
