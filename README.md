# iterm2applescript
Item2 open specific profile or pass a path argument Apple script

# How to Use:

iterm2git.sh
```
 #!/bin/bash
 /usr/bin/osascript ./iTermScript.scpt $1
 ```
 
`iterm2git.sh ~/User` and the iterm2 will open a new tab change the directory to ~/User or change the directory directly if profile 'GitRepo' exist.

