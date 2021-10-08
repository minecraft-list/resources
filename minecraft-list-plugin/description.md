Simple plugin that allows you to reward players for voting without using Votifier.

**config.yml**
```yaml
id: 1 <--- server id (for mclist.io/server/4131 it should be 4131)
requireonline: true <--- require player to be online to get rewarded
debug: false <--- if you have a issues with getting votes from mclist.io, just enable it and send logs on our discord
commands:
  - "say %player% thank you for your vote at mclist.io"
  - "give %player% dirt 1"
```
