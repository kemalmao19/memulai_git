# Git
## Initialization
```git init```

## Staging
```git add <file>```

## Staging
```git commint -m "<your message>"```
pemberian messege bergantung scope & section.
section => macam2 seperti chore, fix, style, feat.
for example:
```git commit -m "chore(codebase): <message>"```

```git commit -m "feat(auth): adding login UI"```

```git commit -m "bug(auth): forgot password feature fixed"```

## melihat list commit
```git log```

## callback 
```git reset --hard <hash commit>```

## cancel changes
```git checkout (file)```

# create branch
Branch adalah percabangan dari repositori Git. Branch digunakan untuk mengembangkan fitur baru tanpa mengganggu branch utama.
```git branch <branch name>```
## change branch 

```git checkout <branch name>```
## merge branch to main branch

```git merge <branch name>```
## delete branch

```git branch -d <branch name>```

# delete commit 
```git reset --hard <hash commit>```

# gitignore
an exception

# git conflicts
Git conflicts adalah konflik yang terjadi ketika dua atau lebih orang mengubah file yang sama. Konflik ini terjadi karena Git tidak tahu perubahan mana yang harus digunakan.
## create conflict
Untuk membuat konflik, buat branch baru, lalu ubah file yang sama di branch tersebut.

```git checkout -b fitur1```

```git checkout -b fitur2```

## handle conflict 
Untuk mengatasi konflik, kita perlu memilih perubahan mana yang akan digunakan. Setelah itu, kita perlu membuat commit.
```
git add index.html
git commit -m "Pesan commit"
```

# Git remote
Git remote adalah repositori Git yang berada di tempat lain. Git remote digunakan untuk menyimpan repositori Git di tempat lain.
## create remote
```git remote add origin```
## commit to git remote
Setelah Git remote dibuat, kita dapat mengirim commit ke Git remote tersebut. Untuk mengirim commit ke Git remote
```git push origin master```
## Mengambil Commit dari Git Remote
Setelah Git remote dibuat, kita dapat mengambil commit dari Git remote tersebut. Untuk mengambil commit dari Git remote
```git pull origin master```