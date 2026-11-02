# 文枝

一份灵感，长成多篇好文章。原「汇智 workflow」的写作工作台，采用米白橄榄三叶标志。

## 下载

- [Windows 正式版](https://github.com/luyouq7/huizhi-workflow/releases/latest)：Windows 10/11 x64，下载 `.exe` 安装程序。
- [Mac 测试预览](https://github.com/luyouq7/huizhi-workflow/releases/tag/v2.12.1-mac-preview)：Intel 选 `x64`，Apple 芯片/M 系列选 `arm64`。打开 DMG 后将文枝拖入 Applications。

**Mac 预览尚未经过 Apple Developer ID 签名和公证，首次打开可能需要在“系统设置 → 隐私与安全性”中手动允许。它不是无提示安装的正式签名版，也不进入正式 Mac 自动更新通道。** 不要关闭整个系统的安全保护；正式版需补齐开发者证书并完成签名公证后发布。Mac 预览用户以后需要手动安装一次正式签名版，之后才能应用内更新。

当前 Windows 正式版与 Mac 手动安装预览均为 **2.12.1**。Windows 的新版检查、完整下载与 SHA512 校验已用真实更新组件验证；Mac 的两种架构均通过原生启动和包内 Hermes 测试。

## 包含什么

写作工作台、一份底稿多平台成稿、可组合的智囊（Skill/语言风格/参考资料）、资料与稿件索引、飞书导入与手动回传、可选 OCR、图片和 PPT 功能入口。随包附六套写作智囊及默认 Skill/示例内容，新增“卡兹克 · 公众号长文”。内置 Hermes Agent v0.22.5、对应平台的独立 Python 与依赖，无需额外安装 Python、Git 或 Hermes。Hermes 写作支持 OpenAI 兼容和 Anthropic 协议，风格、Memory、Skill 与参考资料沿用文枝配置；模型审查仍需人工复核。

不包含作者电脑上的私人文档、聊天记录、Memory、API Key 或飞书绑定。使用 AI 与飞书功能时，请配置自己的模型 API 和飞书授权；供应商支持范围与账号权限会影响实际能力。

每个版本附 SHA-256 校验清单与平台构建/启动报告。程序更新不应覆盖用户资料。旧版带更新能力的 Windows 用户可在设置中检查、下载更新；客户端不需要 GitHub Token。

此仓库仅存放安装文件和公开下载信息；源码保持私有。保留原项目与第三方许可，不额外授予商业使用授权，详见发行包中的 LICENSE.txt。

