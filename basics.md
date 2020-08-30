# Git Basics
- Used to learn git basics

### Basic Commands
- version check ``` git --version ```
- status check ``` git status ```

## Initializing a folder to git
- navigate to folder and use ``` git init ```

- To check updated and untracked files command ```git status```
- To add  modified and untracked files to version control ``` git add .``` or ``` git add <<filename>> ```
- To push the changes to local Git repository
```git commit -m <<commit message all in small>>```
- To push the changes to respository ```git push```

> Alternatively we can use any IDE like visual code or webstorm or intellijIdea or eclipse
## How to delete docs through IDE ##
Intially delete the documents in local respository
* Navigate to sourcde control tab and type your commit message  and click on tick mark and let the timer complete
> By following the above step changes done will be seen in local respository
* Now come down and click on Synchronizer changes option and let the timer complete
> Now changes will be available in remote respository
## To get a remote respository locally
* Create a folder in your local machine.
* Go to respective folder through termnal and type``` git clone <<Paste the URL>>```
