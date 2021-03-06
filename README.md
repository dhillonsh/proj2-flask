# README #

### Author: Harpreet Dhillon , harpreet@uoregon.edu ###

---

### Purpose ###
* This application is for Project 2 of CIS 322 at University of Oregon.
* The purpose was to become familiar with the Flask framework and Jinja2 templating to develop and display a simple schedule.

### Application Specifics ###
* The schedule will be read from [schedule.txt](/data/schedule.txt) and displayed automatically when visiting a routed address.
* Else, a [404 page](/templates/page_not_found.html) will be displayed.
* The current week will be highlighted in a different color on the schedule display.

### Running the Application ###
* Test deployment to other environments including Raspberry Pi.  Deployment 
  should work "out of the box" with this command sequence:
  * `git clone <yourGitRepository> <targetDirectory>`
  * `cd <targetDirectory>`
  * `make configure`
  * `make run`
  * (control-C to stop program)
* The default port is 5000, so the webserver should be reachable at http://localhost:5000 , and also through its IP address.
 
### Testing the Application ###
 * There are no tests for this application other than accessing the webpage at http://localhost:5000 and seeing the schedule display.

