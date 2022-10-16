# INF601 - Advanced Programming in Python
 Jesse Heckman
Mini Project 3  
 
Introduction to Flask project using pycharm.  This project was completed for the INF 601 class at 
Fort Hayes University.  The objectives of the assignment were as follows:
## Objectives

- (5/5 points) Initial comments with your name, class and project at the top of your .py file.
- (5/5 points) Proper import of packages used.
- (70/70 points) Using Flask you need to setup the following:
  -    (10/10 points) Setup a proper folder structure, use the tutorial as an example.
  -    (20/20 points) You need to have a minimum of 5 pages, using a proper template structure.
  -    (10/10 points) You need to have at least one page that utilizes a form and has the proper GET and POST routes setup.
  -    (10/10 points) You need to setup a SQLlite database with a minimum of two tables, linked with a foreign key.
  -    (10/10) You need to use Bootstrap in your web templates. I won't dictate exactly what modules you need to use but the more practice here the better. You need to at least make use of a modal.
  -    (10/10) You need to setup some sort of register and login system, you can use the tutorial as an example.
-    (5/5 points) There should be a minimum of 5 commits on your project, be sure to commit often!
-    (5/5 points) I will be checking out the master branch of your project. Please be sure to include a requirements.txt file which contains all the packages that need installed. You can create this fille with the output of pip freeze at the terminal prompt.
-    (10/10 points) There should be a README.md file in your project that explains what your project is, how to install the pip requirements, and how to execute the program. Please use the GitHub flavor of Markdown. Be thorough on the explanations. You will need to explain the steps of initializing the database and then how to run the development server for your project.

## Install 
`pip install -r requirements.txt`
This will install all of the modules that you will need for the program. 

## Run the Application

`$ flask --app flaskr --debug run`

You’ll see output similar to this:

* Serving Flask app "flaskr"
* Debug mode: on
* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
* Restarting with stat
* Debugger is active!
* Debugger PIN: nnn-nnn-nnn



## Initalize the db file

Run the init-db command:

`$ flask --app flaskr init-db`
Initialized the database.



## Running the program
To run this program clicking the green code button `clone` the code and run in you're preferred python editor. 


## FLASK Documentation 
Flask Tutorial Documentation is available here: [Flask Tutorial Documentation](https://flask.palletsprojects.com/en/2.2.x/tutorial/).

