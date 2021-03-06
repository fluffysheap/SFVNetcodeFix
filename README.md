## TL;DR Instructions (That's how you start the fight and finish it quickly!)
Exactly the same as Altimor's original mod.
Extract the zip to "Steam/steamapps/common/Street Fighter V".

NOTE: I suffered a concussion in between preparing the mod for release and 
actually releasing it.  As a result I will probably not be online for the
first day or two afterward.  I promise I will come back and answer questions
and/or hate mail by Sunday, Jan. 26.

## Special thanks to testers: (It's so nice to meet!)
* Shadowdevo AKA bowlgirlblergh, who probably worked harder on this than
I did, testing, recruiting testers, and getting the word out.
* Arlieth
* @RemoteStealthy
* NoxidLyrrad
* LilEvil
* devildaddy_cokedout80s
* bearp0p
* cowman715 (Watch his stream at twitch.tv/cowman715)
* The Mika discord for support and getting us together
* Random, unsuspecting people online.  You can take me off your blacklist now kthx.

And of course Altimor, whose mod enabled the development of this one.

## Why should I use this? (This is the path... of my destiny!)
Everyone except Capcom understands the one-sided lag problem of SFV.  It 
is possible for the game clients to become slightly desynced, not enough 
to crash the game, just enough to create lag for everyone.  This mod
reduces this problem.  It also will correct for network fluctuations during
the match, lag switches, etc.

Compared to Altimor's mod, this version offers fewer slowdowns, better compatibility
with WiFi and other unstable connections, and of course, crossplay.

## Crossplay compatibility (Harmony.  That is the truth of what you must seek.)
Altimor's mod, while well-intentioned, wasn't compatible with PS4 or unmodded PC.
This incompatibility has caused a lot of problems as many PS4 players turn
crossplay off, leaving both platforms with a smaller matchmaking pool.
Meanwhile, PC players are left with the unappealing choice of using the mod and
lagswitching half their opponents, or not using it, and getting lagswitched
instead.  The situation is very bad.  What's more, given the problems caused,
Capcom might change the game so that the mod doesn't work any more.

This version puts compatibility front and center, while maintaining equal or 
better performance compared to the original.  This should work with modded, 
unmodded, and PS4 versions of the game.  Unmodded and PS4 versions won't get
much benefit from the mod but, critically, won't get worse either.  Hopefully,
this will deter Capcom from doing anything rash, and hopefully they'll adopt
the mod themselves!

The initial release does not work well with Altimor's version of the mod.  If
this proves to be a problem after a few days I have ideas for improving it, but
I don't guarantee it will be possible.

## Faster performance (Come on! Let's turn up the heat!)
Altimor's mod works well when the connection is quality, but it can feel laggy
or "underwater" when on a choppy connection.  This version should run more
smoothly under a wider variety of conditions.  You can only do so much about
that random WiFi player from 5000 miles away.  But it should help.

## Reduced mashing lag (OK.  Let's rumble!)
When your opponent mashes, usually on wakeup or dizzy, it's possible to 
experience some lag.  This mod may reduce this effect.  Your mileage may
vary.

## Reduced stage lag (I'll totally make this look cool!)
The mod should also reduce some of the visual artifacts caused by playing on 
stages other than training stage.  Again, mileage may vary.

## Don't other stages actually cause lag? (Let my beauty intoxicate you.)
Not really, they mostly just look bad when the game is desynced.  This is
a complicated topic.  There is some debate about whether stages actually
even cause frame drops; MDZ_Jimmy has provided some evidence that they
don't, but I have seen them with frame counters on low spec PCs.  I think
his methodology wasn't perfect and frame drops are still real.

However, even if the game drops frames, it generally does so by skipping
frames, rather than slowing down.  As a result, stage-induced frame drops
do not actually contribute to lag.

TL;DR please feel free to use stages other than training stage, especially
if you use the mod, but even if you don't.

## How hard was this to make? (I'll finish this in no time!)
Originally I expected Altimor to make a fixed version, so I didn't even start 
on it for about a week.  It took about a week after that.  However, most of 
that time was testing.  I probably spent only a day or so on the actual code.

Unfortunately, reverse engineering is a specialized skill, and I don't specialize
in it.  It would have been difficult-to-impossible for me to create this mod
without the work done by Altimor to gain access to the necessary internal game
state.

## Who are you and why should I trust you? (I'm not very fond of conflict.)
Just zis guy, you know?

I'm active in the Mika, Kolin, and Menat discords, and I'm a regular in the
nuggybunny and commanderjesse streams on twitch.

I'm the worst Street Fighter player, but I'm not a bad programmer.

The source code is published and if you really don't trust me you can build
it from source yourself.  Simply get a copy of Visual Studio 2019 (it's free
for personal use), open the netcode_fix.sln file, and build a release build.

## What's coming next? (Have you considered your destiny? Do you believe in fate?)
Future versions may make it possible to improve the connection for both sides,
even if only one has the mod.  And compatibility with Altimor's version may
be on the table if not enough people switch to this version.

Of course, nothing can be done for PS4 vs. PS4, unless Capcom adopts these
improvements into the stock game.  Which they should!

## Known Issues (So... where do you want me to break you first?)
About one game in ten, due to some sort of problem with the way the mod gets
data from the underlying code, it can't tell what the ping is and has to turn
itself off.  There is nothing I can do about this.  Altimor wrote that part
of the code and it will be difficult for me to fix it, although there's hope.

## Hey!  My game crashes at startup!  (I... blew it.)
This shouldn't happen, but if it does, go to:
https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads
And download and run vc_redist.x64.exe
Problem will go away.
