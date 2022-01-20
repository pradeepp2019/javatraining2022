# javatraining2022
java training 2022
Lecture Notes
Please follow the instruction to prepare yourself for the course.

1. Create Folder Structure
c:\>md current-training-name
c:\>md current-training-name\trainers-work
c:\>md current-training-name\my-work
Folder Structure should be something like this
[c drive]
    [current-training-name]
        [trainers-work]
            
        [my-work]
        
2. Clone Trainer's Repository to trainers-work folder
c:\react-native-traing\trainers-work> git clone https://github.com/vivekduttamishra/trainer-repo-name .
Notes
Note the command must be executed in trainers-work folder
Note the trailing dot (.) after the url and a blank space
If git command fails, download and install git client from
https://gitforwindows.org/
https://git-scm.com/downloads
3. Copy the following files from trainers-work to my-work folder
c:\current-training-name\trainers-work> copy git-*.* ..\my-work

c:\current-training-name\trainers-work> cd ..\my-work
c:\current-training-name\my-work> git-ignore
c:\current-training-name\my-work> git-ignore-nodejs
4. Create Your own Github repository for the training
Note:
You may need to create an account on github.com
Assuming that your url is https://github.com/participant01/react-native.git
5. Initalize your repository in my-work folder
c:\current-training-name\my-work>git-init your-github-repo-url
6. Share the link of your repository in Partcipant Information Form that would be shared during the training.
Part 2
To download trainer-work whenever required
c:\current-training-name\trainers-work>git pull
Note:
Never change anything in this folder.
If you need you can copy the content from this folder to your folder
To upload your assignments
Create your own examples in my-work folder
to upload your content
c:\current-training-name\my-work>git-update remark-for-this-update
