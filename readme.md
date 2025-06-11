git --version
gh --version


gh auth login
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

gh auth logout
gh auth status


git init
git status
git add .
git config --global user.email "physophearak11@gmail.com"
git config --global user.name "physophearak"
git commit -m "microservice-config-server-repo"

gh repo create microservice-config-server-repo-sample --public
git remote add origin https://github.com/physophearak/microservice-config-server-repo-sample
git push -u origin master

git remote show origin


# micorserivce project 
git clone https://github.com/keoKAY/spring-simple-microservices-breakdown.git
git checkout config-server