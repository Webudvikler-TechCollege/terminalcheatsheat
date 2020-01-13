# terminal cheat sheat

Terminal commands

## basic terminal funktioner

---

**CD**

bevæg dig ind i en mappe
bevæger sig ind i mappen

```console
cd Users
```

bevæger sig ind i en mappe uafhængig af hvor du står

```console
cd ~/Documents
```

bevæger sig ud af mappen

```console
cd ..
```

**LS**

LS i terminalen laver en liste af hvad der er i mappen
Tilføj **-la** hvis du os vil se skjulte folders

```console
ls
```

koble flere commands sammen ved at bruge **;**

```console
cd app/site ; code . ; yarn start
```

Åben vs Code i terminalen i den mappe du står i ( windows skal tillade det først igennem vs code )

```console
code .
```

**Mkdir**
Mkdir laver en ny mappe til dig

```console
mkdir nymappe
```

**Touch**
Laver en ny fil

```console
touch index.html
```

**rmdir**
Deleter mappen brug -i hvis du ikke er sikker

```console
rmdir Archives
```

**rm**
rm fjerner filer eller hvis du skal fjerne en mappe med alt indhold brug -rf for at force det

```console
rm -rf nymappe
```

**Nano**
Her vil du kunne redigere i dine filer i terminale

```console
nano index.html
```

**Reset**
Reset restarter din command line

```console
reset
```

## Github commands

---

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

Ændre din Remote

```
$ git remote -v
> origin  git@github.com:USERNAME/REPOSITORY.git (fetch)
> origin  git@github.com:USERNAME/REPOSITORY.git (push)
```

```
$ git remote set-url origin https://github.com/USERNAME/REPOSITORY.git
```

```
$ git remote -v
# Verify new remote URL
> origin  https://github.com/USERNAME/REPOSITORY.git (fetch)
> origin  https://github.com/USERNAME/REPOSITORY.git (push)
```
