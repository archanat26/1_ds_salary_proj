#  1_ds_salary_proj
cd G:/Archana/Technology/Git/DS/ML/LocalRepo/
git config --global user.email "archana.tamboli@gmail.com"
git config --global user.name "archanat26"


mkdir 1_ds_salary_proj
cd 1_ds_salary_proj/
echo "#  1_ds_salary_proj" >> README.md

git init

## To connect Git Bash with GItHub
git remote add origin https://github.com/archanat26/1_ds_salary_proj.git

## Command to check if we have Push and Pull Access
git remote -v

## Command to add all the files on Local Machine on GitHub
git add .

## Command to Commit all the files added
git commit -m "1. Added Data File"


## Command to Push all the files added
git push origin master
 
