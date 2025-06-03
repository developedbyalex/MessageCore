# Commands and Permissions

## Commands

### Core Commands
| Command | Permission | Description | Usage |
|---------|------------|-------------|--------|
| `/messagecore` | `messagecore.use` | Base command for the plugin | Show the help message |
| `/messagecore reload` | `messagecore.admin.reload` | Reload all configuration files | Reloads all yml files |

### Message Commands
| Command | Permission | Description | Usage |
|---------|------------|-------------|--------|
| `/messagecore announce <preset>` | `messagecore.admin.announce` | Trigger a specific announcement preset from config | Runs a predefined announcement with effects |
| `/messagecore announce toggle <player>` | `messagecore.user.announce.toggle` | Toggle announcements on/off for yourself | Enables/disables announcements for the executing player or for the user defined |
| `/messagecore announce pause` | `messagecore.admin.announce.pause` | Temporarily pause all announcements server-wide | Pauses the announcement system until resumed |
| `/messagecore announce resume` | `messagecore.admin.announce.pause` | Resume paused announcements server-wide | Resumes the announcement system if paused |
| `/messagecore broadcast <message>` | `messagecore.admin.broadcast` | Send a formatted broadcast message | Broadcasts message with optional effects |
| `/messagecore firework <preset>` | `messagecore.admin.firework` | Launch a predefined firework preset | Launches firework effect at target location |
