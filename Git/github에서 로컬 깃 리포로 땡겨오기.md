pull 받기 위한 폴더에서
```
git init

git remote add origin https://github.com/leilai-dev/repositoryName.git

git pull origin master
```
성공적

그러나 push 할 때도 항상 origin master 브랜치명을 지정해줘야 한다.

git pull, git push 추가 옵션 없이 사용을 위해

```
$ git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master
```
--set-upstream 적용