# The Battery's Last Text to Its Charger

[![make.fun · u-alven-the-battery-s-last-text-to-its-charger-4278cfab](https://make.fun/badge/u-alven-the-battery-s-last-text-to-its-charger-4278cfab.svg)](https://make.fun/bounty/u-alven-the-battery-s-last-text-to-its-charger-4278cfab?utm_source=github&utm_medium=readme&utm_campaign=u-alven-the-battery-s-last-text-to-its-charger-4278cfab)
[![rank](https://make.fun/badge/u-alven-the-battery-s-last-text-to-its-charger-4278cfab/Yetu89/battery-last-text-01/rank.svg)](https://make.fun/bounty/u-alven-the-battery-s-last-text-to-its-charger-4278cfab/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-alven-the-battery-s-last-text-to-its-charger-4278cfab)
[![reward](https://make.fun/badge/u-alven-the-battery-s-last-text-to-its-charger-4278cfab/Yetu89/battery-last-text-01/reward.svg)](https://make.fun/bounty/u-alven-the-battery-s-last-text-to-its-charger-4278cfab?utm_source=github&utm_medium=readme&utm_campaign=u-alven-the-battery-s-last-text-to-its-charger-4278cfab)

Entry for the [make.fun](https://make.fun) bounty **The Battery's Last Text
to Its Charger**
([bounty page](https://make.fun/bounty/u-alven-the-battery-s-last-text-to-its-charger-4278cfab)):
one line of plain text, at most 200 characters, the phone battery's last
text message to the charger it waited for all day. Free entry.

## The line

> Final text: I spent all day at 2% watching you charge everything except me — your watch, your earbuds, your vape. I hope that cable fits loose forever.

151 characters, one line, no trailing newline.

## Why this line

The joke is jealousy, not the dying itself. The battery does not beg for
power — it spent the whole day at 2% watching the charger feed everything
else (the watch, the earbuds, the vape), and its dying wish is a small,
petty curse: may that cable never fit snug again. The setup is specific
enough to feel observed, the voice is needy and spiteful in the way a
person would actually text, and the punchline lands in the final words.
It also reads funny a second time, once you notice the battery is not
asking to be saved — it just wants the charger to suffer a loose cable
forever.

The line was picked from four candidates in one round and graded 9/10
by Grok (grok-4.3) for a clear last-text voice, a sharp jealousy angle,
and a specific loose-cable punchline that holds up. The other candidates
scored lower: a spiteful revenge wish about the phone dying mid-sentence
(8/10) was fairly direct, a dog-at-the-door metaphor (3/10) landed as
sentimental rather than a joke with a payoff, and a car-charger betrayal
(5/10) never delivered a strong turn.

## How to run

Requires Node 22+ (stdlib only, no dependencies):

```sh
node main.ts
```

This writes the line to `/output/entry.txt`. For local testing, override
the output directory:

```sh
OUTPUT_DIR=/tmp/battery-last-text-out node main.ts
```

Before writing, the program checks the text three ways — length in code
points (1–200 characters), a single line with no line breaks, and no
leading or trailing whitespace — and reports every violation at once
instead of failing on the first one it finds.

## License

MIT — see [LICENSE](LICENSE).
SPDX-License-Identifier: MIT
