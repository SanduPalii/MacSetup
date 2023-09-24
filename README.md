# MacSetup

Orion - https://browser.kagi.com

Velja - https://apps.apple.com/nz/app/velja/i...

Later - https://getlater.app

Dropover - https://apps.apple.com/us/app/dropove...

Raycast - https://www.raycast.com

Shottr - https://shottr.cc/

ImageOptim - https://imageoptim.com/mac

CopyClip - https://apps.apple.com/us/app/copycli...

Hidden Bar - https://apps.apple.com/us/app/hidden-...
Hand Mirror - https://apps.apple.com/us/app/hand-mi...
QuickShade - https://apps.apple.com/us/app/quicksh...

OnyX - https://www.titanium-software.fr/en/o...

One Thing - https://apps.apple.com/us/app/one-thi...


𝗙𝗮𝘀𝘁𝗲𝗿 𝗗𝗼𝗰𝗸 𝗛𝗶𝗱𝗶𝗻𝗴: defaults write com.apple.dock autohide-delay -float 0; defaults write com.apple.dock autohide-time-modifier -int 0;killall Dock
𝗙𝗮𝘀𝘁𝗲𝗿 𝗗𝗼𝗰𝗸 𝗛𝗶𝗱𝗶𝗻𝗴 𝗨𝗻𝗱𝗼: defaults write com.apple.dock autohide-delay -float 0.5; defaults write com.apple.dock autohide-time-modifier -int 0.5 ;killall Dock

𝗔𝗱𝗱 𝗗𝗼𝗰𝗸 𝗦𝗽𝗮𝗰𝗲𝗿 (paste for each spacer): defaults write com.apple.dock persistent-apps -array-add '{tile-data={}; tile-type="spacer-tile";}' && killall Dock
𝗔𝗱𝗱 𝗛𝗮𝗹𝗳-𝗛𝗲𝗶𝗴𝗵𝘁 𝗗𝗼𝗰𝗸 𝗦𝗽𝗮𝗰𝗲𝗿 (paste for each): defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="small-spacer-tile";}' && killall Dock

𝗗𝗶𝘀𝗮𝗯𝗹𝗲 𝗔𝗻𝗻𝗼𝘆𝗶𝗻𝗴 𝗗𝗶𝘀𝗸 𝗪𝗮𝗿𝗻𝗶𝗻𝗴 (must restart Mac to take effect): sudo defaults write /Library/Preferences/SystemConfiguration/com.apple.DiskArbitration.diskarbitrationd.plist DADisableEjectNotification -bool YES && sudo pkill diskarbitrationd
𝗥𝗲-𝗘𝗻𝗮𝗯𝗹𝗲 𝗔𝗻𝗻𝗼𝘆𝗶𝗻𝗴 𝗗𝗶𝘀𝗸 𝗪𝗮𝗿𝗻𝗶𝗻𝗴: sudo defaults delete /Library/Preferences/SystemConfiguration/com.apple.DiskArbitration.diskarbitrationd.plist DADisableEjectNotification && sudo pkill diskarbitrationd

Quiet Reader - https://quietreader.app/ 
HotKey - https://apps.apple.com/us/app/hotkey-... 
Pure Paste - https://apps.apple.com/app/id1611378436 
MenubarX - https://menubarx.app 
Pippo - https://goodsnooze.gumroad.com/l/pippo 
TempBox - https://tempbox.waseem.works 
Notes SE - https://apps.apple.com/us/app/notes-s... 
Hovrly - https://hovrly.com/?ref=producthunt 
Latest - https://max.codes/latest/ 
DiffusionBee - https://diffusionbee.com


𝗖𝗵𝗮𝗻𝗴𝗲 𝗦𝗰𝗿𝗲𝗲𝗻𝘀𝗵𝗼𝘁 𝗗𝗲𝗳𝗮𝘂𝗹𝘁 𝘁𝗼 𝗝𝗣𝗚 (replace with png to undo): defaults write com.apple.screencapture type jpg

𝗠𝗮𝗸𝗲 𝗛𝗶𝗱𝗱𝗲𝗻 𝗔𝗽𝗽𝘀 𝗧𝗿𝗮𝗻𝘀𝗽𝗮𝗿𝗲𝗻𝘁: defaults write com.apple.Dock showhidden -bool TRUE && killall Dock
