# Exercise 2: add image to git

This exercise asks you to add a folder to your repo, and thereafter
image to that folder.  And finally commit everything to github!

1. make a new folder (e.g. _images_) to this repo.  Hint: `mkdir`

   ```
   mkdir _images_
   ```

2. ensure that the folder is there.  Hint: `ls`

   ```
   ls
   ```

   The folder is in there!

3. download an image you like and save it into the image dir you made
   above.
   
   ```
   cd _images_
   wget https://phoenixdogtraining.com/wp-content/uploads/2017/04/wepwawet-dog-god.jpg.webp
   ```

4. on command line navigate to the image folder.  Hint: `cd`

   ```
   cd _images_
   ```

5. ensure that the image is there.  Hint: `ls`

   ```
   ls
   ```

   It worked!

6. add the image to your git repo.  Hint: `git add image.jpg`

   ```
   git add wepwawet-dog-god.jpg.webp
   ```

7. commit and push the changes.  Hint: `git commit -am ".. your
   message here.. ".
   
   ```
   git commit -am "pushing image"
   git push
   ```

8. go and check on github that the image is there.

9. as before, edit this file and write here the commands you used.
   Hint: you have to do the edits and commit again, in a similar
   fashion as above.

Did the edits show up on github?
