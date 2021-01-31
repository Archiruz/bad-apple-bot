You need to put a token for a bot in to bad apple discord player program so that it can connect

You should put the video to frames program in a folder as it puts every frame in its own directory

You might have to change some paths in the files

Some modules are needed to run the programs, they are:\
	- Discord\
	- Time\
	- Pillow\
	- OpenCV

pip install -U discord.py\
pip install -U Pillow\
pip install -U opencv-python

Step by step (Assuming you have set up the bot and bot token is ready)
1. Run video to frame program first (put video and program in the separate folder to avoid confusion, in my case I put the folder named "frames")
2. Wait until all frames are extracted
3. Put the bot token in bad apple discord player.py
4. Check the path, make sure it's pointed to folder where you extracted the video frame
5. Run the program

NP: I don't recommend using repl.it or Heroku as the frame extraction process will generate more than 6K images, the sites can't really handle it
host it locally using shell, you have to install python first tho

CURRENT "ISSUE"
The bot will do similar thing as original video but it has problem with braille blank character\
the right edges will not be as smooth as the ones you look at the video cuz blank braille character's width is shorter somehow\
but it works nonetheless\
I've tried some workaround like using whitespace and other blank character but the bot will think it sends empty message

![Screenshot](https://cdn.discordapp.com/attachments/804949820690137138/805407906689187850/unknown.png)
