# qb-applerobbery
iFruit Robbery For QB-Core ported to over Dons Apples, because the iFruit MLO used is expensive and buggy, causing holes throughout the entire Vangelico area!
This is a simple coord change etc. made by one of my customers (ᏉfxᏒᎶᎥᏉᏁᎬss#9843 or Jana) and with her permission has now been reposted on my github!


Thanks for showing your personal interest in my work! 
Please consider supporting ❤

🔗 > https://discord.gg/Tu94MCDDEa
🔗 > https://samuels-development.dev/


## Installation
### Manually
1. Place the qb-ifruitrobbery folder anywhere into your resources folder and ensure/start it in your server/resources.cfg

2. Add this item to your qb-core/shared/items.lua

```['imac']                             = {['name'] = 'imac',                               ['label'] = 'iMac',                     ['weight'] = 4000,         ['type'] = 'item',         ['image'] = 'imac.png',                         ['unique'] = false,     ['useable'] = false,     ['shouldClose'] = false,    ['combinable'] = nil,   ['description'] = 'Looks pretty expensive to me'},```


3. Add the images contained in the file to your html/images of your respective inventory system!

4. Go to your qb-pawnshop/config.lua and this as a sellable item!

```
    [9] = {
        item = "imac",
        price = math.random(50,100)
    }
```

5. Done! :)


# License

    QBCore Framework
    Copyright (C) 2021 Joshua Eger

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>

