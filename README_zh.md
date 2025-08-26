# <p align="center"> 🌐 网页一键部署 🚀✨</p>

<p align="center">网页一键部署通过一键部署功能在平台上托管静态网页，支持单个html文件和压缩包部署。</p>

<p align="center"><a href="https://302.ai/product/detail/65" target="blank"><img src="https://file.302.ai/gpt/imgs/github/20250102/72a57c4263944b73bf521830878ae39a.png" /></a></p >

<p align="center"><a href="README_zh.md">中文</a> | <a href="README.md">English</a> | <a href="README_ja.md">日本語</a></p>

![](docs/302_webserve.png)

来自[302.AI](https://302.ai)的[网页一键部署](https://302.ai/product/detail/65)的开源版本。你可以直接登录302.AI，零代码零配置使用在线版本。或者对本项目根据自己的需求进行修改，传入302.AI的API KEY，自行部署。

## 界面预览
文件上传功能，上传一个HTML文件或ZIP压缩包，即可一键部署静态网页。支持设置网页有效期，过期自动下线。
![界面预览](docs/302_Deploy_web_pages_by_one-click_screenshot_01.png)

代码粘贴功能，可以将代码粘贴在此处或使用AI生成代码，支持编辑和实时预览效果。
![界面预览](docs/302_Deploy_web_pages_by_one-click_screenshot_02.png)           

这是实时预览的效果。
![界面预览](docs/302_Deploy_web_pages_by_one-click_screenshot_03.png)        

这是成功部署网页的效果。
![界面预览](docs/302_Deploy_web_pages_by_one-click_screenshot_04.png)      

 
## 项目特性
### 📤 一键部署
支持HTML文件和ZIP压缩包的快速部署。
### ⏱️ 有效期设置
灵活设置网页的在线时长，到期自动下线。
### 🔄 实时预览
支持代码编辑时的实时预览功能。
### 📝 AI代码生成
内置AI辅助生成HTML代码功能。
### 🌍 多语言支持
  - 中文界面
  - English Interface
  - 日本語インターフェース

## 🚩 未来更新计划
- [ ] 新增网页模板


## 🛠️ 技术栈

- **框架**: Next.js 14
- **语言**: TypeScript
- **样式**: TailwindCSS
- **UI组件**: Radix UI
- **状态管理**: Jotai
- **表单处理**: React Hook Form
- **HTTP客户端**: ky
- **国际化**: next-intl
- **主题**: next-themes
- **代码规范**: ESLint, Prettier
- **提交规范**: Husky, Commitlint

## 开发&部署
1. 克隆项目
```bash
git clone https://github.com/302ai/302_deploy_web_pages_by_one_click
cd 302_deploy_web_pages_by_one_click
```

2. 安装依赖
```bash
pnpm install
```

3. 环境配置
```bash
cp .env.example .env.local
```
根据需要修改 `.env.local` 中的环境变量。

4. 启动开发服务器
```bash
pnpm dev
```

5. 构建生产版本
```bash
pnpm build
pnpm start
```

## ✨ 302.AI介绍 ✨
[302.AI](https://302.ai)是一个按需付费的AI应用平台，为用户解决AI用于实践的最后一公里问题。
1. 🧠 集合了最新最全的AI能力和品牌，包括但不限于语言模型、图像模型、声音模型、视频模型。
2. 🚀 在基础模型上进行深度应用开发，我们开发真正的AI产品，而不是简单的对话机器人
3. 💰 零月费，所有功能按需付费，全面开放，做到真正的门槛低，上限高。
4. 🛠 功能强大的管理后台，面向团队和中小企业，一人管理，多人使用。
5. 🔗 所有AI能力均提供API接入，所有工具开源可自行定制（进行中）。
6. 💡 强大的开发团队，每周推出2-3个新应用，产品每日更新。有兴趣加入的开发者也欢迎联系我们
