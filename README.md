# gc-instructions
Lesson instruction on how to clone the google home page. this instruction was put together to help beginners get started with a project.

## Introduction
This project might not be the exact outcome of the original [google](https://google.com) page, 
however it is rather prepared in a way to help you maximize you basic html and css skills, 
with a touch of applied visual design, css flex and grid, and responsive design patterns.


## Instructions
Make sure to practice while following the instructions, make sure you understand or you're comfortable with the result of every instruction before you move on to the next... ask questions from google or me whenever you meet a road block.

#### Task 1
* fork this repo
* make sure this project is part of your repositories.
* launch command prompt/terminal 
* change directory to your documents or desktop folder using,
 ```cd documents``` or ```cd desktop```
* clone your forked repo, using
 ```git clone [forked repo address]```
* change directory to your forked repo, using
 ```cd gc-instructions```
* do not close your terminal yet.
 
#### Task 2
* open your IDE.
* add ```gc-instructions``` to your projects.
* create an ```index.html``` file.
* if you're using [emmet](https://emmet.io/) then type ```html:5``` and press enter to create a html boilderplate.
* create a folder, name it ```css``` and add a ```style.css``` file to it.
* in your ```index.html``` add ```<link rel="stylesheet" href="style.css" />``` to your ```<head> </head>``` tag to link your ```style.css``` file to your ```index.html file.
* in your ```index.html``` change the title of your page to ```Google```. Within you ```<head> </head>``` tag. It should look like this ```<title>Google</title>```.

##### git Instructions
* go back to your terminal, create a new branch (also known as checkout) called ```develop``` using, ```git checkout -b develop```
* check to see if you have added or modified files using, ```git status```
* stage the changes using, ```git add .``` to track all added or modified files.
* save changes using, ```git commit -m "initial commit"```
* push your changes to your remote branch using, ```git push```
* go to your ```gc-instructions``` repo on [github](https://github.com) to do a pull request from develop to master.
