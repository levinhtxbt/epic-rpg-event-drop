# Epic Rpg - EventDrop

This is an automation tool that helps you claim items in the event drops of Epic RPG, including Wood, Fish, Lootbox, Coins, and Legend Boss. It works with various channels like Oasis RPG, ERPG Dungeon Nexus on Discord.

## Feature

-   This tool can automatically click or type the keywords for you, mimicking random human actions to avoid detection.
-   It supports the following actions: **Catch, Lure, Cut, Edgy Lootbox, Legend Boss, and Arena**.
-   It can run in the browser without requiring focus on the message box, allowing you to multitask while using it.

## How to use
1. Download [here](https://github.com/levinhtxbt/epic-rpg-event-drop/releases/tag/1.0)
2. Unzip the file
3. Update appsettings.json
    - if you want to login automatically, please fill
    ```json
      "Discord": {
        "Username": "",
        "Password": "",
        ....
      }
    ```
    - If you want to redirect to channel automatically, update these section:
    ```json
        "GuildId": "",
        "ChannelId": "",
    ```
    - The default browser is Chrome, but you can choose from Chrome, Edge, or Firefox as alternatives.
    ```json
    "Selenium": {
        "Driver": "Chrome"
    }
    ```
4. Run `EpicRpg.EventDrop.exe` and Enjoy your event.

## Note :

-   **USE AT YOUR OWN RISK!!**
-   **I AM NOT RESPONSIBLE IF YOU GET BANNED**

## Sponsor

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://paypal.me/levinhtxbt)
