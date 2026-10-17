<div align="center">

# NotRyzenX

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=22&duration=2600&pause=700&color=4C8DFF&center=true&vCenter=true&width=680&lines=NotRyzenX" alt="Animated header: NotRyzenX">
</p>

A self-hostable multipurpose Discord bot built with Discord.js v14 for moderation, server security, community management, AI, automation, and utility tooling.

[![Discord](https://img.shields.io/discord/1414217749038891102?color=5865F2&label=Support&logo=discord&logoColor=white)](https://discord.gg/aerox)

</div>

---

## Overview

NotRyzenX combines moderation, security, automation, community systems, and utility features in a single Discord bot. It supports both prefix and slash commands through a hybrid command system, with persistent server data stored in PostgreSQL through Sequelize.

Features are configured per server through the bot's setup systems.

## Features

### Security & Anti-Nuke

- Protection against mass channel and role deletions
- Webhook and unauthorized bot-join detection
- Configurable thresholds and punishment actions
- Per-server trusted-user and trusted-bot whitelists

### Moderation

- Ban, kick, mute, and temporary roles
- Slowmode, channel locking, and nickname management
- Bulk message purging with filters
- Voice moderation including mute, deafen, move, pull, and channel controls

### AutoMod

- Invite and URL filtering
- Configurable whitelists
- Anti-spam and mass-mention detection
- Channel and role exclusions

### Logging

- Message edit and deletion snapshots
- Channel, role, and emoji changes
- Member and voice-state events
- Configurable event routing

### AI

- Groq-powered conversational responses
- Gemini Vision image analysis
- SerpAPI-backed web search
- Per-channel AI controls
- Custom bot identity handling

### Tickets & Community

- Multi-category ticket panels
- Claim, transfer, rename, close, delete, and reopen workflows
- Ticket transcripts
- Giveaways and winner rerolls
- Custom welcome and farewell messages
- Profile cards and leaderboards

### Automation

- Join-to-Create voice channels
- Scheduled autoposting
- Automated bump scheduling
- Auto reactions
- Vanity roles
- Reaction and button roles

### Utilities & Fun

- Server, user, role, and invite information
- Data export tools
- AFK, reminders, todo lists, Wikipedia, and calculator utilities
- Animal facts and images
- Meme and roleplay commands
- GitHub and YouTube search

## Setup

### Requirements

- Node.js `>= 18`
- PostgreSQL

### Installation

```bash
git clone https://github.com/PauzeDevs/Pauze-Melon-Moderation.git
cd Pauze-Melon-Moderation
npm install
npm start
```

Configure the bot through the project's configuration system before starting it.

## Configuration

The project uses `src/config.js` for runtime configuration, including the Discord token, client ID, owner ID, prefix, database connection, API keys, status, and support server.

Never commit tokens, API keys, or database credentials.

## Architecture

The existing command, gateway, database, and utility architecture is intentionally preserved. This README documents the project without changing runtime behavior or command structure.

## Credits

**Project:** NotRyzenX  
**Maintained by:** NotRyzenX

## License

See [LICENSE](LICENSE) for the applicable usage terms.
