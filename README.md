LORVENT PROJECT CREATED BY HEMANTH.P

All you need to do is download the project and give "npm start" in your terminal to see my project up and running in your browser.

Note: I have also created the Grunt and Gulp files so that, for the future if anything has to be uploaded on the server, that can be done easily using those files.

You can also serve up the project using these commands: "grunt" or "gulp". By typing these commands on the terminal you will still be able to view the same content.

I have just executed the project using three diffrent task runners: npm, grunt and gulp. 

Grunt:
      To build the 'dist' folder for my project, all you need to do is run "grunt build" on your terminal. The dist folder can be later uploaded to the server.
      
Gulp:
      To build the 'dist' folder for my project, all you need to do is run "gulp build" on your terminal. The dist folder can be later uploaded to the server.
      
While giving "gulp build" few may get a reference error, to solve that issue you need to create a json file in your project directory named "npm-shrinkwrap.json" and type

           {
              "dependencies":{
                  "graceful-fs":{
                      "version":"4.2.3"
                      }
                 }
           }
after that save the json file and in the terminal type "npm install". After that re-run your gulp command, it will work.
