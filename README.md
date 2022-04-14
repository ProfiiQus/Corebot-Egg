# Corebot Egg

A [Pterodactyl](https://pterodactyl.io/) Egg for [Corebot](https://www.mc-market.org/resources/8501/), a premium Discord bot. I re-created this egg, as the official one was not working due to downloading an already unaccessible content.

## Installation

1. Go to the **Nests** section in your Pterodactyl Administration panel.
2. Create a new Nest, with the **Create new** button, call it 'Discord'.
3. Click **Import Egg**, import the [egg-corebot.json](https://github.com/ProfiiQus/Corebot-Egg/blob/main/egg-corebot.json) and select **Discord** as the Associated Nest.
4. Restart the Wings service on your Linux system (`service wings restart`).

## Setting up a Corebot service

1. Create a new server and assign the **Discord Nest**, as well as the **Corebot Egg** egg. I recommend to un-check the **Start after installation** checkbox when creating the server.
2. Go to the **File manager** tab in your server's control panel and upload the Corebot Zip that you have downloaded from the [official MC-Market website](https://www.mc-market.org/resources/8501/).
3. Right-click on the newly uploaded zip file and click **Unarchive** to unzip the files.
4. Open the **config.yml** file and configure the `TOKEN` and `KEY` parameters. Key you will get after purchase on the Corebot Discord, the Token you get from the Discord developer portal - follow [this guide from the official documentation](https://docs.corebot.dev/en/Setup/Pre-Installation).
5. Start the bot and enjoy!