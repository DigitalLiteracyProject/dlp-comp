# DLP TTP Comp
## Mini-project
Interested in getting started with the comp? Here's a small project to set up your development environment and get familiar with Git, the collaboration software we'll use for our projects.

### Setting up
First, let's get your development environment set up. Open up [Mac Dev Setup guide](https://github.com/nicolashery/mac-dev-setup). Do the following steps:
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

We've created a [sample GitHub repository](https://github.com/hathix/dlp-webapp) for a simple frontend web app. Open up that repository and get acquainted with various pages and features of a GitHub repository:
- Pull requests
- Issues
- File browser

Now make your own copy of the repository (or "repo") so you can work with it. On our repo's homepage, use the _Fork_ button to "fork" our repo, making your own version of it that you can work with.

Now you need to get your own repo on your computer so you can actually edit it. Find the HTTPS clone URL on your repo's page; it should be something like _[https://github.com/](https://github.com/)<YOUR_USERNAME>/dlp-comp.git_. Then run:

```sh
git clone <URL>
```

Now that you have your copy of the repo, let's get it up and running:

```sh
npm install
bower install
gulp serve
```

Upon entering that last command, a very simple webpage should open up in your default browser -- that's your app! If something goes wrong, you might have missed a prior step.

Open up your app in Atom:

```sh
atom .
```
