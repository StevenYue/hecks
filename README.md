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
