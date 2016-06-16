# Git
This is personal note for me. 

I keep forgetting setting up git and command. 

### git config --list
to view config file

  
### git config --global user.name "YOUR_NAME"
to add username

  
### git config --global user.email "YOUR_EMAIL_ADDRESS"
to add email 

### ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
generating ssh key. without ssh, you cannot clone git project. click enter then key in password & retype password. 

### Enabled ssh-agent
eval "$(ssh-agent -s)" ===== git-bash command
eval $(ssh-agent -s) ==== other command

### ssh-add ~/.ssh/id_rsa
Add SSH key to the ssh-agent.

### git clone GIT_URL
to clone a project in


### git remote -v
to view origin


### git push origin master
to push to github.com (must set origin first)


## to Commit
1) git add . 

2) git commit -m "Message"
