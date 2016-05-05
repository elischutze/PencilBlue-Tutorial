#PencilBlue Tutorial
##Introducing PencilBlue
###What is PencilBlue?

PencilBlue is a Content Management Platform/System or CMS (think Wordpress, etc) for Node.js 

It prides itself on being highly scalable and business-ready. 

###How does it work? 

The **tl;dr** version of how this framework is structured is that your installation provides a set of **controllers** that are not to be modified, but *extended* by your content. 

In the PencilBlue world, everything you add to your site is a **Plugin** and will live in the `plugins` directory.

All your assets (ie css, img, js) will live in the `public` directory but each **Plugin** will have it's own controllers, views ("templates") and routes. 

##Getting Started
###Setup on Mac
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

###Install

Install from scratch by following these steps:

- Install the PencilBlue CLI by running `npm install -g pencilblue-cli`
- `cd` into the directory where you want your install to live.
- Run `pbctrl install /` and follow the instructions. It will ask you for the name of the app, host, port number, db name, etc. Mostly you can leave the default if you're playing with it locally. 

![PencilBlue Install Settings][install]

[install]: https://github.com/elischutze/PencilBlue-Tutorial/blob/master/resources/install-settings.png

- Fire up your MongoDB instance by running `mongod` and on a separate Teminal tab run `pbctrl start` to start the app. It should now be running and you can access it from your browser at the URL you specified during installation (likely, <http://localhost:8080> !)

If you visit the URL you should see this promp to create a new admin user:

![pencilBlue home](https://github.com/elischutze/PencilBlue-Tutorial/blob/master/resources/pencilblue-home.png)

[//]: # (Insert homepage image here)

[Node]: http://nodejs.org/download
[Homebrew]:http://brew.sh/
[documentation]:https://github.com/pencilblue/pencilblue/wiki/Quickstart:-Installation#-mac-installation

