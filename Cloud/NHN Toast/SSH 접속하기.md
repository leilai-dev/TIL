[개요 - NHN TOAST 사용자 가이드] (https://docs.toast.com/ko/Compute/Instance/ko/overview/#linux)

Windows의 경우 Putty 설치하여 SSH 클라이언트 연결 인증키 설정하기

혹은 PowerShell 활용하여 접속하기

```
choco install openssh
```

ssh -i my_private_key.pem ubuntu@<인스턴스의 IP>

[TIL/SSH-로그인-접속-시-퍼미션-문제-UNPROTECTED-PRIVATE-KEY-FILE.md at master · rangyu/TIL] (https://github.com/rangyu/TIL/blob/master/ubuntu/SSH-로그인-접속-시-퍼미션-문제-UNPROTECTED-PRIVATE-KEY-FILE.md)

.pem 개인키의 파일 권한 설정 필요 위 링크는 우분투 환경에서 chmod 활용

[PowerShell 스크립팅 | Microsoft Docs] (https://docs.microsoft.com/ko-kr/powershell/scripting/overview?view=powershell-6)

PowerShell에 chmod에 대응하는 명령어가 있는지 찾아봤지만 안보임

윈도우 환경에서 그냥 권한 설정 변경함.

chmod 777 -> r = 4, w = 2, x = 1 기억하자

