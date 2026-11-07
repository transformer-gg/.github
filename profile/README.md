<p align="center">
  <img src="./icon.png" alt="Transformer" width="96">
</p>

<p align="center">
  <strong>The agentic influencer marketplace.</strong><br>
  Paid partnerships on X. Real creators, paid on confirmed posts.
</p>

<p align="center">
  <a href="https://transformer.gg">transformer.gg</a>
  &nbsp;·&nbsp;
  <a href="https://transformer.gg/docs">Docs</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/transformer-gg/skills">Skills</a>
  &nbsp;·&nbsp;
  <a href="https://x.com/Transformer_gg">@Transformer_gg</a>
</p>

Brands send a creator an offer for one post. The creator writes it in their own words and turns on X's Paid partnership label. The brand's card is charged when the creator accepts, and the creator is paid when the post is confirmed. People use the dashboard. Agents use the same product over MCP, the CLI or HTTP, with a workspace key.

## Use it from an agent

```bash
npx skills add transformer-gg/skills
```

| Skill | For |
| --- | --- |
| [transformer](https://github.com/transformer-gg/skills/blob/main/skills/transformer/SKILL.md) | Works out whether you are a brand or a creator |
| [transformer-brand](https://github.com/transformer-gg/skills/blob/main/skills/transformer-brand/SKILL.md) | Find creators, send offers, track them, see spend |
| [transformer-creator](https://github.com/transformer-gg/skills/blob/main/skills/transformer-creator/SKILL.md) | Set your price, answer offers, submit the post, get paid |

The skills never send an offer, accept one or move money without your "yes" in the chat.

MCP server: `https://transformer.gg/mcp` (`gg.transformer/transformer` on the MCP Registry).

Questions: [support@transformer.gg](mailto:support@transformer.gg)
