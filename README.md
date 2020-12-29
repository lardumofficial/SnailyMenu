# SnailyMenu
SnailyMenu is server sided menu for FiveM servers, including full\* permission support.


\*(Some features do not have permissions support. However, they will be disabled if you deny access to the submenu that they are a part of (eg: unlimited stamina in Player Options will be disabled if you deny `vMenu.PlayerOptions.Menu`.))

--------

# Download & Installation & Permissions

## Download

Click [here](https://github.com/TomGrobbe/vMenu/releases) to go to the releases page and download it.

--------

## Installation
Please follow the instructions over at the [SnailyMenu docs](https://docs.snaily.run/snailymenu/installation)

## Zap Hosting
If you're using Zap Hosting, you may find that moving the `permissions.cfg` file to the same folder as your `server.cfg` file may not work correctly (it could get reset every time you restart your server).

If this is the case, leave your `permissions.cfg` file here: `/resources/SnailyMenu/config/permissions.cfg` and add the following to the very top of your server.cfg file: `exec resources/SnailyMenu/config/permissions.cfg` (instead of `exec permissions.cfg`).

You can also use ZAP Hosting's one-click installer for SnailyMenu.
--------

## Trouble shooting & support

- [docs](https://docs.snaily.run/SnailyMenu/)
- [discord](https://snaily.run/discord)
- [support](https://snaily.run/support)


--------

## Permissions 
Click [here](https://docs.vespura.com/vmenu/permissions-ref) for permissions information.

## Configuration
Click [here](https://docs.vespura.com/vmenu/configuration) for configuration options information.


--------


## MenuAPI
SnailyMenu will be using [MenuAPI (MAPI)](https://github.com/TomGrobbe/MenuAPI), a custom menu API designed by [TomGrobbe](https://www.vespura.com).



--------

## License
**For an updated license, check the license.md file. This file will always overrule anything mentioned in the readme.md**


Snaily is a subsidiary of [Lardum](https://www.lardum.net).
Copyright © 2021 [TomGrobbe](https://www.vespura.com) & [Lardum](https://www.lardum.net). All rights reserved.
