<img src="assets/logo.png" alt="PromptBase" width="64" height="64">

# PromptBase for Google Antigravity

Search and use 300,000+ AI prompts and skills from [PromptBase](https://promptbase.com) without leaving Antigravity. Find prompts for game sprites, website images, video ads, marketing copy and more, then have your agent fill them in and use them in your project.

## What it adds

- **The PromptBase MCP server** at `https://promptbase.com/mcp`, with tools to:
  - Search prompts and skills
  - View a listing's description, examples and the creator's rating
  - Open prompts you already own and fill in their variables
  - Download free prompts, or use your PromptBase Select downloads (the agent asks first)
  - Check your plan and list your prompts
- **A `find-prompts` skill** that tells the agent when PromptBase can help and how to use it.

Nothing is ever bought for you. For paid prompts, the agent gives you a link to check out on promptbase.com.

## Install

```bash
agy plugin install https://github.com/promptbasedev/antigravity-plugin
```

Then open Agent settings → Customizations and click **Authenticate** next to PromptBase. Sign in to your PromptBase account (or create a free one), approve the connection, and paste the code back into Antigravity. You can disconnect any time in your PromptBase account settings.

## Network and credentials

- **Network:** the plugin only connects to the hosted MCP server at `https://promptbase.com/mcp`. It runs no local code, scripts or hooks.
- **Credentials:** none are stored in this repository. Antigravity signs in with OAuth the first time it connects, and PromptBase issues it a token for your account.

## Links

- Setup for Claude, ChatGPT, Cursor and other agents: https://promptbase.com/agents
- Privacy policy: https://promptbase.com/privacy
- Support: hello@promptbase.com

## License

The files in this repository are MIT licensed. The PromptBase service and its prompts are covered by the [PromptBase terms](https://promptbase.com/tandcs).
