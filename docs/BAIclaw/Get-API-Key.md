---
sidebar_position: 2
---
# Get API Key

To use BAIclaw, you need an API Key from BANK OF AI. This key authenticates your requests and grants access to the large language model capabilities.

## What You Need

- A BANK OF AI account (free to register)

## Step 1: Log in to BANK OF AI

1. Open your browser and navigate to [BANK OF AI](https://chat.bankofai.io/chat)
2. Sign in with your existing account, or register a new one if you don't have it

## Step 2: Create an API Key

1. Look for the **API** section in the left sidebar
2. Click on it to open the API management page
3. Click the **Create API Key** button
4. Give your key a descriptive name (e.g., "BAIclaw Desktop")
5. Copy the generated key immediately — it will only be shown once

![](./assets/Pasted%20image%2020260317232256.png)

## Step 3: Configure in BAIclaw

1. Open BAIclaw and navigate to the **Models** page
2. Paste your copied API Key into the BANK OF AI API Key field
3. Click **Save** or **Verify** to confirm the connection

:::danger[Security Warning]
**Keep your API Key safe at all times:**
- The API Key is a critical credential for accessing the BANK OF AI model interface. Never share it with third parties.
- If leaked, unauthorized parties may consume your quota, resulting in unexpected charges. The account holder is responsible for any losses incurred.
- If you suspect your API Key has been compromised, delete it immediately in the BANK OF AI console, create a new one, and update the key in BAIclaw.
:::

## Verification

To verify your API Key is working:

1. Go to the **Chat** page in BAIclaw
2. Send a simple test message (e.g., "Hello")
3. If you receive a response, your API Key is configured correctly

:::tip[Connection Issues?]
If you encounter errors when testing:
- Double-check that the API Key was copied completely (no extra spaces)
- Ensure your network connection is stable
- Verify your BANK OF AI account has available quota
:::

## Next Steps

Once your API Key is configured:
- [Set up your first agent](./BAIclaw-Introduction.md#multi-agent-collaboration)
- Explore the [Skills](./BAIclaw-Introduction.md#plug-and-play-skills) available to extend capabilities


