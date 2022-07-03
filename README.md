# COWBOT  
AI Linux Assistant named COWBOT written in C++

Cowbot is extremely easy to use. Just type specific KEYWORDS in your sentence to perform operations. Name of the cowbot is DHENU. She is extremely powerful and she can help you save time and manage your Linux machine very easily

Presently, Dhenu can :

* do basic maths : addition, subtraction, multiplication, division, power, factorial, fibonacci
* get time, date, month, year or time in nanoseconds
* clear your conversation with her
* open, install or uninstall softwares
* run linux commands
* create/rename/delete files and folders
* open files and folders
* move/copy files
* search files on your system
* show network properties
* show system properties
* repeat what you say
* reply basic questions like : asking her name, her work, her capability, greet her, etc.
* manage processes running on your system
* tell you quotes which are funny or motivational
* run a train for you
* bring you an aquarium
* bring rain of characters

## System Requirements :
#### OS : Arch Linux or any Arch based distro


#### Kernel : Arch Official Kernels (linux, zen, lts, hardened)


#### GCC : v11.0+ (compiled cowbot with gcc 12.1)


#### Dependencies : pacman, paru for installing other dependencies


#### (Note : May or may not work with custom kernels)


## Installation Instructions :
1. Clone cowbot repository :
~~~
git clone https://github.com/yashslakhtariya/cowbot.git
~~~
2. Run install script :
~~~
cd cowbot && ./cowbot-install.sh
~~~

#### Note : cowbot won't work properly without its dependencies. So step-3 is must! 

3. After installation, for initial setup run :
~~~
cowbot-setup
~~~

It will ask for your user password for installing dependencies. If no error occurs, cowbot is ready. Run ```cowbot``` command anytime to get your assistant!
