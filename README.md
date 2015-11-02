# gbans
## How to install gbans on hopmod/Suckerserv Mod
Find and edit global_bans.lua
```
vi script/base/global_bans.lua
```
Find this line
```
--    { url = "https://raw.githubusercontent.com/pisto/ASkidban/master/compiled/ipv4", format = "raw", name = "ASkidban", reason = "proxy" },
```
Add this one after
```
      { url = "https://raw.githubusercontent.com/Lumiahna/gbans/master/gbans", format = "raw", name = "2FY Gbans", reason = "2FY Global Bans" },
```
It should looks like this
```
local GBAN_MIRRORS =
{
--    { url = "https://raw.githubusercontent.com/pisto/ASkidban/master/compiled/ipv4", format = "raw", name = "ASkidban", reason = "proxy" },
      { url = "https://raw.githubusercontent.com/Lumiahna/gbans/master/gbans", format = "raw", name = "2FY Gbans", reason = "2FY Global Bans" },
}
```
Save and restart the server.
 
### How Can I add ips ?
 * Contact Snipy or pull request ips you would like to ban

### Contact
 * Snipy on #2fy @irc.gamesurge.net
 
