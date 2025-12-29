# Linux Basics (Sequence-wise Cheat Sheet)

## 1) Location
- pwd
- ls, ls -l, ls -a, ls -al

## 2) Navigation
- cd folder
- cd ..
- cd ~
- cd -

## 3) Create
- mkdir folder
- mkdir -p a/b/c
- touch file.txt
- nano file.txt
- cat > file.txt

## 4) Read
- cat file.txt
- less file.txt
- more file.txt
- head file.txt
- tail file.txt
- tail -f file.txt

## 5) Move/Copy
- mv old new
- cp a b
- cp -r folder dest/

## 6) Delete
- rm file.txt
- rmdir folder
- rm -r folder
- rm -rf folder

## 7) Search/Info
- pipe (|)
- grep "word" file
- cat file | grep "word"
- find . -name "file"
- file file.txt
- stat file.txt

## 8) Help/History/Control
- man command
- history
- history | tail -n 20
- clear
- exit
