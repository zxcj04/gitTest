# Git test
[![Build Status](https://travis-ci.com/zxcj04/gitTest.svg?branch=master)](https://travis-ci.com/zxcj04/gitTest)

[TOC]

## Lab 1

```bash=
brew install git
```

## Lab 2

```bash=
git init

git config --global-user-name "zxcj04"
git config --global-user-email "zxcj04@gmail.com"

git clone https://github.com/zxcj04/gitTest.git

git add .

git commit -m "new a.py"

git push

(adding README on site)

git push
```

![](https://i.imgur.com/sFcyZre.png)


```bash=
git pull
```

## Lab 3

```bash=
git branch newfile

git checkout newfile

git add .
git commit "new file"
git push
```

![](https://i.imgur.com/MCLk9Nq.png)

```bash=

git push --set-upstream origin newfile

(change a.py)

git add a.py
git commit "making conflicts"
git push

git checkout master

(change a.py)

git add a.py
git commit "making conflicts on master branch"
git push

git merge newfile
```

![](https://i.imgur.com/FkOiG2H.png)


```bash=
(changing the right thing)

git add .

git commit -m "fix conflict"

git push
```

(adding issue on github site)

(comment and close it)

![](https://i.imgur.com/3wXyjb0.png)

```bash=
gitk --all
```

![](https://i.imgur.com/WSEGQrK.png)

## Lab4

```bash=

(add cal.py and testCalc.py)
(add .travis.yml)

git add .
git commit "travis"
git push

```


![](https://i.imgur.com/AllmPgq.png)

## Lab4-