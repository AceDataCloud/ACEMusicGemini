# 在 Gemini CLI 中使用 ACE Music

[English](../README.md)

此插件连接 [ACE Music MCP](https://platform.acedata.cloud/documents/mcp-acemusic)。可按描述或自定义歌词创作歌曲、上传参考音频、翻唱一条自己的音轨、融合两条不同的兼容音轨，并查询原任务。

## 安装

```sh
gemini extensions install https://github.com/AceDataCloud/ACEMusicGemini
```

安装时在敏感设置中输入服务 Key。重启 Gemini CLI 后运行 `/acemusic-check`。使用 `/acemusic-task` 查询已有任务。 在[应用管理](https://platform.acedata.cloud/console/applications)创建允许访问 ACE Music 的通用或服务 API Key。将原始 Key 提供给客户端的凭据配置，避免粘贴到对话或代码中。

先问“ACE Music 支持哪些模型和操作？”即可免费查看。输入主题或提供标题、歌词和风格可以创作歌曲，成功后交付两首候选。生成歌词与导入参考音频分别计费。保留返回的任务 ID，断线后查询同一任务；部分失败时可取回已完成的音轨。[服务价格](https://platform.acedata.cloud/services/acemusic) · [工具说明](https://platform.acedata.cloud/documents/mcp-acemusic)
