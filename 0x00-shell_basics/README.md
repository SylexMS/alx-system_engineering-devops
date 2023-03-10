# 0x00-shell_basics

## Hi 👋, I'm Sylex
## in this readme i wiil explain each script is doing

in ```0-current_working_directory```, the command ```pwd``` means that print working current_working_directory.

in ```1-listit```, the cammand ```ls``` means that list files.

in ```2-bring_me_home```, the command ```cd ~``` means that change directory to ```/home```.

in ```3-listfiles```, the command ```ls -l``` means that list files in long format.

in ```4-listmorefiles```, the command ```ls-la``` means that list all files and hidden files in long format.

in ```5-listfilesdigitonly```, the command ```ls -lan``` means that list all files and hidden files digitonly in long format .

in ```6-firstdirectory```, the command ```mkdir /tmp/my_first_directory``` means that creat directory ```my_first_directory.```

in ```7-movethatfile```, the command ```mv /tmp/betty /tmp/my_first_directory``` means that move the file betty from ```/tmp``` to ```/tmp/my_first_directory```.

in ```8-firstdelete```, the command ```rm /tmp/my_first_directory/betty``` means that remove the file betty.

in ```9-firstdirdeletion```, the command ```rmdir /tmp/my_first_directory``` means that romove directory ```my_first_directory```.

in ```10-back```, the command ```cd -``` means that change directory to previous one.

in ```11-lists```, the command ```ls -la . .. /boot``` means that list all files and hidden files in the current directory and in the parent directory and in the ```/boot``` directory (in this order) in long format.

in ```12-file_type```, the command ```file /tmp/iamafile``` means that print the type of ```iamafile```.

in ```13-symbolic_link```, the command ```ln -s /bin/ls __ls__``` means that Create a symbolic link to ```/bin/ls``` named ```__ls__ ```

in ```14-copy_html```, the command ```cp -un *.html ../``` means that copy all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

in ```100-lets_move```, the command ```mv [[:upper:]]* /tmp/u``` means that move all files beginning with an uppercase letter to the directory ```/tmp/u```

in ```101-clean_emacs```, the command ```rm *~``` means that delete all files in the current working directory that end with the character ```~```

in ```102-tree```, the command ```mkdir -p welcome/to/school``` means that create the directories ```welcome/```, ```welcome/to/``` and ```welcome/to/school``` in the current directory.

in ```103-commas```, the command ```ls -amvp``` means that list all the files and directories of the current directory, separated by commas (```,```)
* Directory names should end with a slash (```/```)
* Files and directories starting with a dot (```.```) should be listed
* The listing should be alpha ordered, except for the directories ```.``` and ```..```which should be listed at the very beginning
* Only digits and letters are used to sort
*  Digits should come first
* You can assume that all the files we will test with will have at least one letter or one digit
