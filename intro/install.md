# Install Instructions

Normally you *NEVER* want to run random commands that you get from the internet in your terminal without understanding what they are and exactly what they do. The terminal could give anyone full access to your entire computer. In this case these commands are coming from a trusted source (me) so it's okay. **Anywhere you have to make a public facing account, be aware that employers may see your handle/username.  Make sure to pick something professional.  I also like to make sure my handles and profile pictures match across services so I'm easier to find.**

Short link to this document [http://bit.ly/1RvOdnj](http://bit.ly/1RvOdnj)

### Run Software Update
> We want the newest version of OS X and all updates before we move on.

Follow [these instructions](https://support.apple.com/en-us/HT201541) to update to the newest version of OS X.

### Chrome
> A fast free web browser with great web developer tools.

Use [this link](https://www.google.com/chrome/browser/desktop/index.html) to download and install Chrome on your computer.

##### Set chrome as your default web browser.
1. From the Apple menu, choose System Preferences, then click General.
2. Click the "Default web browser" pop-up menu and choose Chrome.

### Slack Desktop and Mobile Apps
> Slack is a chat tool that I (and the rest of the staff) will use to do all of our online communication.

Use [this link](https://itunes.apple.com/us/app/slack/id803453959?mt=12#) to install the Slack desktop app.

Go to your Applications folder and find Slack. Drag it into your dock.

Open up slack. It will prompt you to enter your teamdomain. Enter: *theironyardatx*

Enter your email address and password.

Channels to star/join in slack:
- 2016-06-cohort (this cohort's channel)
- design-2016-06 (this class's channel)
- _campus (the campus channel)
- jobs (channel for job postings)
- events (channel for tech/design events)
- watercooler (channel for general alumni/current student banter)

> You should have received an email with instructions on how to set up your account. If you did not, grab Travis or one of the instructors. 

##### Automatically open Slack on login
1. From the Apple menu, choose System Preferences, then click Users & Groups.
1. Make sure your user is selected on the left and then click Login Items on thr upper right.
1. Click the `+` button to add a new Login Item.
1. Select Slack from the Applications folder and click Add.

The teamdomain is *theironyardatx*. 

Also go to the app store on your mobile phone and install the slack app for your mobile device as well.

### iTerm
> iTerm2 is a replacement for Terminal and the successor to iTerm. It works on Macs with OS 10.5 (Leopard) or newer. iTerm2 brings the terminal into the modern age with features you never knew you always wanted.

1. Use [this link](http://iterm2.com/) to download iTerm2.
1. Drag the iTerm application into your Applications folder.
1. Drag the iTerm application from your Applications folder into your dock for easy access.

### Git
> Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

In iTerm2 type the command `git`. If it is not already installed, it will prompt you with instructions on how to install.

You should also identify yourself to git. Use the following commands:

```
git config --global user.name "Your Name"
git config --global user.email you@example.com
git config --global credential.helper osxkeychain
git config --global push.default matching
```

### oh my zsh
> Gives our terminal a facelift.

In iTerm2 run the following commands one by one:

```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
```
curl https://gist.githubusercontent.com/alarner/cf808bc1eccaae7198c6/raw/dbla.zsh-theme > ~/.oh-my-zsh/themes/dbla.zsh-theme
```
```
sed -i '.zshrc_original' 's/robbyrussell/dbla/g' ~/.zshrc
```
```
source ~/.zshrc
```

### Homebrew
> Homebrew installs the stuff you need that Apple didn’t.

Use [this link](http://brew.sh/) and follow the instructions to install Homebrew. When the intructions reference the Terminal you can use iTerm2 that you just installed instead.

### Sublime Text 3
> Sublime Text is a sophisticated text editor for code, markup and prose. You'll love the slick user interface, extraordinary features and amazing performance.

Use [this link](http://www.sublimetext.com/3) to download Sublime Text 3 for OS X. It says that it's still in beta, but it's already very stable.

### Sublime Text 3 Package Manager
> The Sublime Text package manager that makes it exceedingly simple to find, install and keep packages up-to-date.

Use [this link](https://packagecontrol.io/installation) and follow the instructions to install the Sublime Text 3 package manager. You will need to use Sublime to install the package manager. Be sure to restart Sublime after installing the package manager.

### Git Editor
> Change git to use Sublime as your editor

Run this command in iTerm `git config --global core.editor "subl -n -w"`

### node / npm
> Node.js is a platform built on Chrome's JavaScript runtime for easily building fast, scalable network applications. npm is the package manager for node.

Using iTerm run the command `brew install node`.

### GitHub
> GitHub is where people build software. More than 10 million people use GitHub to discover, fork, and contribute to over 26 million projects.

Use [this link](https://github.com/join) to sign up for a GitHub account. You just need the free plan. On your profile upload a picture of yourself. This will help me to remember your name.  Follow me (abbylarner) on GitHub so I can easily find you.

### CodePen
> CodePen is an app for sharing and playing around with front end code.

Use [this link](http://codepen.io/) to sign up for a CodePen account. Use your GitHub account to sign up for CodePen. You just need the free plan.mFollow me (abbylarner) on CodePen so I can easily find you. 

##Adobe
Sign up for [Adobe Creative Cloud](https://creative.adobe.com/plans) (if you don't already have Adobe CS4 or higher). You can use everything free for the first 30 days but the will have to pay for at least the 12 weeks of class. 

There are two options we recommend:

**Option 1**
- The CC annual account, paid monthly: $49.99 for all of the programs if the you agree to one year contract Total student cost for 4 months = $200 plus tax (plus remaining 8 months = $600 plus tax)

**Option 2**
- The CC monthly account month-to-month pricing: $74.99 for all of the programs (without cancellation fees) Total student cost for 4 months = $300 plus tax

If you are using the free trial, we won't need it for the first couple of weeks.  I'll let you know when we do.  However, downloading these programs takes a while, so please do it before you get to class.




