SSH 접속하여 운영환경을 구성하기 위한 리눅스 패키지 설치하기

기본 설정되어 있는 계정명은 ubuntu
```
sudo apt-get update
...
```

## Ubuntu
### Nodejs 설치
[distributions/README.md at master · nodesource/distributions] (https://github.com/nodesource/distributions/blob/master/README.md#debian-and-ubuntu-based-distributions)
패키지 매니저를 통해 쉽게 설치 가능

### yarn 설치
[Installation | Yarn] (https://yarnpkg.com/lang/en/docs/install/#debian-stable)

## Git Repo
### build용 브랜치 새로 파기
.gitignore에서 RN에 해당하는 패키지 폴더를 지정하기

근데 그래도 웹이 돌아가려나?? 안될 것 같다...

### 특정 branch만 git clone 하기
```
git clone -b <branchName> --single-branch <RepoURL>
```
git clone -b build --single-branch https://github.com/leilai-dev/InstaRedManager.git

git clone 후
```
yarn workspace mobile install
```
등 각 packages의 모듈 설치. 근데 하나만 하면 다 설치되는듯

## MongoDB Atlas
DB 접근 권한 설정 및 네트워크 설정