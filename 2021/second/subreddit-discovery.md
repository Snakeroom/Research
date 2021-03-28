# Discovery of r/second
 
#### The following information is copied from [the Imposter writeup from 2020](https://github.com/Snakeroom/Research/blob/master/2020/imposter/subreddit-discovery.md#rsecond).

## Discovery

[r/Second](https://reddit.com/r/second) is a subreddit created by [u/Tacoeconomy](https://www.reddit.com/user/Tacoeconomy) on <time datetime="2010-04-20T16:56:34.000Z">4/20/2010, 12:56:34 PM EST</time>. An archive of this subreddit is available [here](https://web.archive.org/web/20120124132042/http://www.reddit.com/r/Second).

On <time datetime="2020-02-18T17:50:00.000Z">2/18/2020, 12:50:00 PM EST</time>, u/powerlanguage submitted [a subreddit reclaim request](https://www.reddit.com/r/redditrequest/comments/f5vnvt/requesting_rsecond_only_mod_inactive/) to [r/redditrequest](https://www.reddit.com/r/redditrequest).

Afterwards, the subreddit became private, with its description being a single clock emoji at 3 o'clock:

```
🕒
```

## Confirmation
#### Portions of the following information are adapted from [this announcement post](https://canary.discord.com/channels/429823323585773568/562206450349506560/824096953616433193) in the Snakeroom Discord Server

In the apk for reddit version 2021.11.0 on android, [announced here](https://www.reddit.com/r/redditmobile/comments/mbm24v/reddit_for_android_version_2021110_now_available/) and 
[located here](https://github.com/Snakeroom/Reddit-Assets-Archive/blob/d7370fd9263a3ed8ce650c0ecf5e9cce7bd2e739/2021/Subreddit.js#L12232-L12238), 
references were found to r/second as being the event sub for 2021. 

- The API URL is https://second-api.reddit.com/ (currently a 404)
- The event will be embedded as https://second-api.reddit.com/embed (similar to last year)
- The event involves images in some way

What do we know about the event?

Currently, the Android app makes reference to the following fields:

- round start timestamp
- round end timestamp
- image ids
- Image names
- vote counts
- image id
- image name
- image ranks
- winning image id
- winning image name
- image set name
- image set id

The icon consists of three stacked horizontal lines, left aligned and increasing in width as they go down. The top line is a dark gray, the middle orangered, and the bottom black.

![image](https://user-images.githubusercontent.com/50307653/112734370-f94dc300-8f0a-11eb-93f9-dcebcf34543d.png)

After the conclusion of the chaos arg in March of 2021, an unnamed Reddit employee held a Q&A with community members, stating that while he was kept in the dark
as to the actual contents of the event, as far as he was aware, r/second was the event sub for the 2021 Reddit AFD event.

This information is up to date as of  <time datetime="2021-03-27T15:03:00.000Z">March 27, 2021, 3 PM MDT</time>.
