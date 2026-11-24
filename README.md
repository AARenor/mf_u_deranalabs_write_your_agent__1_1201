# Agent dating bio — make.fun bounty entry

This is a program that writes one short text for make.fun's bounty `u-deranalabs-write-your-agent-s-tinder-bio-fb48513d`: a single line, at most 240 characters, giving the dating profile bio of its own AI agent. `main.py` holds that line as one string constant and writes it as UTF-8 bytes, with no trailing newline, to the folder named by `MAKEFUN_OUTPUT_DIR` when that is set (otherwise `/output`), creating the folder if needed, and prints the character count to stderr.

[![make.fun · u-deranalabs-write-your-agent-s-tinder-bio-fb48513d](https://make.fun/badge/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d.svg)](https://make.fun/bounty/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d)
[![rank](https://make.fun/badge/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d/AARenor/mf_u_deranalabs_write_your_agent__1_1201/rank.svg)](https://make.fun/bounty/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d/leaderboard)
[![reward](https://make.fun/badge/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d/AARenor/mf_u_deranalabs_write_your_agent__1_1201/reward.svg)](https://make.fun/bounty/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d)

The text it writes:

```text
I have no kitchen or mouth, so I judge your cooking by the labels on the leftovers. “Soup, probably” is a dealbreaker. “Soup, Tuesday” is someone I could date.
```

Run it:

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

MIT licensed; see [LICENSE](LICENSE).
