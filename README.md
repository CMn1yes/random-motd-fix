# random-motd with a fix??

ChatGPT said that it might cause a tiny memory leak, so I fixed it. That's all.  
Don't know if it would have caused a memory leak or if I even fixed it or not.  
Also this got updated to 1.21.7, so that's pretty cool (the old mod still works in 1.21.7)
## ORIGINAL PROJECT
This mod randomizes the Message of the Day.

You can change what messages are randomized via the "`message-list`" file in the "`random-motd`" folder in the config folder.  
You can change how often you want the message to be updated via the "`randomize-message-timer`"   
It defaults to changing the MOTD every minute.  

Random MOTD does support basic formatting using the offical/vanilla format.  

If server properties has `pause-when-empty-seconds` greater than 0. When the server pauses it will stop updating the MOTD.  
Set `pause-when-empty-seconds` to 0 if you want the MOTD to always be changed.  

message-list default config:  
  `Welcome Server`  
  `Test`  
  `Change these strings!`  

randomize-message-timer default config:  
  `#Change MOTD timer set below`  
  `hours=0`  
  `minutes=1`  
  `seconds=0`



