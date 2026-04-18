```
#initiate git locally
git init
git add.
git commit -m"Init"

#add remote repo add and push initially commited repo
git remote add origin https://php_<PAT>@gmail.com/<username>/<repo_name>.git
git remote set-url origin https://php_<PAT>@gmail.com/<username>/<repo_name>.git
git config --global user.name "<userName>"
git config --global user.email "<userEmail@gmail.com>"
git push -u origin main

#maven build persion  class and push to origin
./mvnw compile
git add.
git commit -m"added person class"
git push origin master

#add and push README file
git add .
git commit -m"added readme file"
git push origin main
```