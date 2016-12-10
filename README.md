# Availabook

COMS W4156 Advanced Software Engineering

##How to execute the maven project
1. Open your terminal and git clone this repository `git clone https://github.com/StarBugs-ASE/Availabook.git`
2. Change the current working directory to your local project.
3. Execute `mvn package` and `mvn compile`, this will install the package into the local repository and compile it.
4. Execute `mvn exec:java` will run our project on your local machine and create a sqlite database.
5. Execute `mvn -Dtest=TestCircle test` will automatically run all the test cases.
5. Execute `mvn clean` will remove all files generated by the previous build, but the database will remain.

## Development Overview
1. Use [Spark Framework](http://sparkjava.com/) to create the Java web application.
2. Use [SQLite](https://sqlite.org/) database to store all the backend data.
3. Use [Jade template language](https://www.npmjs.com/package/jade) to write HTML.

## Completed Development
1. Created User sign up and log in module.
2. Created User add friends module.
3. Created User add available time module.
4. Wrote blackBox test cases for completed development. 
 * Check the user input of the sign up, log in and add available time function. If the input is not correct, it will display an error message on the page.
5. Created buildscript for the project.
6. Created functions that forbids user to return to the former page when he/she logs out.
7. Added function that forbids the users to sign up with a username that is duplicate with others.
8. Addded feature for user to delete their friends.

## Current Development

1. Creating friend group module.
2. Modifying the display of available time list on the home page.
3. Creating display of friend list on the friend page.
4. Creating the delete button for users to delete the available time.
5. Producing alerts for error message when users' inputs are wrong.
6. Creating Unit test cases for every function.
7. Creating more system level cases for the whole project.
8. Sorting availatime by starting time or by user name.

## Questions to find out
1. Jade Template are hard to implement
2. Friend Group logic.

### Team StarBugs
Xun Xue(xx2241)
Xiaofei Chen(xc2364)
Maolin Zuo(mz2584)
Jing Zhong(jz2748)
