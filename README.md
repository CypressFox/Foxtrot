# FoxTrot updates

**Download the latest from [Releases](https://github.com/SnowberriFox/Foxtrot-Updates/releases).** Early-access builds are marked pre-release.

FoxTrot is the rhythm game: the Minecraft mod (`foxtrot-X.jar`) and the desktop app (`FoxTrot-X-x86_64.AppImage` for Linux, `FoxTrot-X-windows-x64-setup.exe` for Windows, or `foxtrot-app-X.jar` with Java 21+). The app plays with Minecraft players through the FoxTrot Hub.

`update.json` is what the game reads to tell players there's a newer build (a toast on the title screen and a chat line with a link when they join):

- `promos."1.21.1-latest"`: the newest build, early access included. EA players are told about it.
- `promos."1.21.1-recommended"`: the newest stable build. Everyone is told about it.
- `"1.21.1"`: a one-line note per version, shown with the notice.

Releases from before this repo existed (up to FoxTrot 4.5.4) are in [Pokeshift-updates](https://github.com/SnowberriFox/Pokeshift-updates/releases).
SnowberriLib is needed by every mod: [SnowberriLib-Updates](https://github.com/SnowberriFox/SnowberriLib-Updates/releases).

Keep the repo public so games can read `update.json`. The code lives in the private PokeShift repo.
