Simple plugin that allows you to reward players for voting without using Votifier.

**config.yml**
```yaml
id: 1 <--- server id (for minecraft-list.org/server/4131 it should be 4131)
requireonline: true <--- require player to be online to get rewarded
commands:
  - "say %player% thank you for your vote at Minecraft-List.org"
  - "give %player% dirt 1"
```