+++
title = "Create a SSH key"
chapter = false
weight = 2
+++

1. Create a ssh key and add it to your GitHub account.
```
ssh-keygen
```
  - Press `enter` 4 times to take the default choices

1. copy the public key to your clipboard
```
cat ~/.ssh/id_rsa.pub
```
  - Go to https://github.com/settings/ssh/new and paste your key in the box marked "key"

1. Type `Workshop Cloud9` in the title, and select **Add SSH key**
  - You should be prompted to confirm your password