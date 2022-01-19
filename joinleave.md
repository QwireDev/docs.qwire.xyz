# Join and Leave Messages Configuration

Setup welcome and goodbye messages that will be sent when people join or leave the server.



## Join Settings
For setting up Join messages.
| Command | Description |
| -------- | -------- |
| **joinsettings** | Shows all the options for the join settings. |
| **joinsettings settings** | Displays the current join message settings. |
| **joinsettings enable** | Enables join messages. |
| **joinsettings disable** | Disable join messages. |
| **joinsettings channel \<channel>** | Set the channel where join messages will be sent. |
| **joinsettings message \<message>** | Set the join message to be sent.<br> * Insert `[user.mention]` to ping the new member.<br> * Insert `[user.name]` to just say the name of the new member.<br> * Insert `[user]` to say that name and the tag. (e.g. CoolGuy#2021)<br> * Insert `[count]` to give the current member count.<br> * Insert `[server]` to say the name of the server. |
| **joinsettings test** | Sends a preview of the join message in the set channel. |

## Leave Settings
For setting up Leave messages.
| Command | Description |
| -------- | -------- |
| **leavesettings** | Shows all the options for the leave settings. |
| **leavesettings settings** | Displays the current leave message settings. |
| **leavesettings enable** | Enables leave messages. |
| **leavesettings disable** | Disable leave messages. |
| **leavesettings channel \<channel>** | Set the channel where leave messages will be sent. |
| **leavesettings message \<message>** | Set the leave message to be sent.<br> * Insert `[user.name]` to just say the name of the new member.<br> * Insert `[user]` to say that name and the tag. (e.g. CoolGuy#2021)<br> * Insert `[count]` to give the current member count.<br> * Insert `[server]` to say the name of the server. |
| **leavesettings test** | Sends a preview of the leave message in the set channel. |