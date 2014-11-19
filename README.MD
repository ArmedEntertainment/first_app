Ruby on Rails Tutorial: first application
=========================================

This is the first application for [*Ruby on Rails*](http://rubyonrails.org) in a [Debian_Linux](https://www.debian.org) environment.  

This README file contains the tutorial information and process of this repository creation.  
All files creates with Ruby 2.1.5 and Debian Linux 7 "Wheezy".  

Created by ArmedAres from ArmedEntertainment.

Prerequisites:  
--------------
[Ruby on Rails](http://rubyonrails.org) **Installed**.  
[GitHub Repository](http://github.com) **Account**.  

#*Commands Setup: Setup Workspace Directorys*  
*Launch Terminal Window :: use commands*  

'mkdir rails_projects'   // Creates a new directory for ruby on rails projects.  
'cd rails_projects'      // Enter the directory.  

#*Now to Setup Rails*
'rails new first_app'   // Creates a new directory for web application called first_app.  
'cd first_app'          // Enter the directory.  
'rails server'          // Start a rails webserver to test the application.  

#*Now launch a webrowser to confirm its working.*  
*Browse to *, 'http://localhost:3000',*. This is where the rails server is running on your computer.*  

*When finished,*, press **Control-C** to stop the rails server.  

#*Setup: GitHub Version Control*  
*Launch Terminal Window :: use commands from *, 'first_app', * directory.*  
'git init'                          // This initializes the current directory as a git repository.  
'git add .'                         // Adds all the files and folders to the repository.  
'git status'                        // Check to see the files were added.  
'git commit -m “Initial Commit”''   // Commits the files with a message.  
'git log'                           // Check to see what was commited.  

#*Setup: GitHub Website Repository Setup*  
From github.com/yourrepository/:
* Project Name: first_app
* Description: Ruby on Rails Tutorial – Debian
* Anyone.

#*Setup: Git\Hub Upload Current Version  
*Launch Terminal Window :: use commands from *, 'first_app',* directory.*  
'git remote add origin https://github.com/ArmedEntertainment/first_app.git'   // Uploads existent setup   
'git push -u origin master'                                                   // Login if required.  

*Check the github.com/yourrepository/first_app*  

#*Version Control Workflow  
*Launch Terminal Window :: use commands from *,'first_app', * directory.*  
'git checkout -b modify-README'            // Creates a mew branch, in this case modify.README  
'git mv README.rdoc README.MD'             // Renames the filentype to [Markdown](http://en.wikipedia.org/wiki/Markdown) with 'mv' which notifys Git.  
'git status'                               // Shows the status of the changes  
'git commit -am "Improve the README file"' // Commits -a all changes with -m message.  
'git checkout master'                      // Change to the master branch from sourcecode branch  
'git merge modify-README'                  // Merge the new created branch and the changes.  
'git branch -d modify-README'              // Since were finished with the README modifications, -d delete the branch.  
'git push'                                 // Push the changes to github.com  

#*Now launch a webrowser to confirm the repository changes.*  
*Browse to*, 'http://github.com/yourrepository/first_app', * to view the changes.*  

|| END README.MD || CONTINUED IN TUTORIAL_ONE.MD ||  
---------------------------------------------------