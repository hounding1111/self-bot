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

# Requirements

To use the tool, you need the following permissions in the target server:

Manage channels

Manage webhooks

For best results, having Administrator permissions is recommended.

# Future plans?

I probably won’t be updating it as it is functioning well as is.
