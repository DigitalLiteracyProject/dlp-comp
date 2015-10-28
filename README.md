# DLP TTP Comp
## Mini-project
Interested in getting started with the comp? Here's a small project to set up your development environment and get familiar with Git, the collaboration software we'll use for our projects.

### Setting up
First, let's get your development environment set up. Open up this [Mac Dev Setup guide](https://github.com/nicolashery/mac-dev-setup). Do the following steps:
- [iTerm2](https://github.com/nicolashery/mac-dev-setup#iterm2)
- [Homebrew](https://github.com/nicolashery/mac-dev-setup#homebrew)
- [Git](https://github.com/nicolashery/mac-dev-setup#git)
- [Node.js](https://github.com/nicolashery/mac-dev-setup#nodejs)

Feel free to do other steps as well!

That'll get you some of the core tools you'll need for web development, including Git and Node.js. But we'll need a few more ones; run the following in your terminal:

```sh
npm install -g yo bower gulp
```

Grab a copy of the [Atom](http://atom.io/) text editor. I highly recommend it and will be using it for the purposes of this comp.

### Getting started with Git
Now you'll learn how to use Git and GitHub. If you aren't already familiar with Git, try this [this interactive Git tutorial](https://try.github.io).

#### Getting the repo
We've created a [sample GitHub repository](https://github.com/hathix/dlp-webapp) for a simple frontend web app. Open up that repository and get acquainted with various pages and features of a GitHub repository:
- Pull requests
- Issues
- File browser

Now make your own copy of the repository (or "repo") so you can work with it. On our repo's homepage, use the _Fork_ button to "fork" our repo, making your own version of it that you can work with.

Now you need to get your own repo on your computer so you can actually edit it. Find the HTTPS clone URL on your repo's page; it should be something like `https://github.com/<YOUR_USERNAME>/dlp-comp.git`.

 Then run:

```sh
git clone <URL>
```

#### Running the app
Now that you have your copy of the repo, let's get it up and running:

```sh
npm install
bower install
gulp serve
```

Upon entering that last command, a very simple webpage like the below will open in a browser; that's you app!

![Sample webapp before modifications](img/sample-webapp-before.png)

You should also see terminal output that looks something like this:

```sh
Fresh-Prince:dlp-webapp neel$ gulp serve
[11:23:39] Requiring external module babel-core/register
[11:23:40] Using gulpfile ~/Documents/Git/dlp-webapp/gulpfile.babel.js
[11:23:40] Starting 'styles'...
[11:23:40] Starting 'scripts'...
[11:23:40] Starting 'fonts'...
[11:23:42] Finished 'styles' after 2.27 s
[11:23:42] Finished 'fonts' after 1.65 s
[11:23:42] Finished 'scripts' after 1.74 s
[11:23:42] Starting 'serve'...
[11:23:42] Finished 'serve' after 91 ms
[BS] Access URLs:
 --------------------------------------
       Local: http://localhost:9000
    External: http://10.252.141.93:9000
 --------------------------------------
          UI: http://localhost:3001
 UI External: http://10.252.141.93:3001
 --------------------------------------
[BS] Serving files from: .tmp
[BS] Serving files from: app
```

If something goes wrong, you might have missed a prior step. Go back and try again!

Open up your app in Atom:

```sh
atom .
```
