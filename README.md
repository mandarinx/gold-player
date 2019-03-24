# Gold Player Package
A first-person player controller for Unity, built with being user-friendly and developer friendly in mind.

## What?
Gold Player aims to be an easy to use first person player controller for your Unity games. Its goal is to work with as many first-person games as possible without the need to modify much code if any. So be it if it's a horror game, puzzle game or first-person shooter; it should *just work*!

## Why?
I feel like the standard controllers provided by Unity is REALLY bad, like seriously bad. So I once set out to create a player controller that I could use in multiple projects without the need of editing the code for it. It worked fine at first but it was full of bad practices and bugs. So I used my new knowledge to create a new one and it went really good. It even got used in [a game I published](https://hertzole.itch.io/jumps)! But I once started a major refactor and I never finished it and I left it in a weird place. Half good, half really bad. And since that, my coding style has evolved even more. So I wanted to make "the ultimate controller" with all the knowledge I already have and fix stupid problems from the get-go. 

## How do I get started?
This is the package version of Gold Player. See the [normal version](https://github.com/Hertzole/gold-player/tree/master) if you're interested in actually having the code in your project.

**NOTICE: This is how you install it as of writing this. Better git support is rumored to come in 2019.1!**

To install the package version, make sure you're in Unity 2018.3+!

1. Open up your `manifest.json` in `YourGameFolder/Packages/`.
2. Add `"se.hertzole.gold-player": "https://github.com/Hertzole/gold-player.git#package"` to your dependencies list.
3. Go into Unity and it should resolve the packages and include Gold Player.

**UPDATING GOLD PLAYER**
Again, as of writing this, Git support is not finished and the only way to update Gold Player is to manually remove the `lock` section that will be generated at the bottom of your `manifest.json`.
## What do I get?
When you use this player controller you will get the following:
- A solid player controller
- Running and crouching
- Head bob
- Audio for footsteps, jumping, and landing
- Moving platforms support
- Easy to use functions
- Extendable classes
- Documented code
- Interaction component
- Easy to use UI component

## What can I expect later?
I have several things I want to do with this player controller. Here are some thing I would like to do.
- Extra components (stuff that could help you make your game and hooks into the player)
- Intergrate the [new Unity Input System](https://github.com/Unity-Technologies/InputSystem) (when it becomes more stable).
- More easy to use API

Those are just some things I can think of right now. I will, of course, add more stuff as time goes on!

## Q&A
Q: Why the name 'Gold Player'?  
A: I'm a big fan of the player controller is [GoldSrc](https://en.wikipedia.org/wiki/GoldSrc) engine and I want to make a player controller that feels just as good, so I went with "Gold Player".

Q: Why open source?  
A: I had my other two player controllers closed source, but I treated them as open source with documentation and such, so I thought it would be fun to make it open source and it could help someone looking for a solid player controller!

Q: Can I use this for my project?  
A: Yes! No restrictions! You can do whatever you want with it. The only thing you can't do is directly reselling my player controller. 

## Screenshots and testing
The available editors.
![Editor](https://raw.githubusercontent.com/Hertzole/gold-player/gh-pages/docs/screenshots/editor.png)
You can also try out a web version of the player controller [here](http://hertzole.github.io/gold-player/docs/play). You can tweak almost all the settings at runtime.
