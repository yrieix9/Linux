# TD6
## Exercise 1


```
git config --global user.name "Yrieix Simon"
git config --global user.email "yrieixsimon@yahoo.fr"
git config --list
```

## Exercise 2

### 1.
```
git init
```

### 2.
```
ls -a
```

### 3.
```
git status
```

### 4.
```
echo "# Test repository" > readme.md
```

### 5.
```
git status
```

### 6.
```
git add readme.md
```

### 7.
```
git status
```

### 8.
```
git commit -m "Add readme.md file"
```

### 9.
```
git status
```

### 10.
```
git log
```


## Exercise 3

### 1.
```
touch main.py functions.py
```

### 2.
```
git status
```

### 3.
```
git add main.py
```

### 4.
```
git status
```

### 5.
```
git commit -m "Add main.py file"
```

### 6.
```
git status
```

### 7.
```
git add functions.py
git commit -m "Add functions.py file"
```

### 8.
```
git status    
```

### 9.
```
git log
```

## Exercise 4 :

```
touch requirements.txt .gitignore .private
git status
git add .
git status
git commit -m "Add requirements.txt, .gitignore, and .private files"
git status
git log --oneline
```
## Exercise 5 :

```
touch temp.ipynb
git status
nano .gitignore
temp.ipynb
git status
touch temp.aux temp.log
git status
temp*
git status
.private/

```

## Exercise 6 :

```
nano readme.md
git add readme.md
git diff HEAD
git commit -m "Added online description to readme.md"
git log --oneline -n 1 -p
git diff HEAD
nano readme.md
git log --oneline -n 1 -p
```

## Exercise 7 :

### 1.
```
git rm -rf *
```

### 2.

```
git checkout .
```

### 3.
```
cp -R project safeplace
cd safeplace
```

### 4.
```
rm -rf project
cp safeplace project
cd project
```

### 5.
```
git reset readme.md
```

### 6.
```
git commit -am "commit changes"
```

### 7.

Yes, the new commit is visible

### 8. 

```git log --all```

### 9.

```git checkout HEAD~2```

### 11.

```git revert HEAD~1```

### 12. 

The previous changes are still in my root directory

### 13.

Yes, I see the revert commit

### 14. 

```git reset HEAD~ ```





