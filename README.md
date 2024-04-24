# FoliaWorldLoader

A (temporary) world manager for Folia

_Why does this even exist ??_

## Not Working

- Respawn World
- Portal Teleporting

> Because the current Folia builds don't support them. If one of them does get supported, the related commands will be working.

## Commands & Permissions

| Command                                               | Permission                    | Description                                        |
|-------------------------------------------------------|-------------------------------|----------------------------------------------------|
| `/fwl current`                                        | `foliaworldloader.current`         | Shows the current world                            |
| `/fwl current <player>`                               | `foliaworldloader.current.others`  | Shows the current world of another player          |
| `/fwl teleport <world>`                               | `foliaworldloader.teleport`        | Teleports you to the specified world               |
| `/fwl teleport <world> <player>`                      | `foliaworldloader.teleport.others` | Teleports another player to the specified world    |
| `/fwl linkworld <from_world> <to_world> <nether/end>` | `foliaworldloader.linkportal`      | Link Portals between `from_world` and `to_world`   |
| `/fwl unlinkworld <world> <nether/end>`               | `foliaworldloader.linkportal`      | Un-link Portals of a `world`                       |
| `/fwl linkrespawn <from> <to>`                        | `foliaworldloader.linkrespawn`     | Link Respawn points between `from` and `to`        |
| `/fwl unlinkrespawn <world>`                          | `foliaworldloader.linkrespawn`     | Un-link Respawn points of a `world`                |
| `/fwl setspawn`                                       | `foliaworldloader.setspawn`        | Set the spawn point when a player joins the server |
