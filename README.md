//"build periodically" and "poll SCM" are mechanisms within Jenkins to periodically trigger builds based on time or source code changes, "webhooks" are a way to trigger Jenkins builds automatically in response to external events from your version control system or other tools.

𝗣𝗼𝗹𝗹𝗶𝗻𝗴 𝗶𝘀 𝗮 𝗴𝗼𝗼𝗱 𝗰𝗵𝗼𝗶𝗰𝗲 𝗶𝗳:
• You need to receive updates from a data source that is not frequently updated.
• You are on a limited budget, as polling is a simpler and less expensive solution than webhooks.
• You want to have more control over when you receive updates.

𝗪𝗲𝗯𝗵𝗼𝗼𝗸𝘀 𝗮𝗿𝗲 𝗮 𝗴𝗼𝗼𝗱 𝗰𝗵𝗼𝗶𝗰𝗲 𝗶𝗳:
• You need to receive updates from a data source that is frequently updated.
• You want to be notified as soon as new data is available.
• You want to decouple your systems and make them more scalable

![screen-shot-2017-06-21-at-43750-pm](https://github.com/1998shehab/docker-compose/assets/170943489/8d0548b9-eeef-4ca8-b5be-1ff373ccde7b)
