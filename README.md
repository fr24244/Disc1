# DigiLab ↔ Discord Integration via Node-RED

This project connects DigiLab with a Discord server using **Node-RED**.

##  What It Does

Whenever an event happens in DigiLab (like a new result, alert, or update), it sends a message automatically to a specific Discord channel.

##  How It Works

- **Node-RED** listens for events from DigiLab.
- It processes the data using custom logic.
- Then, it sends a formatted message to Discord using a Webhook or a Discord bot.

##  Requirements

- Node-RED installed and running
- Access to your DigiLab's API or event stream
- A Discord bot or Webhook URL
- Optional: JSON or HTTP nodes in Node-RED

##  How to Set It Up

1. Clone this repo or import the Node-RED flow.
2. Set up your Discord Webhook or bot token.
3. Connect your DigiLab data source.
4. Customize your flow to suit your needs.
5. Deploy and test!

##  Example Use Case

> “When a new test result is ready in DigiLab, my Discord bot posts:  
> ` New result available for Patient X - Test: CBC - Status: Completed`”

##  Contributing

Feel free to fork and improve the flow! Pull requests are welcome.

##  License

MIT — use it freely.

---

Made with  using Node-RED + Discord
