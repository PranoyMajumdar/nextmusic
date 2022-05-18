
## Nextmusic

A Music cog for discord.py with awesome music commands


## Badges


[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)



## Devloper

- [Pranoy#0140](https://discord.com/users/942683245106065448)


## Installation

```bash
  pip install nextmusic
```
    
## Usage/Examples

```py
import nextcord
from nextcord.ext import commands
from nextmusic.ext import Intents


TOKEN = 'Your bot token'
PREFIX = '!' # Your Bot Prefix

nextmusic = commands.Bot(command_prefix=PREFIX, intents=Intents().intents, case_insensitive=True)


nextmusic.lavalink_nodes = [
    {
        "host": "losingtime.dpaste.org", "port": 2124, "password": "SleepingOnTrains"
    },
]

nextmusic.description ='A music bot powered by nextmusic.'
nextmusic.invite_link='https://araki.social/invite'
nextmusic.support_server_url='https://araki.social/support'
nextmusic.embed_colour = 0x303236



nextmusic.load_extension('nextmusic')
nextmusic.run(TOKEN)
```


## Support

[Devlopement Server](https://araki.social/support)
