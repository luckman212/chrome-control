Chrome Control (luckman212 fork)
================================

<img src="img/banner.png" width="256">

Forked from [bit2pixel/chrome-control](https://github.com/bit2pixel/chrome-control)

## Changes vs original:

- removed a couple of gremlins
- matching on `title` + `url` instead of just url, ref: [#9](https://github.com/bit2pixel/chrome-control/issues/9)
- integrated efficiency improvement from [AnthoPakPak's #7](https://github.com/bit2pixel/chrome-control/pull/7)

## Setup

- For URL matching to work, your script filter match mode should be set to **Exact from word boundary**:

<img src="img/match-mode.png">
