# Welcome to this history revision site!

This is a site I made to help myself study for my upcoming Pearsons May/June iGCSE History Modular program, I think that combining history with some thing that I find fun and interesting and will help me better remember my notes for the exam

# Features

This project features a lot of the important the notes for Civil Rights in the USA 1945-74 and Germany 1918-1945, the rise of a dictatorship (in-progress, not ready yet, civil rights page is 70% ready). This is designed to function as a planner and knowledge organiser that I simply can't lose. It is further designed to help me with units which I have difficult remembering

# Tech Stack

This project uses the main.html page as the site where people are introduced to the topics and can choose which one they want notes for, The germany.html page (not ready yet) features all notes about germany between 1918 to 1945 while the Civil Rights page focuses on all civil right notes between 1945-74. for the reviewers, This website is not complete yet and still requiers a lot of work to be done, Please do not deduct my hours for this reason.

# How to contribute

You contribute to this project if you want to add your own notes for the topic or if you want to fix any spelling or grammer error. To add notes for your own topic or to a existing topic please create a fork od this project


# To fix a grammer/spelling error/add your notes to a existing topic
1. first clone or fork this project
2. Locate and find the error or locate the page where you want to add your own notes in the respective webpage (i.e if the webpage contains notes about civil rights, the file is most likely civil-rights.html)
3. fix the error in the file or add your own notes to the file in the desired section, If the notes are for (i.e Unit 3.4, add your notes under 3.4)
4. save the progress and create a pull request here once your done fixing errors or adding notes


# to add a new topic and notes for that topic
1. first clone or fork this project
2. in the root directory of this project create a new file with the format [course-name-here].html to create a file for the topic
3. you can then go ahead and add your own notes to the file, but make sure that you first insert this 

```
<!DOCTYPE html>
<html>
    <head>
        <title>Pearsons Edexcel iGCSE History Modular notes = Germany 1918-45</title>
        <link rel="stylesheet" href="style.css">
        <style>
            html {
                scroll-behavior: smooth;
            }
        </style>
    </head>
    <body>
        <nav>
            <h2>Germany 1918-45 notes</h2>
            <div>
                <ul>
                    <li><a href="#unit1">Unit 1</a></li>
                    <li><a href="#unit2">Unit 2</a></li>
                    <li><a href="#unit3">Unit 3</a></li>
                    <li><a href="#unit4">Unit 4</a></li>
                    <li><a href="#unit5">Unit 5</a></li>
                </ul>
            </div>
        </nav>
    </body>
</html>
```
4. you can then replace the 'Unit 1/2/3/4/5' with your units and then go ahead and put down your notes, Put them in a format like this:
```
<div class="container">
                <h2>Unit 1 - Red Scare and McCarthyism all notes</h2>
                <h3>1.1 - Background: The American Political system</h3>
                <ul>
                    <li><p style="text-align: left;">The US government consists of 2 different parts, The federal government and state governements. The federal government is reponsible for governing the whole country while state governements govern their own individual states.</p></li>
                    <li><p style="text-align: left;">The federal government is based in Washington D.C.</p></li>
                    <li><p style="text-align: left;">The executive part of the government runs the country. It is led by the president who is also helped by the vice-president and cabinet</p></li>
                    <li><p style="text-align: left;">The executive government also has departments, They carry out government policies. They are led by secretaries chosen by the president</p></li>
                    <li><p style="text-align: left;">The Congress makes new laws, It is made up of 2 houses, The house of senate and the house of representatives</p></li>
                    <li><p style="text-align: left;">The supreme court and other federal courts make sure that the laws passed are constitutional and clear, Judges are chosen by the president but have to be approved by the senate/p></li>
                    <li><p style="text-align: left;">The US system of government is designed to limit the powers of each group or person, including the president</p></li>
                    <li><p style="text-align: left;">Each state also has its own political system, with a governor, a legislature and a supreme court. While the federal government is reposible for taxation and foreign policy</p></li>
                    <li><p style="text-align: left;">State governments have control over most of the laws in their state</p></li>
                    <li><p style="text-align: left;">Each state also has a national guard, commanded by the governor, to enforce the law</p></li>
                    <li><p style="text-align: left;">There have only been 27 additions or ammendments to the US constitution. An ammendment to the constitution requires two-thirds majority of both houses in congress and has to be ratified by three-quarters of the states</p></li>
                </ul>
```
you can replace my notes with your one. However please keep the css styling.

5. Once you have finished adding your own notes, commit everything and create a pull request on this github!
