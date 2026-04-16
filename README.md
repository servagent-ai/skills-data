# ServAgent Skills Data

Auto-updated skill registry for [ServAgent](https://servagent.ai).

- `data/skills.json` — all approved skills, updated weekly by the crawler
- PRs are opened automatically by [servagent-ai/crawler](https://github.com/servagent-ai/crawler) every Thursday
- Merge a PR → triggers automatic upload to production

## Structure

```
data/
  skills.json       # full skill list (approved)
  skills-latest.json  # latest crawler output (pre-review)
```
