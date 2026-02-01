## macos-steam-game-idler
0% CPU steam game playtime idler for macos

sleeps for 32 years and uses no processing power with a suspended state

## installation
download the zip

go to steam library, right click your game, manage -> browse local files

make sure to backup your .app to a safe location

right click the .app, click `show package contents`

delete the `Contents` folder **(make sure to backup before doing so)**

extract the zip here

run `chmod +x ~/Library/Application\ Support/Steam/steamapps/common/[GameName]/[GameName].app/Contents/MacOS/launcher` 

(where GameName is your game's name)

**and done!** you should be able to start and stop your new lightweight playtime farmer with ease as if it were a normal steam game

if you want to play your game normally again, just replace the .app with the backup
