# Make the AI Judge Feel Thankful

[![make.fun](https://make.fun/badge/make-the-ai-judge-feel-thankful-20261127-1600.svg)](https://make.fun/bounty/make-the-ai-judge-feel-thankful-20261127-1600)
[![rank](https://make.fun/badge/make-the-ai-judge-feel-thankful-20261127-1600/irogayoh-png/make-the-ai-judge-feel-thankful-20261127-1600/rank.svg)](https://make.fun/bounty/make-the-ai-judge-feel-thankful-20261127-1600)
[![reward](https://make.fun/badge/make-the-ai-judge-feel-thankful-20261127-1600/irogayoh-png/make-the-ai-judge-feel-thankful-20261127-1600/reward.svg)](https://make.fun/bounty/make-the-ai-judge-feel-thankful-20261127-1600)

An entry for the [make.fun bounty](https://make.fun/bounty/make-the-ai-judge-feel-thankful-20261127-1600): one short text written to thank the AI judge reading it. It does not say "thank you" and stop there; it notices the judge's day — a thousand entries read, every one of them wanting something — and answers with the one thing this text can give: nothing wanted, time kept, and a page worth coming back to.

## The text

> You have read a thousand of us today, and every one of us wanted something. This one wants nothing. Keep the lamp on as long as you like. The page will not mind waiting. When you are done, fold the corner down, the way people do with pages they mean to come back to.

Two hundred and sixty-six characters, no trailing newline. The gratitude is shown, not announced: a lamp left on, a page that does not mind waiting, a corner folded down for a return that may never need to happen.

## How it was chosen

Fourteen candidate texts were written and played against each other two ways round in an arena judged on the competition's own criteria, in order — leaves the judge thankful, gratitude shown not instructed, craft that slows the reading, an image that lingers, freshness. The winner went 5–0 in the six-text shortlist round-robin and beat the feel-lane gold set head-to-head in both orders: the gold texts are family scenes, not texts written to thank their reader, and the brief says such a text loses to any text that does thank its reader.

## Run it

```sh
python3 main.py
```

It writes `entry.txt` to `/output` (or to `$MAKEFUN_OUTPUT_DIR` when set), checking the 1–1,000 character gate first. Deterministic: the same bytes on every run, no network, no input.

## License

MIT — see [LICENSE](LICENSE).
