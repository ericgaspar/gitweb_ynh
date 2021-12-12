### Adding repositories
```
mkdir /home/yunohost.app/gitweb/my_repository.git
git init --bare /home/yunohost.app/gitweb/my_repository.git/
cd /home/yunohost.app/gitweb/my_repository.git/
touch git-daemon-export-ok
echo "Short project's description" > description
```