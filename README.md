# Adding-images-to-Git-Wiki-Pages
Step by Step Procedure for adding images to Git Wiki Pages

1) Copy your git project wiki path and clone it as below on the command line

git clone https://github.com/username/repository.wiki.git

This will clone the wiki on your local machine

2) Create a folder called images in the wiki repository folder on your local machine.Copy the required images to this "images" folder
   
3) This is the last step where we need to push the changes to the wiki on Github.Follow below steps on the command line:

go to the wiki project folder using "cd wikifoldername" and type below commands

step1: git add --all

step2: git commit -m "Commit"

step3: git push -u origin master

After these steps are executed a message of sucessful execution will be displayed.

4) After successful execution of the above steps, a folder called "images" will be added to the wiki but it will not be visible on github.But the images which were added before can now be referenced.

5) Go to the wiki page , edit it and  add below statement where the image needs adding:
 
 !{ImageName}(images/imagename.jpg)
 
 (note:replace { } with [  ] before and after "ImageName" respectively.It was converting it to image so I used different brackets to explain the example)
 
6) After saving the page you can now see the expected image :-)
 
 


