To set up git with your vs code you first need to navigate to this link and download the git program https://git-scm.com/downloads
Next you need to set your username and email if you have a github account already ( not sure if you have to use an account if we are gonna use a central repo for the project)
either way it'll be helpful to do this 
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
then use $ git init to initialize a repo so you can clone this one to it
finally you will be able to use the git commands in the control pallete (ctrl+shift+p) and you can select Git: Clone 
(if the git commands do not show up you may need to restart vscode
it will prompt you after using the git: clone for a link, then all you need to do is paste the sharable link
https://github.com/baker5aaron/Card-Game
