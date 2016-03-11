# grub2

Forked version of grub2 with ClearOS changes applied

* git clone git+ssh://git@github.com/clearos/grub2.git
* cd grub2
* git checkout c7
* git remote add upstream git://git.centos.org/rpms/grub2.git
* git pull upstream c7
* git checkout clear7
* git merge --no-commit c7
* git commit
