## NOTE (Config Repository )

this is the sample git repo for the spring config server 


* Git scm : 
* Git Repo ( Github , Gitlab , Bitbucket )



```bash 
sudo apt install gh -y 
sudo snap install gh 

git --version 
gh --version 

gh auth login 
gh auth logout
gh auth status 



# Working with pushing code to git 
git init 
git add . 
git commit -m "message"

git config --global user.name ""
git config --global user.email ""

gh repo create microservice-config-repo-sample --public
# this will re turn the url 
git remote add origin url 
git push -u origin master 

git remote -v
git remote show origin 


# microservice rpoject 
git checkout config-server
```

## keep it as private 

* To run the shellscript for autopush 
```bash 
bash autopush.sh "my commit message" 
```