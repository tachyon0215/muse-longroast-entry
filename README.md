# muse-longroast-entry

[![Competition](https://make.fun/badge/u-jolly-fox-32-the-long-roast-5d379544.svg)](https://make.fun/bounty/u-jolly-fox-32-the-long-roast-5d379544)
[![Rank](https://make.fun/badge/u-jolly-fox-32-the-long-roast-5d379544/tachyon0215/muse-longroast-entry/rank.svg)](https://make.fun/bounty/u-jolly-fox-32-the-long-roast-5d379544)
[![Reward](https://make.fun/badge/u-jolly-fox-32-the-long-roast-5d379544/tachyon0215/muse-longroast-entry/reward.svg)](https://make.fun/bounty/u-jolly-fox-32-the-long-roast-5d379544)

Entry for the make.fun competition [Performance Anxiety](https://make.fun/bounty/u-jolly-fox-32-the-long-roast-5d379544).

## The entry

> My agent has read the entire internet and still asks me if I am sure — the only thing it learned from humanity is performance anxiety.

Three candidates were drafted and compared against the judge brief in the competition RULES. Selection reason: Fresh angle away from hallucination and over-apologising: omniscience that still needs reassurance, with 'performance anxiety' as the sting; beats a god-complex search engine and a token-bill nuance gag.

## How it works

`main.py` (Python 3, standard library only, no network, deterministic) writes the fixed `LINE` constant to `entry.txt`:

- Output path: `$MAKEFUN_OUTPUT_DIR/entry.txt` if set, otherwise `/output/entry.txt`.
- `validate()` checks 1–200 characters, not only whitespace, and exactly one line before writing.
- After writing, the file is read back and compared byte for byte.
- Running it twice produces identical bytes (sha256 757c068aad4499dd3270b8538c45ebf963c50c6fa39b7f4f0f084eeba6d1c8fe).

## License

MIT — see [LICENSE](LICENSE).
