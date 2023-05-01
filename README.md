# Twitch-ChatGPT
A ChatGPT powered Twitch bot using Streamer.bot and ChatGPT

This is a compilation of existing code that I have modified to send any canned notification through ChatGPT for my twitch stream. 

Elements include:

 - Discord Notifications
 - Twitch Chat Response
 - Twitch Cheer Events
 - Twitch Follow Events
 - Twitch Follow Events
 - Twitch Gift Subs
 - Twitch New Subscriber
 - Twitch Raid Events
 - Twitch Resup Event
## Why?

I am very thankful to LeBluxTV and Raith for creating the integration between Streamer.bot and ChatGPT. 

ChatGPT has become a key part of my streams and I wanted to further integrate it into all "canned" responses. Initially I started by just duplicating the ChatGPT action over and over. 

This obviously wasn't efficitent. So this project is focused on creating a ChatGPT action that can be referecenced by other actions. This makes scaling easier and keeps the personality consistent. 

I am very open to feedback and am excited to see what you can do as well!


## Installation

Import the following into Streamer.bot

```bash
coming soon
```
After importing, update the following:
- _ChatGPT API Handler
    - Set argument chatGPT3APIkey to your API key
    - Set argument model to gpt-3.5-turbo or gpt-4
    - Update argument behavior to match your chatbots personality
- Discord.Go Live
    - Set argument inputGPT to prompt GPT to announce that you are going Live
    - Set argument discordWebHookUrl to your discord webhook Url
    
## Coming Soon

- Twitch Shout Out Integration


## Acknowledgements

 - [Streamer.bot](https://streamer.bot)
 - [LeBluxTV](https://www.twitch.tv/lebluxtv)
 - [Raith](https://about.raith.one)
 - [StreamUp.tips](https://streamup.tips)

