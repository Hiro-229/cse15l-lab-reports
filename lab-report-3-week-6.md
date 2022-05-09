# **Lab Report 3 - Week 6**

## **Streamlining `ssh` Configuration**

Creating and editing the `.ssh/config` file:

![config-image](config.png)

Contents of `.ssh/config`:

![configcontents](config-content.png)

`ssh` command log in using alias/shortform:

![alias-login](alias-login.png)

`scp` copying using an alias:

![scpusingalias](scpalias.png)

## **Setup Github Access from ieng6**

Public key stored on Github:

![KeyOnGitHub](key-github.png)

Content of the Public key stored in your user account:

![KeyOnUser](pubkey-content.png)

Path of Private key on user account:

![PrivKeyOnUser](privatekey-location.png)

Running `git` commands to commit and push a change to Github while logged into ieng6 account:

![GitCommandsOnieng6](comit-from-ieng6.png)   
Disclaimer: I had some trouble in pushing out the changes, thus the "status, add, and commit" section of the command not included in the picture.

Link for resulting commit:
[Link-For-Commit](https://github.com/Hiro-229/markdown-parser/commit/f1ee54801dffa5878867917e0b438cbf5b07f287)

## **Copy whole directories with `scp -r`**

Copying whole markdown-parse directory to ieng6 account:

![SCP1](copying-entire-directory-using-scp-pt1.png)

![SCP2](copying-entire-directory-using-scp-pt2.png)


Logging into ieng6 account and compiling/running the tests:

![RunningTestsOnRemote1](compiling-and-running-ieng6server.png)

![RunningTestOnRemote2](compiling-and-running-ieng6server-pt2.png)


Combining `scp`, `;`, and `ssh` to copy the whole directory and run the tests as one command:

![MultipleCommand1](multiple-command-pt1.png)

![MultipleCommand2](multiple-command-pt2.png)

