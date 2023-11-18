# ChronAntiVPN

![CHRONANTIVPN-2023-11-15-](https://github.com/Nemanuel2004/ChronAntiVPN/assets/151379636/c7d05658-6f48-449f-96bb-0551101de503)

USAGE: **SPIGOT AND BUNGEECORD!**

⚠︎ **Tʜᴇ ᴀᴘɪ ᴋᴇʏ ɪs ʀᴇǫᴜɪʀᴇᴅ ғʀᴏᴍ ᴛʜᴇ ᴘʀᴏxʏᴄʜᴇᴄᴋ.ɪᴏ ᴡᴇʙsɪᴛᴇ!** ⚠︎ 

Cʜᴇᴄᴋs ᴠᴘɴs, ᴘʀᴏxɪᴇs, ᴀɴᴅ ʀᴇsᴛʀɪᴄᴛᴇᴅ ᴄᴏᴜɴᴛʀɪᴇs!

**Functions:**
Cᴜsᴛᴏᴍ ᴀᴘɪ!
Asʏɴᴄʜʀᴏɴᴏᴜs ᴏᴘᴇʀᴀᴛɪᴏɴs!
Cᴀᴄʜɪɴɢ!
Vᴘɴ ᴄʜᴇᴄᴋs!

**#Rᴇᴛʀɪᴇᴠᴇ ᴛʜᴇ ᴜsᴇʀ's ᴄᴏᴜɴᴛʀʏ ʙᴀsᴇᴅ ᴏɴ ᴛʜᴇɪʀ ɪᴘ ᴀᴅᴅʀᴇss!**
String iso = IPChecker.getIsoCode(address);

**#Rᴇᴛʀɪᴇᴠᴇ ᴛʜᴇ sᴀᴠᴇᴅ ʙᴏᴏʟᴇᴀɴ ᴠᴀʟᴜᴇ ғᴏʀ ᴛʜᴇ ɪᴘ ᴀᴅᴅʀᴇss, ᴅᴇᴛᴇʀᴍɪɴɪɴɢ ᴡʜᴇᴛʜᴇʀ ᴛʜᴇ ᴄᴏᴜɴᴛʀʏ ɪs ʀᴇsᴛʀɪᴄᴛᴇᴅ!**
if (IPChecker.cacheCOUNTRY(address)) {}

**#Rᴇᴛʀɪᴇᴠᴇ ᴛʜᴇ sᴀᴠᴇᴅ ʙᴏᴏʟᴇᴀɴ ᴠᴀʟᴜᴇ ғᴏʀ ᴛʜᴇ ɪᴘ ᴀᴅᴅʀᴇss, ᴅᴇᴛᴇʀᴍɪɴɪɴɢ ɪғ ʏᴏᴜ ᴀʀᴇ ᴜsɪɴɢ ᴠᴘɴ/ᴘʀᴏxʏ!**
if (IPChecker.cacheVPN(address)) {}

**#Tʜᴇ ᴅᴀᴛᴀ ᴄᴏᴜʟᴅ ɴᴏᴛ ʙᴇ sᴀᴠᴇᴅ ɪɴ ᴛɪᴍᴇ!**
if (IPChecker.checkTimeout(address)) {}

**#Tʜᴇ sᴀᴠᴇᴅ ᴠᴀʟᴜᴇ ʀᴇʟᴀᴛᴇᴅ ᴛᴏ ᴛʜᴇ ᴘʟᴀʏᴇʀ ᴀɴᴅ ᴜᴜɪᴅ ғᴏʀ ᴛʜᴇ ᴄᴏᴜɴᴛʀʏ ʜᴀs ᴄʜᴀɴɢᴇᴅ!**
if (IPChecker.checkCHANGE(iso, name, uuid)) {}

**#Cʜᴇᴄᴋ ғᴏʀ ʀᴇsᴛʀɪᴄᴛᴇᴅ ᴄᴏᴜɴᴛʀɪᴇs!**
if (IPChecker.checkCOUNTRY(address)) {}

**#Cʜᴇᴄᴋ ғᴏʀ ᴠᴘɴ/ᴘʀᴏxʏ ᴜsᴀɢᴇ!**
if (IPChecker.checkVPN(address)) {}

#
#░█████╗░███╗░░██╗████████╗██╗██╗░░░██╗██████╗░███╗░░██╗
#██╔══██╗████╗░██║╚══██╔══╝██║██║░░░██║██╔══██╗████╗░██║
#███████║██╔██╗██║░░░██║░░░██║╚██╗░██╔╝██████╔╝██╔██╗██║
#██╔══██║██║╚████║░░░██║░░░██║░╚████╔╝░██╔═══╝░██║╚████║
#██║░░██║██║░╚███║░░░██║░░░██║░░╚██╔╝░░██║░░░░░██║░╚███║
#╚═╝░░╚═╝╚═╝░░╚══╝░░░╚═╝░░░╚═╝░░░╚═╝░░░╚═╝░░░░░╚═╝░░╚══╝
#

AntiVPN:

  Code: 'none'

  Blocked-on-the-server-vpn: |-
    &r
    &8【&c✽&8】 &eYou have been kicked from the server! &8【&c✽&8】
    &r
    &bBlocked on the server vpn!
    &r
    &7Join our discord if there's an issue!
    &7&o(https://discord.io/chroncode/)
    &r

  The-server-has-banned-the-country: |-
    &r
    &8【&c✽&8】 &eYou have been kicked from the server! &8【&c✽&8】
    &r
    &bThe server has banned the country!
    &r
    &7Join our discord if there's an issue!
    &7&o(https://discord.io/chroncode/)
    &r

  Failed-to-spoof-the-country: |-
    &r
    &8【&c✽&8】 &eYou have been kicked from the server! &8【&c✽&8】
    &r
    &bFailed to spoof the country!
    &r
    &7Join our discord if there's an issue!
    &7&o(https://discord.io/chroncode/)
    &r

  The-verification-took-a-lot-of-time: |-
    &r
    &8【&c✽&8】 &eYou have been kicked from the server! &8【&c✽&8】
    &r
    &bThe verification took a lot of time!
    &bPlease reconnect to the server!
    &r
    &7Join our discord if there's an issue!
    &7&o(https://discord.io/chroncode/)
    &r

  Notification: '&8[&4AntiVPN&8] &7(&c%iso%&7) &9» &e%user%'

  Exception: []

  Whitelist:
  - 'RS'
  - 'HU'
  - 'SK'
  - 'RO'
  - 'UA'

Placeholder:

  Unknown: 'Unknown'
