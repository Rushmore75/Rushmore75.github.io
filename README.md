
Context, Action, Result, Reflection

___
## [Jack-AoIP](https://github.com/Rushmore75/Jack-AoIP)
Having used autiodante's audio over ip in professional situiations, I decided to try my hand at making my own version. After a few iterations and trying different things such as TCP vs UDP connections, i've settled on an ok re implementation of Dante. It is still realtivly latent but it would require further testing to find where this latency is coming from.

TL;DR

Sending audio from one computer to another, where both are using [Jack](https://github.com/jackaudio/jack2) for audio subsystems.

___
## [pulse_remote](https://github.com/Rushmore75/pulse_remote)
This project is for remote controlling the audio levels of a system running with the [pulse audio](https://wiki.archlinux.org/title/PulseAudio) subsystem. While watching a show at my house late at night I noticed that I had no way to change audio levels on my laptop, which was sitting across the room next to the tv. Thus, I wrote wrote a server with node.js to remidy this. It was my first project using node and as such it was quite bad. I have now rewritten the project using Rust and Typescript so it works much better now.

TL;DR

Control audio on a computer using pulse audio via a website

___
## [personal_website](https://github.com/Rushmore75/personal_website)
The year is 2022 and I didn't yet have a personal website... what was I doing with my life? I went ahead and build a quick [server](https://github.com/Rushmore75/personal_website_server/) using Rust, then with the power of [Hugo](https://gohugo.io/) built a static blog-style site. (Note that it doesn't work well on mobile.) So now I have [a website](https://oliveratkinson.net) it's not anything too fancy but it gets the job done and was a good learning experaiance as it was the first website I ever published.

TL;DR

[I have a website](https://oliveratkinson.net)

___
## [player_logger](https://github.com/Rushmore75/player_logger)
Me and some friends were making a modded Minecraft server, and one of the mods was [Open Computers](https://www.curseforge.com/minecraft/mc-mods/opencomputers) which allows you to build little computers inside Minecraft, then run Lua inside them. Considering that the server was a "factions" server it made sense to utilize computeres to help protect the base. So, I made this player logger. A device ingame would scan for players in a radius, then upoad to a [website](https://friendlyfire.oliveratkinson.net/), where it would be timestamped. This was a good project for learning some Lua, as well as how subdomains work. It also has quite nices css in my opinion.

TL;DR

I have [*another* website](https://friendlyfire.oliveratkinson.net/) that kept track of players that visited our Minecraft base.

___
## [notification_relay](https://github.com/Rushmore75/notification_relay)
This was built for a class, but was something I had wanted to make for a while now. It allows for multiple locations to all send notifications to one centeralized system. Where they could then be (un)read from any of the devices. Simmilar to how notifications work for iphone <-> mac. But considering I would never willingly purchace Apply *anything* I needed my own solution. While [kde connect](https://kdeconnect.kde.org/) *does* exist, I could never get it to work. So I made my own. The system usese both Redis and Postrgres for handling information. So it was a fun learning experiance.

TL;DR

Relay messages (notifications) between multiple clients. Has ability to scale way more than it will ever need.

___
## [RushmoreTweaks](https://github.com/Rushmore75/RushmoreTweaks)
RushmoreTweaks is a mod for Minecraft, developed for the same server that [player_logger](#player_logger) was built for. It relays chats & other important events to to a [webserver](#ftbu-drp--ws) where they can then be send to [Discord](https://discord.com). This allows for players to be able to interact, even when not by their gaming pc. It was the first Minecraft mod I had ever made and it was for an old, unsupported version to boot! Making this a quite challenging project to tackle, because if you want to ask for help online anywhere, they will just get mad that you aren;t using the newest version of the game.

TL;DR

Mod for old Minecraft. Relays chats to a server for useage there.

___
## [ftbu-drp-ws](https://github.com/Rushmore75/ftbu-drp-ws)
Coming in with the best name out of all of them is [ftbu-drp-ws](https://github.com/Rushmore75/ftbu-drp-ws). The name is just an acronym for "Feed The Beast Utilities, Discord Rich Presense, Web Server." What it does it recieve messages from [RushmoreTweaks](#RushmoreTweaks) to then send them to Discord. It handles all the formatting and making sure the correct server's messages are getting send to the right place. It also provides a way for the mod to listen for messages coming from Discord, to then relay back into the game.

TL;DR

[RushmoreTweaks](#RushmoreTweaks) sends information here, to be sent to Discord.

___
## [cap_web_api](https://github.com/Rushmore75/cap_web_api)
This is my capstone project at while at getting my associates in software development at college. It is a ticketing system for submitting issues. It allows for users to login, submit tickets, and if they are a staff, see what tickets are assigned to them. If the account is a manager it can assign tickets to people.


