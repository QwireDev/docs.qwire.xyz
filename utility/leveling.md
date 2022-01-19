# Leveling
Commands to configure leveling and to get leveling information. Includes message counting.

| Command | Required Permission | Aliases | Description |
| ------- |------| ------ | ------- |
| **rank [user]** |None| level | Get the leveling stats of yourself or another user. |
| **messages [user]** |None| None | Get how many messages a ceratin user has sent. |
| **clearlevels \<user>** |Administrator| None | Administrator perms required, remove level information of a user. |
| **setlevel \<user> \<level>** |Administrator| None | Administrator perms required, change the level of a user. |
| **leveling** |Administrator| None | Shows all the options for leveling and message counting settings. |
| **leveling enable** |Administrator| None | Enables leveling on the server. |
| **leveling disable** |Administrator| None | Disables leveling on the server. |
| **leveling rolesettings** |Administrator| None | Displays all the level role rewards. |
| **leveling roleset \<level> \<role>** |Administrator| None | Set a role to be achievable at a level. |
| **leveling roleremove \<level>** |Administrator| rolerem, rolepop,<br>roledelete, roledel || Remove a role from being achievable. |
| **leveling channel** |Administrator| None | Shows the current leveling channel. If it is none, level up messages will appear in the channel the user levelled up. |
| **leveling channelset \<channel>** |Administrator| chset | Set the leveling channel. |
| **leveling channelunset** |Administrator| chunset | Remove the leveling channel. |
| **leveling messagesenable** |Administrator| None | Enable message counting. |
| **leveling messagesdisable** |Administrator| None | Disable message counting. |
| **leveling blacklistchannel** |Administrator| None | Displays all the blacklisted channels, channels where people will not gain xp in. |
| **leveling blacklistchannel add \<channel>** |Administrator| None | Add a channel to blacklist. |
| **leveling blacklistchannel remove \<channel>** |Administrator| rem, pop, <br>delete, del | Remove a blacklisted channel from blacklist. |
| **leveling blacklistrole** |Administrator| None | Displays all the blacklisted roles, people with these roles will not gain xp. |
| **leveling blacklistrole add \<role>** |Administrator| None | Add a role to blacklist. |
| **leveling blacklistrole remove \<role>** |Administrator| rem, pop, delete, del | Remove a blacklisted role from blacklist. |