All modifications can be done on DatHost after following the [Installation](docs/installation.md). Edit your server and go to 'File Manager'.

### **Set custom ready message**
Use .readymsg [text] ingame to change your ready message to [text]. eg: .readymsg ready to rumble 

### **Associate a teamname with a player**
Use .teamname "[player]"  "[teamname]"  [teamflag] ingame to associate a [player] with a "[teamname]" and [teamflag] <a href="https://countrycode.org/" target="_blank">CountryCodes</a> eg: .teamname "player" "Team 1" CH

### **Custom prefix for chat messages**
Open **csgo/cfg/custom.cfg** and change the prefixes. (You can use the colors that are indicated at the top)

### **Custom spectator banners**
Download the files **csgo/bottom1.png** and **cfg/right2.png**. Create pngs with the same names and dimensions (or just edit the ones you downloaded). They have to be smaller than 16kb. Then upload them to the same directory.

### **Serverside player names**
Open **csgo/namesfile.txt**. Add the playernames usig the format ```"steamID64 (Dec)"	"playername"``` You can find the ```steamID64 (Dec)``` on <a href="https://steamidfinder.com/" target="_blank">steamIDfinder</a>. eg: "13371234567891337"	"playername"

### **Serverside player images**
Follow <a href="https://steamcommunity.com/sharedfiles/filedetails/?l=german&id=765964792" target="_blank">this</a> tutorial on how to generate the avatars. Then copy the ```'steamID64 (Dec)'.rgb``` files to **csgo/avatars**. You can find the ```steamID64 (Dec)``` on <a href="https://steamidfinder.com/" target="_blank">steamIDfinder</a>.