[Git pull/push 시 Password 물어보지 않도록 설정하기(credential.helper) - HAHWUL :: 하훌](https://www.hahwul.com/2018/08/git-credential-helper.html)

이건 상관 없을수도?

git push 먼저 시도 후 인증 창 뜨면 로그인 수행
git commit 시도 시
```
*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.
```
에러 발생
--global 옵션 제외하여 해당 레파지토리만 설정 저장