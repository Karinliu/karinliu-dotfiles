# My dotfiles

When I first opened my terminal it was only white and black. It is kinda boring to see that. That is the reason I wanted to personalize it.



Before u want to customise your terminal you have to edit one of the following config files `.bashrc`, `.bash_profile` or `.profile`. To find the config file you have to go to your root directory `cd ~`  and print out hidden files ` ls -a` U can open the file by typing the following command: `nano .bashrc` (Don't worry, if the document you are looking for does not exist, nano will create this file).



# Make alias

I started by making an alias. First you have to open a config file. After that u can make an alias. For example: I am going to make an alias for my hidden file: ` alias .bashrc="nano .bashrc"`. When u made the alias, exit the .bashrc by hitting the button `control` and `x`. Save it with button `y`, hit `enter` and restart the terminal. Now your alias is made!



# Change prompt

To modify your prompt u have to open your config file. For example what I have:

`PS1="🌱 \$(basename \$(pwd))$ ";`. After that save your file and restart the terminal. Now your prompt is changed!



You can also add colors in your prompt. For example I want to add another color for the command I am typing. To do that you can add in the config file the folowing line: PS1="🌱 `\$(tput sgr0 )`\$(basename \$(pwd))$ `\$(tput setaf 217)`";



`\$(tput sgr0 )` will reset colors

`\$(tput setaf 217)` will set color 217



Save it, restart your terminal and see the result.



# Add a welcome message

For my terminal I want to add a welcome message. Again open and edit your config file. For example I want to see the weather in seoul for only today. To do that u have to add the following command: `curl wttr\.in/seoul?0 #` (see `curl wttr.in/:help` for more information). Save and restart your terminal to see the weather.



Also I like to add a welcome message in the top of my terminal (WARNING, for this command we will use Sudo). First type in `cd /etc`. This command will go to your hidden files. After that type in `sudo pico motd` and type your password. (your password wil not be shown when u are typing it). Then u can add a welcome message. For example what I have: `Welcome Karin!🍃`. After that you can hit button `control` and button `x` to exit the motd. Save it with button `y`, hit `enter` and restart the terminal.


# Result

See here under the result of my terminal! :)

<img width="586" alt="screenshot 2018-02-10 17 03 33" src="https://user-images.githubusercontent.com/32538678/36064003-d4892fb4-0e84-11e8-8f68-d2494254bfcc.png">

