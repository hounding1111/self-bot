# What it does
The nuker deletes every channel in the server, sparing 2 channels. It also creates 3 new channels with webhooks that can generate 200-300 pings (depending on your latency) within 10 seconds, which is quite effective.

This works best in servers with fewer channels, as the tool might not delete every channel in larger servers. It is capped at around 40-50 channels.

Note: If you want to "crack" the tool, feel free, but there’s little need to. I’ve already tried optimizing it, and it’s nearly impossible to bypass the rate limits Discord applies.

# How to use it

There are 3 inputs when you run the tool:

Token - Your Discord account token.

Guild ID - The server ID of your target server.

Message - The message you want the webhooks to spam.

I advise closing the tool after around 300-500 pings to avoid hitting account rate limits.

# showcase

![Alt text](https://cdn.discordapp.com/attachments/1340764591554039893/1355258299125338416/unknown_2025.03.28-19.07_1_clip_1.mp4?ex=67e84625&is=67e6f4a5&hm=139271b5e5caf4638fd041621767b137d9c6b4714ab857c119e3ffe63656eb69&)

# Requirements

To use the tool, you need the following permissions in the target server:

Manage channels

Manage webhooks

For best results, having Administrator permissions is recommended.

# Future plans?

I probably won’t be updating it as it is functioning well as is.

# Is this a rat / logger?

Im not to familiar with this and im unsure why it gets a 7/10.

No it isnt a rat / logger you can upload the file to triage yourself right now its only a 7/10 on triage because of aiohttp connections ( this is what i think anyway ).

Triage - 
![Alt text](https://cdn.discordapp.com/attachments/1355238883050393737/1355251987209261186/image.png?ex=67e84045&is=67e6eec5&hm=bb9d25515ce0eaed7c46b5e392366e2625f3385ced1a7a4965420c4ff51af415&)

Viruts Total -
![Alt text](https://cdn.discordapp.com/attachments/1355238883050393737/1355253669599117444/image.png?ex=67e841d6&is=67e6f056&hm=188f4198beb6f2a7367dfddeea06186782780a28761addea5283006875cfc199&)
