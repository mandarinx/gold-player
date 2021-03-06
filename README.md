# Gold Player
A first-person player controller for Unity, built with being user-friendly and developer friendly in mind.

## What?
Gold Player aims to be an easy to use first person player controller for your Unity games. Its goal is to work with as many first-person games as possible without the need to modify much code if any. So be it if it's a horror game, puzzle game or first-person shooter; it should *just work*!

## Why?
I feel like the standard controllers provided by Unity is REALLY bad, like seriously bad. So I once set out to create a player controller that I could use in multiple projects without the need of editing the code for it. It worked fine at first but it was full of bad practices and bugs. So I used my new knowledge to create a new one and it went really good. It even got used in [a game I published](https://hertzole.itch.io/jumps)! But I once started a major refactor and I never finished it and I left it in a weird place. Half good, half really bad. And since that, my coding style has evolved even more. So I wanted to make "the ultimate controller" with all the knowledge I already have and fix stupid problems from the get-go. 

## How do I get started?
#### If you want to use it in a game:  
**NEW PACKAGE VERSION!**  
Starting with Unity 2018.3, you can use git as packages in the package manager! Go [here](https://github.com/Hertzole/gold-player/tree/package#package-installation) for installation instructions. If you don't want to use that, you can go the normal route...

Go to [Releases](https://github.com/Hertzole/gold-player/releases) and get the latest release in the form of a Unity package. This will make sure you get a version that should work just fine without any problems. The player is *supported* from Unity 2018.1 and up but it should work fine to at least Unity 2017.1. You may just need to do some manual work on import (like taking care of assembly definitions) (Notice! If you want to use the provided UI component you NEED to use TextMesh Pro in 2018.1 and up and normal text in 2017.3 and down)  
However, if you want to get the latest version (that might not work as intended!) you have to download the entire repository and extract the needed files from it. **NOTICE THAT THE PROJECT REQUIRES AT LEAST UNITY VERSION 2019.3!**
#### If you want to contribute:
Fork the project and start making your changes. Commit them in your own repository and then submit a pull request on this page. Keep in mind that if you want to contribute you should follow the coding style present in the other files. **NOTICE THAT THE PROJECT REQUIRES UNITY VERSION 2019.3!**

## What do I get?
When you use this player controller you will get the following:
- A solid and performant player controller
- Running and crouching
- Head bob
- Audio for footsteps, jumping, and landing
- Moving platforms support
- Easy to use functions
- Extendable classes
- Documented code
- Interaction component
- Easy to use UI component
- Support for [Unity's new Input System](https://github.com/Unity-Technologies/InputSystem/)

## What can I expect later?
I have several things I want to do with this player controller. Here are some thing I would like to do.
- Extra components (stuff that could help you make your game and hooks into the player)
- Performance improvements
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

##

<a href='https://ko-fi.com/I2I4IHAK' target='_blank'><img height='40' style='border:0px;height:40px;' src='https://help.ko-fi.com/hc/article_attachments/360016971454/Ko-fi_Red.png' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a> 
