# Tutorial

## What is Git?
Git is a version control system where you can track changes to your files. Every file can have a version history, and you can view these different versions at any point in time. These files are kept in a central repository, or folder, in the cloud (in this case, GitHub). This means that multiple people can work on the same folder at the same time on their own devices (i.e. they have a local copy on their machine), and upload their changes once they're done. 

## Basics of Git
The 3 main concepts you need to know are "committing", "pushing", and "pulling".

### Committing
A "commit" is an individual change to a file (or set of files). Git will keep track of all commits so that you can go back to and view any commit in the past (i.e. viewing a particular version in the past). The process "committing" means that you are done with some changes to a file(s) and want to save that version before making any more changes. This is accompanied with the commit message, which is a short description of what those changes are. You should commit your changes regularly, especially when working with other people. You don't want to be making a big change over multiple days, only to find that it's not compatible with what has been changed over those days. To commit a change on GitHub desktop, select the files you want to be committed, write a commit message, and click commit. The "description" text box in GitHub Desktop is there for if you need to write any additional information to accompany the commit message. This isn't usually needed unless your commit is especially complex.

<img width="954" alt="Screen Shot 2022-09-16 at 3 10 22 PM" src="https://user-images.githubusercontent.com/30307624/190548771-51df0a0f-28ec-4aa6-9d2e-2a4fa62b3d80.png">

### Pushing
"Pushing" basically means uploading your commits to the central repository. When you commit changes, those commits still live on your computer. When you're ready, you can push those commits to the central repository so that others can see your changes and download them into their own local copies of the repository. To do this, click "Push origin" and it should upload. You should push your changes at least by the end of the day so that everyone has access to your changes quickly.

<img width="956" alt="Screen Shot 2022-09-16 at 3 14 33 PM" src="https://user-images.githubusercontent.com/30307624/190549765-d87f00ff-ac52-4b2e-8754-575fbd60eb2e.png">

### Pulling
"Pulling" is when you download changes from the central repository into your own local copy of the repository. This is useful when other people have updated files and have uploaded their changes, but you don't have those changes yet in your copy. To pull from a repository, just click the "Fetch Origin" button in GitHub Desktop. It's good to do this periodically so that you always have the most up to date changes. You should pull before you commit any changes just in case those changes conflict with what's already been uploaded.

<img width="960" alt="Screen Shot 2022-09-16 at 3 00 20 PM" src="https://user-images.githubusercontent.com/30307624/190547552-460fd3c4-23df-4302-93f2-dc48931c6876.png">
