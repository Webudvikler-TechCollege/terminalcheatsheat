# terminal cheat sheat

Terminal commands 

## basic terminal funktioner
**CD**

//bevæg dig ind i en mappe
bevæger sig ind i mappen
```console
cd Users
```

bevæger sig ind i en mappe uafhængig af hvor du står 
````console
cd ~/Documents
```
bevæger sig ud af mappen
```console
cd ..
```

**LS**

LS i terminalen laver en liste af hvad der er i mappen
```cosole
ls
``
**Mkdir**
Mkdir laver en ny mappe til dig
````console
mkdir nymappe
```
**Touch**
Laver en ny fil 
```console
touch index.html
```
**Nano**
Her vil du kunne redigere i dine filer i terminale
```console
nano index.html
```



## Github commands

Laver mappen README of skriver indhold i den
```
echo "# terminalcheatsheat" >> README.md
```
Starter en Repo
```
git init
```
Tilføjer din README.md fil 
```
git add README.md
```
Tilføjer Alt
```
git add -A
```
Commiter det du har tilføjet 
```
git commit -m "first commit"
```
Connecter til dit Github Repo
```
git remote add origin https://github.com/user/repoName.git
```
Pusher til Master
```
git push -u origin master 
```
