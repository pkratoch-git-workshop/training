Git Cheatsheet
==============

Basic commands
--------------

git add     - add file contents to the index
git commit  - record changes to the repository

```
 +-----------+          +---------+             +------------+
 |  working  | -------> | staging | ----------> | repository |
 | directory | git add  |  area   | git commit  |            |
 +-----------+          +---------+             +------------+
```


Viewing changes
---------------

git status  - show the working tree status
git log     - show commit logs
git show    - show various types of objects


Remote repositories
-------------------

git push    - update remote refs along with associated objects
git fetch   - download objects and refs from another repository

