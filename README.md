# ux-san-francisco

This is a node app! It is running on a Heroku instance and deploys from `gh-pages` on Github.

## Installation
1. `git clone git@github.com:makemodel/uxsanfrancisco.git`
2. `npm install`

## Starting your server
Type `npm start` in terminal to get your server going, then navigate to `localhost:3000` in a browser of choice.

## Testing on another device.
1. Type `ifconfig` in terminal on your host device, find `en0`, then `inet`. There should be an IP address there starting either with `10.0.0.X` or `192.168.1.X`.
2. On the remote device (such as your phone) you'll need to make sure you're connected to the same wifi.
3. In the browser on this device: type in the IP from step 1 and the port the app is served on. Ex. `10.0.0.X:3000`.

## Making changes
Make sure you're making changes on a relatively titled branch. *Do not* work off of `master` or `gh-pages`.

When you're ready to have you changes merged, simply push your branch and make a pull request in to master. Deploying will be handled by the code owner [@kidfribble](https://github.com/kidfribble).
