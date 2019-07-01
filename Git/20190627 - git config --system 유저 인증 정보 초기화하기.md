```
$ git config --system --unset credential.helper

error: could not lock config file C:/Program Files/Git/mingw64/etc/gitconfig: Permission deniedconfig: Permission denied
```

다른 Github계정의 저장소에 접근하려 했더니 권한이 없음
Git 계정 설정을 바꿔주었으나 VS Code의 bash 터미널이나 Source controller에서는 시스템 설정을 따르고 있었음
시스템 설정을 초기화 하려했지만 권한 없음 에러 발생.

Windows 환경의 경우 Git bash 등 터미널을 관리자 권한으로 실행하여 다시 시도하여 해결

그 외 유용할 것 같은, 연관된 git 설정 명령어
https://help.github.com/en/articles/setting-your-username-in-git
https://git-scm.com/book/ko/v1/Git%EB%A7%9E%EC%B6%A4-Git-%EC%84%A4%EC%A0%95%ED%95%98%EA%B8%B0


비슷한 사례의 자세한 설명 포스트
https://meaownworld.tistory.com/78