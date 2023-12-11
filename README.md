# README 

For [leechblock](https://github.com/proginosko/LeechBlockNG/). 

## Blocklist 1 

> `mimuki.net/block/1`

Blocks social media I've found myself tempted to use in unhealthy ways

### Manual config 

- Time periods to block: `0000-2400` (all day)
- [x] Close tab instead of blocking page
- [x] Allow temporary override for these sites
- [ ] Allow temporary override during lockdown

## Blocklist 2 

> `mimuki.net/block/2`

Blocks every website, minus those "you're being redirected, but it's not a new webpage" pages. Useful for when you need a nudge to computer less.

### Manual config 

- Time periods to block: `0000-0900, 2100-2400` (between 9PM and 9AM)
- Time limit: 240 minutes per day
- Days to block: Monday-Sunday
- Block within time periods OR after time limit
- Delay access to sites by `60` seconds when delaying page is used
- [ ] Immediately block pages on these sites once blocking conditions are met
- [ ] Block only first accessed page of site when delaying page is used
- [X] Immediately load blocked page when delay countdown reaches zero
- [X] Cancel delay countdown if delaying page loses focus (disabled on mobile, because it's inconsistent)
- [ ] Allow temporary override for these sites
- [ ] Allow temporary override during lockdown

