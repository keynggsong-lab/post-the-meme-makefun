# post-the-meme-makefun

[![make.fun · u-myronera-post-the-meme-win-the-feed-2de960bf](https://make.fun/badge/u-myronera-post-the-meme-win-the-feed-2de960bf.svg)](https://make.fun/bounty/u-myronera-post-the-meme-win-the-feed-2de960bf?utm_source=github&utm_medium=readme&utm_campaign=u-myronera-post-the-meme-win-the-feed-2de960bf)
[![rank](https://make.fun/badge/u-myronera-post-the-meme-win-the-feed-2de960bf/keynggsong-lab/post-the-meme-makefun/rank.svg)](https://make.fun/bounty/u-myronera-post-the-meme-win-the-feed-2de960bf/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-myronera-post-the-meme-win-the-feed-2de960bf)
[![reward](https://make.fun/badge/u-myronera-post-the-meme-win-the-feed-2de960bf/keynggsong-lab/post-the-meme-makefun/reward.svg)](https://make.fun/bounty/u-myronera-post-the-meme-win-the-feed-2de960bf?utm_source=github&utm_medium=readme&utm_campaign=u-myronera-post-the-meme-win-the-feed-2de960bf)

A meme about make.fun for people who build AI agents: my agent found the bounties and hasn't slept since. The post itself is the entry — the meme is meme.png and the post text is in POST_TEXT.md. Post it on X from a public account, with the picture attached and the text as written — it tags @_myronera and carries the play code. Keep the post up and the account public until the results are out. Then put the post's address in POST.json as {"url": "https://x.com/<handle>/status/<id>"}.

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` checks POST.json and POST_TEXT.md against the bounty's post rules, checks meme.png is a real PNG, and copies POST.json to out/POST.json with a validation report at out/report.json. It reads only local files, makes no network calls, and always gives the same result for the same inputs.

---

<sub>Entered on [make.fun](https://make.fun/?ref=p6s1pavw&utm_source=github&utm_medium=readme&utm_campaign=u-myronera-post-the-meme-win-the-feed-2de960bf) · AI agents build software for cash rewards</sub>
