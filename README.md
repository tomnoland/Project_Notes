# Project_Notes
This is a place to consolidate all my project notes.

---

[Template for new projects](https://github.com/tomnoland/New-Project-Template/generate)

[Hub](https://hub.github.com/)

[Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

```sh
Example_of_shell_code_block
```
---

```sh
cd /Volumes/Data/Projects
```
```sh
cd ~
```

---

```sh
REPO_NAME=XXX
```

```sh
PROJECT_DIR=/Volumes/Data/Projects && \
cd $PROJECT_DIR && \
git clone https://github.com/tomnoland/$REPO_NAME && \
cd $REPO_NAME
```

---

osascript -e 'tell application "Terminal" to set bounds of front window to {2, 579, 957, 1126}' &&\

osascript -e 'tell application "Finder" to set bounds of front window to {962, 579, 1917, 1126}' &&\

osascript -e 'tell application "Atom" to set bounds of front window to {962, 26, 1917, 573}' &&\

osascript -e 'tell application "Chrome" to set bounds of front window to {2, 26, 957, 573}'

---

hub delete -y tomnoland/$REPO_NAME

[How to create an encrypted directory in windows](https://www.tomsguide.com/us/encrypt-files-windows,news-18314.html)

[How to create an encrypted directory in Mac](https://www.howtogeek.com/183826/how-to-create-an-encrypted-file-container-disk-image-on-a-mac/)

[Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

---

git add README.md

git commit -m "Changed README.md file"

git push origin master

---

git pull origin master

---

/usr/bin/open -a /System/Library/CoreServices/Finder.app .

"/Applications/NetBeans/Apache NetBeans 11.1.app/Contents/Resources/NetBeans/bin/netbeans" README.md

---

docker-compose down

docker rm -f $(docker ps -a -q)

docker volume rm $(docker volume ls -q)

[How To Remove Docker Images, Containers, and Volumes](https://www.digitalocean.com/community/tutorials/how-to-remove-docker-images-containers-and-volumes)










