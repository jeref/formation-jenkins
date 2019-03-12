# test si connecté :
 ??ssh -T git@github.com
Hi jeref! You've successfully authenticated, but GitHub does not provide shell access.
# génération d'une clé SSH
ssh-keygen -t rsa -b 4096 -C "orsys-jenkins"
cat /c/Users/orsys/.ssh/id_rsa.pub
#ajout clé dans  github
git remote show origin
git remote rename origin old
git remote add git@github.com:jeref/formation-jenkins.git
????git push origin master


