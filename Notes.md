Angular Knowledge base 

Requirements 
Node.js – a runtime environment for executing JS code without a web browser
NPM – a package manager for managing JS libraries

Setup
If Node and NPM has not already been installed follow this guide
1.	Install NVM, a command line tool for installing and using different version of Node.js (https://github.com/nvm-sh/nvm)
2.	Once installed run “nvm install node”, this will install Node and NPM
Note: nvm is not supported on windows but will work with git bash and WSL
Note: there may be compatibility issued between Angular and Node. You will know if you run “ng –version” in your project folder and it says “Warning: The current version of Node (18.2.0) is not supported by Angular.”. If this is the case check the compatible version here (https://stackoverflow.com/questions/60248452/is-there-a-compatibility-list-for-angular-angular-cli-and-node-js) and download a compatible version of Node.js with the command “nvm install <MAJOR_VERSION_NUMBER>”, in my case the major version number was 16. Then run “nvm use <MAJOR_VERSION_NUMBER>” and then reinstall Angular, check there are no issues with “ng --version”

Note: with my set up I would get a command not found after installation. I eventually worked out it was because I didn’t have a profile file for my terminal, git bash. I was able to fix this by creating a “.bashrc” file in my home directory, then restarting my terminal. I then re ran the install.sh script for nvm and this resolved my issue.

Install angular 
To install angular run the command “npm install -g @angular/cli@latest”
Use “ng --version” to confirm the installation

Starting a new project
To start a new project run “ng new <PROJECT_NAME>”, this will create a folder for your project and populate it with the required packaged to get the project running

Running a project
If you cd into the project and run “ng serve” the node runtime will start up the project and in the output will be a local URL, if you go to that in a web browser you will see the app.

Continue from 30:48 on this video https://www.youtube.com/watch?v=2OHbjep_WjQ
Why am I getting the error about the return type?
Check out this site for information on using typescript and decorators https://www.digitalocean.com/community/tutorials/how-to-use-decorators-in-typescript

That course was of poor quality but the tutorial in the Angular Docs is much better 
Continue following the Tour Of Heroes Tutorial from here https://angular.io/tutorial/toh-pt1
At Edit the Hero

Got up to part 5 of the tutorial https://angular.io/tutorial/toh-pt4
Just starting
