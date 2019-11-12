Git global setup

git config --global user.name "Александр"
git config --global user.email "pasik-napas@mail.ru"
***
Create a new repository

git clone https://gitlab.roskomsvoboda.org/web/wp/chcop.git
cd chcop
touch README.md
git add README.md
git commit -m "add README"
***
Push an existing folder

cd existing_folder
git init
git remote add origin https://gitlab.roskomsvoboda.org/web/wp/chcop.git
git add .
git commit -m "Initial commit"
***
Push an existing Git repository

cd existing_repo
git remote rename origin old-origin
git remote add origin https://gitlab.roskomsvoboda.org/web/wp/chcop.git

