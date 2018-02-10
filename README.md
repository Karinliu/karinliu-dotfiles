# Make alias
alias .bashrc="nano .bashrc"        open hiddenfile .bashrc

# change prompt
1. Go to home directory: cd ~
2. Type: ls -a
3. Find file .bashrc
4. Edit .bashrc: open -a TextEdit .bashrc
5. Modify prompt with the following command: PS1="🌱 \$(basename \$(pwd))$ ";
6. Save it and restart terminal.
7. Prompt is changed! :)

8. Adding colors into command
9. Open .bashrc
10. Add: PS1="🌱 \$(tput sgr0 )\$(basename \$(pwd))$ \$(tput setaf 217)";
    tput sgr0 = reset colors
    tput setaf = set color 217

# Add a welcome message
1. Again edit the .bashrc file.
2. Under the command "PS1.." type the following command: curl wttr\.in/seoul?0 #
3. Save it and restart terminal to see the weather.

4. Add above weather message a welcome message
5. Go to cd /etc (go to hidden files)
6. Type command: sudo pico motd and type in your password.
7. Type welcome message. (welcome Karin!🍃)
8. Hit button “control” and button “x” to exit the motd.
9. Hit button "y" (save).
10. Hit enter and restart your terminal.
11. Welcome message it added! :)

# Result
<img width="584" alt="screenshot 2018-02-09 18 17 20" src="https://user-images.githubusercontent.com/32538678/36062777-45a08b00-0e73-11e8-9d0b-f9599d0f4351.png">