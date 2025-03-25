# MaiMBot-WiKi 项目介绍

🍔 **麦麦！MaiMBot** 是一个基于大语言模型的智能QQ群聊机器人，旨在为用户提供拟人化的聊天体验和丰富的功能支持。

## 📝 项目简介

- **框架**：基于 `nonebot2` 开发
- **核心能力**：利用大语言模型（LLM）提供智能对话
- **数据存储**：使用 `MongoDB` 实现数据持久化
- **QQ协议支持**：通过 `NapCat` 实现

## 🎯 主要功能

1. **智能聊天**
   - 支持关键词检索主动发言
   - 支持多模型、多厂商自定义配置
   - 动态的 `prompt` 构建器，使回复更拟人

2. **表情包功能**
   - 根据发言内容发送对应情绪的表情包
   - 自动“偷”群友的表情包

3. **日程与记忆**
   - 自动生成一天的日程
   - 聊天记录概括存储，实现记忆功能

4. **知识库与关系系统**
   - 基于 `embedding` 模型的知识库
   - 针对用户和群组的个性化回复（开发中）

## 🚀 开发计划

- **0.6.0**：记忆系统更新
- **0.7.0**：麦麦运行时优化

更多功能正在开发中，欢迎关注！

## 📌 注意事项

- 项目处于活跃开发阶段，可能存在已知或未知的 Bug。
- QQ机器人存在被限制风险，请谨慎使用。

## 💬 交流群

- [一群](https://qm.qq.com/q/VQ3XZrWgMs) 766798517
- [二群](https://qm.qq.com/q/RzmCiRtHEW) 571780722
- [三群](https://qm.qq.com/q/wlH5eT8OmQ) 1035228475
- [四群](https://qm.qq.com/q/wlH5eT8OmQ) 729957033

## 📚 文档结构

- **`docs/notes`**：包含项目介绍、部署指南、工具说明等文档。
- **`docs/.vuepress`**：VuePress 相关配置。

## 🌟 致谢

感谢以下开源项目：

- [nonebot2](https://github.com/nonebot/nonebot2)
- [NapCat](https://github.com/NapNeko/NapCatQQ)

---

📅 **最后更新**：2023年11月

🔗 **项目地址**：[GitHub](https://github.com/Ziphyrien/MaiMBot-WiKi)