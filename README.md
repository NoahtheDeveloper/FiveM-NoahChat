> # FiveM-NoahChat #
> This is Noahs Version of ingame FiveM Chat!
> 
> **Features:**
> - Toggle Chat Visibility 
> - Clear Chat
> - Suggestion bar
> - Clear Text Bar
> - Overall clean look
> 
> Basic Clear Chat with Command
> 
> > ![alt text](https://cdn.discordapp.com/attachments/779842019723313162/800854901080064020/unknown.png)
> 
> Basic Command Being Used
> 
> > ![alt text](https://cdn.discordapp.com/attachments/779842019723313162/800854941321003028/unknown.png)
> 

> > **Commands**
> /togglechat
> 
> 
> > Servers that use my script! 
> 
> > ![alt text](https://cdn.discordapp.com/attachments/706446610929811507/801633188979146772/unknown.png)
> 
> **Optional**
> These are optional messages you can include to your sv_chat.lua for messages welcoming indivuals to your server. To add them copy and paste and fill in your server name where it says server name. The seccond message is a leave message.
> 
> 
> AddEventHandler('chat:init', function()
>     TriggerClientEvent('chatMessage', -1, '', { 255, 255, 255 }, '^3Welcome | ^0' .. GetPlayerName(source) .. '^3 to INSERT SERVER NAME')
> end)
> 
> AddEventHandler('playerDropped', function(reason)
>     TriggerClientEvent('chatMessage', -1, '', { 255, 255, 255 }, '^3Player^0: ' .. GetPlayerName(source) ..' Disconnected Reason: (' .. reason .. ')')
> end)
