# hello-world
In the "Description" box, type a short description.
In the editor, write a bit about yourself. Try using different Markdown elements.
K:\exp>git config --global http.proxy http://127.0.0.1:7890

K:\exp>git config --global -l
user.name=Walter Madelim
user.email=3468274604@qq.com
credential.helperselector.selected=manager
http.proxy=http://127.0.0.1:7890

K:\exp>git config --global --unset http.proxy

K:\exp>git config --global -l
user.name=Walter Madelim
user.email=3468274604@qq.com
credential.helperselector.selected=manager

To push a local repo to github/a_repo, do: (firstly make sure that a_repo exists on github)
git remote add origin https://github.com/WalterMadelim/a_repo
git push -u origin master
