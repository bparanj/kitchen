1. echo 'rvm use 1.9.3' > .rvmrc
   echo 'rvm gemset use kitchen' >> .rvmrc

2.
$ gem install librarian
$ echo cookbooks >> .gitignore
$ echo tmp >> .gitignore
$ librarian-chef init

3. Add cookbooks needed to Cheffile
4. Run : librarian-chef install to download the specified cookbooks
5. gem install vagrant
6. vagrant init
7. vagrant up

To Create the VM from scratch

$ git clone <your_git_repository_url>
$ cd <repository_name>
$ librarian-chef install
$ vagrant up