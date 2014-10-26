rosalynandeston.com
=====================

Rosalyn and Eston's website built on Foundation 5.4.6

This repo has installed wordpress as a git submodule (read more at the [Git Reference Manual](http://git-scm.com/book/en/v2/Git-Tools-Submodules#Cloning-a-Project-with-Submodules) ).  

* To clone this repo and instantiate the submodules, run:
```
git clone --recursive <url-for-this-repo>
```

* To update the wordpress repo you'll want to run the following commands:
```
cd wordpress
git fetch --tags
git checkout 4.0.0
```

Instructions for installing wordpress as a submodule and updating it can be found on [David Winter's website](https://davidwinter.me/install-and-manage-wordpress-with-git/)