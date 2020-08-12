# BSFETranslation
 A translation of the four episodes of Broadcast Satellite Fire Emblem:
 Akaneia Saga into English.

Patching Instructions:
1: Aquire roms of each individual episode of the game. I cannot direct you
to where these can be found.
2: Apply patches to the appropriate rom. "BSFE1.ips" is applied to the
Episode 1 rom, and so on. Ensure Lunar IPS is downloaded.
3: ZSNES ONLY: Apply the appropriate patch in the "fepatches" folder.
Otherwise, the emulator will only produce a black screen on load. I suggest
soft-patching the rom with these. To do so, name your patch the same as the
rom. Eg: "BSFE1Eng.sfc", "BSFE1Eng.ips". SKIP THIS STEP IF NOT USING ZSNES!
4: Load the rom using your emulator of choice. It is recommended to load the
episodes through the BS-X BIOS. I cannot provide this. Once inside the BIOS,
proceed through initial setup if necessary and then enter your house.
Select the top option (Load Stored Data) and select the only option. It should
be labelled "BSFireEmblem EpX", with X being the appropriate episode number.
5: Adjust the clock if necessary. BSNES+ defaults to using system time. To
change this, go to Settings -> Configuration -> BS-X and set the time as
appropriate. Each episode is intended to start roughly ten minutes past the
hour.

Known Issues:
* Some letters highlight incorrectly in the storage menu.
* Eight letter names bleed into the border of certain menus.
* The menu that appears when you select nobody doesn't fully clear when exited.

Please note that these patches translate everything present inside the roms.
It does not in any way restore missing elements of presentation, such as the
illustrations or voice acting. The game is silent and it is recommended to
listen to videos of audio from recordings of the original broadcast.
I fully encourage using this as a base for any restoration attempts. However,
please ask me for permission before using my work here.

Credits:
* All hacking work by Darrman.
* Font taken from VincentASM/RPGuy FE3 translation
* Some unused script blocks taken from bookofholsety's TCRF contributions
and edited to fit better in game

History:
The year is 1997. Two years have passed since the release of Nintendo's
Satellaview perephial. Attached to a Super Famicom, the Satellaview allows
users to download data from a satellite in space for various purposes.
In co-operation with St. Giga, a Japanese radio company, Nintendo broadcasted
a large variety of games. One of the major selling points were "Soundlink"
games. These blended video game and radio show: players could play the game
while listening to live voice-acted commentary regarding the game's events.
Generally, these games were prefixed with "BS", standing for Broadcast
Satellite. Many properties received games for the service.

One such game was BS Fire Emblem: "Akaneia Senkihen", Akaneia Saga in English.
By this stage, Fire Emblem had received four games, and the third entry,
Mystery of the Emblem, had sold particularly well. Being the first foray
into a particularly detailed story in the franchise, the developers desired
to expand it. Akaneia Saga was divided into four episodes, each focusing
on different characters from the game. Marth, the protagonist, was absent.
All four episodes took place before the events of Dark Dragon and the Sword
of Light, the first game. A new episode was aired each week, with players
encouraged to obtain a high score. The first episode was broadcast on the
28th of September 1997... [1 https://web.archive.org/web/20160915163501/http://homepage3.nifty.com/imoko/bsfe/whatis.bsfe.html]

These four episodes provided background information on`various happenings
between many characters, but the primary focus falls upon the Camus/Hardin/
Nina love triangle, a primary driving element of the overall Akaneian story.
However, due to the Satellaview's very nature, the game could not be played
at will. Akaneia Saga has only been broadcast in its original form three times:
reruns took place on the 30th of November 1997 and the 4th of April 1999, 
each episode following a week after the previous. After the April 1999 showing,
Akaneia Saga's original form vanished into the mists of time. Nintendo
withdrew all support for Satellaview just before the final broadcast, and
the platform itself shut down the next year. All the games produced for the
system were believed to be lost forever. With no physical copies ever sold,
how could one access a Satellaview game?

Fortunately, the games haven't been completely lost to time. All Satellaview
games are downloaded into a special cartridge before they can be played.
While Soundlink games such as Akaneia Saga are not intended to be played
outside of its scheduled time, some of the game's data still must be downloaded
to the cartridge. From there, the cartridge can be taken to a cartridge copier
and from there, safely backed up onto a computer. However, this was not without
cost. The dumped rom did not contain significant amounts of the broadcast.
The chapter proper is present, but the voice acting and music is absent. The
artwork shown as the game loaded in was missing as well. Parts of the game
were preserved, but by no means was it entirely so.

Fire Emblem is a popular franchise, and BS Fire Emblem was one of the more
fortunate games for the platform. Dedicated fans recorded gameplay footage
along with the voice acting and images and uploaded them to various video
sharing sites. A Youtube user has uploaded mirrors of these here: [2 https://www.youtube.com/channel/UC-Ff9CzJ90hZc3c3ANpJrGw]
An early Japanese romhacker created ZSNES compatability patches to allow
Akaneia Saga to be played once more. The date on these patches places their
release on the 3rd of October 1999. These eventually found their way to
English-speaking Satellaview sites. However, the Fire Emblem community had
their focuses on other entries of the series. Akaneia Saga was just an odd
footnote.

Time flowed onwards. Fire Emblem games started getting official translations.
And for the older games, fans picked up the slack. First Sword of Seals
received a full translation. Then Mystery of the Emblem was translated.
Genealogy of the Holy War had all but the ending translated. Even Fire Emblem
Gaiden had some form of effort, and the Thracia 776 patch had the dialogue
mostly completed. There was momentum, and in 2009, a script translation was
done by KiddoCabbusses, a Satellaview enthusiast and operator of a blog on
the platform. This was possible due to a dedicated Japanese fan transcribing
the dialogue and placing it up on a website. The script is available here:
[3 https://forums.serenesforest.net/index.php?/topic/8989-bs-fire-emblem-information/]
The translation of the voiced dialogue is an important milestone, but there
was still no progress on actually hacking the games. Then, something unusual
happened.

A remake of Mystery of the Emblem was announced. The unusual part of this was
the fact that the Akaneia Saga chapters would be included as bonus content
in New Mystery. This was a very rare case of Satellaview content being
acknowledged outside of its initial production. The DS version of Akaneia
Saga, dubbed "Archanean War Chronicles" in the New Mystery fan translation,
converted the events of each chapter into a more traditional form. The endless
reinforcements were replaced with standard objectives, the real time clock
was completely removed, and the scoring system was completely changed. This
version of Akaneia Saga is by far the easiest to play. No special emulators
are required to emulate strange Satellaview elements. They are just standard
chapters to be played on standard Nintendo DSes. Most people were content with
this form of the game, and did not consider the original worth the effort.

By the time New Mystery's fan translation was completed, Fire Emblem Gaiden
and Dark Dragon and the Sword of Light were fully translated. Revisions of
the other games' translations to conform with Awakening's decisions were also
taking place. Soon, Akaneia Saga received its first attempt at translation.
Done by Serenes Forest user joesteve1914, a partial menu translation of the
first episode was released on the 6th of November 2014. [4 https://forums.serenesforest.net/index.php?/topic/50511-fire-emblem-archanea-chronicles-fall-of-the-palace-translation-patch/]
This initial build translated little more than the basic menus, with
important messages such as reinforcement spawns and almost all the dialogue
being untranslated. The project's original post considered translating the
remaining three episodes before working on a Thracia 776 project, but neither
of these came to be. On the 9th of May 2016 a cleaned up version of the
Episode 1 patch was released, before the translation effort was cancelled on
the 18th of Feburary 2017. The cited reason for the cancellation was Akaneia
Saga's inability to run in any debuggers, inhibiting attempts at a complete
restoration.

However, this wasn't true. joesteve1914 found out a few months later there was
a debugger capable of running Akaneia Saga: bsnes+. However, he begun working
on updating the New Mystery translation to use Fire Emblem Heroes names.
Akaneia Saga no longer had an active translation effort. At around the same
time, bookofholsety, leader of Project Naga, the completed Genealogy of the
Holy War translation, had done some digging into the internals of Akaneia Saga.
He discovered that a massive amount of leftover data from Mystery of the Emblem
remained intact in Akaneia Saga, posting a Fire Emblem Universe thread on the
topic. [5 https://feuniverse.us/t/bsfe-unused-stuff-and-you/2174]
Several more discoveries were made throughout the next few weeks, with the
final results being gathered onto a Cutting Room Floor page. [6 https://tcrf.net/BS_Fire_Emblem:_Akaneia_Senkihen]
Once again, developments on Akaneia Saga fell silent.

On another note, members of the Fire Emblem romhacking community
are fond of attempting to remake other games in the series in different
engines. Before New Mystery was announced, Arch, founder of Fire Emblem
Universe, begun planning a recreation of Akaneia Saga in Blazing Sword. These
plans were soon scrapped on New Mystery's announcement, and the concept was
transferred to Elibe, evolving into Elibian Nights. No other attempts were
made at porting Akaneia Saga until 2019, where Fire Emblem Universe user Sme
begun porting the New Mystery versions of the chapters to Sacred Stones. [7 https://feuniverse.us/t/fe8u-bs-fire-emblem-archanea-saga-1-0/5173]
The project was completed on the 21st of September the same year. In addition,
it was also showcased in that year's Fire Emblem E3, an annual showcase of rom
hacks and fan games based off of Fire Emblem. While this hack was an easily
accessible form of Akaneia Saga, it still was closer in content to the altered
New Mystery form of the chapters, although it did utilise the original's
illustrations.

Outside of the New Mystery remake, Akaneia Saga has been the most neglected
title in the Fire Emblem franchise. Every other game has been represented in
the Fire Emblem Cipher card game, and it is also one of the very few titles
not to have any representation in Fire Emblem Heroes, the mobile game. The
developers of Fire Emblem are inconsistent on whether Akaneia Saga is a
numbered title or not; the fandom as a whole near-unamiously does not count it.
Due to its inaccessibility, very few people have played the game in any form.
The Satellaview as a whole was a strange, obscure platform few have paid notice
towards. By the end of 2019, Thracia 776 finally received a full translation.
Every Fire Emblem game could be played fully in the English language. Every
Fire Emblem game... except Akaneia Saga.

The year is 2020. Darrman, a Fire Emblem Universe user who had previously
created menu translations for several hacks, begun investigating Akaneia Saga.
After figuring out how to calculate the checksum to allow the translations to
run properly in the BS-X BIOS, he begun work on hacking the game from scratch.
He had already translated a Mystery of the Emblem hack, and due to the
similarities between it and Akaneia Saga, much of the work for it could be
reused. This helped to speed up the process of hacking greatly. All four
episodes were completely translated. And so, on the 12th of August, 2020,
BS Fire Emblem: Akaneia Saga received a complete English translation for the
first time. Finally, every game in the series was 100% playable in English.

This is the end of what has been recorded in history. But this is not the end
of the story of Akaneia Saga. The game has been fully translated. But that
is not a restoration. There is still no audio. There are still no images.
There is no voice acting. The game is fully playable, but the Soundlink
elements of St. Giga's original broadcast are still missing. Some day in the
future, a brave fan may undertake the difficult task of restoring Akaneia Saga
to its former glory. Only once the entire game has been completely restored,
with an English dub to go with the original illustrations, will the tale of
Akaneia Saga reach its conclusion.

Story summary:
SPOILERS FOR ALL STORIES AS LABELLED

EPISODE 1: THE FALL OF PALES
In the first episode, Pales, capital of the Holy Kingdom of Akaneia, was
under siege. The forces of the Durhuan Empire under Emperor Mediuth were
poised to overrun the palace and utterly destroy the kingdom. The king of
Akaneia was notoriously incompetent. More concerned with his own pleasure than
properly running his kingdom, he put up little resistance. Knowing his end was
nigh, he wanted his daughter, Nina, to escape. To this end a small group of
Akaneian knights attempted to cover her. Yet, Durhuan soldiers cornered this
small band and despite their valiant resistance, were captured by General
Camus of Grunia. The king of Akaneia was dead. Pales had fallen. Driven to
despair, Nina attempted to stab herself, but Camus prevented her from following
through. Although there was no reversing the loss in battle and the knights
guarding Nina would be taken prisoner, the princess herself would still be
given some dignity under Camus's occupation. Nina still had the hope that
Akaneia would be free some day...

EPISODE 2: RED DRAGON KNIGHT
With Akaneia subjugated, Durhua's next target was the Kingdom of Orleans.
The king of the country was old and frail, but his younger brother, Hardin,
was a much more vigourous man. The conquest of Orleans was delegated to the
kingdom of Macedonia, with Princess Minerva in charge of the occupation army.
Unknown to the leadership of Macedonia were a renegade group of deserters,
causing chaos wherever they went and brutally mistreating the local residents.
As the deserters abducted a villager, Hardin soon arrived in the region.
Upon encountering Minerva, he realised she was not behind the deserter's
actions. He then decided that working together would be in their best interests
for the time being. Minerva wasn't any the wiser to Hardin's true identity;
by right, the two were enemies. The commander of the deserters was coercing
a bishop - Frost - to fight for him: his family would be killed otherwise.
Upon Minerva's approach, he joined her side instead. Soon the rebel leader
was killed and his fort seized; Hardin's job was done and he left the scene.
Minerva was completely oblivious: her own soldiers suspected Hardin's true
identity, but she emphatically denied the possibility. Meanwhile, Hardin
was well aware of who Minerva was, and was excited to battle her in the future.
Orleans and Macedonia were at war, after all...

EPISODE 3: THIEVES OF JUSTICE
Soon after Pales had fallen, the surrounding areas had succumbed to anarchy.
Thieves and slavers were rampant, and the Durhuan authorities had little
interest in surpressing these illicit activities. Ricardo was one of many
such thieves, aiming at one thing: stealing as much treasure from the shell
of Pales as possible. By his side was Rena, who only joined his heist to
give the money to the poor citizens of Pales. After the duo recruited some
additional manpower to help infiltrate the palace, the group begun raiding
the tresure. A pair of disgruntled mercenaries were bought off with the
promise of gold, and a competing group of thieves attempting to run off with
Pales's gold was defeated. The corridors of the palace were long and winding;
soon the alarm was raised. Durhua's reinforcements rushed in, and General
Camus, leader of the occupation army, prepared to apprehend the thieves.
Despite Rena's pleas, Camus was under orders from Durhua to protect Akaneia.
He was not going to defy them, until the woman he defied orders to protect
previously entered the room. Princess Nina encouraged the general to turn a
blind eye so long as the money was given to the poor; this eye was turned.
Ricardo and his company walked free; the money was given to Rena to hand out.
Camus's ultimate loyalty is to Grunia, not Durhua: he was willing to commit
small acts of defiance. But will this continue?

EPISODE 4: THE BEGINNING
Two years have passed since Pales fell. Emperor Mediuth's frustration at
Princess Nina's continuing freedom only grew as time went on. Camus needed
to get Nina out of Akaneia as soon as possible to prevent her from falling
into Mediuth's grasp. Camus's loyal knights wanted to participate in the
battle - Durhua's troops were no match for Grunia's elites. However, Camus
refused to involve the entirety of the Black Knights: that would be taken
as a betrayal of Grunia as a whole, not just himself. Grunia would be
destroyed, and its prince executed. The operation would be carried out with
just Camus and his three lieutenants. Their aim was to defend Nina no matter
what. A long drawn out pursuit followed. But just before they reached the
border with Orleans, the Durhuan army caught up. Once Nina was in Orleans,
Hardin could take Camus's role in protecting her. Word had somehow spread to
Orleans of Nina's flight; Hardin was ready and waiting at the border.
Camus and his subordinates, however, were captured and imprisoned. He wasn't
to be killed: he was instead to be made an example of what happens if one
betrays Durhua. Nina had safely arrived in Orleans and entered Hardin's
protection. A call for help was soon launched. But would anybody answer?
