# DiscordJockeybyAakash
STEP ONE: installing dependicies 

if you're not a coder and dont have an IDE, get one. Google  VScode and get it


To actually use this code you'll need the following dependencies:
Node : https://nodejs.org/en/
npm: https://www.npmjs.com/
ffmpeg: This one's really tricky here's a youtube tutorial https://www.youtube.com/watch?v=r1AtmY-RMyQ&ab_channel=TroubleChute

You'll need to aquire other dependencies through npm, run these commands in your terminal whereever you downloaded the source code
npm install discord.js@^12.5.3 ffmpeg fluent-ffmpeg @discordjs/opus ytdl-core --save
npm install yt-search

The ffmpeg stuff doesnt import properly sometimes try these if you run into issues:
npm i ffmpeg-static
npm install -g ffmpeg-binaries

STEP TWO: ask Aakash nicely for the new bot token
paste this into the config.js folder 

STEP THREE: open terminal where all the code is and run
node index.js
