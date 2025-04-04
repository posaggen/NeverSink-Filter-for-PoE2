# **CHANGELOG - NeverSink's Filter 2**
----------------------------------
PoE2 is currently in an early access. As the game changes and adjusts you can expect large changes in the filter as well. 

Suggestions and feedback is highly welcome! Please take a moment to write in our [DISCORD](https://discord.gg/zFEx92a).

Major thanks to all patreon supports to help us fund the continious development. [Patreon](https://www.patreon.com/Neversink) supporters.

----------------------------------
# **VERSION 0.7.0** - Dawn of the Hunt
----------------------------------

## SHORT OVERVIEW:

All of the Dawn of the Hunt content and also improves upon the existing sections, such as economy tiering, gems etc. 
It also comes with a new style: Zen! Happy hunting!

## NEW CONTENT:
- Added all of the dawn of the hunt basetypes
- Added a kalandra jewellery section
- Added new style: Zen! Minimal, clean and great for customizing.
- Added a new vault key section (reqliquary keys). They all make the SHWING sound for now!
- Added spear and buckler relevant sections and classes
- Renamed all the advanced and expert bases according to GGG's migration table
- Added the new omens to the tierlist. I suspect they're mostly there to clutter up the omen pool, since every ritual now has an omen. They should be all fairly low tier according to poe2db description.

## LARGE REWORKS:
- Reworked the gem section
- Reworked the socketable section (merged it soulcores and runes and added better campaign overrides)

## TIERING:
- Retiered all uniques and added some to the early league tier
- Retiered all the currencies by hand for the new league (until economy data is available and reliable)
- Moved many S tier items into A tier (until economy data is available and reliable)
- Moved catalysts up by one tier
- Moved stellar amulet a tier down in temrs of chancing. Moved sapphire ring a tier down.
- Adjusted the basetype tiering

## COMING SOON:
- Added advanced economy tiering sections and rules for SC/HC. THose will be enabled in a couple of days, once I'm sure it'll work (too risky for release)

----------------------------------
# **VERSION 0.6.0** - Finetuning
----------------------------------

## SHORT OVERVIEW:

This patch introduces multiple new rules and features and also reintroduces economy-based updates and improved tiering

## CHANGES:

- TODO: one more special map type tier (maybe 2 for S tier class things)

- Added 2 more rules for chancing. A high tier chancing rule (sapphire ring) and a super-tier chancing rule (stellar amulet) that produces a shwing sound/highlight on drop. From the eyes of a PoE1 player this is blasphemy.
- Added new rules for T15+ 8moded maps and T14+, T11+ delirium maps
- The T15+ 8moded map, T14+ delirium map and T16+ maps rules now have a new visual
- Reworked visuals for lower delirium/8mod maps
- Added a dedicated rule for logbooks that can't spawn olroth (ilvl77) with a lower visual
- Addded the gem progressino that gives the desirable gem level drops more highlight while progressing through the campaign
- Added a new rule to the maps, that allows still showing RARE maps of low tiers, even if they are disabled otherwise
- The splinter currency sound is now less loud compared to the other rules
- The highest strictness no longer shows single splinters on the minimap or plays any sound for them
- Salvaging bases (quality armors etc), now have less priority than normal/magic crafting bases
- The barya rule that highlighted baryas 75-79, now highlights 60-79
- 'Futureproofed' the artificer salvage rules to define 'large' as 4x1, 4x2 and 3x2 items
- Removed the dropsound from baryas and ultimatum keys that can NOT grant you the third ascendancy and increased their strictness filtering
- Split the special 'run in progress' Djinn barya rule into 
- Adjusted some font sizes during early campaign for magic items
- Strict no longer hides lower (1-6) waystones. Very strict now removes icons/sounds of Tier 1-13 the waystones and uber-strict hides all 1-13 waystones.

## MISC CHANGES:
- Maps now have a dedicated hide rule. Maps are now disabled instead of hidden on higher strictnesses (has no practical ingame effect, but allows for more filterblade editing).

----------------------------------
# **VERSION 0.52.0a** - Overseer's Tablets and adjustments
----------------------------------

## SHORT OVERVIEW:

This patch adresses changes in PoE2 patch 0.1.1 and also adds a bit of finetuning here and there.
Changed "Overseer's Precursor Tablet" to "Overseer Precursor Tablet"

## CHANGES:

- Changed
- Economy adjusted the tiering of some catalsts, currency, fragments etc
- Added the new "Overseer's Precursor Tablet"
- Reworked flasks and crafting sections slightlx to adjust for the new glassblower salvaging change
- Slightly retiered rare/crafting bases
- Slightly adjusted the tiering on some salvaging rules

----------------------------------
# **VERSION 0.52.0** - Overseer's Tablets and adjustments
----------------------------------

## SHORT OVERVIEW:

This patch adresses changes in PoE2 patch 0.1.1 and also adds a bit of finetuning here and there

## CHANGES:

- Economy adjusted the tiering of some catalsts, currency, fragments etc
- Added the new "Overseer's Precursor Tablet"
- Reworked flasks and crafting sections slightlx to adjust for the new glassblower salvaging change
- Slightly retiered rare/crafting bases
- Slightly adjusted the tiering on some salvaging rules

----------------------------------
# **VERSION 0.5.1** - Initial Public Version
----------------------------------

## SHORT OVERVIEW:

- Removed emerald ring from chancing list
- Iron Rune tier is hidden on Uber Plus Strict instead of Uber Strict now
- Added a section to highlight ilvl81+ siphoning and attuned normal wands for crafting, since these are in high demand right now.
- Fixed multiple dozens of bugs and small improvements for FilterBlade

----------------------------------
# **VERSION 0.5.0** - Initial Public Version
----------------------------------

Keep in mind this is just the initial release. The filter will be updated and improved over the days, weeks and hopefully years to come.

## SHORT OVERVIEW:

- The filter comes with a companion website: [FilterBlade.xyz](https://filterblade.xyz). FilterBlade allows modifying, previewing and customizing the filter to your needs and to your specific build. It's also a great way to learn what the filter can do and it's many features/colors.
- 7 levels of strictness ranging from soft to uber-plus-strict (semi-strict is recommended for beginners). These define the number of items hidden. A higher strictness filter shows fewer items. Very Strict or above should not be used while leveling, unless you're twinked out in leveling gear.
- Item colors, map icons and beams are clustered in a way to make item recognition really easy and minimize the cognitive efforts required to make good decisions. Plus due to the reuse of similar patterns it's good for your dopamin-on-drop-maxing.
- added first alternative style: Dark Mode
- the filter is written using a dedicated programming domain language to minimize errors, optimize performance, increase quality and make its management easier. This concept has been proven quite effective in the many years that I've been supporting PoE1.
- added the following economy based tierlists: currencies, runes, soul cores, catalysts, distilled emotions, essences, omen, fragments/tablets and others. Most bases come with 6 tiers (S,A,B,C,D,E) that are economically tiered and easily distinguishable
- uniques have their own tierlist, that is slightly different and has support for boss-drops and uniques with multiple bases. NOTE: in POE(2) you can't distinguish an specific unique on the same base. For instance the filter can't tell if a unique 'silk robe' is a 'cloak of flame' or a 'temporalis'.
- added neutral-basetype-tiering: a comprehensive tiering of every single basetype from the endgame's player perspective. In the future FilterBlade will provide the choice of the neutral and the meta-based basetype tiering. You'll also be able to mix and match those
- added rare and normal/magic crafting progression: the filter now scales the basetypes available depending on the map tier. For instance: in a level 68 zone a 'advanced dualstring bow' is still one of the best bases. However, in a level 80 zone it is quite poor, since new bases get unlocked
- added special highlight and treatment for bases in arealevel 82
- added campaign leveling mode. The shift between leveling and endgame happens at arealevel 65. Campaign and endgame is handled by the same filter.
- every single item type in the game is tiered or otherwise handled. If it's NOT known, the filter will notify you with a special PINK/CYAN color. If you see this color, you most likely should update the filter.

----------------------------------
# **SPECIAL THANKS:**
----------------------------------

- Tobnac/Haggis for their amazing contribution to the project development and support
- GGG for the awesome game with a special shoutout to Bex, Chris, Rory, Zeyra and Jatin for their assistance!
- A massive thank you to all the [PATREONS](https://www.patreon.com/Neversink), [DISCORD](https://discord.gg/zFEx92a) and [TWITCH](https://www.twitch.tv/neversink) community!
- The FilterBlade Team on discord - Abyxcos, Cdr, Mellontoss, Really Evil bunny, TarrasqueSorcerer, Thesenzei, VenomsAssassin
- The community (that includes you!) for using the filter and providing feedback and support!
