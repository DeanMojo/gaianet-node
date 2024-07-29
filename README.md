
## Installation


https://github.com/dxzenith/gaianet-node/assets/161211651/d4cde105-a6ed-4415-a701-7694e7d4ed4e


- You can either use VPS or can use Codespace, it is totally depend upon you. If you use VPS, your node will be active all the time but if u use Codespace, your node will active until you close the codespace terminal

- Open [Codespace](https://github.com/codespaces) or Termius (If you are using VPS)
- Use this command first to create a Screen session
```bash
sudo apt-get update
sudo apt-get install screen
```
```bash
screen -S Gaianet
```
- Then Paste this command :
```bash
wget https://raw.githubusercontent.com/dxzenith/gaianet-node/main/script.sh && chmod +x script.sh && ./script.sh
```

- Copy your Node ID and Device ID. This is very important.
- Go to https://www.gaianet.ai/node , click on Add Node and add your node and device id.
- Find the link to your AI. For example : https://0x588db55d1e19e1c7ed6189f7e129539c1b1d1fdx.us.gaianet.network/chatbot-ui/index.html
- Chat with that bot and increase your throughputs, It may take 1 hr to 2 hr to update throughputs
- Also try to grab node and profile roles on Galxe

## Notes for Codespace User

- When you will close codespace, your node will also be stopped, so if u want to chat with your bot to increase throughputs, U first need to run the node again, so don't delete the existing codespace terminal, otherwise it will generate a new node ID

- If u want to chat with the bot so u first need to open existing terminal, use `gaianet start` command to start your existing node. Then go to the bot link to chat
