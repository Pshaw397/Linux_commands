# Using SSH keys for GitHub

## Create an SSH key pair
Navigate to: C:\Users\[Username] in the terminal
- Create a directory to store the SSH key: `mkdir .ssh`
- Move into this new directory: `cd ~/.ssh`
- Create an SSH Key: `ssh-keygen -t rsa -b 4096 -C [example@email.com]`
- View the created key: `cat id_rsa.pub`
- Select the displayed key and use `CTRL + C` to copy

## Connect SSH key to your GitHub
- Login to your GitHub account on the GitHub webiste
- Click your profile image and the top right of the screen
- From the drop down menu, select: `setting`
- From the seleciton bar on the left, select: `SSH and GPG keys`
- Click the `New SSH Key` button
- Paste your copied key into the `Key` input box
- Click `Add SSH Key`
