# Upload and Download Steps
## Step0: the first time
```
  git init
  git clone https://github.com/STICKER1998/Digital_Tools_for_Finance_Project.git
```

## Step1: Download the Lastest Version (Warning: not "origin master")
```
  git pull origin version_active
```
## Step2: Change the files in the folder `Homework/`: You can add/delete/change the folders or files
```
  git add .
  git commit -m "(#WHAT YOU DID: eg: Upload Homework 2)"
  git pull origin version_active
```

## Step3: Push it back
```
  git push origin version_active
```

## Warning: 
1) Don't pull/push "origin master";
2) Don't merge the branch "version_active" to the master;
3) Don't forget to "git add <file>" / "git add ." after you delete any file;
4) If you have any data (.csv) / code (.py) .etc , please upload it to the corresponding folder;
5) The branch "version_protect" would be updated once everyday in order to prevent some special circumstance;
