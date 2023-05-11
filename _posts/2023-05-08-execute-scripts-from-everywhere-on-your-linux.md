---
title: How to create make your scripts executable form everywhere
date: 2023-05-08 00:00:00 -500
categories: [linux]
tags: [cybersecurity,hacking,shell,linux]
---

# How to create make your scripts executable form everywhere

create a folder at the base of your home directory 
```
cd ~ # go to your home directory
mkdir NAME_OF_FOLDER # create your new folder
touch helloworld.sh # create your firts scripts
nano helloworld # Open your file
```

Content of helloworld.sh
```
#!/bin/sh # use shell scripting

echo "Hello world!" # Print hello world! on your terminal
```

1. Open the `.bashrc` file in your home directory (for example, `/home/your-user-name/.bashrc`) in a text editor.
2. Add `export PATH="your-dir:$PATH"` to the last line of the file, where _your-dir_ is the directory you want to add.
3. Save the `.bashrc` file.
4. Restart your terminal.

Now you can run your scripts form everywhere on your terminal