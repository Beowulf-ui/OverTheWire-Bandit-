# Bandit game walkthrough
## level 0 - straightfoward its just sshing to overthewire.labs.org with the user and password being bandit0 ssh on port 2220 ssh bandit0@bandit.overthewire.labs.org -p 2220 <img width="1102" height="506" alt="image" src="https://github.com/user-attachments/assets/ce799705-45c3-415b-af82-663118d897b3" />
## level 1 - We now have to login into the server with user bandit1. We've been told the password is stored in the readme file. We use "ls" to list the files to find the readme and then "cat" to read it. We then use the outputed password to login in with bandit1  "ls" "cat readme" ssh bandit1@bandit.labs.overthewire.org -p 2220

