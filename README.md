##Why
This project is all about [eliminating my trivial inconveniences](http://samsaffron.com/archive/2013/05/03/eliminating-my-trivial-inconveniences)

Every time I want to setup a new Vagrant/Berkshelf project, I have to do the following:

1. Create a git repo.
2. Create a Vagrantfile.
3. Remember/lookup the syntax and config options for the above.
4. Create a Berksfile.
5. Remember/lookup the syntax and config options for the above.
6. Create a .gitignore

Well, no longer do I have the burden of performing *all* of these steps each and every time.

##HowTo

```
$ git clone https://github.com/jkburges/vagrant_berkshelf_template.git <fantastic new project>
$ cd <fantastic new project>
$ git remote set-url origin git@github.com:<username>/<fantastic new project>
```

Done!

