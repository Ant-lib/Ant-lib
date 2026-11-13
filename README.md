## Ant

Twenty years of building software, from the first line of code to running
the whole engineering org. These days I build agent-first and keep a
short list of rules for when the model is wrong.

```yaml
ant:
  shipped:
    - a loyalty platform past 1M registered users
    - a Bitcoin-native lending protocol, solo, to testnet
    - computer vision damage detection for used cars
    - real-money trading systems, live, with the LLM kept away from the order path
    - an ISO 27001 certification (the least fun, the most useful)
  stack: [TypeScript, Node.js, Python, Kotlin, AWS, Postgres, Next.js, Supabase]
  builds_with: [Claude Code, MCP, subagents, a written plan]
  currently: building NightMarquee, open to leadership roles
```

### Rules I actually follow

- **LLMs stay out of the hot path.** Models suggest, state machines execute.
- **Fail open on data, fail closed on money.**
- **Never serve a stale negative.** A cached "yes" can age a little. A cached "no" has to be rechecked.
- **Verify visibility, not mechanism.** It worked in the logs is not it worked.
- **Bound what the model may touch.**

### In the open

| | |
|---|---|
| **[hingewave](https://github.com/Ant-lib/hingewave)** | The fold animation for MacBook lids, Windows laptops and Android foldables. Reads the hinge sensor every 20 ms. Three native apps, one effect, parity proved by golden images. |
| **[nightmarquee](https://nightmarquee.com)** | Cinematic websites you can make your own: pick a scene, put your brand in it, export a working site. Also runs as an [MCP server](https://github.com/ant-dev-lab/nightmarquee-mcp) inside Claude Code and Cursor. |
| **[honest-crypto-research-data](https://github.com/Ant-lib/honest-crypto-research-data)** | Free crypto data sources, each tested for signal. Spoiler: mostly no. |

### Hire me

Fractional engineering leadership, agent-first builds, architecture
reviews, or a second opinion before you put an LLM near money.

**[constant.engineer](https://constant.engineer)** · **[Message me on LinkedIn](https://www.linkedin.com/in/anton-kraskov)**
