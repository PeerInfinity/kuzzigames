# Prismatic Adventure - Automation & QoL Fork

This is a fork of the original [KuzziGames by ssiatkowski](https://github.com/ssiatkowski/kuzzigames).

In this fork, I've added some automation tools, game modifications, and quality-of-life improvements to **Prismatic Adventure**. The goal of these changes is to make the game easier, less stressful, and more enjoyable for players who prefer a more automated or experimental playstyle. The other games in the collection are currently unmodified.

## Play Now

To play this version of the game, go to: **https://peerinfinity.github.io/kuzzigames/**

## Changes in This Fork

Here are the changes I’ve made so far in this version. You can access most of these new features via the new **"Game Mods"** button in the main Settings menu.

### 1. Game Mods (Settings Menu)

A new "Game Mods" button has been added to the settings panel, which opens a menu to change some details of how the game works.

*   **Permanently Unlock Automation**: Instantly unlocks all automation-related perks and Serenity upgrades (`Self-Operating Gadget`, `Simulation Engine`, `Smarter Automation`, `Cognitive Cache`, etc.) so you can use the full automation suite from the very beginning.
*   **Enable Advanced Automation**: Unlocks a new, collapsible "Automation Settings" panel below the "Automate" buttons in the main UI. This must be enabled to use the advanced automation features described in the next section.
*   **Award Serenity on Discovery**: Changes how Serenity is gained. Instead of waiting to click the "Prestige" button, Serenity points are awarded *immediately* upon completing a Prestige task.
*   **Use Constant Serenity Scaling Factor**: Modifies the Serenity gain formula. Instead of dividing by your total number of resets (which makes Serenity harder to get over time), this uses a fixed number as the divisor, making gains more consistent.
    *   **Serenity Scaling Factor**: Lets you set the custom divisor used by the above setting.
*   **Disable Pause on Game Over**: Prevents the "Game Over" screen from appearing. The game will automatically restart after a short delay, which is useful for continuous automation.
*   **Disable Serenity Unlocked Modal**: Skips the pop-up modal that appears when you first unlock the ability to Prestige.
*   **Disable 10 Completion Requirement**: Allows the "Automate" buttons to appear for a zone without needing to complete it 10 times first.

### 2. Advanced Automation

When "Enable Advanced Automation" is checked, a new collapsible panel appears below the "Automate" buttons. It contains the following options:

*   **Lock Automation Order**: Prevents you from accidentally changing the automation order by right-clicking or long-pressing tasks.
*   **Resume on Reset**: If you run out of energy/copium/delusion while "All" automation is active, the game will automatically re-enable "All" automation after the reset.
*   **Auto-apply Armor**: Intelligently uses a Cybernetic Armor before starting a task if the estimated energy cost is high, saving you from running out of energy.
*   **Auto-use Options for Resets**:
    *   **Disable Auto-use on Copium Reset**: Automatically turns off the "Auto-Use" resource button after a copium reset.
    *   **Enable/Disable Auto-use after Energy Resets**: Automatically toggles the "Auto-Use" resource button on or off after a specified number of energy resets.
*   **Auto-use Options for Resources**:
    *   **Auto-use All Gauntlets on Reset**: Automatically consumes all Infinity Gauntlets after an energy reset.
    *   **Auto-use One Gauntlet when Even**: Automatically consumes one Infinity Gauntlet whenever you acquire one and your total becomes an even number.
    *   **Auto-use All but One Gauntlet on Acquisition**: Automatically consumes all but one Infinity Gauntlet whenever you acquire more.
    *   **Auto-use Stardust on Reset**: After an energy reset, automatically uses a selected resource once (to add it to the "used" pool) and then consumes all Stardust.
    *   **Auto-use Cosmic Shard for Action**: When a specific task is started, automatically consumes all but one Cosmic Shard to maximize the XP bonus for that task.
*   **Stop Automation at Zone #**: Automatically stops "All" automation when you reach a specific zone number.

## Original Game

*   **Original GitHub Repo**: [https://github.com/ssiatkowski/kuzzigames](https://github.com/ssiatkowski/kuzzigames)
*   **Original Playable Version**: [https://www.kuzzigames.com](https://www.kuzzigames.com)
