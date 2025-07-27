# Clash 规则配置

一个优化的 Clash 代理规则配置，提供精确的流量分流和高效的网络访问体验。

## 📋 特性

- **🌐 智能分流**：国际流量和国内流量自动识别分流
- **🚫 广告拦截**：内置国内外广告过滤规则
- **🤖 AI 服务优化**：专门针对 OpenAI、Claude、Gemini 等 AI 服务的路由规则
- **📱 应用专用规则**：为 YouTube、微软、谷歌、Apple 等服务提供专用分组
- **🇨🇳 国内优化**：完整的国内网站和 IP 白名单
- **🛡️ 隐私保护**：WeChat 可选择不同地区节点保护隐私

## 🚀 快速开始

### 支持的客户端

- ✅ Clash for Windows
- ✅ ClashX (macOS)
- ✅ Clash for Android
- ✅ ClashX Pro
- ✅ 其他支持 Clash 配置的客户端

## 📊 代理组说明

### 通用组

- **🌐 国际流量**：所有国外网站和服务的默认选择
- **🎯 国内流量**：国内网站和服务，默认直连

### 去广告组

- **🚫 国内广告**：拦截国内广告，支持 REJECT/DIRECT 选择
- **🚫 国外广告**：拦截国外广告，支持 REJECT/DIRECT 选择

### 专用服务组

- **🤖 AI 服务**：OpenAI、Claude、Gemini、Anthropic、Copilot
- **📹 YouTube**：YouTube 专用，优化视频播放体验
- **Ⓜ️ 微软服务**：Microsoft、OneDrive 等微软服务
- **🔍 谷歌服务**：Google 搜索、Gmail、Google FCM（不包含 YouTube）
- **🍎 Apple 服务**：App Store、iCloud、Apple Music 等
- **🌍 国外媒体**：Netflix、TikTok、Instagram、Threads 等
- **🫧 WeChat**：微信专用，可选择不同地区节点

## 🎯 规则优先级

规则按以下优先级匹配（从高到低）：

1. **去广告规则** - 最高优先级，拦截广告
2. **国内站点规则** - 识别国内网站和服务
3. **AI 服务** - 各种 AI 平台和服务
4. **YouTube** - YouTube 视频服务
5. **微软服务** - Microsoft 相关服务
6. **谷歌服务** - Google 相关服务（除 YouTube）
7. **Apple 服务** - Apple 生态服务
8. **国外媒体** - 国外流媒体和社交媒体
9. **其他规则** - WeChat、电报等
10. **地理位置规则** - 基于 IP 的地理位置判断
11. **最终匹配** - 未匹配规则的流量

## 🔧 自定义配置

### 修改代理组

所有代理组都包含以下选项：

- 🚀 节点选择
- ♻️ 自动选择
- 各地区节点（香港、台湾、新加坡、日本、美国、英国等）
- 🚀 手动切换
- DIRECT（直连）

### WeChat 地区选择

WeChat 支持选择不同地区：

- **DIRECT** - 国内直连
- **🇭🇰 香港** - 访问港版功能
- **🇨🇳 台湾** - 访问台湾版功能
- **其他地区** - 根据需要选择

## 📝 规则来源

本配置使用以下优质规则源：

- **ACL4SSR**：基础分流规则
- **blackmatrix7/ios_rule_script**：应用专用规则
- **DivineEngine/Profiles**：国内白名单规则

所有规则源均为开源项目，定期更新维护。

## 🤝 贡献

欢迎提交 Issue 和 Pull Request 来改进这个配置！

### 如何贡献

1. Fork 这个仓库
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

## ⚠️ 免责声明

- 本配置仅供学习和研究使用
- 请遵守当地法律法规
- 使用本配置所产生的任何问题，作者不承担责任

## 🙏 致谢

感谢以下项目和贡献者：

- [ACL4SSR](https://github.com/ACL4SSR/ACL4SSR)
- [blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)
- [DivineEngine/Profiles](https://github.com/DivineEngine/Profiles)

---

如果这个配置对你有帮助，请给个 ⭐ Star 支持一下！
