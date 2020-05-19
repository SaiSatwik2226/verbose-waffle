# Anyone can edit this file

# If you dont have a [git](https://git-scm.com/downloads) in your PC download and install it.
  the procedure is very simple click on next and install with the given conditions approved
  
# Next create an account in [Github](https://github.com/) using your mail address.
this procedure is also simple.

# if you are new to this:
  ## 1.use the fork option to fork the repo.
  
  ## 2.open the forked repo
      open command prompt
      use
      'cd desktop'
      to come to desktop.
      use 
      /*git clone <url>*/
      url is the url from the cloned repo in your profile
          
  ## 3.Now the repository is downloaded to your local repository
      use
      /*cd <name>*/
      name is the name that y used if none then use verbose-waffle
      
  ## 4.Now use <editor> Contributions.md
     you need to have an editor such as [Atom](https://atom.io/) or [Sublime Text](https://www.sublimetext.com/3)
     (download if needed)
     
  ## 5.after opening the file add your name.
      [name](url)
      
      save your file and close the editor.
      
  ## 6.After that check /*git status*/
      it shows you modified Contributors.md
      
  ## 7.use command
     /*git add <file name>*/ 
     to add the file to staging area.
     here the file name is Contributors.md
     
     Now check git status it gives new file contributors.md
    
  ## 8.use command
      /*git commit*/ 
      to add the file into ur local repository.
  
  Now check /*git status*/ it gives nothing to be commited
  
  you can skip the steps 7. and 8. by using git commit -a -m "/*commit message*/
  
  ## 9.now to push the changes made in local repository to remote repository use git push -u origin master
  
  now checkout the file in your remote repo you will see the changes.
  
  ## 10.to add it to this file create a new pull request which is visible at the top and create a new pull request.
  
  u can use Github
