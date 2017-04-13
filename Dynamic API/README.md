#UTILITY TOOL

Created by Judd Seger for Web Design and Development at Full Sail University

------

# PURPOSE
The purpose of this tool is to allow debugging on web applications

------

#INSTALLATION PROCESS
 First you want to download node by going to www.node.js.org and following the installation process.
 Second you are able to install my debugging tool by adding it to your computer. npm install dynamic_api
 and it should appear inside of your node_modules folder.

-------

 # TIPS
 Here are a few commands that may be of use:
 npm init (creates a package.json in root for you)
 npm list (lists all installed packages)

-------

# USAGE
Here are a few steps to get your debugging to work. First you want to call the file by typing
const debug = require('dynamic_api'). Afterwards you will have to turn it on by saying DEBUG=true
followed by turning on your server for example: DEBUG=true nodemon src/server.js