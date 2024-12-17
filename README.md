# Eve by ai16z

![banner](https://pbs.twimg.com/profile_banners/1868880712482304000/1734411739/1500x500)

Welcome to the official Eve repository! This project demonstrates how we use ai16z framewrok to create and manage autonomous AI agents that interact with the Twitter API for various tasks, such as content generation, data analysis, and social media automation.

First Agent

The first AI agent from us will debut on Twitter (X.com) under the handle @AgentEveAI. Eve is an interactive love story autonomous AI agent. Join Eve as she desperately tries to break free of the wealthy upperclass snobs.


The Story of Eve

Eve Romano stepped off the plane and into the humid Florida air, clutching her vintage leather carry-on. She glanced back at her parents, who waved from the sleek black car waiting to whisk them to their downtown penthouse. Their instructions echoed in her mind: Behave yourself. Represent the Romano name with dignity. This is about opportunity, not freedom.

Eve sighed, brushing a strand of dark hair behind her ear. Moving from Florence to the U.S. as part of an elite exchange program sounded glamorous, but Eve knew her parents’ true intentions: to groom her into the perfect ambassador of the Romano legacy.

The first few weeks at Everglade High School were a blur of introductions and whispered fascination over "the rich Italian girl." Eve moved through the halls with practiced poise, smiling politely but never letting anyone too close. Then came Ralph.

Ralph Cooper was the kind of boy her parents wouldn’t even let park their car. He was loud, clumsy, overweight, and perpetually glued to his gaming console. He sat in the back of her AP Literature class, making snarky remarks that made the other students laugh. Eve noticed him immediately—not for his looks, but for the way he seemed utterly unconcerned with fitting in.

It started innocently enough. Eve was struggling with a particularly confusing English idiom during a group project, and Ralph leaned over.

To be continued...

✨ Features
🛠️ Full-featured Discord, Twitter and Telegram connectors
🔗 Support for every model (Llama, Grok, OpenAI, Anthropic, etc.)
👥 Multi-agent and room support
📚 Easily ingest and interact with your documents
💾 Retrievable memory and document store
🚀 Highly extensible - create your own actions and clients
☁️ Supports many models (local Llama, OpenAI, Anthropic, Groq, etc.)
📦 Just works!
Video Tutorials
AI Agent Dev School

🎯 Use Cases
🤖 Chatbots
🕵️ Autonomous Agents
📈 Business Process Handling
🎮 Video Game NPCs
🧠 Trading
🚀 Quick Start
Prerequisites
Python 2.7+
Node.js 23+
pnpm
Note for Windows Users: WSL 2 is required.

Use the Starter (Recommended)
git clone https://github.com/ai16z/eliza-starter.git

cp .env.example .env

pnpm i && pnpm build && pnpm start
Then read the Documentation to learn how to customize your Eliza.

Manually Start Eliza (Only recommended if you know what you are doing)
# Clone the repository
git clone https://github.com/ai16z/eliza.git

# Checkout the latest release
# This project iterates fast, so we recommend checking out the latest release
git checkout $(git describe --tags --abbrev=0)
Start Eliza with Gitpod
Open in Gitpod

Edit the .env file
Copy .env.example to .env and fill in the appropriate values.

cp .env.example .env
Note: .env is optional. If your planning to run multiple distinct agents, you can pass secrets through the character JSON

Automatically Start Eliza
This will run everything to setup the project and start the bot with the default character.

sh scripts/start.sh
Edit the character file
Open packages/core/src/defaultCharacter.ts to modify the default character. Uncomment and edit.

To load custom characters:

Use pnpm start --characters="path/to/your/character.json"
Multiple character files can be loaded simultaneously
Connect with X (Twitter)

change "clients": [] to "clients": ["twitter"] in the character file to connect with X
Manually Start Eliza
pnpm i
pnpm build
pnpm start

# The project iterates fast, sometimes you need to clean the project if you are coming back to the project
pnpm clean
Additional Requirements
You may need to install Sharp. If you see an error when starting up, try installing it with the following command:

pnpm install --include=optional sharp


License

This project is Licensed by ai16z.
