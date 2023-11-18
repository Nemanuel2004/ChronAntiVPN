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
