# Cakey Bot Translations
[![Discord](https://discord.com/api/guilds/408424043482447872/widget.png)](https://discord.gg/Y3VdQAD)

The goal of this repo is to allow anyone to contribute to Cakey Bot's translations easily and quickly. You do not have to ask permission to contribute, just make your chanegs and create a pull request! Please be sure to follow our Formatting and Translation rules below. This helps keep consistency accross all languages. 

If you have any questions, you can also check out our FAQ section below or join our [Discord](https://discord.gg/Y3VdQAD) and ask.

# How Do I Translate?
1) Fork the project
2) Make any translations/edits/updates to your language
3) Create a pull request to have your changes accepted into the main repo
4) Make any reuqested edits to your pull request
5) Wait for the strings to be merged and enjoy!

# Formatting, Rules, Requirements
1) Please do not insert unnecessary punctuation into strings, unless it is required for that language
2) Any string that contains ` symbols, please leave them in the same position and don't remove them. Also do not change them to other symbols like ' or ", these are used to highlight certain text or to prevent "@everyone" pings from being used/abused. Removing or changeing these could break formatting in Cakey Bot
3) If you encounter any placeholders like {0}, {1}, etc, keep them in the string. These are automatically replaced in the bot with text so `Requested by {0}#{1}` when used in the bot will be replaced with like `Requested by MrCake#1337`
4) If you need more context/info about how/where a string is used to provide an accurate translation, you can create a discussion or issue here on Github or you can join our [Discord](https://discord.gg/Y3VdQAD) and a reviewer will provide further info/screenshots.
5) Do not translation the string identifiers, these are often on the left side of the string and act as unique identifiers for the strings.
6) Do not translate commands. Cakey Bot only accepts base commands in english. For example if the translaiton string is `Usage: !userinfo <user>`, you can translate the `Usage:` and `<user>` parts, but you must leave the command (`!userinfo`) in english.

# FAQ
**1) What if I don't see a section for my language?**
   - You can simple create a new section for your language and clone the english file into it.

**2) What do the folders mean?**
   - Bot: This folder contains all translations that are used in the Cakey Bot itself on [Discord](https://discord.gg/Y3VdQAD).
   - Website: This folder contains all translations that are used on Cakey Bot's [web dashboard](https://cakeybot.app/dashboard/public).
     - Note: Website also has subfolders for each language type, where as the Bot folder does not.

**3) What languages are currently added?**
   - English (en)
   - Dutch (nl_NL)
   - German (de_DE)
   - Korean (ko_KR)
   - Greek (el_GR)
   - Swedish (sv_SE)
   - Turkish (tr_TR)
   - Italian (it_IT)
   - Arabic (ar_SA)
   - Romanian (ro_RO)

**4) Do I need permission to contribute?**
   - Nope! Anyone can contribute, just be sure to follow our rules and formatting guidelines above.
