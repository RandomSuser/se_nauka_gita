#Commands
command
```
Tworzenie od podstaw:
pwd 
mkdir se_nauka_gita
cd se_nauka_gita
pwd
git init
git config –l
# ustaw username z konta serwera github "Suser" 
$ git config --global user.name "Suser" 
# adres email z konta serwera github 
$ git config --global user.email "suser@mail.com" 
# ustawienie domyslnego edytora dla commitów
$ git config --global core.editor "'C:/Program Files/Notepad++/notepad++.exe' -multiInst -notabbar -nosession -noPlugin"

#Utwórz repozytorium nauka_gita , aby umieścić pliki z Twojego lokalnego repozytorium na github.com
git remote add origin https://... # tak jak na github.com 
git remote -v 
git push origin master 
```

```
command
```
Klon:
git clone <https>

Aktualizacja w zdalnych branch:
git push --set-upstream origin wazona
git push --set-upstream origin master

Usuwanie branch localnych:
Git branch –d wazona
Git branch –D wazona   (jesli nie zostało scalone)
```