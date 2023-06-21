Note: As of 2022, **Greenworks has no active maintainer and is no longer in active development**. While **many games continue to use greenworks successfully in production**, depending on your needs, you might want to consider alternatives:

* https://github.com/Spacetech/greenworks - A greenworks fork which seems to have better workshop support and is context-aware but does not seem to have automated builds.
* https://github.com/ceifa/steamworks.js - A greenworks alternative built on Rust, it's unclear what the feature set is.
* https://github.com/greenworksjs/greenworks - A community attempt at reviving greenworks - did not go past the planning stages yet.

Feel free to add a PR for other alternatives. Again, [many projects](https://github.com/greenheartgames/greenworks/wiki/Apps-games-using-greenworks) use greenworks successfully, so this might still be your best choice.

---

# THIS REPO HAS BEEN MODIFIED TO COMPILE GREENWORKS FOR arm64 nw.js! NO OTHER PLATFORMS / FRAMEWORKS HAVE BEEN TESTED.

---

# Greenworks

* Greenworks is a [node.js addon](https://nodejs.org/api/addons.html) that
allows you to integrate your HTML5 game (or app) with
[Steamworks](https://partner.steamgames.com/) by exposing a number of
Steamworks APIs to JavaScript.
* Greenworks was originally developed by
[Greenheart Games](http://www.greenheartgames.com) to enable Steam integration
in [Game Dev Tycoon](http://www.greenheartgames.com/app/game-dev-tycoon/).
Since then, it has been open-sourced and is
[used in many other projects](https://github.com/greenheartgames/greenworks/wiki/Apps-games-using-greenworks).
* Currently Greenworks supports:
  * node v0.8, v0.10, v0.12, v4, v5, v6, v7, v8, v9 and v10
  * NW.js v0.8, v0.11+
  * Electron v1.0.0+
  * Steam SDK v1.53a 
* Greenworks is built using [Native Abstractions for Node.js](https://github.com/nodejs/nan) to
support different node versions.
* The project is currently funded by Greenheart Games and other
donors.

## Download

Prebuilt binaries of Greenworks for NW.js & Electron can be found on
the [releases](https://github.com/greenheartgames/greenworks/releases) page.

You can also download [daily automated builds](https://greenworks-prebuilds.armaldio.xyz/) for a variety of platforms (electron, nw.js, node) and systems (Windows, Mac Linux - 32/64 bit). This is site is graciously provided by [@armaldio](https://github.com/armaldio).

## Documentation

Guides and the API references are located in [docs](docs) directory.

## License

Greenworks is published under the MIT license. See the [license file](https://github.com/greenheartgames/greenworks/blob/master/LICENSE) for details.

## Twitter

If you use Greenworks, please let us know at
[@GreenheartGames](https://twitter.com/GreenheartGames)
and feel free to add your product to our
[product list](https://github.com/greenheartgames/greenworks/wiki/Apps-games-using-greenworks).
