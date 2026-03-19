# Discord

## Prerequisites

- Discord account
- A server with admin permissions

## Configuration Steps

### 1. Create an Application

Go to [Discord Developer Portal](https://discord.com/developers/home) → Applications → Create New Application

![](assets/Pasted%20image%2020260318015402.png)

### 2. Add Bot and Get Token

Enter the application, click **Add Bot** on the **Bot** page, then copy the Bot Token, paste it into BAIclaw, and fill in the target **Server ID** and **Channel ID**.

![](assets/Pasted%20image%2020260318015134.png)

![](assets/Pasted%20image%2020260318015147.png)

### 3. Enable Gateway Intents

In **Bot → Privileged Gateway Intents**, enable **Message Content Intent** and **Server Members Intent**.

![](assets/Pasted%20image%2020260318015231.png)

### 4. Configure OAuth2 Permissions

In **OAuth2 → URL Generator**, select `bot` + `applications.commands`, and check **Send Messages** and other message permissions.

![](assets/Pasted%20image%2020260318015243.png)

### 5. Invite the Bot

Use the generated URL to invite the bot to your server.

![](assets/Pasted%20image%2020260318015258.png)
