# Random frames from [Hamish Macbeth](https://en.wikipedia.org/wiki/Hamish_Macbeth_(TV_series))

Inspired by [kothscreens](https://twitter.com/kothscreens)

![](https://upload.wikimedia.org/wikipedia/en/0/0d/HamishMacbethTitle.png)

## Follow along

* [Twitter](https://twitter.com/hamish__macbeth)
* [Tumblr](https://hamishmacbeth.tumblr.com/)

## Where to watch

* [Acorn TV](https://acorn.tv/hamishmacbeth/)
* [Amazon](https://www.amazon.com/gp/video/detail/B07VWS3T7M/ref=cm_sw_tw_r_pv_wb_Vyx16JI2EAK8s)

## Install

```bash
npm ci
```

### crontab

Every 2 hours for now

```
20 */2 * * * export PATH=/usr/local/bin:$PATH && node /full/ass/path/hamish__macbeth/random-frame.js >> /tmp/cron.log 2>&1
```

### Dependencies

```bash
brew install coreutils ffmpeg node
```
