### I have deployed this site by taking help of gh-pages

1. Create a new repository with no additional settings in github.
2. In package.json add a property homepage under private in the following format.
    > "homepage": "https://UserName.github.io/Project-name",
3. In scripts in package.json add these property-values
    > "predeploy": "npm run build",
    > "deploy": "gh-pages -d build",
4. Open CMD/Terminal and run the following commands to add origin and url of your project
    > git remote add origin https://github.com/UserName/Project-name
    
    > git remote set-url origin https://github.com/UserName/Project-name
5. run command 
    > npm run build
6. run command to install gh-pages
    > npm i gh-pages
7. run command
    > npm run deploy
