# electronjs-everything
If you're tired of using ubuntu apps (or lack there of), use this eletronjs wrapper to use your favorite webapps without the browser.

Prior requisites to run app:
- Install nodejs and npm (https://nodesource.com/blog/installing-node-js-tutorial-ubuntu/)
- Install electronjs (https://electronjs.org/docs/tutorial/installation)

Once those are installed, do the following:
- Clone the repo
- Go to directory and open main.js. Replace the url with the webapp of your choice. For instance, 'chat.google.com'
- Open a terminal, and run: npm start
- If there are any missing packages just do: npm install package-name --save
- run npm start until you see "electron ."
- Once you see that, you can see the app on your dock/launcher. Pin it and you don't have to open the terminal to run it again
