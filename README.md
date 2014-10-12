test-custom
===========

We have added this repo as a subtree.

The commands we used were:

git remote add -f test-custom https://github.com/t4k/test-custom.git
git subtree add -P subdir/test-custom test-custom/master
git subtree split -P subdir/test-custom --annotate="(split) " --branch test-custom

(changed README)

git subtree push -P subdir/test-custom test-custom master
