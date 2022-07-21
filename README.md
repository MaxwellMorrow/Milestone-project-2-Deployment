# Milestone-project-2-Deployment

##Description
The intend was to create a bug-tracker app. This is a built-in react-redux app. It has 2 seperate files. The first file runs the front-end and the second file runs the backend of the app. When going into the app, you will see on the top left hand corner the navbar containing the dashboard, viewbugs, and create bugs. We tried to make the app as simple as possible.
##Demo
After the project was checked for errors firs then we chose heroku to host our application. We went through a few steps to try to host it and after a few tries we submitted the application and hosted it to heroku.
##Technologies/Technical 
In the front end we installed an npm within the directory and added the layouts and components folder in the directory. Then we imported code from those folders into the app.js. The layouts folder contains 2 files, the newTickets.js and the tickets.js. One has the code responsible for submitting new tickets and the other file contains the tickets. The components folder contains different files such as viewbugs, navbar, login, errorpage, editbugs, dashboard, and createbugs. These are the files that manage the frontend for the user to submit tickets, view tickets, recieve error page and edit bugs. The backend contains 2 folders. The first directory is models and the other one controllers. The backend also operates with the server.js directory. For the backend, we used mongoDB to operate our database with our project. Within the backend, we installed the npm express and dotenv package. In the models folder we have the user and bug files that are built on schema. 
##issues
The only issues we had when installing the project is that we did not add a logging page due to time constraints but other than that, no other issues with the app. 
#changelog
mac@Macs-MacBook-Pro Milestone-project-2-Deployment % git log 
commit 26fe87101125beda238267d12fdaf7c63887d36e (HEAD -> main, origin/main, origin/HEAD)
Author: Mae Pena <93175349+maepena91@users.noreply.github.com>
Date:   Mon May 23 20:29:09 2022 -0700

    Update bugs_controller.js

commit 1068cab55b9be1f0caa16f9f8e8f82dc82e65b1e
Author: Mae Pena <93175349+maepena91@users.noreply.github.com>
Date:   Mon May 23 20:28:10 2022 -0700

    Update DashBoard.js

commit b08d50775368edd845b7cc1fe7d8c3262192c0b6
Author: Mae Pena <93175349+maepena91@users.noreply.github.com>
Date:   Mon May 23 20:26:29 2022 -0700

    Update ViewBugs.js

commit 33541bc105ec58103cb91a10670abd6e9b5261d6
Author: Maxwell Morrow <maxdmorrow@yahoo.com>
Date:   Sun May 22 10:18:02 2022 -0700

    first deployment commit!
