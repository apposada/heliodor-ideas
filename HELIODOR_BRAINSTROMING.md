# Project Heliodor Suggestions and Ideas
List of ideas/suggestions for Project Heliodor (a legacy expansion pass for Pokemon R/S/E, aiming to provide players with the most complete experience of Gen 3).

## Mechanics
 - Rumble support: Rumbles for taking a large percentage of damage, rumbles for the bounces of the pokeball hitting the ground as well as for each shake, rumbles for several legendary cutscenes, rumbles for encountering a shiny, rumbles for each bite during fishing, rumbles for the movements of a Pokémon egg when viewing its status as well as for the cracks when it hatches, maybe even rumbles for certain move animations if they deal a good percentage of damage. (Mr E)
 - H-power revamping: Unlock the h-powers storywise, better explanation at how they are gained, etc. (CB, Soulart)
 - De-activate powers in the facilities (Jaizu, CB)
 - Trash bytes: Dig into trash bytes both in OT name as well as nickname, see if that could possibly be a piece of identifiable information in terms of determining a mon is not from RSFRLGE, and if so, start brainstorming to see if we can perfectly replicate trash byte generation. This will likely be a lot of work
 - SRAM expansion: Flags will be reserved for new trainers in Kanto and Sevii, classes/titles will be unlockable for the Trainer Card, inventory is expanded, there will be Medals like in Gens 5 and 6, a few more berry trees will be added in the form of Berry Pots, storage for Apricorns, Pal Pad, outfits, e-Card collecting, and space will be reserved in case I ever get Pokéwalker and/or GTS functional. There's probably some other stuff I can't think of right now too (CB)
 - Colosseum MB: I'd like to see if anything could be easily edited in this, like UI elements. Possibly override the gift Jirachi and Celebi ones too to work with Heliodor instead of just RS
 - Sleep mode: some GBA games have a button combination that puts the system into a rudimentary sleep mode.  I'd like to replicate this, but I have to make sure it's not going to impact any linking or rumble stuff
 - At some point before the next release, go through GF header field  again and make sure nothing is broken with ColoXD, Box RS, and DPPtHGSS
 - Xboo: This is an old protocol used by OG GBA homebrew devs with a special link cable to PC.  GBI also implements it for the Game Boy Player.  I have some preliminary code for it that I was exploring for another potential Internet connection, or for filesystem access, so PC storage can be extended to an SD or have downloadable maps or something
 - Test party in box space: This probably won't work, but I wanted to see if the party could be moved to the section of save space used for PC storage to free up a bit of space in the normal section

## Legality and compatibility
 - Include the Japanese (and all other languages) name of Pokémon so when mons are traded from other language games, they don't count as nicknamed for evolution purposes.  (e.g. upon evolving, a Japanese Pikachu will still have the Japanese name for Pikachu -in kanji- instead of Raichu)
 - JP text: Currently a different font is used for "Japanese" Latin characters, and I'd like to change it so they use the normal ones, so like a Mew named "Mew" isn't in the fullwidth font
 - RNG history (CB)

## Connectivity
 - Online connectivity through the Mobile GB adapter and/or the Wii: GTS, online battles and trades (Mister E)
 - Link class names: Seeing if the classes used for the Trainer Card can be used in link battle.  We won't currently have space for it, so it'd require special handling of link data for ROM hacks so they can transmit for data than normal

## Maps
 - Add Kanto and Sevii (maps are added, need to be filled)
   - **The progression will most likely be the new/OC island for nl001 with a staggered release of Sevii islands and then Kanto**
 - Expanded maps: i.e. expanded areas in Hoenn. Nothing too crazy, more areas with walkable paths and interconnecting the map; perhaps with one or two static encounters and things like that. IIRC some hacks like Altered Emerald have played with this idea and there's been a bunch of posts on reddit of people toying with the maps. I find it very endearing, expanding the landscape and making more places that are interesting to explore (evZ) 
   - **At the very least, I would like to edit Hoenn maps based off of ORAS and Kanto based off of HGSS.  OC modifiations wouldn't be undesirable, but owuld probably require someone to step up to help from a design perspective as I feel that I'm going to struggle just to the one new island I want to introduce**

## Visual style and aesthetics
 - Gen 3 summary screen or Gen IV style summary screen 
 - Gen 3 bag UI or Gen IV bag UI
 - Toggle FLRG-revamped sprites/sprites from all gens/original sprites (during compilation or in-game?) (evZ)
 - What if we got rid of the "Exit" option in the menu and put the clock in the bottom right corner? I  was thinking a separate window just bumping up to the main one, if it'd even fit. (Jaizu)
 - Use narrow font in interfaces as much as we can to fit necessary info without cluttering/cramping up everything?
 - Sprite shadows in the overworld (from EC) (Jaizu, Fender)
 - Abandoned Ship tiles (from Alistair) (MoriyaLuna)
 - More precise edits to some palettes with the day/night system. e.g. the clouds in Route 119 acquire a pink/orangey/purple-ish tone in the afternoon/evening rather than dulling their blue hues.
   - **I've kept this mockup in the `bug_reports` channel as I'd really like to do this at some point.  I've become more familiar with the palette systems recently, so I think this is doable**
 - Party/PC icons from GenVI
   - **This would be a very nice addition at some point**
 - Day/night colouring for outdoor battle backgrounds
 - More backgrounds: shoal cave's ice, mt chimney, mt.pyre, meteor falls, volcano ash route. In order to keep gen3 style, they could be recolors of current ones (evZ)

## Game Main Menu
 - Mirror either Groudon or Kyogre in the intro so they face opposite directions (currently the two face left. I think it would look better if groudon faces right and kyogre faces left, or vice versa. I think facing opposite directions makes more visual sense as they are enemy counterparts plus it is not visually imbalanced?).
   - **Having a Heliodor-specific intro would be nice, but would probably be a lot of work**
 - Original/Groudon/Kyogre screens toggleable by the user or during compilation options.
   - **If there is an artist willing at some point, I'd love new custom title screens too, ideally all Gen 1-3 Legendaries/Mythicals**
 - Rework how the main menu (continue, new game, option, ...) works as it's a bit of a pain to edit and we'll probably eventually need more stuff added for features like Mobile Adapter, Pokéwalker, etc.
 - Add sprites for the player and party on the Continue window

## User customisation
 - Music on/off (keep SFX): good for playing with background music (Mr E)
 - Wild battle music on/off: if off, the area's background music keeps playing in the background while in battle. (Mr E)
 - Light/Dark mode UI (text boxes turn black-ish and text turn light grayish) changing with toggle on/off or with the time of day (evZ)

## New or reworked items
 - Re-do the held items tables to incorporate changes from future games (such as new items or the fossils, see below)
 - Experience Candies
 - Nature Mints
 - Bottle caps
 - Replenishable, non-key item fossils
 - Gen2 pokeballs. They would behave as intended and turn into normal pokeballs upon transferring (CB)
 - The Ruby and Sapphire (key items) also determine which origin game FRLG mons get flagged as, but with next-level, that feature will be removed and the items will either be given a new story purpose or won't be obtainable. (CB)
 - Drop items: When KOing a wild Pokémon that's holding an item, it'd be cool to allow the player to pick up the item

## PokeDex
 - Have a pokedex with more useful information and/utilities: base stats, breeding groups, evolutionary methods, learnsets etc. A lot of this information is present in the game but not directly accessible to players. I guess by now  many of us will know most of this from heart just out of having played the games for so long but i don't know, I think it aligns with the feeling of an overall ultimate experience. To me it makes sense and I do not think it would feel like an info-dump or out of place (after all emerald is very focused on battling and competitive having the battle frontier). Maybe it would be available in the postgame or after certain requirements are met? Maybe the most cumbersome would be the move learnsets, but these could be ommitted (or maybe not all the moves a mon can learn, just the ones by level) (evZ)
 - Dex data:Add description text from different games, maybe additional info like what Switch-era games they can be transferred to (CB)

## Pokemon party and summary screen
 - Move an item from one mon to another directly without having to go through the bag
 - Adding a Condition page to the Summary Screen
 - Additional screen pages: one for the battle palace that informs you what moves your mon will want to use, in what priority etc. Another one for ribbons, another one for contest moves (already exists), another one with techincal info one might be interested? like the PID/SID/HidPow type, another one for contest conditions, another one for pokeathlon data as well?. If these are way too many, maybe they can be chosen for displaying by the user? (i.e. a menu where you can choose to have 1 or 2 additional screens besides the customary pages 1,2,3).

## Mon catching mechanics
 - More encounter types: shaking grass, dust clouds, looming shadows, rippling water like BW? (evZ)
 - Safari-like pokeblock lures (throughout the routes, not only safari zone).
   - **The Pokéblock feeders in the wild are an interesting idea.  Maybe they could be purchasable and placeble by the player?**
 - DexNav-like gimmicks?
 - Shiny hunting mechanics, CC SRAM chaining? something like that? (Mr E, DotMatrixGirl, evZ)
   - **Poké Radar will be introduced in some fashion**
 - FRLG fishing system: exclamation mark (Soulart, evZ, Jaizu)
 - Another rod that allows to catch better pokemon but has a minigame where the longer the pressing minigame lasts/the more complex it is, the more likely it is to find a high IV/shiny/tutor-moves mon. (If the biting minigame thingy escalated with the level and/or IV total sum of the mon that you hooked with the rod) (evZ)
   - **Having only a single Rod that accesses all three encounter tables might be neat**
 - Fishing and other elaborated gimmicks could be tied to a mon’s prowess: the better IVs/rarity/higher level, the more shaking of the rod; the better pokeblocks, the more likely to attract a better mon, …
 - Ball confirm: For the Poké Ball quick use in the battle screen, I'd like to add a confirmation so valuable Poké Balls aren't accidentally used by pressing R.  I'd also like to add an ability to scroll through Poké Balls without having to go to the Bag

## Pokemon Abilities
 - Re-work pickup ability (CB)
 - Add a prompt at the end of battle to stash a stolen item in the Bag (Covet, Thief) like we currently have for Pickup
 - Rework some abilities field effects
   - **I'm definitely open to this as I think the out-of-battle effects of abilities are neat.  Currently, I think I have all of the Gen 3-accessible ability effects implemented from future games**
 - Add field effects to other abilities

## Pkmn Breeding
 - Have a new hatching path (treadmill connecting to itself). (CB, Soulart)
 - Have an option to send to the incubator. (CB, Soulart)
 - Have an more informative way to see how long an egg remains to be hatched. (CB, Soulart)
 - Also, when picking up eggs: withdraw to PC as an option, send to incubator as an option too. (CB, Soulart)
 - Summary option for Daycare mons (evZ)
 - Numerical countdown on eggs is unlocked like the IV/EV viewer (evZ, CB)
 - Being able to release eggs like in gen2 (DMG)

## Battles
 - Ideas on visual/audio modifications for high IV indication
 - Add visual indication of Hidden Power type: i) currently (Jan 2024) shown as Normal type when in battle, not as the actual type it takes for a given user mon; ii) make the animation use the colors of the type HP is acting at? E.g. red for hidden power fire, green for HP grass, etc.
  - Summarise exp gaining: "and the rest of the party also gained Exp."
  - Changing some animations/sound effects of some iconic moves, such as psychic or hyper beam.
  - Transforming the Open Level option of the Battle Frontier in an autolevel-like mode. Like in newer games where mons are lowered/raised to a given level and their stats are re-calculated. It makes the preparation for the battle frontier a bit less tedious I'd say. (Citrus: I've considered it (at least leveling up; leveling down has some potential for illegal ribbons) but haven't really looked into it to see how tricky it'd be to implement)(I add: maybe also illegal for some moves?? i.e. some mon knowing a lv50+ move at level 50? would that be considered unfair? Also Dragonite/Tyranitar at lv 50 would cheese the challenge?)
  - Prevent running away from shiny pokemon (CB; on Oct 22 2022 : "I thought this would be a neat feature to have" )
  - Held items replenish: It might be nice to make some consumable held items be given back after battle (evZ: e.g. berries, herbs?)

## PC
- PC switch: Being able to rearrange the PC menu so the "Move Pokémon" option is the default, although the ability to send a party member to PC to make room for a newly captured Pokémon is something I want to do eventually too
- PC wallpaper: Ya, this would be for new ones like Emerald Cross has
- Make the custom wallpaper gimmick more accesible (the baby girl who cannot laugh in Rustboro)
- Marking: I want to see if we're able to add more Marking stuff for the Storage System like dual colored markings in newer games or the Favorite marking.  I haven't looked at the Marking data, so it may not be doable without allocating more mon data to it.  If that's so, it won't happen as I'd consider it an unacceptable use of a very limited data space

## Battle facilities
- Battle Tower: I want to port the feature of encountering e-Card trainers.  I poked into it with Richter for Revelation and it should be super trivial. Other opponents like story NPCs would be nice too, similar to Sinnoh
- Battle Tower level 50: Ya, just making the requirements less strict

## Secret bases
 - Utility decorations: I'd like to add decorations that have a function to Secret Bases, like a healing machine, Berry Blender, Cable Club entrance, if possible
 - I would aim at making secret bases a bit more permisive with item decoration, to not count the wooden slabs as items to the total amount of items, and perhaps to allow putting dolls on the floor. But maybe this would be constrained externally for other non-ROMhack players to enjoy your secret base too.
   - **We are pretty restrained here due to Record Mixing, but I do want to see exactly how far we can push it to allow more customization**

## Trainer Card and Player info/achievements
 - Classes: Currently, there are a bunch of trainer classes that can be displayed on the Trainer Card, but I still need to add a way to select it, and a system for unlocking them, like once you defeat a Hiker for the first time, you can call yourself a Hiker
 - Record book
 - Having each Gym rematch beaten change the respective gym leader badge's color on the trainer card. On vanilla emerald the badges are gray/silver, so I guess having like: bronze, gold and ?? for the others. (Ihridan) (CB: Something like that might be cool if we have a record book like mentioned earlier and we could have a section to stamp in rematches)

## PokeNav
 - PokéNav will eventually be completely removed (see the rest of this section)
 - Vs. Seeker will be a standalone item,
 Condition and Ribbon screens will be integrated into the Summary Screen,
 - Replace the rest with the Pokégear (with additional features such as the radio and hopefully some custom app cards like showing Wireless Adapter activity or some based on Pokétch apps)
 - Adding a "do not disturb" mode, so trainers can't call about BS all of the time
 - Have NPCs call you with more interesting dialogue (e.g.: tips for other game mechanics such as the different gimmicks from the battle frontier facilities, contests, berry growing, ...) 

## Berries
 - Revisit the berry growing mechanics
 - Potentially add some effects to berries that currently don't have any, such as ones that give EVs like vitamins
 - Re-do berry trees mechanic: add the pots from HGSS (Soulart) (or a map where to plant and grow more berries? (evZ))
 - Add Mulch like in gens IV and VI

## Contests and Pokeblocks:
 - Making the premade Pokéblocks for sale or otherwise coming up with some way to make Condition handling easier for players
 - Rework pokeblocks feel and level; as well as contest stats? (evZ)
   - **Some pre-made Pokéblocks will be available for purchase like in Platinum**

## Minor fixes and upgrades
 - Visual indicator for Feebas (some tile animation or sparkle or something) (evZ)
 - Tradeback guy like in CC (or better explanation of how to trigger trade evolutions) (evZ)

## Additional content
 - Add Elite 4 rematch with upgraded teams (evZ did some teams a while ago)
 - Add ADV OU/UU rosters to Battle Frontier facilities/E4 rematch? (ev)
 - e-Card decks: This is just the card collecting mechanic
 - e-Reader card collecting mechanic to get e-Reader berries and content in-game without the need for extra hardware.
 - Add all e-Reader berries; add all trainers from trainer hill 
 - More facilities: Pokemon World Tournament (SHD), LT surge's gym gimmick but with dolls instead of trashcans (Jaizu, evZ, I know it was somebody else too). A "Randomized Battle" facility (PKZB). An invese type chart facility (RaTT). A "best of 3"
 - Add the 100 trainers challenge.
 - Add overworld sprites from all pokemon (HGSS, PMD?)
   - **This unfortunately probably won't happen unless someone does a full set of Gen 3 styled OW sprites.  Maybe we could do something like Amity Square though if a small collection of sprites are put together?**
 - A new move tutor that will teach mons moves it would be able to learn after transferring up to Gens 4/5
 - Move reminder and move tutors ask for less amount of X (heartscales e.g.) if you visit them more than 3 times on a row in 3h or something like that.
   - **Following BDSP's lead of making the Reminder free after 10 purchases or so may be nice**
 - Move tutors to teach the moves the gen1-3 mons would learn in gen1/gen2/gen4+
 - Hyper Training
 - Outbreaks in Kanto
 - Gym leader rematches revisited
 - Allow Pokémon to have different forms, including Deoxys, but also some cosmetic forms like Spiky Eared Pichu. Forms with other types and stats may be an option, but likely won't be included since if we also change movesets, there'd be some legality concerns. Related to the Deoxys mechanic and form system yet to publish (CB)
 - Wonder News: I don't believe any Wonder News events that were ever ran were archived, so it may not make sense to keep this functionality (and the reserved save space).  It should either be removed or a new use case needs to be put together

## Other 
 - Spread out TMs around kanto and sevii
 - Rework lottery prizes (one only needs one EXP share in this game for example)
 - Make a documentation listing changes, features, additions, etc.
 - Make a gameplay documentation listing items, encounters etc. (Ideally making parsing scripts that parse through the repo and collect info from the actual code).
 - Providing ways to get all the gen 3 distribution mons ( https://www.youtube.com/watch?v=NKBb-YS34wg )
 - State more of these changes in-game (through NPCs, interfaces, etc.)
 - The shiny collecting bot from https://github.com/40Cakes/pokebot-gen3 : swap the symbol files for Heliodor symbols, ROM verit, etc.
   - **I'm not terribly interested in doing this myself, but if anyone attempts to, I'm willing to offer assistance if there are roadblocks**

## Distant things for far off in the future:
- Split versions: I want to explore the possibility of splitting Heliodor into two (or three) versions to have version exclusives and potentially a story closer to Ruby and a story closer to Sapphire.  It'd be a bunch of work and I doubt many people would be interested in it, but it's something I don't want to 100% discount
 - Allow for battle intros and exits to be fast as well the feature, or change, that makes battle animations and damage animations/updates? not take as long as normal battles (very low priority bc Jaizu said they'd rather not have them in a game that is focused in a more immersive experience, I kind of get it too).
 - Could something be worked/figured out to do the reverse save conversion (from Heliodor to Emerald)? (Citrus said: It should be fairly doable, depending on how destructive the primary conversion is (based on what my finalized spec of the new save file ends up being), but I could probably do it as a secret menu function or something)
 - Infrarred support: I'll be hyped if I can get any sort of functionality working in Heliodor, but my goals in order of decreasing perceived feasibility are GSC Mystery Gift, Pokémon Pikachu 2 GS Mystery Gift (probably the same protocol), Pokéwalker, and o3DS NFC reader (CB)
 - More hardware support (CB): Everything not already supported are pretty long-shot goals: utilizing the infrared adapter to communicate with Gen 2 Mystery Gift (GSC and/or VC GSC and/or Pokémon Pikachu 2 GS, Pokéwalker, and o3DS NFC reader/writer; Game Boy Printer support, and Mobile Adapter GB.  Again, these are all long-shots, so it's entirely possible none of these ever come to fruition.
 - Add Johto? if so, what should the content be like?
   - **If we end up at this point, depending on the Kanto and Sevii stories introduced (and assuming Johto will be forced to be after Kanto), we'd likely be at a point in the timeline ~6 months before HGSS.  I don't think there is anything concrete about this time in canon, so we'd probably have a decent amount of freedom**
 - GBA Orre maps (at least colosseums where to obtain the shadow mons already purified). (DotMatrixGirl, hyo)
   - **Orre maps would be very nice, but would probably be lower priority than possible Johto maps (although it's a smaller region, so would require less maps.  It'd probably require more custom tiles, though)**

## Random things I (evZ) have thought (not necessarily for Heliodor but feel free to draw from here)
 - "Blind" switch: You defeat your opponent's mon, they are about to send another one, and then you are asked if you want to switch (without letting you know the opponent's mon). And vice versa (they faint a mon of yours, you send another one, and they do send another one. It could easily transition to "best of 3 1 vs. 1 battles".
 - Different NPCs and stuff happening at night and day. Like in GSC.
 - Visiting Orre's colosseum to battle for the custody of Colo/XD shadow mons, which you get to purify through other mechanics in game (not battling with them etc.). 
 - Trading with RBYGSC? There's been attempts to work some kind of mechanic (it was discussed in the discord a while ago).
   - **This would require a lot of legality work.  I'm not 100% discounting it, but I wouldn't want to start thinking about it for a long time**
 - Include a DS-mode where the game would detect it is running on a Nintendo DS (or NDS emulator), and have some extra functionality only when detected  Like, for example, discounts or some random events being forced out (the lilycove sales, Mirage island, etc.). Or gift mons ready for transferring to GenIV.
   - **I have some rough DS identification code somewhere and eventually, I want to complete this so that GBA, GBP, GBM, NDS, and DSL are all detectable and tallied so players who own different hardware can get something like extra icons for their Trainer Card or something**
 - Some DLC for the wild beasts like they did with the unofficial e-reader cards and scripting?
 - Expand movesets, legality checker for later transferring?
 - Rebalance the mon stats and learnsets etc. (toggle on/off or during compilation). Where to take them from though: Altered Emerald? Kaizo? Hoenn Gaiden?
 - Improve some characters' arc/stories: (I) Wally's quest (nothing mandatory that steers you away from the main plot, but maybe have him appear in Trainer Tower after beating Flannery, to "race you to the top" so you can see him getting better at battles). Also have him participate in the battle tents during the game. // (II) The Rival // (III) Steven . Etc.
