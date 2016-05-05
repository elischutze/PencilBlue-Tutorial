#PencilBlue Tutorial
##The all-in-one Getting Started guide

This is an intro.



##Setup on Mac
Note: Windows/Linux users please see the PencilBlue [documentation].

There are 3 things you need to have on your computer before you install PencilBlue: 

- Node.js
- Homebrew
- MongoDB

If you don't already,

1. Download and install node [here][Node].
2. Install [Homebrew] by just pasting this into your Terminal 
`
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
`
3. Install MongoDB by running `brew install mongodb` on the Terminal

Now that your setup is ready let's move on to installation.

#Install

Install from scratch by following these steps:

- Install the PencilBlue CLI by running `npm install -g pencilblue-cli`
- `cd` into the directory where you want your install to live.
- Run `pbctrl install /` and follow the instructions. It will ask you for the name of the app, host, port number, db name, etc. Mostly you can leave the default if you're playing with it locally. 

![PencilBlue Install Settings][install]

[install]:/Users/elianne/Documents/Screenshots/Screen Shot 2016-05-06 at 12.10.24 am.png



- Run `pbctrl start`


[Node]: http://nodejs.org/download
[Homebrew]:http://brew.sh/
[documentation]:https://github.com/pencilblue/pencilblue/wiki/Quickstart:-Installation#-mac-installation

