# Gensyn-RL swarm Node-Discord role
This is a guide on how to to run the Gensyn RL Swarm easily and get the swarm role on Gensyn DIscord

For this node, we are going to need :

- Gensyn Testnet account
- a Huggingface token
- Funded octaspace account to run the node ( least $3 )

**Step 1: Creating a Gensyn Account**

- Visit: https://dashboard.gensyn.ai
- Sign up with your Gmail

**Step 2: Generate a Hugging Face token**

- Visit: https://huggingface.co/settings/tokens and create an account
- Go to profile → Access Tokens → Create token
- Enable read and write access for repositories
- Create the token and copy it somewhere safe


**Step 3: Buy GPU and deploy a node on OctaSpace**

- Go to: https://marketplace.octa.space
- Create an account and top up with USDT/USD (on ETH or BNB chain) or buy Octa from Mexc and top up your account with it
- Select Gensyn public testnet
- Choose an affordable instance (e.g. RTX 3090 24GB at 0.1–0.5 octa/hr)
- Click Configure, paste your Hugging Face token
- Input your ‘huggingface token’ in the ‘hf token’ section and  set ‘prg game’ as true
- then Deploy and wait until the dashboard shows Service configured

**Step 4:  First time node setup**

- Open your session on OctaSpace
- Click HTTPS Services and connect your Gensyn account
- To confirm it’s running: click the clipboard icon → Container logs. (Logs should show the node starting.)

# Get Swarm Role on discord

#Step 1: Install GSwarm (Node monitor) 

For WIndow Users:
- Download and install Go from https://go.dev/dl/
- After installing, open CMD (as administrator) 
- and run the command on CMD: go install http://github.com/Deep-Commit/gswarm/cmd/gswarm@latest
- then Run this: gswarm 
(you will see a huge Gwarm text and it will ask for your Telegram Bot Token)

Step 2: Create your Telegram bot
- Open Telegram and message @BotFather 
- Type /newbot. Give it a name (e.g., "SwarmBot").
- Choose a username ending in "bot" (e.g. hkswarmbot).
- Copy the bot token (e.g. format: 80000000:AAxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx)

**Step 3: Paste the copied bot token into your CMDl when prompted**

**Step 4: Next, it will ask for your Telegram chat ID**

- Message @get_id_bot or @RawDataBot in Telegram to get your ID (e.g. 6000000000).
- Paste it into your CMD




