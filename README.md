# test3
# This file was created on github.

# The github repository was then cloned to the laptop:
laptop:/gitroot$ git clone --mirror https://github.com/ad0es/test3

# The laptop repository was then cloned top the development box:
devbox:~/git$ git clone smp@laptop:/gitroot/test3.git
Cloning into 'test3'...
remote: Counting objects: 3, done.        
remote: Total 3 (delta 0), reused 0 (delta 0)        
Receiving objects: 100% (3/3), done.
Checking connectivity... done.

# I will next commit this file and push it back to the laptop.
# After that I will take the laptop back to the hotspot and push back to github.
# Those two steps will bew recorded ion a followup file.
