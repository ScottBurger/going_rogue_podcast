# Q&A with KorgGent of Cataclysm: Dark Days Ahead

## How did you get interested in video games?
Well this is a bit of a tricky question. I'm a millenial, so it pretty much tracks that I play video games as a matter of course. I don't really want to give my life story, but The types of video games I played in my developmental years were RTS.

## How did you first get involved with contributing to the CDDA codebase?
Well, I had been playing dda for a short while, maybe a month or so. I had been on the discord during that time, and in the past I had very thoroughly modded Factorio. Plus, I had a coding background from school.
I had noticed that when you butchered animals that you hunted, you got a generic "offal" item, and I thought "why don't we add stuff like liver? people eat that irl all the time!" and now here I am.

## What additions to CCDA did you add that you are most proud of? Most Difficult?
Both of these can be answered with a single project: Nested Containers. I've talked about nested containers a great deal when it was added, and it took me around 18 months to get it into the game proper, with an additional lag time of about 6 months to fix bugs and let it settle.

## What are some of your favorite things about dda?
Well, two things come to mind off the bat: the community, and the thoroughness of the engine.
I had played dwarf fortress a lot, way before i found dda, and I love dwarf fortress for its complexity, and dda for the same.
The community for dda, especially the people on the discord, is probably the best community I've ever been a part of. They are welcoming, inclusive, and want to see you succeed so they are extremely helpful toward that end.

## What does your typical day-to-day look like when handling the Steam side of DDA?
Well, most of the time it's forum moderation that takes my time. The way I code is often in chunks, but that's honestly very similar to how I code features for dda. The only difference is that it's Steam API specific stuff, so it's a lot of unfamiliar documentation.

## Do you rely on different tools now?
Nope. I don't consider the Steam API to be a "different tool" either. Once I finish that feature (i promise i'm working on it!) I will attempt to not touch the steam api again if i can help it.

## Some other F2P rogues that have commercial front ends on Steam are Tales of Maj’Eyal, Shattered Pixel Dungeon, and notably the recent Steam release of Dwarf Fortress. How is the CDDA release on Steam similar or different to those?
Well... DF, Tales of Maj'Eyal, and actually Mindustry are games I looked to for guidance about certain practices that I decided on when designing the store page and deciding the price of the game. Technically the license allowed me to do pretty much whatever I wanted, but I feel that it's important to consider the community's response to doing something like releasing a paid version of a free game, as I already knew that some people were going to be against it on principle. So, I listened to player feedback, especially reviews, but with a grain of salt. I knew that there were people who were going to be against me receiving all of the funding, and I knew there would be some people who did not understand the philosophy of the license despite explaining it to them.
This release was different from DF in that I did not plan to do any steam-exclusive features, like the tileset that peopel keep asking me for. And really, that would probably cost tens of thousands of dollars. I do not count the (still wip!) steam workshop feature to really be in the same vein as a steam exclusive feature; it's going to be more like a mod repository.

## In interviews with other CDDA devs, it’s clear they nominated you to head up the project of hosting the Steam version. It’s a rare phenomenon to see in the open source development world. What was this process like from your side?
A lot of this is the community that I mentioned before - we have a very tight-knit group of developers who all trust each other and help each other. We regularly recruit more developers from the collaborators (discord role) because they've displayed the ability to be trusted.
The process actually stemmed from the aborted steam sale - someone who wasn't attributed to the project at all decided to sell the game on Steam. They didn't follow the license correctly so they took it down, but most of us didn't really like the idea of someone just picking up the game from outside the community and making money off of it. They wouldn't be able to guarantee updates for major versions, wouldn't be able to guarantee features, and all of that stuff. Erk really was the one that convinced me that I should do it. Though, that conversation was about 2 years ago now, many of the devs at that time as well voiced their affirmations of the idea of "someone" from the developer group picking it up and selling it.

## Had you always wanted to be the Steam-based representative for the project?
No, not really. But since I'm the owner of the discord I didn't think it would be that much of a stretch.

## There are those that say, “I’d gladly support the game if the $20 didn’t just go to one person, but to the broader project as a whole.” How should people expect their Steam purchase to contribute to the development of the project? How do you see the Steam version of CDDA enhancing the free version and vice-versa?
Well... To those people, all of the other developers would say "We would just spend that money on hiring KorGgenT" but you didn't have to hear that from me. Just take a look at all of the projects I've done in the past - If I were able to focus on DDA instead of the crazy hours of my day job, I'd be able to program some cool stuff again. It hasn't really fallen back into place because I also went back to school, but I still feel that I will probably be able to really get some more major projects done with a better personal fiscal health. Really I have to say that the money is still a bit nebulous to that regards, but I'd think the 5 years I put in because I wanted to and not because I'm getting paid should say something?

## Do you foresee any splits in the codebase in the coming years?
No. Not because of steam. Not in any big way, at least, since the workshop code will definitely have to be its own fork. But that's basically like, a couple commits, and likely to be static, rebased on top of stable.

## Are there any other projects or things you'd like to promote or draw attention to?
Go check out Thrive. It's a really cool open source project that aims to make a better and modernized Spore.
