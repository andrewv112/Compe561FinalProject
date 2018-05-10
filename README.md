# Compe561FinalProject
Cintora University

This website is an example of how to use asp.net core with Razor Pages to create a data base. The website is based of the tutorial at: https://docs.microsoft.com/en-us/aspnet/core/data/ef-rp/?view=aspnetcore-2.1. 

If attempting to run this code beware that it will not work with the latest update of Visual studio. 

The website keeps a record of students first name, last name, and the dates they Enrolled. The administrator is capable of adding, removing, and editing students on the data base. I was not able to implement administrator privileges so as it stand any user would have full access to the data base. The website has three entities: course, Enrollment, and student. These each have corresponding ID's with characteristics to their entity like credits, grade, enrollment date, etc.

Challenges: 1. Getting the sql on the sdsu database. I could not find a way to publish the data base without paying money. 2. Getting code to work. I spent a great amount of time get a working website. Had to do the tutorial 4 times. Eventually got error free code to work after some minor changes and changing the website browser. The program does not work in debug mode. Must use ctr-F5 to run without debugging. 3. Spent most of my time troubleshooting command tool issues. The latest version of Visual Studio 17 messed up dependencies so when adding Scaffold using the command prompt I would get the error "The located assembly's manifest definition does not match the assembly reference." Do fix this I had to use another computer that didn’t have the latest update of visual studio. 4. The rest of my time i spent learning how to change the html to represent my personal website. 

![alt text](https://raw.githubusercontent.com/username/projectname/branch/path/to/img.png)
