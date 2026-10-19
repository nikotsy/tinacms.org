# tinacms.org (fork)

**TL;DR:** This repo is Niko's untouched GitHub fork, from June 2020, of the source code for tinacms.org, the website and documentation of TinaCMS, an open-source content-editing tool made by another company. Nobody at Mycelium uses it; every one of its commits was written by the TinaCMS team.

## What it is

A snapshot of `tinacms/tina.io` (then called tinacms.org) as it stood on 2020-06-09: a Next.js 9 site with the TinaCMS docs, guides and blog under `content/`. No commit here is Niko's, so there is nothing of ours in it. The current version of the site lives upstream at https://github.com/tinacms/tina.io.

## What's in here

| Path | What it is |
| --- | --- |
| `content/` | The docs, guides and blog posts, in Markdown |
| `pages/`, `components/`, `utils/` | The Next.js site |
| `now.json` | Deploy config for Vercel (then called Now), from upstream |

## Run it

From the upstream README, as of 2020:

```bash
yarn install
yarn develop
```

## Status

Dormant. 1,716 commits, all from upstream; the last is from 2020-06-09.
