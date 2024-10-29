
---

# CraftRise-EcoSystem-Plugin


![CraftRise Logo](https://www.speedrun.com/static/game/kdkzwpgd/cover.png?v=85a7caf)
![Spigot Logo](https://static.spigotmc.org/img/spigot-og.png)

**CraftRise Coin Level XP Plugin** is a powerful tool designed for CraftRise servers, allowing for the tracking of player levels and experience points while they engage in gameplay. Below are important details and legal notices regarding the usage of this plugin.

## Usage

To utilize this plugin, you must have Spigot and PlaceholderAPI installed. Follow these steps to get started:

1. Place the JAR file into your `plugins` directory.
2. Start your server to generate the `config.yml` file.
3. Stop the server and edit the `config.yml` file to enter your MySQL connection details.

## Legal Notice

This plugin is intended for personal and entertainment purposes only. Any advantages or unfair gains obtained through its use may lead to penalties and legal actions.

Unauthorized copying, distribution, or sale of this plugin is strictly prohibited.

## Placeholder Usage

1. Ensure PlaceholderAPI is installed.
2. Use the placeholders provided by this plugin to display player-specific information.

### Available Placeholders:
- `%expercoins_xp%`: Displays the player's current XP.
- `%expercoins_coin%`: Displays the player's current coin balance.
- `%expercoins_level%`: Displays the player's current level.
- `%expercoins_join_date%`: Displays the player's join date.
- `%expercoins_top_coin%`: Displays the leaderboard of players with the most coins.
- `%expercoins_top_xp%`: Displays the leaderboard of players with the highest XP.
- `%expercoins_top_level%`: Displays the leaderboard of players at the highest levels.

## Coin API Usage

The following methods are available for managing coins:

- `CoinManager.getPlayerCoins(playerName)`: Retrieves the player's coin balance.
- `CoinManager.setPlayerCoins(playerName, amount)`: Sets the player's coin balance to the specified amount.
- `CoinManager.resetPlayerCoins(playerName)`: Resets the player's coin balance.
- `CoinManager.addPlayerCoins(playerName, amount)`: Adds coins to the player's balance.
- `CoinManager.removePlayerCoins(playerName, amount)`: Deducts coins from the player's balance.
- `CoinManager.sendPlayerCoins(senderName, receiverName, coinsToSend)`: Transfers coins from one player to another.
- `CoinManager.getTopPlayerCoins(limit)`: Retrieves the top players based on their coin balance.

## Level API Usage

The following methods are available for managing player levels:

- `LevelManager.getPlayerLevel(playerName)`: Retrieves the player's current level.
- `LevelManager.setPlayerLevel(playerName, amount)`: Sets the player's level to the specified amount.
- `LevelManager.resetPlayerLevel(playerName)`: Resets the player's level.
- `LevelManager.addPlayerLevel(playerName, amount)`: Increases the player's level.
- `LevelManager.removePlayerLevel(playerName, amount)`: Decreases the player's level.
- `LevelManager.getTopPlayersLevel(limit)`: Retrieves the top players based on their level.

## Experience API Usage

The following methods are available for managing player experience:

- `ExpManager.getPlayerXp(playerName)`: Retrieves the player's current XP.
- `ExpManager.setPlayerXp(playerName, amount)`: Sets the player's XP to the specified amount.
- `ExpManager.resetPlayerXp(playerName)`: Resets the player's XP.
- `ExpManager.addPlayerXp(playerName, amount)`: Increases the player's XP.
- `ExpManager.removePlayerXp(playerName, amount)`: Decreases the player's XP.
- `ExpManager.getTopPlayerXP(limit)`: Retrieves the top players based on their XP.

## Experience System

The experience system is designed to increase levels every 100 XP earned. This can be adjusted as per your requirements.

## Commands

The following commands are available for players and administrators:

- **/coinim**: Displays the player's current coin balance.
- **/topcoin**: Displays the leaderboard of players with the highest coin balances.
- **/expim**: Displays the player's current XP.
- **/c**: Admin commands related to coins.
- **/l**: Admin commands related to levels.
- **/e**: Admin commands related to XP.
- **/p**: Admin commands related to profiles.
- **/fipcoin**: Performs a coin flip.
- **/oduller**: Displays available rewards.
- **/coinyolla**: Sends coins to another player.
- **/toplevel**: Displays the leaderboard of the highest levels.
- **/profil**: Displays the player's profile.

---

**CraftRise Coin Level XP Plugin** is developed by Ozaii and his team. All rights reserved. Legal action will be pursued for unauthorized use or distribution.

---
