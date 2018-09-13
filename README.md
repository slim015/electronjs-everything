# electronjs-everything
If you're tired of using ubuntu apps (or lack there of), use this eletronjs wrapper to use your favorite webapps without the browser.

Prior requisites to run app:
- Install nodejs and npm (https://nodesource.com/blog/installing-node-js-tutorial-ubuntu/)

Once node and npm are installed, do the following:
- Clone the repo
- Go to the directory and open main.js. Replace the url with the webapp of your choice. For instance, 'chat.google.com'
- Save it and change the name and description fields in package.json to whatever you want (The name field in package.json has to start with a lowercase with no spaces so your-first-app is acceptable but not Your First App. The description can be whatever you want).
- Open a terminal in the directory, install electron by running the following command: npm install electron
- Run the program with: npm start
- Once you see "electron .", you can see the app on your dock/launcher. Pin it and you don't have to open the terminal to run it again

In order for your app to have an icon, place the icon in the icons folder and name it "icon.png". If the name is different, be sure to change it in main.js. 

Note: if you are running ubuntu, you may run into several issues having your icon displayed. Here are some quirky things that got mine to work:
- Rename your icon photo to "icon.png"
- Make sure the icon is 128x128
- Make sure you have the most up to date version of node and npm
- Change the name and description in package.json 
