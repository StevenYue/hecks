# hecks
xxxxx:
> Keeping notes makes live different

##chrome on ubuntu
1. correct ownership
```
chown -R <username>:<username> /home/<username>
```
2. add permission to all folders
```
find /home/<username> -type d -print0 | xargs -0 chmod 775
```
3. if there is "Preference cannot be read" error, check and create 
```
mkdir -p /home/<username>/.config/chrome/Default
```
4. Run mongodb on ubuntu, except for installing (process all of the enternet) 
```
//mongod --port <port num> --dbpath <file path> --journal
mongod --port 10000 --dbpath /var/lib/mongodb --journal //bring up mongo server
mongo --port 10000 //to bring up the mongo shell
```
5. update tmux.conf
```
tmux source-file ~/.tmux.conf
```

6. install gnome flash back
```
sudo apt-get install gnome-session-flashback
```

7. install vim-gnome instread of just vim (enjoy all the simply y and p for yanking and pasting)
```
sudo apt install vim-gnome
```

