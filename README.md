## VSCode Git Instructions
#### Disclaimer: I haven't tried this with multiple accounts on Github, but it works with mine. I'm thinking that if the student has multiple github accounts, configure the local .git file to the user settings that the account is used for. i.e `git config user.name "CianteJones"` rather than `git config --global user.name "Ciante Jones"` I think this could fix the issue Prof. Bang was having with the UI. I don't know what changes we would to make to this file.

#### Cloning a repo
1. Go to View > Command Palette or if on a Mac (Cmd - Shift - P) or on Windows (Ctrl - Shift - P)

2. Type git clone into the search and click the first result

<p align="center">
  <img src="palette.png" alt="Command Palette">
</p>

3. It will ask for a repository URL. Go to your github assignment, click the Clone or download button, copy the URL.

<p align="center">
  <img src="url.png" alt="Github Url">
</p>

4. Paste the URL into the repository URL and choose the location where you want to clone the repository.

<p align="center">
  <img src="urlpaste.png" alt="URL in VSCode">
</p>

Your repository will should now be on your computer in the location you chose to clone it!

#### Committing files

1. Once we make changes to the files click on the 3rd tab (middle tab) that has the branches.

<p align="center">
  <img height="350px" src="tabbar.png" alt="tabbar">
</p>

2. Then we need to click on the pluses in the git control tab to stage all the files that were changed. You can also click the pluses one by one per file if you don't want to add a certain file to the stage area

<p align="center">
  <img src="stage.png" alt="staging">
</p>

3. The files will move to stanged changes. This is where I initially got confused. Since I'm used to the terminal, git commit -m is the first thing that comes to mind, however, I didn't see the Command-Enter to commit. But, you type whatever commit message you want up there and hit Command-Enter (I'm pretty sure it's Ctrl-Enter for Windows users).

<p align="center">
  <img src="commit.png" alt="commiting">
</p>

#### Pushing files to github repo

1. After you commit, you need to click on the horizontal ellipsis in the Source Control tab, and click the push. This automatically did it for me, and I'm unsure of what happens with multiple users since I only have my Github account on this computer.

<p align="center">
  <img src="push.png" alt="pushing">
</p>


Overall, I think it's kinda confusing if you don't understand what the different git commands mean. I think this could be a cool alternative if they don't want to use the command line, but I personally don't enjoy the workflow for this system.
