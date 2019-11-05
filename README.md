# Gold Player Package

## Package Installation

To install the package version, make sure you're in Unity 2018.3+!

### Unity 2018.3 and below 2019.3

1. Open up your `manifest.json` in `YourGameFolder/Packages/`.
2. Add `"se.hertzole.gold-player": "https://github.com/Hertzole/gold-player.git#package"` to your dependencies list.
3. Go into Unity and it should resolve the packages and include Gold Player.

### Unity 2019.3+

1. Open your package manager from Window - Package Manager
2. Click the Plus (+) icon in the top left corner and click "Add package from git URL..."
3. Paste `https://github.com/Hertzole/gold-player.git#package` into the little text box that appears.
4. Unity should soon start resolving packages and download the package.

**UPDATING GOLD PLAYER**
Again, as of writing this, Git support is not finished and the only way to update Gold Player is to manually remove the `lock` section that will be generated at the bottom of your `manifest.json`.
