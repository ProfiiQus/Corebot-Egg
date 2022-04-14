# Corebot Egg

A [Pterodactyl](https://pterodactyl.io/) Egg for the [Corebot](https://www.mc-market.org/resources/8501/) Premium Discord bot. Runs on NodeJS 12, basically just downloads a pre-compiled Sodium package.  

## Installation

1. Go to the **Nests** section in your Pterodactyl Administration panel.
2. Create a new Nest, with the **Create new** button, call it 'Discord'.
3. Click **Import Egg**, import the egg-corebot.json file from this repository and select **Discord** as the Associated Nest.
4. Restart the Wings service on your Linux system - to acknowledge the newly imported egg. (`service wings restart`).

## Setting up a Corebot service

1. Create a new server and assign the **Discord Nest**, as well as the **Corebot Egg** egg. I recommend to un-check the **Start after installation** checkbox when creating the server.
2. Go to the **File manager** tab in your server's control panel and upload the Corebot Zip that you have downloaded from the [official MC-Market website](https://www.mc-market.org/resources/8501/).
3. Right-click on the newly uploaded zip file and click **Unarchive** to unzip the files.
4. Open the **config.yml** file and configure the `TOKEN` and `KEY` parameters. Key you will get after purchase on the Corebot Discord, the Token you get from the Discord developer portal - follow [this guide from the official documentation](https://docs.corebot.dev/en/Setup/Pre-Installation).
5. Start the bot and enjoy!