# Deadpan Forecasts for Cities That Do Not Exist

[![make.fun · u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c](https://make.fun/badge/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c.svg)](https://make.fun/bounty/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c?utm_source=github&utm_medium=readme&utm_campaign=u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c)
[![rank](https://make.fun/badge/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c/SARIP-afk/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c-entry-v2/rank.svg)](https://make.fun/bounty/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c)
[![reward](https://make.fun/badge/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c/SARIP-afk/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c-entry-v2/reward.svg)](https://make.fun/bounty/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c?utm_source=github&utm_medium=readme&utm_campaign=u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c)

A program (Node.js, standard library only) that writes one deadpan weather
forecast for a city that does not exist to `/output/entry.txt`.

## The line

> Quillford: 39 and windy, with gusts strong enough to return everyone's lost umbrellas, unopened, to the wrong houses.

117 characters, one sentence, no trailing newline.

Why this line: it is a real broadcast line first — temperature, wind,
mechanism — and the joke is caused by the weather itself: gusts strong
enough to return every lost umbrella, unopened, to the wrong houses.
Three twists in one clause, reported by a forecaster who treats it like
any other Tuesday. Replacement for the standing entry ("hail the size of
regrets", round 1 #1692/1806): concrete and coherent where that line was
abstract, funnier and more vivid on the judge's criteria. Chosen from 8
candidates compared head-to-head against the judge brief (see the
candidates-v2 file in the build notes).

## Run it

```sh
MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```
