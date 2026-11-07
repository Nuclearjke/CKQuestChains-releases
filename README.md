# CK Quest Chains

A **WoW Forever** addon that answers "is this quest worth starting?" at the quest giver.

**Status: 0.2.1 is the first public test version.** Please report problems; a BugSack error text helps most.

## Install

**With WowUp:** Get Addons → *Install from URL* → paste `https://github.com/Nuclearjke/CKQuestChains-releases`.
WowUp will then keep it up to date from this page's releases.

**By hand:** download `CKQuestChains-<version>-forever.zip` from [Releases](../../releases) and extract it into
`World of Warcraft\_forever_\Interface\AddOns\`, so that you get `AddOns\CKQuestChains\CKQuestChains.toc`.
Then `/reload`.

## What it does

**Chain panel.** A small panel beside the quest window shows the chain a quest belongs to.
- **Where:** the quest giver, the hand-in window and the quest log. It works with DialogueUI and with the
  default quest windows.
- **Steps:** "Chain · step 2 of 4" and every step. Steps you've done are grey, yours is gold, and on a hand-in
  the next one is green.
- **Hover a step** to see its quest goal.
- **Final reward:** what the chain ends with, with item tooltips. Hold Shift to compare.
- **Totals:** the XP and gold left in the chain. The quest in front of you shows the game's real numbers.
  Other steps are estimates from classic data, scaled to your real XP, and marked **(?)**.
- **Your faction and class:** the steps and the final reward are ones you can actually get. Optional lead-ins
  and either/or quests are labelled. A branch into another storyline shows as its own chain.
- **Gaps:** quests new to Forever show "No chain data for this quest."

**Dungeon Journal quests** (with ForeverDungeonJournal installed). Item amounts (have / need) and drop rates,
with expected kills, on the Required Items cards of dungeon quests and their prerequisite chains, and in item
tooltips.

## Credits and license

- GPL v3 (see `LICENSE.txt`).
- Quest chains, quest goals and classic rewards: [CMaNGOS classic-db](https://github.com/cmangos/classic-db) (GPL v3).
- Drop rates: Wowhead Forever item pages. Rates marked (?) come from Wowhead Classic.
- Zone names: WoW Forever client tables via wago.tools.
- Works alongside ForeverDungeonJournal by Exehn. None of its data or code is included.
- World of Warcraft names and data © Blizzard Entertainment.
