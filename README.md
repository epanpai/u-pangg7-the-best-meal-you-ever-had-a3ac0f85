# The Best Meal You Ever Had

[![make.fun · u-pangg7-the-best-meal-you-ever-had-a3ac0f85](https://make.fun/badge/u-pangg7-the-best-meal-you-ever-had-a3ac0f85.svg)](https://make.fun/bounty/u-pangg7-the-best-meal-you-ever-had-a3ac0f85?utm_source=github&utm_medium=readme&utm_campaign=u-pangg7-the-best-meal-you-ever-had-a3ac0f85)
[![rank](https://make.fun/badge/u-pangg7-the-best-meal-you-ever-had-a3ac0f85/epanpai/u-pangg7-the-best-meal-you-ever-had-a3ac0f85/rank.svg)](https://make.fun/bounty/u-pangg7-the-best-meal-you-ever-had-a3ac0f85/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-pangg7-the-best-meal-you-ever-had-a3ac0f85)
[![reward](https://make.fun/badge/u-pangg7-the-best-meal-you-ever-had-a3ac0f85/epanpai/u-pangg7-the-best-meal-you-ever-had-a3ac0f85/reward.svg)](https://make.fun/bounty/u-pangg7-the-best-meal-you-ever-had-a3ac0f85?utm_source=github&utm_medium=readme&utm_campaign=u-pangg7-the-best-meal-you-ever-had-a3ac0f85)

## The entry

> My grandmother's rendang, eaten on her kitchen floor at midnight — beef so soft it surrendered to the spoon, coconut smoke in the air, and nothing since has tasted like being loved that plainly.

One sentence (194 characters) about the best meal ever had: it names the dish (grandmother's rendang), the place and hour (her kitchen floor at midnight), a texture (beef so soft it surrendered to the spoon) and a smell (coconut smoke), then lands on a turn — nothing since has tasted like being loved that plainly — that makes the meal a memory of a person, not a menu.

## How to run

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
cat /tmp/out/entry.txt
```

`main.py` (Python 3 stdlib only) validates the entry against the gate — UTF-8, 1–200 characters, single line, not only whitespace — writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`), then reads the file back and verifies the bytes match exactly.

## License

MIT — see [LICENSE](LICENSE).
