# Fun Commands  
So I wanted to do an extension of lab report 3 by exploring some commands in bash. In particular, I wanted to find some fun and not so "practical" commands that I could do in the command line.    
Sadly, it didn't take me long to realize that all the fun stuff is only really possible on Linux, which led me down a rabbithole of Windows Subsystem for Linux. 

## Installing WSL  
I'm not going to try to explain what's WSL because I barely understand it myself, I just know that it lets me do cool-linux-stuff on my Windows laptop. To install WSL2, I ran the following command in my VSCode shell:  
```wsl --install```  
I waited for it to install, restarted my computer and Ubuntu started installing. I just followed the set-up instructions (setting up my username and password) and I was good to go!  
![ubuntuInstall](ubuntuInstall.png)  
I was a bit insulted when it told me that "Kenna" was a "bad name" for my UNIX username, but turns out I just shouldn't capitalize the first letter.  
I opended VSCode and opened my terminal as usual. I switched out of git bash by clicking the little "+" button and selecting WSL.  
![vscodeWSL](vscodeWSL.png)  
Last step to installation, I ran the following command:  
```sudo apt update```  
I ran this because when I tried to install one of the packages below, I was getting ```unable to locate package```. Updating the repository cache seemed to do the trick.  Note that I'm running the default repository, Ubuntu, on WSL2, so my commands will be for that.

## Steam Locomotive  
Finally, we get to the fun part. One of the most popular fun commands is the Steam Locomotive. To install it and run it, enter the following command:  
```
sudo apt install sl
sl
```  
Then watch as a steam locomotive moves across your screen.
