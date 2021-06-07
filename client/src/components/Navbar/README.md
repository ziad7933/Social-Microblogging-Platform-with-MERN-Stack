# A simple webapp for posting and liking them
All of the authentication codes are already included and all you need to do is run the program.
To run, 
- Open the folder in VSCode.
- There will be two folders named ***server*** and ***client***.
- Open a bash terminal in VSCode and split it into two bash terminals.
- Type ```cd server``` in one terminal and ```cd client``` in the other. This will have the terminal working in both of the directories.
- Type ```npm start``` in both of the terminals and wait for the server to start.
- If it shows any errors such as a module not found or a package is missing, install it using ``` npm install <package name>```. 
- The server should be up and running and the webapp will be visible in the browser.

## Issues That I Faced
- The assessment asked for firebase integration which was not possible as they have removed the free access for firebase integration. Which is why I used MongoDB as the alternative. I created a cluster on my own account and the database is automatically created from the code. 
- I used JavaScript to write the code instead of TypeScript as I am much more familiar with it.
- Could not use GraphQL as I am not familiar with the syntax. I tried but the server kept crashing for it. The data was not updating so I left the case. 
