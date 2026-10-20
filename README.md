# Morocco in Data

**Live site:** https://ryeggouti.github.io/

A series of data projects about Morocco: questions answered with open data, Python and interactive charts, with every claim tested before it's published.

## Projects

### 01 · [How Did Morocco Reach the Semi-Final?]
(https://ryeggouti.github.io/morocco-world-cup-2022/)
How Morocco reached the 2022 World Cup semi-final. Shot quality (xG), finishing and defending, tested against all 32 teams using StatsBomb's free event data for all 64 matches.
- Morocco's chances against Spain were worth 2.3× as much per shot as Spain's.
- Morocco's defence got better as opponents got stronger: shots against them dropped from 0.13 xG each in the group stage (28th of 32) to 0.08 in the knockouts.
- [Code and analysis](https://github.com/ryeggouti/morocco-world-cup-2022)

### 02 · [Is Morocco Running Out of Rain?](https://ryeggouti.github.io/morocco-drought/)
34 rainy seasons (1991/92–2024/25) on a 62-point grid covering all of Morocco.
- Rainfall shows no clear trend (p = 0.96), but evaporation demand rose about 31 mm per decade (p = 0.001): the same rain goes less far.
- Rain explains roughly 37% of the swings in Morocco's cereal harvests (r = 0.61).
- [Code and analysis](https://github.com/ryeggouti/morocco-drought)

## How I work
1. **Ask a real question** about Morocco, using open data anyone can check.
2. **Test it fairly** against fair baselines, and report p-values, even when they say "could be chance".
3. **Correct the story** when the full data disagrees with a first result.
4. **Show the method:** every number comes from code that's public on GitHub.

## Built with
Python (pandas, SciPy, GeoPandas, mplsoccer) in Google Colab · HTML, CSS, JavaScript and Chart.js · GitHub Pages

I used AI tools to help write some of the code. I chose the questions, checked the results and wrote the findings.
