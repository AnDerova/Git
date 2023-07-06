
## Homework Git, part 3

**1. Create the 7 new branches on your local repository.**
```
$ git clone git@github.com:AnDerova/GitHub_Homework.git
$ git touch README.md
$ git add README.md && git commit -m 'Create README.md'
$ git branch Postman
$ git branch Jmeter
$ git branch CheckLists
$ git branch Bug_Reports
$ git branch SQL
$ git branch Charles
$ git branch Mobile_testing

$ git branch
  Bug_Reports
  Charles
  CheckLists
  Jmeter
  Mobile_testing
  Postman
  SQL
* main
```
**2. Push all branches to your remote repository on GitHub.**
```
 $ git push -u origin Bug_Reports
 $ git push -u origin Charles
 $ git push -u origin CheckLists
 $ git push -u origin Jmeter
 $ git push -u origin Mobile_testing
 $ git push -u origin Postman
 $ git push -u origin SQL
```
**3. Create a new file with the structure of a bug report on branch Bug_Reports into your local repository.**
```
$ git checkout Bug_Reports

$ touch Bug.txt

$ vim Bug.txt

$ cat Bug.txt
ID
Severity
Title
Environment
Precondition
Steps
Expected results
Actual results
Attachment
```

**4. Push a file to your remote repository on GitHub.**
```
$ git add Bug.txt && git commit -m 'Create Bug.txt' && git push

```
**5. Merge the Bug_Reports branch into Main.**
```
$ git checkout main
$ git merge Bug_Reports
```
**6. Push the Main branch to your remote repository on GitHub.**
```
$ git push
```
**7. Create a new file with the check list's structure on branch CheckLists in your local repository.**
```
$ git checkout CheckLists
$ touch Checklist.txt
$ vim Checklist.txt

$ cat Checklist.txt
ID
Title
Environment
Precondition
Inputs
Steps
Exp.resuls
Act.results
Status
Attachment
```
**8. Push a file to your remote repository on GitHub.**

```
$ git add . && git commit -m 'Create Checklist.txt' && git push
```
**9. On a remote repository, make a Pull Request of the CheckLists branch in main**

**10. Keep your local repository in sync with your remote repository.**
```
$ git pull

```


