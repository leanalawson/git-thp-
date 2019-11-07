Last login: Fri Nov  8 00:10:34 on ttys000

The default interactive shell is now zsh.
To update your account to use zsh, please run `chsh -s /bin/zsh`.
For more details, please visit https://support.apple.com/kb/HT208050.
imac-de-papa:~ papasambaseck$  
imac-de-papa:~ papasambaseck$ echo "bonjour monde"
bonjour monde
imac-de-papa:~ papasambaseck$ pwd
/Users/papasambaseck
imac-de-papa:~ papasambaseck$ ls
Desktop				Pictures
Documents			Public
Downloads			README.md
Library				iCloud Drive (archive)
Movies				iCloud Drive (archive) - 1
Music
imac-de-papa:~ papasambaseck$ ls-a
-bash: ls-a: command not found
imac-de-papa:~ papasambaseck$ ls -a
.				Desktop
..				Documents
.CFUserTextEncoding		Downloads
.DS_Store			Library
.Trash				Movies
.anydesk			Music
.bash_history			Pictures
.bash_sessions			Public
.cups				README.md
.git				iCloud Drive (archive)
.gitconfig			iCloud Drive (archive) - 1
.ssh
imac-de-papa:~ papasambaseck$ ls -l
total 8
drwx------@  11 papasambaseck  staff    352  4 nov 19:54 Desktop
drwx------@  16 papasambaseck  staff    512  7 nov 21:15 Documents
drwx------+ 942 papasambaseck  staff  30144  7 nov 17:25 Downloads
drwx------@  75 papasambaseck  staff   2400 19 oct 21:45 Library
drwx------+   4 papasambaseck  staff    128 19 oct 11:21 Movies
drwx------+   5 papasambaseck  staff    160 19 oct 11:21 Music
drwx------+   9 papasambaseck  staff    288 18 sep  2018 Pictures
drwxr-xr-x+   5 papasambaseck  staff    160  6 déc  2014 Public
-rw-r--r--    1 papasambaseck  staff      8  7 nov 17:26 README.md
drwxr-xr-x    7 papasambaseck  staff    224 26 mai  2017 iCloud Drive (archive)
drwxr-xr-x    6 papasambaseck  staff    192 20 jul  2017 iCloud Drive (archive) - 1
imac-de-papa:~ papasambaseck$ ls -al
total 56
drwxr-xr-x+  23 papasambaseck  staff    736  7 nov 17:26 .
drwxr-xr-x    7 root           admin    224 13 oct 01:15 ..
-r--------    1 papasambaseck  staff      7  5 oct  2016 .CFUserTextEncoding
-rw-r--r--@   1 papasambaseck  staff  10244  5 nov 21:14 .DS_Store
drwx------  232 papasambaseck  staff   7424  7 nov 17:17 .Trash
drwxr-xr-x    6 papasambaseck  staff    192 25 aoû  2017 .anydesk
-rw-------    1 papasambaseck  staff    872  8 nov 00:07 .bash_history
drwx------   27 papasambaseck  staff    864  8 nov 00:11 .bash_sessions
drwx------    3 papasambaseck  staff     96  7 déc  2014 .cups
drwxr-xr-x   13 papasambaseck  staff    416  7 nov 17:26 .git
-rw-r--r--    1 papasambaseck  staff    198  7 nov 17:18 .gitconfig
drwx------    2 papasambaseck  staff     64 10 jan  2015 .ssh
drwx------@  11 papasambaseck  staff    352  4 nov 19:54 Desktop
drwx------@  16 papasambaseck  staff    512  7 nov 21:15 Documents
drwx------+ 942 papasambaseck  staff  30144  7 nov 17:25 Downloads
drwx------@  75 papasambaseck  staff   2400 19 oct 21:45 Library
drwx------+   4 papasambaseck  staff    128 19 oct 11:21 Movies
drwx------+   5 papasambaseck  staff    160 19 oct 11:21 Music
drwx------+   9 papasambaseck  staff    288 18 sep  2018 Pictures
drwxr-xr-x+   5 papasambaseck  staff    160  6 déc  2014 Public
-rw-r--r--    1 papasambaseck  staff      8  7 nov 17:26 README.md
drwxr-xr-x    7 papasambaseck  staff    224 26 mai  2017 iCloud Drive (archive)
drwxr-xr-x    6 papasambaseck  staff    192 20 jul  2017 iCloud Drive (archive) - 1
imac-de-papa:~ papasambaseck$ man ls
imac-de-papa:~ papasambaseck$ 
imac-de-papa:~ papasambaseck$ open index.html
The file /Users/papasambaseck/index.html does not exist.
imac-de-papa:~ papasambaseck$ cd desktop
imac-de-papa:desktop papasambaseck$ ls
Aide et didacticiels.webloc
CV NOUVEAU REANA.exr
CV Ousmane Oct 19.pages
Notice à l’attention des por.textClipping
Nouveau dossier contenant des éléments
Photo le 07-10-2019 à 18.15.jpg
imac-de-papa:desktop papasambaseck$ cd ..
imac-de-papa:~ papasambaseck$  cd Document/Projet
-bash: cd: Document/Projet: No such file or directory
imac-de-papa:~ papasambaseck$ mkdir dossier2
imac-de-papa:~ papasambaseck$ index.html
-bash: index.html: command not found
imac-de-papa:~ papasambaseck$ 
