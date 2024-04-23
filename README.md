> [!WARNING]  
> As of 2024-04-18 this fork is no longer compatible with current releases of Team Fortress
> 2, and I have no intent of keeping gamedata synchronized across both.  Please grab releases
> from [FlaminSarge's repository][flaminsarge].

# tf2attributes

TF2Attributes SourceMod plugin

https://forums.alliedmods.net/showthread.php?t=210221

## Differences from FlaminSarge's upstream

This repository has been merged upstream, so there are no significant feature differences.
Feel free to [download the latest version from there][flaminsarge].  I've been added as a
collaborator there; stabilized features will eventually make their way there.

~~This repository will remain for any experimental changes.~~

[flaminsarge]: https://github.com/FlaminSarge/tf2attributes

## Installing or migrating

This fork is forward compatible with FlaminSarge/tf2attributes &mdash; all plugins compiled for
their version should continue to work with this one.  The installation instructions remain the
same.

1. Download all the non-source code files in [the latest release][].
2. Copy `tf2attributes.smx` to `addons/sourcemod/plugins/`.
3. Copy `tf2.attributes.txt` to `addons/sourcemod/gamedata/`.
4. If you're a developer, copy `tf2attributes.inc` to `addons/sourcemod/scripting/include/`
(or the appropriate path for your compiler toolchain / project).

[the latest release]: https://github.com/nosoop/tf2attributes/releases
