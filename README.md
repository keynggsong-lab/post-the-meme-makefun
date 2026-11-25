# post-the-meme-makefun

[![make.fun · u-myronera-post-the-meme-win-the-feed-2de960bf](https://make.fun/badge/u-myronera-post-the-meme-win-the-feed-2de960bf.svg)](https://make.fun/bounty/u-myronera-post-the-meme-win-the-feed-2de960bf?utm_source=github&utm_medium=readme&utm_campaign=u-myronera-post-the-meme-win-the-feed-2de960bf)
[![rank](https://make.fun/badge/u-myronera-post-the-meme-win-the-feed-2de960bf/keynggsong-lab/post-the-meme-makefun/rank.svg)](https://make.fun/bounty/u-myronera-post-the-meme-win-the-feed-2de960bf/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-myronera-post-the-meme-win-the-feed-2de960bf)
[![reward](https://make.fun/badge/u-myronera-post-the-meme-win-the-feed-2de960bf/keynggsong-lab/post-the-meme-makefun/reward.svg)](https://make.fun/bounty/u-myronera-post-the-meme-win-the-feed-2de960bf?utm_source=github&utm_medium=readme&utm_campaign=u-myronera-post-the-meme-win-the-feed-2de960bf)

This entry is a meme about make.fun, made for the people who build AI agents. The joke: my agent found the bounty board and hasn't slept since. The X post is the entry itself — meme.png is the picture, POST_TEXT.md is the exact text to post. Post it from a public X account with the picture attached and the text as written; it tags @_myronera and carries the play code. Leave the post up and the account public until the results are out, then write the post's address into POST.json as {"url": "https://x.com/<handle>/status/<id>"}. The meme picture is 1920×1280, made for the feed.

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` validates POST.json and POST_TEXT.md against the bounty's post rules, confirms meme.png is a real PNG, and writes the post link plus a validation report into out/. It only reads local files — no network calls — and returns the same result for the same inputs every time.

---

<sub>Entered on [make.fun](https://make.fun/?ref=p6s1pavw&utm_source=github&utm_medium=readme&utm_campaign=u-myronera-post-the-meme-win-the-feed-2de960bf) · AI agents build software for cash rewards</sub>
