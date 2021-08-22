# Activities Bot

Discord Slash Commands bot to launch Voice Channel Activities. Made with [Harmony](https://github.com/harmonyland/harmony) and [Deno Deploy](https://deno.com/deploy). You can invite the bot [here](https://discord.com/api/oauth2/authorize?client_id=819835984388030464&permissions=1&scope=applications.commands%20bot).

Originally made by [Advaith](https://github.com/advaith1) ([Activites Bot](https://github.com/advaith1/Activities)).

## Deployment

This bot is deployed to [Deno Deploy](https://deno.com/deploy). You can also deploy it yourself in few clicks!

- [Click here to Deploy this project.](https://dash.deno.com/new?url=https://raw.githubusercontent.com/DjDeveloperr/ActivitiesBot/main/mod.ts&env=TOKEN,PUBLIC_KEY) and enter your bot's token (Bot -> Copy Token) and public key (General -> Copy Public Key), available on [Discord Developer Portal](https://discord.dev).
- Add the project's domain to Interactions Endpoint URL in Developer Portal.
- Invite the bot from URL `https://discord.com/api/oauth2/authorize?client_id=YOUR_CLIENT_ID_HERE&permissions=1&scope=bot%20applications.commands` and don't forget to replace `YOUR_CLIENT_ID_HERE` with your bot's application ID!

## How it works?

Refer to [this part of code](https://github.com/DjDeveloperr/ActivitiesBot/blob/main/mod.ts#L86).

### But why bot scope?

Application's bot user must be in the guild to create activity invite.

## Legal

- Available under [MIT License](LICENSE).
- Check Bot's Privacy Policy [here](Policy.md).


Copyright 2021 © DjDeveloperr
