
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
