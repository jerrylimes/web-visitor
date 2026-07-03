# Jerry Li's Website

Note to self: to update `layout.html` across different repositories, run
```
git subtree pull \     
--prefix=common \
git@github.com:jerrylimes/website-common.git \
main \
--squash
```

To add a subtree, run
```
git subtree add \ 
--prefix=common \ 
git@github.com:jerrylimes/website-common.git \ 
main \ 
--squash
```

If changes are made to the local `common/` folder, run
```
git subtree push \
--prefix=common \
git@github.com:jerrylimes/website-common.git \
main
```