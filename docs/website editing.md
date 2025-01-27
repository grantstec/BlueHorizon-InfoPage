# 🌐 Website Editing How-To

## GitHub

### What is GitHub?

GitHub is where the website source code is hosted. GitHub was developed to make using Git more intuitive. Git (Not GitHub) is an effective version control software that allows a group to work on a project whilst dispersing the workload to multiple members. **To accomplish this we will have each editing user create their own branch separate from the main branch**. The main branch is where the live code sits for the website. Different branches allows individual users to make a copy of this main branch and work on their own aspects of the website/code without effecting others, if one user makes an update to main before another the other user can do a "pull" request to their branch and update it so it is that same as the main branch, if they need to see that other users code to accomplish there task. Otherwise once done with the update you want to make you can commit your changes to your branch and then "push" them. Then the owner can review your update branch and decide to "pull" your code to the main branch if it is good. The "pushing" and "pulling" can all be done in our coding software which we will go over later. 

### Setting up GitHub

Navigate to http://github.com and **sign up using your afacademy email**. This will allow you to get GitHub pro for free which provides some nice AI assisted code benefits. If you want to activate GitHub pro go into your account and sign up for it. Follow all instructions to create your account, once done send **Grant Stec** a teams message and he will invite you to the BlueHorizon github organization. 

Within the BlueHorizon github you should be able to see the different repositories (folders for different projects) the one titled **"BH Website"** is the website repo (repository). You should see something like this.

Create your own branch 



## VSCode

```{image} ./pictures/vs-code.jpg   
:height: 200
:align: center  
``` 

### What is VSCode?

VS Code (VSC) is a coding IDE that allows you to write in multiple coding language with a very well designed UI and good integration with Git. 

You can download from the microsoft app store or online [here](https://code.visualstudio.com/download) Be sure to download the x64 bit Windows System Installer. 

### Setting up VSCode

Accept the default options for all of the VS Code install prompts.  Click the Finish button to complete the install and launch VS Code.  Accept any defaults that are presented during your first launch of VSC.  You should see an image like the one below once complete.

```{image} ./pictures/vsc-welcome.png   
:height: 200
:align: center  
``` 
You will now install extensions to assist the development process. Click the extensions button on the side, it looks like a teri block. Search for **Code Spell Checker and install the one by Street Side Software** as seen in the picture below. 

```{image} ./pictures/VSC_extensions.png  
:height: 200
:align: center  
``` 

If you had signed up for github and gotten github pro it would be useful now to also download the **GitHub Copilot and GitHub Copilot Chat extension along with the GitHub Pull Requests** extension. All of the website files are markdown based so you should also get the Markdown **All in One extension by Yu Zhang** and **Markdown Preview Enhanced by Yiyi Wang** to quickly see the markdown pages in VSC. 

If any extensions ask for setup or gives any setup instructions after installation don't bother just continue. 

Now we will sign into GitHub on VScode so we can easy push pull and commit to our respective branches on GitHub. To Login click the account looking icon in the bottom 

```{image} ./pictures/VSC_Account.png  
:height: 200
:align: center  
```
There should be a connect to GitHub button or something similar. Click and that and you should be re directed to your browser to connect your github account to VSCode. 

Now create a folder to have the Website files on your computer, this can be made anywhere, Onedrive folders etc. Now once that folder is created go back to VSCode if you have a current folder open go to file and new windows or simple click open folder on the main page and navigate to open the folder you just made. 

```{image} ./pictures/Open_Folder.png  
:height: 200
:align: center  
```

Now on the bottom of VSCode if there is not a terminal window similar to the one in the bottom of the picture then you would want to move your mouse to the bottom of the window as seen in the next picture and once your courser turns into the double vertical arrows click and drag up this will open the terminal or you can use the hotkey of Ctrl+` (Not apostrophe, button below esc usually).

```{image} ./pictures/vsc_terminal.png  
:height: 200
:align: center  
```

```{image} ./pictures/Terminal_Open.png  
:height: 200
:align: center  
```

Make sure the command line in the terminal windows looks like the folder location you have created and has the same name at the end of the printed line in terminal. Navigate back to the VSC terminal with your folder in the directory and copy this command `git clone https://github.com/grantstec/BlueHorizon-InfoPage.git` and hit enter. 


Once the git clone has finished you should now see your folder populated with all the same files from github. Now you can begin editing and or adding the files. Familiarize yourself with the file structure snd files like intro.md, _config.yml and _toc.yml to learn more about how this file structure works and some niche formatting as seen in intro.md you can visit [Built with Jupyter Book](https://jupyterbook.org/en/stable/intro.html)

Once you are ready to commit and push a new change there are a few things we must make sure as to not destroy the live functioning website running from GitHub. Navigate to the source control tab on the left hand bar above the extensions and above the debugger as seen in the photo. 

```{image} ./pictures/Source_Control.png  
:height: 200
:align: center  
```

You will want to get very familiar with this tab as this is where our version control will be based from and allows us to keep a functioning website running whilst having multiple people edit seperate files. If you have made any changes you will see the **Commit** button in blue. We will worry about this later. Most importanlty we have to go back to some things we discuessed in the begining of this page and create a new branch for yourself. To do so you should see a little branch icon like the soruce control tab we clicked with the **"main"** branch title as seen in the picture below. Click on this. 

```{image} ./pictures/branch.png  
:height: 200
:align: center  
```

This will open up a window at the top 


Some other helpful things are the Spell Checker, as seen in the terminal window you can find a word and double click and be directed to it and given options for suggested words and select which ever is correct. You can also add niche words like names to the dictionary so they are ignored by double clicking the word and then click the little diction on the right side of the column. You can find easy to copy emojis [here](https://emojikitchen.dev/) and a nice table generator [here](https://www.tablesgenerator.com/markdown_tables).
