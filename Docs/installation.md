# Getting the Dev environment set up

### **software used in this project**

-- add in install links here

- [VS code](https://code.visualstudio.com/)
- [node.js](https://nodejs.org/en/download/)
- [Windows terminal](https://www.microsoft.com/en-ca/p/windows-terminal/9n0dx20hk701?rtc=1#activetab=pivot:overviewtab) (optional)
- [GitHub Desktop](https://desktop.github.com/)
- [Git](https://git-scm.com/downloads)
- [vue](https://vuejs.org/v2/guide/installation.html)
- [Vue CLI](https://cli.vuejs.org/guide/installation.html)

<br>1. Install Github desktop [here](https://desktop.github.com/ "here")

<br>2. Clone the repository to your local computer. - Click on the green code Button - Click the "Open with GitHub Desktop" button on the drop-down menu - note your browser may prompt you with a button to confirm this, click Open with GitHub Desktop again on this prompt

<br>

[![cloning the repository part 1 gif](https://media.discordapp.net/attachments/913259753948446720/913273808536883241/install_ins_1.gif?width=720&height=527 "cloning the repository part 1 gif")](http://https://media.discordapp.net/attachments/913259753948446720/913273808536883241/install_ins_1.gif?width=720&height=527 "cloning the repository part 1 gif")

<br>3. open Github desktop, follow the steps in the GIF to create a new fork for your dev branch. your branch should be named as the name of your account, with a dash after it, followed by Dev. EX: PFD-Dev

<br>

[![Intro to forking and collaborating](https://media.discordapp.net/attachments/913259753948446720/913332772662288414/forking_-_intro_compressed.gif?width=720&height=514 "Intro to forking and collaborating")](https://cdn.discordapp.com/attachments/913259753948446720/913332772662288414/forking_-_intro_compressed.gif "Intro to forking and collaborating")

<br>4. Next, we need to get the terminal set up, this step is completely optional, but is recommended. you can install windows terminal through the Microsoft Store by clicking [here](http://https://www.microsoft.com/en-ca/p/windows-terminal/9n0dx20hk701?SilentAuth=1&wa=wsignin1.0&rtc=1#activetab=pivot:overviewtab "here")

you will do all your work on your local branch. if you wish to merge your work into the main, you will have to open a pull request so it can be reviewed by everyone before being merged. ideally the main should be the "slowest" and most stable branch, having all of the code together in a stable product

when Pushing your code, there is a branch called **DEV-COMBINED** this branch is the "fast" branch and is where all the most up-to-date code is. you will always want to merge your work into this branch

**Do not delete the branch after it has been merged to another branch, you need to keep pushing to it. think of it like your own personal version of the repository**

<br>

---

<br>

Now that our repository is installed, we need to install the Vue command line tooling. this is super simple and only requires some basic knowledge of NPM and node

if you haven't already installed Node.js, you can head over to the install page [here](https://nodejs.org/en/download/) and grab the latest version of Node and NPM.

You can see the docs [here](https://vuejs.org/v2/guide/installation.html) for any additional reference needed.

Vue can be installed with

    npm install Vue

For this project, we will also be installing the command line tooling.

Installing:

    npm install -g @vue/cli

The Vue CLI docs can be found [here](https://cli.vuejs.org/guide/installation.html) for additional reference

After installation, you will have access to the `vue` binary in your command line. You can verify that it is properly installed by simply running `vue`, which should present you with a help message listing all available commands.

You can check you have the right version with this command:

    vue --version

    or

    vue -v

## congratulations! you have now set up your dev environment

<br>

**_Note this file is subject to change a lot, keep an eye on it_**
