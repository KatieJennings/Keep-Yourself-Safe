# Privacy Policy
This is the privacy policy for Keep Yourself Safe. By using the bot, you accept the terms of this policy. You may also opt out of certain aspects of the bot via the `/opt` command in Discord itself.

Last updated on `June 12th, 2026`

## Stored Data
Some data is necessary to be stored in a local database for certain features to work. Some of this data may be viewed by all members via commands, only viewable to moderators of the server, or completely hidden.

1) **Punishment Data**: If any punishments are applied to you (warning, timeout, captcha, kick, ban), this data is logged for moderators of the server to view. This data is stored *as long as required to maintain safety*, unless requested (see bottom of policy).
    - You cannot opt out of this feature.
2) **Memory Data**: When interacting with the bot using Generative AI features, the bot may be asked to remember something you said. This data will be stored *until* you ask to remove it, and the AI model can view it if asked.
    - You can opt out of this feature by opting out of Generative AI features entirely or by never asking the bot to remember something.
3) **Reminders**: When interacting with the bot using Generative AI features, the bot may be asked to set a reminder. This data is stored *until* the reminder is fulfilled.
    - You can opt out of this feature by opting out of Generative AI features entirely or by never asking the bot to set a reminder.
4) **Reputation Points**: Users can use the `+rep` and `-rep` commands on users. When this occurs, the reputation points will be logged and are viewable via the `$rep` command. This data is stored *as long as required to maintain safety*, unless requested (see bottom of policy)
    - You cannot opt out of this feature.
5) **Malware Scans**: When users upload files, the bot will automatically scan them if they are executables, scripts or anything of that nature. This data is stored *as long as required to maintain safety*, unless requested (see bottom of policy)
    - You cannot opt out of this feature.
6) **Messages**: When you send a message in a channel with the bot, it will store your message for a short period of time in memory only. A rolling history of about 10 messages is temporarily stored.
    - You can opt out of this feature by doing `/opt aspect: Generative AI option: Disabled` in any discord server with Keep Yourself Safe, or in DMs.

## Accessed Data
This is data that is accessed but never stored.

1) **Online Status**: Online status will be checked when users use the @there command/mention.
    - You can opt out of this feature by doing `/opt aspect: Online Status option: Disabled` in any discord server with Keep Yourself Safe, or in DMs.
2) **Guild Members**: The bot must access the guild member list when applying/removing punishments and for listing the members in Generative AI features.
    - You cannot opt out of this data being accessed overall, but you can opt out of Generative AI features and that data will not be used there.

## Shared Data
We do not sell or share your data with third parties for advertising. However, when using free-tier AI models (Google, Cerebras, OpenRouter), your prompts may be used for model training.

You may fully opt out of this collection by using the following command:

`/opt aspect: Generative AI option: Disabled`

| Router | Description | Privacy Policy |
| ------ | ----------- | -------------- | 
| `openRouter` | Heavily depends on chosen model | Depends on model, use `$get-model` in the channel and search at https://openrouter.ai |
| `google` | We use the free tier, so data is subject to collection. | https://ai.google.dev/gemini-api/terms |
| `cerebras` | We use the free tier, so data is subject to collection. | https://www.cerebras.ai/policies |

## Request Data Export and Deletion
You may request a data export and/or a partial or full data deletion by DMing me on discord `ktyjennings` or via email at `katie@dreamninjas.eu`. I will respect this choice even if you are not in a country with strong data protections like GDPR.

However, requesting a full data deletion (punishment logs, reputation points) necessitates you are removed from the servers where the bot operates. This bot is not a public bot, it only operates in servers where I am also an admin. Thus, in order to protect the members and not allow scammers to remove negative reputation points or previous punishment logs, you must be removed from the server(s). Consider it the same as removing your account on a website. You may come back on a new account, but not the same account that you requested data deletion on. Removal from the server is implemented via a Discord ban. Discord maintains its own records of server actions and we cannot delete those on your behalf.
