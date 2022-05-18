
## Nextmusic

A Music cog for discord.py with awesome music commands


## Badges


[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)
[![Discord Server](https://araki.social/invite)


## Devloper

- [Pranoy#0140](https://discord.com/users/942683245106065448)


## Installation

```bash
  pip install nextmusic
```
    
## Usage/Examples

```py
import discord, nextmusic
from discord.ext import commands
from nextmusic.ext import Intents

bot = commands.Bot(command_prefix='!', intents=Intents.intents, case_insencitive=True)

bot.description = "A music bot with awesome music commands" #Your bot description

bot.embed_colour = 0x00FF13 #Your bot embed colour

bot.invite_link = "https://araki.social" #Your bot invite link

bot.support_server = "https://araki.social/support" # Your bot support server link


bot.lavalink_nodes = [
    {"host": "losingtime.dpaste.org", "port": 2124, "password": "SleepingOnTrains"},
    # Can have multiple nodes here
]


bot.load_extension('nextmusic')
bot.run('You Bot Token ')


```


## Support

[Devlopement Server](https://araki.social/support)
