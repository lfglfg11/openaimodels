# OpenAI API余额与模型查询工具/硅基流动余额与模型查询工具

## 项目概述

这是一个轻量级的纯HTML实现的API查询工具，支持OpenAI及任意中转API通道。无需安装部署，开箱即用，通过简单的界面操作即可快速查询账户余额和可用模型列表，支持多个API密钥批量查询。

## 功能特点

- **轻量级实现**：纯HTML+JavaScript开发，无需安装，打开即用
- **通用性支持**：支持OpenAI官方及任意中转API通道查询
- **余额查询**：快速查看账户余额、已用额度和剩余额度
- **模型列表**：展示API支持的所有模型，支持一键复制模型名称
- **多密钥支持**：支持多个API密钥批量查询（回车分隔）
- **本地存储**：API密钥和URL本地保存，保护隐私数据安全

## 界面展示

![API查询工具界面](./screenshot.png)

## 使用方法

1. 在"API请求URL"输入框中选择或输入API服务地址
   - OpenAI官方通道：https://api.openai.com
   - 硅基流动通道：https://api.siliconflow.cn
   - 其他支持的通道也可以手动输入

2. 在"API密钥"文本框中输入您的API密钥
   - 可以输入多个密钥，每个密钥用回车分隔
   - 系统会保存您的输入，下次使用时无需重新输入

3. 点击"查询余额和模型列表"按钮
   - 系统将显示每个密钥的账户余额信息
   - 同时显示该API支持的所有模型列表

4. 模型列表支持点击复制模型名称，方便在其他应用中使用

## 部署说明

### 本地使用

1. 下载项目中的HTML文件
2. 直接双击HTML文件在浏览器中打开即可使用
3. 无需安装任何依赖或配置环境

### 服务器部署

本工具是纯静态网页，可以部署在任何支持静态文件托管的Web服务器上：

## 技术特点

- 纯HTML实现，无需安装部署，开箱即用
- 轻量级设计，不依赖复杂框架和后端服务
- 支持任意OpenAI API中转通道查询
- 本地数据存储，保护API密钥安全
- 响应式界面，适配多种设备使用
- 灵活部署，支持本地直接使用或服务器托管

## 隐私说明

本工具仅在用户浏览器本地运行，不会将您的API密钥发送到除您指定的API服务器以外的任何地方。所有数据仅保存在您的浏览器本地存储中。

## 使用须知

- 请妥善保管您的API密钥，不要在公共设备上使用本工具
- 本工具仅供个人学习和研究使用

## 贡献指南

欢迎对本项目提出改进建议和贡献代码！

1. Fork本仓库
2. 创建您的特性分支 (git checkout -b feature/AmazingFeature)
3. 提交您的更改 (git commit -m 'Add some AmazingFeature')
4. 推送到分支 (git push origin feature/AmazingFeature)
5. 创建一个Pull Request

## 开源协议

本项目采用MIT开源协议，详见[LICENSE](./LICENSE)文件。