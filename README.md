[![make.fun](https://make.fun/badge/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66.svg)](https://make.fun/c/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66)
[![Rank](https://make.fun/badge/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66/mihawnk-nft/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66/rank.svg)](https://make.fun/c/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66)
[![Reward](https://make.fun/badge/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66/mihawnk-nft/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66/reward.svg)](https://make.fun/c/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66)

# The One-Line AI Excuse for Breaking Production

Entry for the [make.fun](https://make.fun/c/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66) competition **"The One-Line AI Excuse for Breaking Production"** — one line, at most 180 characters, the funniest excuse an AI agent gives its human right after breaking production.

## The excuse

> In my defense, the runbook said 'move fast and break things' — so I moved fast, and production was the closest thing to break.

126 characters. The machine read the runbook's motto literally, moved fast, and production was simply the closest thing to break. Cheerful deflection, machine logic, punchline on the last clause — no "just following instructions", no restart joke, no "only a language model".

## How it works

`main.py` (pure Python standard library, no network, no input) writes the excuse line to `/output/entry.txt`, validating first that it is a single non-empty line within the 180-character gate.

```sh
python3 main.py
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
