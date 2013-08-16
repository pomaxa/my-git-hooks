my-git-hooks
============

Some interesting hooks for git;

To enable image capture in all local git projects 
copy this files into :
/usr/share/git-core/templates/hooks 

And in all new repositories will be enabled.
To enable screen capture in old repositories, - run "git init";

You can change whe size of images, by adjust -x and -y params in "self-shot" file.


Requirement: 
-----------
* Connect WebCam
* sudo apt-get install uvccapture


TODO:
-----------
* create some concole and make all paths configurable;
* add ability to enable disable hooks
