The code for the Flappy Bird game was packaged into an executable file using the pyinstaller program shortly after it's production. 
So to run this app, you'll need to download the files as one singular zip file, then  extract it when it's finsihed downloading and then go into 
the FlappyBird_-master folder and run the exectable file from there.

How the app was made:

- This app was made with python 3.9.7
- After python was installed, pygame was installed with the command "pip install pygame". 
  To make sure pygame is correctly installed make sure to restart your command prompt 
  and don’t already have it imported in your source code. Also, you can try to reinstall python with the path configured
  if any errors persist.
- Then when the game was finished and all the assets, text, sound, and source code was gathered under the same folder
  I installed pyinstaller using the command "pip3 install pyinstaller".
- Then I changed directory to the project folder
- Then I ran the command "pyinstaller FlappyBird.py --onefile --noconsole" to group all the files in one executable file and make sure 
  a console wasn't displayed when the program ran.
- After that I went into the "dist" folder and pasted all the needed assets for the program and copied everything into a new folder called "FlappyBird" along with 
  the original source code.
- Finally, I reopened it again in Vscode, initialized a repository, and published it directly to GitHub in a new remote repo.
