# hello

```sh
# https://iphysresearch.github.io/blog/post/programing/git/git_submodule/

git submodule add <url> <repo_name>

git submodule update --init --recursive
```


```bash
git clone https://github.com/zhubinqiang-intel/hello
cd hello
git checkout origin/main
git pull origin main
git checkout -b local_dev
# modify your code ...

git add .
git commit
dt pr create --base=main
```
