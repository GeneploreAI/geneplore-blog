---
date: 2024-09-22
categories:
  - Getting Started
authors:
    - geneplore
---

# How to use our Discord bot

## Main Commands

### `/chat`
`/chat` is the most common command you will use when interacting with our bot. It creates a new conversation in a thread, where you can talk to the bot just like you would when chatting with a friend. You can use this command to ask questions, get help, or just chat with the bot. This command makes it easy to keep your conversations organized and focused. This command automatically opens `/settings` at the top of the chat.

??? tip "Access Previous Conversations"
    Discord automatically archives threads after a few days of inactivity. To return to previous conversations, use `/home` or click the thread icon at the top right of your channel: ![Thread Icon](/img/thread.png)

### `/settings`
Use `/settings` to customize your chat experience. You can change the chat model, personality, plugins, system prompt, and more. This command is a great way to personalize your chat experience and make it your own.

![/settings diagram](/img/settings.drawio.png)

### `/home`
Use `/home` when you want to access your previous conversations. This command will show you a list of all the threads you have created, so you can easily find and return to them. Load any previous conversation into a new thread that you can continue chatting in with the Load button.

!!! tip
    Conversations loaded into a new thread with the Load button will share the same settings and knowledge as the original conversation. This makes it easy to continue a conversation in a different channel or server.


![/home diagram](/img/home.drawio.png)

### `/image`
Use `/image` to generate an image from text. Use models like FLUX.1, Stable Diffusion 3, DALL-E 3, and more. 

??? note "Premium Models"
    Models with the ⭐ are premium-only models which require a subscription to use.

![/image diagram](/img/image.drawio.png)

### `/serversettings`
Use `/serversettings` to customize the bot's behavior in your server. You can enable automatic AI Moderation, enable automatic refill of credits, set models and personalities as the default, and more.

!!! warning "Only members with the `Manage Server` permission can use this command."

![/serversettings diagram](/img/serversettings.drawio.png)

## Additional Commands
#### `/activate`
#### `/balance`
#### `/premium`
#### `/video`
#### `/music`
#### `/summarize`