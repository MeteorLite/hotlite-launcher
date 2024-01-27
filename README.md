![](https://runelite.net/img/logo.png)
# hotlite-launcher  

Using hotlite-launcher, you can run custom RuneLite builds with the official Jagex/RuneLite launchers even using jagex accounts.  
This is done by swapping/adding jars on the classpath in the launcher before the client is ran.  
There is a build config included in the launcher project but you must manually replace RuneLite.jar with hotlites in your RuneLite Launcher installation directory.  
Because we use runelites official injected-client, we MUST maintain api consistency with the current live release of RuneLite.  
hotlite-client provides a Build/Export run config to update a hotlite-client build for hotlite-launcher  
If there is no exported hotlite for the current runelite release, a warning box will inform the user, and vanilla runelite will be launched instead.

Kotlin 1.9.22 support is bundled into the launcher/client.  
Ethans API is bundled.

# launcher [![Discord](https://img.shields.io/discord/301497432909414422.svg)](https://discord.gg/mePCs8U)

This repository holds the launcher for the [RuneLite client](https://github.com/runelite/runelite).

If you have any questions, please join our [Discord](https://discord.gg/mePCs8U) server or alternatively our IRC channel on [irc.rizon.net #runelite](http://qchat.rizon.net/?channels=runelite&uio=d4).

### License

RuneLite is [licensed under the BSD 2-clause license](https://github.com/runelite/launcher/blob/master/LICENSE).
