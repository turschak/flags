# Flags Project

## Getting the project repository

To get started with this project, "Fork" the repository (see the button in 
the upper right corner of the Github page).  This will move you to your own copy 
of the project repository, with the URL: 
~~~
https://github.com/your_username/flags
~~~

Once you've completed this step, open a command line prompt and clone your copy 
of the repository from Github.  
~~~
git clone https://github.com/your_username/flags
~~~

Change into the downloaded directory.  
~~~
cd flags
~~~

## Submitting changes

Once you have made changes (created or edited a file), commit your changes in git.  
~~~
git add file
git commit -m "Commit message"
~~~

Check the name of your remote copy on Github (should be `origin`)
~~~
git remote -v
~~~

Push your changes to your remote repository
~~~
git push origin master
~~~

Go to your copy of the repository on Github, and look for the green pull request
button.  

## Updating your copies of the repository

Back inside your copy of the repository on your computer, you can add the 
original source repository as a secondary remote: 
~~~
git remote add upstream https://github.com/crazapplejuice/flags
~~~

You can pull down changes from this copy of the repository using the `pull` command:
~~~
git pull upstream master
~~~

To update your *own* remote, you can then run: 
~~~
git push origin master
~~~