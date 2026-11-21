# ACE Music for Gemini CLI

[简体中文](readme/README_zh_Hans.md)

Create ACE Music songs and lyrics, upload reference audio, cover one owned track, blend two, and retrieve the original task. This Gemini CLI integration connects to the [hosted ACE Music MCP](https://platform.acedata.cloud/documents/mcp-acemusic). You can use the plugin independently of other music integrations.

## Install

```sh
gemini extensions install https://github.com/AceDataCloud/ACEMusicGemini
```

The extension installer prompts for an API token in a sensitive setting. Restart Gemini CLI and run `/acemusic-check`. Use `/acemusic-task` with the original ID to look up a task. Get a general or service API key with ACE Music access from [Applications](https://platform.acedata.cloud/console/applications). Enter the raw key through the client configuration. Keep it out of prompts and repositories.

## First use

Ask “List the ACE Music models and capabilities.” This only reads service information. To make a song, describe the idea or provide the title, lyrics and style. A successful song task returns two candidates. Uploading a reference and generating lyrics are separate billable actions. For a cover, supply one owned audio ID; for a mashup, two different compatible IDs. Keep the returned task ID and query it after reconnecting. [Pricing](https://platform.acedata.cloud/services/acemusic) · [MCP tool reference](https://platform.acedata.cloud/documents/mcp-acemusic)
