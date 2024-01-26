Macros
------

Macros are simple, in-game tools which allow you to sequence spells together, create custom names and icons, cast different abilities depending on whether the target is friendly or hostile, define targeting conditions, and much, much more. While the amount of options can be complex, making them is easy, so in this section we'll go over how to set them up yourself.

-   To open the in-game Macro interface, type "/macro" or "/m".

-   Choose between the General and Character-specific macro tabs. Then click the "New" button on the macro window.

-   Choose a Name and an Icon so you can easily recognize your macro, then click "Okay."

-   Select your new macro and use the text editor below to tell it what to do. If copying ours below, you can simply copy/paste the text in.

-   Click the "Save" button, and drag your macro icon onto your bars, which will allow it to be used just like any other spell from your spellbook.

-   To close the window, click "Exit", or just press Escape.

For more information on creating macros, including full lists of conditionals, modifiers, and other command customizations you can use, check out our full [Macros guide](https://www.wowhead.com/making-a-macro-commands-modifiers-warcraft-guide).

| Macro Description | Macro Text (Copy Paste into macro window) | Notes |
| Generic Stop Channeling |

#showtooltip [SPELLNAME]\
/stopmacro [channeling:Eye Beam]\
/stopmacro [channeling:Fel Barrage]\
/cast [SPELLNAME]

 | Simply replace *[SPELLNAME]* with the desired spell name. This macro prevents you from canceling the channel of Eye Beam and Fel Barrage. |
| [![](https://wow.zamimg.com/images/wow/icons/tiny/ability_demonhunter_metamorphasisdps.gif) Metamorphosis](https://www.wowhead.com/spell=191427/metamorphosis) at your cursor's location |

#showtooltip\
/stopmacro [channeling:Eye Beam]\
/stopmacro [channeling:Fel Barrage]\
/cast [@cursor] Metamorphosis

 | Jump at the location of your cursor. |
| [![](https://wow.zamimg.com/images/wow/icons/tiny/ability_demonhunter_metamorphasisdps.gif) Metamorphosis](https://www.wowhead.com/spell=191427/metamorphosis) without moving |

#showtooltip\
/stopmacro [channeling:Eye Beam]\
/stopmacro [channeling:Fel Barrage]\
/cast [@player] Metamorphosis

 | Stay stationary when meta jumping. |
| Focus [![](https://wow.zamimg.com/images/wow/icons/tiny/ability_demonhunter_consumemagic.gif) Disrupt](https://www.wowhead.com/spell=183752/disrupt) with Regular Kick Override |

#showtooltip\
/cast [mod:alt,@target][@focus,harm,nodead][] Disrupt

 | You can replace alt with ctrl, or shift for a different modifier key |
| Focus [![](https://wow.zamimg.com/images/wow/icons/tiny/spell_misc_zandalari_council_soulswap.gif) Consume Magic](https://www.wowhead.com/spell=278326/consume-magic) with Regular Purge Override |

#showtooltip\
/cast [mod:alt,@target][@focus,harm,nodead][] Consume Magic

 | You can replace alt with ctrl, or shift for a different modifier key |
| Focus [![](https://wow.zamimg.com/images/wow/icons/tiny/ability_demonhunter_imprison.gif) Imprison](https://www.wowhead.com/spell=217832/imprison) with Regular Cage Override |

#showtooltip\
/cast [mod:alt,@target][@focus,harm,nodead][] Imprison

 | You can replace alt with ctrl, or shift for a different modifier key |
| [![](https://wow.zamimg.com/images/wow/icons/tiny/ability_demonhunter_sigilofinquisition.gif) Sigil of Flame](https://www.wowhead.com/spell=389810/sigil-of-flame) at your cursor's location |

#showtooltip Sigil of Flame\
/cast [@cursor]Sigil of Flame

 | Casts Sigil of Flame at the location of your cursor. |
| [![](https://wow.zamimg.com/images/wow/icons/tiny/ability_demonhunter_sigilofmisery.gif) Sigil of Misery](https://www.wowhead.com/spell=207684/sigil-of-misery) at your cursor's location |

#showtooltip Sigil of Misery\
/cast [@cursor]Sigil of Misery

 | Casts Sigil of Misery at the location of your cursor. |
| [![](https://wow.zamimg.com/images/wow/icons/tiny/ability_bastion_demonhunter.gif) Elysian Decree](https://www.wowhead.com/spell=394985/elysian-decree) at your cursor's location |

#showtooltip Elysian Decree\
/cast [@cursor]Elysian Decree

 | Casts Elysian Decree at the location of your cursor. |

* * * * *

Addons
------

Addons are powerful tools that can be used to both customize your gameplay experience, ranging from graphical overlays, replacement action bars, and unit/raid frames, to performance enhancements such as rotation helping spell reminders, buff/debuff tracking, popup reminders, and boss warnings. Here are some of the highly recommended and commonly used Havoc Demon Hunter addons, which are certainly not required to play, but can go a long way toward increasing the information available to you in combat or simply make for a more pleasant viewing experience.

Unlike Macros, managing Addons is done outside of the game, but our [How to Install and Maintain Addons Guide](https://www.wowhead.com/addons-how-to-install-and-maintain) will take you step-by-step through the process.

Havoc doesn't have any special addons that are helpful. It is recommended that you get WeakAuras as it is the most flexible and useful addon available. Other generic addons that are extremely useful.

AD

### User Interface

-   [ElvUI](https://www.wowhead.com/guide/elvui-addon-setup-customization) - Very popular all-in-one UI overhaul.

-   [Bartender4](https://www.curseforge.com/WoW/addons/bartender4) - Highly customizable action bars which can be moved and organized however you like.

-   [Chatter](https://www.wowace.com/projects/chatter) - Replacement chatbox addon, with custom themes, fonts, and functions.

-   [Deja Character Stats](https://wow.curseforge.com/projects/dejacharacterstats) - Adds more stats to the character panel, with customizable filters.

-   [Elkano's Buff Bars](https://www.wowace.com/projects/elkbuffbars) - Replaces the standard buff/debuff icons with ordered lists, including names and bar graph-style durations.

-   [Mapster](https://www.curseforge.com/wow/addons/mapster) - World map enhancement which adds coordinates, icons, and more.

-   [Move Anything](https://wow.curseforge.com/projects/move-anything) - Allows any part of the default UI to be moved around.

-   [OPie](https://wow.curseforge.com/projects/opie) - A specialized radial menu style actionbar, very useful for condensing less frequently used spells that don't always need to be on your main bars.

-   [OmniCD](https://www.curseforge.com/wow/addons/omnicd) - A specialized addon to track your group members' cooldowns.

-   [Sexy Map](https://www.curseforge.com/wow/addons/sexymap) - Makes your minimap sexy!

-   [Shadowed Unit Frames](https://www.wowace.com/projects/shadowed-unit-frames) - Customizable player, target, and raid unit frames.

-   [ThreatPlates](https://wow.curseforge.com/projects/tidy-plates-threat-plates) - Customize nameplates styles and add various information including buffs, debuffs and casting indicators

-   [World Quest List](https://www.curseforge.com/wow/addons/world-quests-list) - Attaches a sortable list of active world quest lists, filtered by zone, to the edge of your map.

### Combat and informational

-   [BigWigs Bossmods](https://www.wowhead.com/guide/bigwigs-boss-mods-addon-guide-6097) - A lightweight, open source raid encounter addon.

-   [Deadly Boss Mods](https://www.wowhead.com/guide/deadly-boss-mods-addon-guide-5995) - A more robust encounter addon for dungeons, raids, PvP, and more.

-   [Details](https://www.wowhead.com/guide/details-damage-meter-addon-guide-6112) - A highly customizable damage and healing meter

-   [Method Raid Tools](https://www.curseforge.com/wow/addons/method-raid-tools) - Modular addon containing raid coordination tools for raid leaders and officers.

-   [SimulationCraft](https://www.wowhead.com/guide/how-to-use-simulationcraft-and-pawn-4885) - Simplifies simming your character by generating an in-game script to paste into SimCraft or Raidbots

-   [WeakAuras2](https://www.wowhead.com/guide/how-to-create-and-use-weakauras-5929) - A very powerful addon that can display a massive variety of information including procs, casting indicators and raid boss warnings.

Of course, these recommendations are not the only useful addons out there; there are hundreds to choose from, of every type imaginable. If you're looking for something a little different, search through [Curseforge](https://wow.curseforge.com/addons) or [WoWInterface](https://wow.curseforge.com/addons) to find the right Havoc Demon Hunter addons for you.