# git-to-svn-deploy.sh
A modification of Dean Clatworthy's deploy script as found here: https://github.com/deanc/wordpress-plugin-git-svn

Public version of .sh script use to deploy WordPress plugin to git and svn at the same time. This script is a work in progress please feel free to raise issues and improve. 

* tags git 
* tags svn
* updates svn trunk
* imports gitignore into svnignore & adds custom ignore rules
* automatically reads plugin version number
* pushes to multiple origins (bitbucket,github) if exits
