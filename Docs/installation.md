# Getting the Dev enviornment set up

### **software used in this project**

-- add in install links here
* [VS code](https://code.visualstudio.com/)
* [node.js](https://nodejs.org/en/download/)
* [Windows terminal](https://www.microsoft.com/en-ca/p/windows-terminal/9n0dx20hk701?rtc=1#activetab=pivot:overviewtab) (optional)
* [GitHub Desktop](https://desktop.github.com/)
* [Git](https://git-scm.com/downloads)
* [vue](https://vuejs.org/v2/guide/installation.html)
* [Vue CLI](https://cli.vuejs.org/)

<br>1. Install Github desktop [here](https://desktop.github.com/ "here")

<br>2. Clone the repository to your local computer.
	- Click on the green code Button
	- Click the "Open with GitHub Desktop" button on the drop down menu
	- note your browser may prompt you with a button to confrim this, click Open with GitHub Desktop again on this prompt
  
<br>

[![cloning the repository part 1 gif](https://media.discordapp.net/attachments/913259753948446720/913273808536883241/install_ins_1.gif?width=720&height=527 "cloning the repository part 1 gif")](http://https://media.discordapp.net/attachments/913259753948446720/913273808536883241/install_ins_1.gif?width=720&height=527 "cloning the repository part 1 gif")

<br>3. open Github desktop, follow the steps in the GIF to create a new fork for your dev branch. your branch should be named as the name of your account, with a dash after it, followed by Dev. EX: PFD-Dev

<br>

["intro to forking to get the project set up"](https://cdn.discordapp.com/attachments/913259753948446720/913332772662288414/forking_-_intro_compressed.gif)

<br>4. Next we need to get the terminal set up, this step is completely optional, but is recommended. you can install windows terminal though the microsoft store by clicking [here](http://https://www.microsoft.com/en-ca/p/windows-terminal/9n0dx20hk701?SilentAuth=1&wa=wsignin1.0&rtc=1#activetab=pivot:overviewtab "here")

you will do all your work on your local branch. if you wish to merge your work into the main, you will have to open a pull request so it can be reviwed by everyone before being merged. ideally the main should be the "slowest" and most stable branch, having all of the code together in a stable product


when Pushing your code, there is a branch called **DEV-COMBINED** this branch is the "fast" branch and is where all the most up to date code is. you will always want to merge your work into this branch

**Do not delete the branch after it has been merged to another branch, you need to keep pushing to it. think of it like your own personal version of the repository**

<br>

--------
<br>

Now that our repository is installed, we need to install the vue command line tooling. this is super simple and only requires some basic knowledge of NPM and node

if you havent already installed Node.js, you can head over to the install page [here](https://nodejs.org/en/download/) and grab the latest version of node and NPM.

You can see the docs [here](https://vuejs.org/v2/guide/installation.html) for any aditional reference needed.

Vue can be installed with
    
    npm install vue

For this project we will also be installing the command line tooling.

Installing:
        
    npm install -g @vue/cli
    

The vue CLI docs can be found [here](https://cli.vuejs.org/) for additional reference

## congratulations! you have now set up your dev enviornment

<br>

***Note this file is subject to change a lot, keep an eye on it***
