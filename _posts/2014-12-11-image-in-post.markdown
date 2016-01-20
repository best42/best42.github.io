---
layout: post
title:  "Common command in Terminal"
date:   2016-01-11
---
{% highlight html %}
pwd                # present working directory
mkdir <FILENAME>   # crete an empty directory
touch <FILENAME>   # create an empty file
ls                 # List files and folders
ls -a              # list all files and folders including hidden files
ls -la             # list all files and folders including hidden files in detail
cd <FOLDERNAME>    # change directory to specific folder
cd /               # change directory to root
cd ~               # change directory to home folder
cd ..              # change directory up one level
cd <old name> <new name>       # copy file
cat <FILENAME>      # see file detail
tail <FILENAME>     # see file content from the last line of the file.
cp <SOURCE FILE NAME> <DESTINATION FILE NAME>   #copy file
mv <SOURCE FILE NAME> <DESTINATION FILE NAME>   #move file
rm <FILENAME>       # delete (remove) file
rm -r <FOLDERNAME>  # delete (remove) file or folder
rm -f <FILENAME>    # force delete (remove) file
rm -rf <FOLDERNAME> # force delete (remove) file or folder
ln -s <FILENAME1> <FILENAME2>  # symbolic link file (like shortcut)
{% endhighlight %}
