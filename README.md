# Adding-images-to-Git-Wiki-Pages
Steps by Step Procedure for adding images to Git Wiki Pages


1) Copy the git wiki path and clone it as below

git clone https://github.com/Username/Repository.wiki.git

This will clone the wiki in your local machine

2) Create a folder called images in wiki repository folder on your local machine
   Copy the required images to this "images" folder
   
3) This is the last step where we need to push the changes we made back to the Github.Follow below steps
   
*git add --all
*git commit -m "Commit"
*git push -u origin master

After these steps are executed a message of sucessful execution can be seen.

4) After successful execution of the above steps, a folder called "images" will be added to the wiki but it will not be visible.
   But the images which were added before will can now be referenced.

5) Go to the wiki page , edit it and add below statement where the image needs adding
 ![ImageName](images/imagename.jpg)
 
6) After saving the page you can now see the expected image :-)
 
 


