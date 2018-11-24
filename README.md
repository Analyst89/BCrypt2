# FreeCodeCamp - Data Protection with BCrypt Challenges
=======================================================

This is the _second_ repository for the freeCodeCamp [Information Security with HelmetJS Challenges](https://learn.freecodecamp.org/information-security-and-quality-assurance/information-security-with-helmetjs/),   
starting with the 12th challenge and upwards.  
For the first 11 challenges you will have to clone [Applied InfoSec Challenges](https://github.com/freeCodeCamp/boilerplate-infosec)     

If you haven't used **git** before, you might want to first read
[a bit](http://try.github.io/) about it, or try the [Glitch](https://glitch.com/) 
way as described on the challenge introduction page mentioned above.

To clone this Repository, go to a directory of your choice and enter:

```
git clone https://github.com/freeCodeCamp/boilerplate-bcrypt.git
cd boilerplate-bcrypt
```

In order to be able to import your local clone to Glitch (or any other coding 
platform of your choice),  
you have to [create your own repository on GitHub](https://help.github.com/articles/creating-a-new-repository/), or [fork this repository](https://help.github.com/articles/fork-a-repo/).
To be able to push to it, you have to remove the remote `origin`,
rename the "gomix" branch to "master" and delete the gomix branch
(to have a clutter-free repository):

```
git remote remove origin
git branch -m master
git branch -d gomix
```

Then follow the steps outlined in the **Quick setup** screen (you could also push 
to some other existing repository from the command line):

```
git remote add origin git@github.com:<yourname>/<your_repository>.git
git push -u origin master
```

Now you should have a fully functional repository you can import to any coding platform.  
**Important:**
In order to develop locally, there is one more step necessary. Run:

```
npm install
```

Don't forget to commit and push your changes after each challenge step (and, 
depending on your coding platform      
of choice, reimport it there), so that freeCodeCamp is able to test your results!  

*Happy Coding!*

#### Informational

You might want to take a look at [this page](https://help.github.com/articles/ignoring-files/#create-a-global-gitignore)
for information about a global `.gitignore` file, so you won't accidentally commit
and push your IDE's of choice helper files.
