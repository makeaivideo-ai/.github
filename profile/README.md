# MakeAIVideo

**MakeAIVideo is an AI video generator that turns a prompt, a script, an image or a talking avatar into a finished short-form video (script, AI voiceover, AI or stock scenes, captions and music) and posts or schedules it to connected TikTok, Instagram, YouTube, Facebook Pages, LinkedIn, Threads, Pinterest, Bluesky, Telegram and Discord accounts.**

This organization holds the official, MIT-licensed developer packages for [makeaivideo.ai](https://makeaivideo.ai): build video generation and social posting into your code, your terminal or your AI assistant.

| Package | What it does | npm | Docs |
| --- | --- | --- | --- |
| [**mcp**](https://github.com/makeaivideo-ai/mcp) | MCP server with 44 tools. Lets Claude, ChatGPT, Cursor and any MCP client create videos and post them. Hosted at `https://mcp.makeaivideo.ai` | [@makeaivideo/mcp](https://www.npmjs.com/package/@makeaivideo/mcp) | [makeaivideo.ai/docs/mcp](https://makeaivideo.ai/docs/mcp) |
| [**sdk**](https://github.com/makeaivideo-ai/sdk) | TypeScript / JavaScript SDK for the REST API | [@makeaivideo/sdk](https://www.npmjs.com/package/@makeaivideo/sdk) | [makeaivideo.ai/docs/sdk](https://makeaivideo.ai/docs/sdk) |
| [**cli**](https://github.com/makeaivideo-ai/cli) | Command line tool: brief in, finished MP4 out, then post it | [@makeaivideo/cli](https://www.npmjs.com/package/@makeaivideo/cli) | [makeaivideo.ai/docs/cli](https://makeaivideo.ai/docs/cli) |

## Quick start

```bash
# Connect an AI assistant (Claude Code shown; Claude.ai, ChatGPT and Cursor take the same URL)
claude mcp add --transport http makeaivideo https://mcp.makeaivideo.ai

# Or call the API from code
npm install @makeaivideo/sdk

# Or from a terminal
npx @makeaivideo/cli login
```

## Links

- Website: [makeaivideo.ai](https://makeaivideo.ai)
- Developer hub: [makeaivideo.ai/developers](https://makeaivideo.ai/developers)
- API reference: [makeaivideo.ai/docs/api](https://makeaivideo.ai/docs/api)
- OpenAPI spec: [app.makeaivideo.ai/api/v1/openapi.json](https://app.makeaivideo.ai/api/v1/openapi.json)
- REST base URL: `https://app.makeaivideo.ai/api/v1`
- MCP server: `https://mcp.makeaivideo.ai`
- For AI agents: [makeaivideo.ai/agents](https://makeaivideo.ai/agents) · [llms.txt](https://makeaivideo.ai/llms.txt)
- Pricing: [makeaivideo.ai/pricing](https://makeaivideo.ai/pricing) (paid plans with a 7-day trial, card required)
- Support: support@makeaivideo.ai

MakeAIVideo is operated by MintClips Ltd (UK).
