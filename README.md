# Combat Logger
Logs everything related to combat

## Configuration

Default configuration:

```json
{
  "Combat Logging Main": {
    "Log Combat Damage (Will Override All)": {
      "Log to File": true,
      "Log to Console": true
    },
    "Log Combat Death (Will Override All)": {
      "Log to File": true,
      "Log to Console": true
    },
    "Log Healing Items": {
      "Log to File": false,
      "Log to Console": false
    },
    "Log Player Downed": {
      "Log to File": true,
      "Log to Console": true
    },
    "Show if Player is Sleeping in Log (Only for Attacking not Death)": true,
    "Log Players Getting Attacked while Sleeping": true,
    "Show Body Part Hit": true,
    "Log Respawns": {
      "Log to File": true,
      "Log to Console": true
    }
  },
  "Combat Hurt Logging": {
    "Log Player Attacking Player": {
      "Log to File": true,
      "Log to Console": true
    },
    "Log Animal Attacking Player": {
      "Log to File": true,
      "Log to Console": true
    },
    "Log NPC Attacking Player": {
      "Log to File": true,
      "Log to Console": true
    },
    "Log Player Attacking NPC": {
      "Log to File": true,
      "Log to Console": true
    },
    "Log Player Attacking Animal": {
      "Log to File": true,
      "Log to Console": true
    },
    "Log Entity Attacking Player": {
      "Log to File": true,
      "Log to Console": true
    }
  },
  "Combat Death Logging": {
    "Log Player killing Player": {
      "Log to File": true,
      "Log to Console": true
    },
    "Log Animal killing Player": {
      "Log to File": true,
      "Log to Console": true
    },
    "Log NPC killing Player": {
      "Log to File": true,
      "Log to Console": true
    },
    "Log Player killing NPC": {
      "Log to File": true,
      "Log to Console": true
    },
    "Log Player killing Animal": {
      "Log to File": true,
      "Log to Console": true
    },
    "Log Entity killing Player": {
      "Log to File": true,
      "Log to Console": true
    },
    "Log Other Player Death": {
      "Log to File": true,
      "Log to Console": true
    }
  },
  "Print Debug Info To Console (Dev)": false,
  "Version": {
    "Major": 2,
    "Minor": 0,
    "Patch": 0
  }
}
```
### Notes
- `Log Combat Damage (Will Override All)` or `Log Combat Death (Will Override All)` - Putting False to Either Put/Log will Override anything put to true below, this should remain on unless you do not want a specific logging
- `Show if Player is Sleeping` - Setting this to True will place a `(*Sleeping*)` Next to the Name of the player if they are sleeping
- `Log Players Getting Attacked while Sleeping` - Log player being attacked while sleeping
- `Show Body Part Hit` - Will show the Body Part that was hit

#### Credits
- Tori1157, the original author of this plugin
- RocketMyrr, for updating and Maintaining
