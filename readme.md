To solve this error
```
> student@0.1.0 start
> react-scripts start

sh: 1: react-scripts: not found
```
Use this

```npm install react-scripts --save-dev```



Fetch code from the git for Update

See this video ----> GitHub Forks and Pull Requests | Step by Step
    ```https://www.youtube.com/watch?v=a_FLqX3vGR4```
                Or

    git status                                                                        //Only for first time
    git remote add upstream https://github.com/ma-anand/Student-Management-System     //Only for first time
    git remote -v                                                                     //Only for first time

    
    git fetch upstream
    git checkout master
    git merge upstream/master
