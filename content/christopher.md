Title: Christopher De Jesús Vélez
Date: 2016-02-01
Modified: 2016-02-01
Tags: bro-network
Category: People

## Bio:
 My name is Christopher De Jesus and im currently in my 5th year in college and 4th year as computer science major.
 My main interest this past year has been cybersecurity and I've been participating in conferences, competitions and classes
 throughout the last semester and the current one trying to specialize in it. 
 

## Contact info:

 - e-mail - <chrisoname@gmail.com>
 - Github - <https://github.com/Chrisoname/>

### Research Goals

My main goal during this research is to learn how to make an auditory in a network using tools that would help me 
detect any anomaly. With this I can enhance my knowledge in the cybersecurity branch. 

## Weekly UPDATE


WEEK 1: (25 - 29:
Reading about Bro Network, documentations, requirements and scripting.


WEEK 2:
Began downloading packages in Hulk, but didnt have permissions for installing Bro inside Hulk, so I'll just wait till I find a sudoer. Found the sudoer (Bianca) but apparently the server (HULK) is making it too difficult to install all the requirements and libraries it needs to download Bro. I'll try a different approach next week.

WEEK 3:
After talking to Humberto we concluded it would be best to be connected directly in an ethernet cable to the Science DMZ and just install Bro in my Mac. It worked after many downloads and a few hours of installation. Finished the first tutorial which consisted of 7 challenges to learn how to use the bro language. It was pretty basic, using strings, split(), replace(), etc. 

WEEK 4:
At the end of week 3 Humberto told me to start working in an SSH detection first. I discovered on Tuesday that Bro Network had some tools already made for SSH detection. I spent all week trying to make it work with my network, learning how to use the events on the Bro language. Still working on it, hopefully for week 5 I will have results of SSH detection or maybe even more.

WEEK 5:
After discovering the scripts that I needed for start network monitoring, I found some tutorials on how to start doing this but with virtual environments. Part of the tutorial mentioned to install Vagrant, which goes hand-by-hand with VirtualBox. With these environments of Ubuntu 12.04 LTS 64-bit we will start testing the scripts inside them. It was pretty easy to understand, pretty basic commands on how to set up an environment, how to destroy one, etc. At the beginning of the week, I was pretty lost because I have a very weak knowledge of networking and setting up an ssh-detection script was starting to get difficult. That's why I changed my approach to ask Google for help on how to start setting clusters on Broconctrol, learning the synxtax for this shell, etc. 

I've been working on the weekend trying to set up a cluster of environments. This site: http://jessesnet.com/development-notes/2014/vagrant-virtual-machine-cluster/ helped configure and set up 1 main and 2 slaves to start working on Brocntrl form there. Already installed bro inside the main cluster and it was a success, for now. Now I'm actually trying to connect the main with the slaves. My lack of knowledge on networking has been a setback but I took this weekend to work on this because during the week I want to have everything on point to start the monitoring of these 2 slaves that I have put to work retrieving network traffic. 

WEEK 6:
I never managed to cluster the Vagrant environment of Ubuntu 12.04 LTS 64-bit. After a week of trying, what I managed to do was to set up a cluster that practically is his own master and slave. That means, that it wll monitor itself and it worked! After 5 weeks of trying to get output, I finally managed to get logs of what is happening in the network. It is setup for every hour to create a log that would be manageable by the scripts. This means that, I can finally start programming, or at least analizing how to send these logs by parameter with these scripts and start getting results that can be graphed. Next week will be mostly of reading how to script for bro.
