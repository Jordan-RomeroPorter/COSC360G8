COSC360G8
=========

Our Project

The objective is to make it easy to create Teams.


Go team.
Thank you for the project. Please modify it according to the comments:
1. You need basic documentation including a flowchart describing files and their relationship in addition to describing each function.
2. The variables are not introduced e.g. $k, $l and $p. They are not well-named variables.
3. In create.php, there is a loop. I think the value of p should get back to zero at the beginning of the loop. If it shouldn't, what is the reason?
4. Each file should have a description.

Your choice of using Cloud9 is problematic. I have no way to assess personal contribution. Please send me the address of a git repository for your project. 
Using a versioning system is mandatory for this project. I understand Cloud9 is using git in the background but I need access to it or at the very least a way to assess 
individual contribution.


Yves on LICENSING:

Any code you write has to have a license that explains under which condition the code can be used. 
Some of the most popular licenses in the open source community are the Apache license (free to do anything 
including reselling the code), GPL (cannot resell the code, need to publish the source and any modification has to be GPL), LPGL, etc. 
See http://opensource.org/licenses
 
Have a look at various licenses and pick one.

brett's pick : GPL
andrea's pick: GPL 
jordan's pick: GPL
------------------------------------------------

Basic:
- students log into a website using their usual credentials (Novell). They enter their name, degree (BA/BSc), major, minor, programming experience (ranked from 1: very low (no experience outside courses) to 5 very good (professional consultant)), list of skills relevant to the course, blacklist, days/time they cannot meet, and (optionally) they select a project.
- instructor log in, enter the number of teams to create, and place students in teams according to the following soft constraints: balance male/female, balance BA/BSc, avoid blacklist, balance experience.

Normal:
- when student enters his data, the camera takes a picture that is uploaded with their profile (see https://developer.mozilla.org/en-US/docs/WebRTC/Taking_webcam_photos for pictures)
- checkbox: remove students from available list after it is placed in a team
- after instructor click create, emails are sent to students informing them of their teams (manual)

Fancy:
- random assignments while respecting blacklist
- optimal assignments using optimation

#Needs to be done:
    

    Form.php
        takes picture of user -- https://developer.mozilla.org/en-US/docs/WebRTC/Taking_webcam_photos
        http://stackoverflow.com/questions/3922723/using-a-webcam-with-javascript
        
        

    Optimal.php *needs algorithm* -- andreaA
        able to make changes to db values for group
        algorithm
        
        
        
    Connect.php
        Connect.php *db implementation* -- jordan
        for easy connection to db
        *change values*

db columns exactly as named below        
    #                       auto incrementing number
    username                text
    salt                    ???
    hash                    ???
    firstname               text
    lastname                text
    studentnumber           text or number
    email                   text?
    degree                  text
    major                   text
    minor                   text
    experience              number
    skills                  text
    fblacklist1             text
    fblacklist2             text
    fblacklist3             text
    lblacklist1             text
    lblacklist2             text
    lblacklist3             text
    busydays                ??? checkboxes that store multiple things not sure how this works
    project                 test
        

#Is done: (12/15)
    
    Login.php
    
    Logout.php
    
    New.php
    
    Add.php

    Validate.php
    
    Display.php
    
    Enter.php *check if defaults work* *check if $found works*
    
    Students.php
    
    Manual.php
    
    Change.php
    
    Random.php
    
    Create.php


#Comments:
    
