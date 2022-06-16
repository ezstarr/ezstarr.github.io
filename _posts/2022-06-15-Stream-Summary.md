---
layout: post
title:  "Stream Summary Mon, June 15, 2022"
date:   2022-06-15 21:47:56 -0700
categories: jekyll update
---

# Bots
## Discord bot
Broke discord bot, heroku no longer has environment variables, wordle doesn't work, announcments don't work.
- [ ] fix wordle
- [ ] after fixed, add scoreboard/leaderboard
  - [ ] look into 
        - postgres, @abstractmethod, base_storage, service-level agreement (SLA)

## Twitch Bot

### Speech recognition works now
- [ ] should include words surrounding 'test', or 'cute' or whatever.
- [ ] add a count

### XKCD
Spent a long time trying to fix comic_num range errors, such as comic_num=0 or 404. Turns out, the API wrapper makes it really easy to do. 
Apparently, the API returns the most recent comic for number '0', so we are all good with that.
- [ ] html scrape through xkcd.com/archives 
  - [ ] !xkcd

### Raided by:
- twitch.tv/anthonywritescode

### TIL:
- "pour one out" means pay respects
  - https://www.youtube.com/watch?v=mi_CgRU63d8 (ty ucelot for sad naruto song)

- `<?php echo "this is php echo" ?> my html here`
  - ^ for when I want to put HTML in PHP? 
- github issues for comments?

Other reminders: 
Get data from chat, including tarot-reading ratings