# Commands and Permissions

## Commands

### Core Commands
| Command | Permission | Description | Usage |
|---------|------------|-------------|--------|
| `/messagecore` | `messagecore.use` | Base command for the plugin | Shows plugin info and version |
| `/messagecore reload` | `messagecore.admin.reload` | Reload all configuration files | Reloads config.yml, ranks.yml, and fireworks.yml |
| `/messagecore help` | `messagecore.use` | Display help information | Shows all available commands for your permission level |

### Message Commands
| Command | Permission | Description | Usage |
|---------|------------|-------------|--------|
| `/messagecore announce <preset>` | `messagecore.admin.announce` | Trigger a specific announcement preset from config | Runs a predefined announcement with effects |
| `/messagecore broadcast <message>` | `messagecore.admin.broadcast` | Send a formatted broadcast message | Broadcasts message with optional effects |
| `/messagecore firework <preset>` | `messagecore.admin.firework` | Launch a predefined firework preset | Launches firework effect at target location |
| `/messagecore effect <player> <effect>` | `messagecore.admin.effect` | Apply visual/sound effects to a player | Applies specified effect to target player |