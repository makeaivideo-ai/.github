# MakeAIVideo

**MakeAIVideo is an AI video generator that turns a prompt, a script, an image or a talking avatar into a finished short-form video (script, AI voiceover, AI or stock scenes, captions and music) and posts or schedules it to connected TikTok, Instagram, YouTube, Facebook Pages, LinkedIn, Threads, Pinterest, Bluesky, Telegram and Discord accounts.**

This organization holds the official, MIT-licensed developer packages for [makeaivideo.ai](https://makeaivideo.ai): build video generation and social posting into your code, your terminal or your AI assistant.

| Package | What it does | npm | Docs |
| --- | --- | --- | --- |
| [**mcp**](https://github.com/makeaivideo-ai/mcp) | MCP server with 44 tools. Lets Claude, ChatGPT, Cursor and any MCP client create videos and post them. Hosted at `https://mcp.makeaivideo.ai` | [@makeaivideo/mcp](https://www.npmjs.com/package/@makeaivideo/mcp) | [makeaivideo.ai/docs/mcp](https://makeaivideo.ai/docs/mcp) |
| [**sdk**](https://github.com/makeaivideo-ai/sdk) | TypeScript / JavaScript SDK for the REST API | [@makeaivideo/sdk](https://www.npmjs.com/package/@makeaivideo/sdk) | [makeaivideo.ai/docs/sdk](https://makeaivideo.ai/docs/sdk) |
| [**cli**](https://github.com/makeaivideo-ai/cli) | Command line tool: brief in, finished MP4 out, then post it | [@makeaivideo/cli](https://www.npmjs.com/package/@makeaivideo/cli) | [makeaivideo.ai/docs/cli](https://makeaivideo.ai/docs/cli) |

## What you can make with MakeAIVideo

MakeAIVideo turns almost any starting point into a finished short-form video. Start from a single idea with [prompt to video](https://makeaivideo.ai/prompt-to-video), or bring your own words with [script to video](https://makeaivideo.ai/script-to-video) and [blog to video](https://makeaivideo.ai/blog-to-video), which narrates a blog post you paste in. To teach a topic, [AI explainer videos](https://makeaivideo.ai/ai-explainer-video) add voiceover, scenes, captions and music in one pass.

For a presenter on screen, [AI talking avatar videos](https://makeaivideo.ai/talking-avatar) lip-sync a presenter you pick, or one made from your own reference photo, to a script. [AI spokesperson videos](https://makeaivideo.ai/ai-spokesperson-video) suit corporate messaging you want to re-render when details change, and [AI UGC video ads](https://makeaivideo.ai/ai-ugc-video) put an AI spokesperson on your ad script for Meta and TikTok. [Character swap](https://makeaivideo.ai/character-swap) replaces the person in a video you upload while the motion and audio stay as filmed.

From a still image, [image to video](https://makeaivideo.ai/image-to-video) turns product shots, landscapes and album art into a moving clip, and [animate a photo](https://makeaivideo.ai/animate-a-photo) brings portraits, pets and old family photos to life.

Every video is sized for short-form platforms: use the [TikTok video generator](https://makeaivideo.ai/tiktok-video-generator), the [Instagram Reels generator](https://makeaivideo.ai/instagram-reels-generator) or the [AI YouTube Shorts generator](https://makeaivideo.ai/ai-shorts-generator), or run a [faceless YouTube channel](https://makeaivideo.ai/faceless-youtube-channel) without filming. When a video is ready, [auto-post to social media](https://makeaivideo.ai/auto-post) posts or schedules it to TikTok, Instagram, YouTube, Facebook Pages, LinkedIn, Threads, Pinterest, Bluesky, Telegram and Discord (X is not supported). Plans and credits are on the [MakeAIVideo pricing page](https://makeaivideo.ai/pricing), and AI assistants connect through the [MakeAIVideo MCP server setup guide](https://makeaivideo.ai/docs/mcp).

The SDK, CLI and MCP server above cover the brief-driven tools (explainer, listicle, story, UGC, demo, article and spokesperson), your own scripts, and posting to social accounts.

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
