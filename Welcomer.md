# Requirements #
### Privileged Gateway Intents ###
You must enable intents to [Discord Developer](https://discord.com/developers/applications) and in your bdfd bot settings

- [ ] Enable message content intent
- [x] Server members intent
- [ ] Presence intent

### Variables ###
| Variable Name | Variable Value |
| :-: | :-: |
| embeD | Disabled |
| autoRole | Disabled |
| roleID_Var | 0 |
| channelIDVar | 0 |

### Trigger and Codes ###
| Command Trigger | Code |
| :-:| :-: |
| $onInteraction | [Code](https://raw.githubusercontent.com/paratmr/BDFD-Wikis/main/Welcomer%20CODE/%24onInteraction) |
| /settings | [Code](https://raw.githubusercontent.com/paratmr/BDFD-Wikis/main/Welcomer%20CODE/%5Csettings) |
| $onJoined[$getServerVar[channelIDVar]] | [Code](https://raw.githubusercontent.com/paratmr/BDFD-Wikis/main/Welcomer%20CODE/%24onJoined%5B%24getServerVar%5BchannelIDVar%5D%5D) |
