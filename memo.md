# Memo

## open vs code
    1. open terminal 
    2. go to directory including target file.
    3. code .

## TEX
### tex compile by vscode
    1. edit tex file
    2. select TEX in the left.
![](picture/tex1.png)

    3. click Recipe:pLateX (only 1 time)
    4. click View in external viewer (only 1 time)
    5. after 4, autmatically compiled and synced pdf after edit.
![](picture/tex2.png)

### bib tex
    1. make xxxx.bib file in the same directory as tex file.
    2. in bibfile, each reference is written as 
        @xxx{ } 
    3. write key name in the first line. 
![](picture/bib.png)

    4. write following 2 line in tex file.
    (e.g. ref.bib)
![](picture/bib2.png)

## Git, GitHub
### basic
    - git: version manger in local
    - GitHub: remote version manger in web brouser

### Setting
    1. Make repository in GitHub
![](picture/newrepo.png)

    2. connect remote repository to local repository
        git clone "url of remote repository"
![](picture/clone.png)
![](picture/clonecmd.png)

### version mange
    after file edit,
    1. click git mark: list of changed files
    2. check diff by this file mark: view diff from previous commit
    3. click + mark: add change
    4. write message and alt + enter: local commit (update local repository).
    4. remote commit: update remote repository
        from terminal: "git push"
![](picture/gitvscode.png)
![](picture/push.png)

## screen shot
- command + shift + 4: drug drop
- command + shift + 5: rectangle area
- add memo to picture: after save, can edit.