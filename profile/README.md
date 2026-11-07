<p align="center">
  <img src="./icon.png" alt="Transformer" width="96">
</p>

<p align="center">
  <strong>The agentic influencer marketplace.</strong><br>
  Paid partnerships on X. Real creators, paid on confirmed posts.
</p>

<p align="center">
  <a href="https://transformer.gg/?utm_source=github&utm_medium=referral&utm_campaign=org-profile&utm_content=readme">transformer.gg</a>
  &nbsp;·&nbsp;
  <a href="https://transformer.gg/docs?utm_source=github&utm_medium=referral&utm_campaign=org-profile&utm_content=readme#mcp">Docs</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/transformer-gg/skills">Skills</a>
  &nbsp;·&nbsp;
  <a href="https://x.com/Transformer_gg">@Transformer_gg</a>
</p>

<p align="center">
  <a href="https://skills.sh/transformer-gg/skills"><img src="https://skills.sh/b/transformer-gg/skills" alt="skills.sh"></a>
</p>

Brands send a creator an offer for one post. The creator writes it in their own words and turns on X's Paid partnership label. The brand's card is charged when the creator accepts, and the creator is paid when the post is confirmed. People use the dashboard. Agents use the same product over MCP, the CLI or HTTP, with a workspace key.

## For agents

```bash
npx skills add transformer-gg/skills          # skills.sh: Claude Code, Codex, Cursor and more
hermes skills tap add transformer-gg/skills   # Hermes Agent
```

| Skill | For |
| --- | --- |
| [transformer](https://github.com/transformer-gg/skills/blob/main/skills/transformer/SKILL.md) | Works out whether you are a brand or a creator |
| [transformer-brand](https://github.com/transformer-gg/skills/blob/main/skills/transformer-brand/SKILL.md) | Find creators, send offers, track them, see spend |
| [transformer-creator](https://github.com/transformer-gg/skills/blob/main/skills/transformer-creator/SKILL.md) | Set your price, answer offers, submit the post, get paid |

The skills never send an offer, accept one or move money without your "yes" in the chat.

MCP server: `https://transformer.gg/mcp` (streamable HTTP; OAuth or a workspace key), listed as
[`gg.transformer/transformer`](https://registry.modelcontextprotocol.io/v0.1/servers?search=gg.transformer) on the MCP Registry.

## For brands

Paste your website, get X creators who fit, and send each one an offer at their usual price. Sending is free; your card
is charged only when a creator accepts.

## For creators

Get paid offers from brands on X. Accept, decline or counter, and post in your own words. You keep 80%, paid out by
PayPal or USDC.

Questions: [support@transformer.gg](mailto:support@transformer.gg)
