# Unit-10-JSLibraries
Lesson 1: NPM, installing libraries, node_modules

# js Libraries
Libraries allow for programmers to develop dynamic interfaces 

# NPM
NPM is the package manager for Node JavaScript platform, putting modules in place so that node can find them, and manages dependency conflicts intelligently.

# NPM COMMANDS
<p>npm help: get list of commands<br>
npm: JavaScript package manager<br>
npm cache: manipulates packages cache<br>
npm config: manage the npm configuration files<br>
npm edit: edit an installed package<br>
npm explore: browse an installed package<br>
npm init: create a package.json file<br>
npm install: install a package<br>
npm run start: opens site in browser<br>
npm uninstall: remove a package<p/>

# Installing NPM Libraries
Installing an NPM library is done by using the terminal in vscode to run the command **npm i** followed by the name of the package, for example, if you wanted to install parcel-bundler you would type **npm i parcel-bundler** into the terminal.

# The node_modules folder
When you download a library using npm, that library goes to your node_modules folder.  However, when uploading to github, you want that folder to be ignored because it is such a big file. This can be done by putting node_modules in a .gitignore file placed in your main folder.
