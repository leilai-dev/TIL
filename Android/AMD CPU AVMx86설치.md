[WHPX Problem - Android Emulator - Developer Community] (https://developercommunity.visualstudio.com/content/problem/528337/whpx-problem-android-emulator.html)

WIP 189XX 버전에서 해결되었다는 간증 확인

[Getting started with Windows 10 Insider Preview Builds - Windows Insider Program | Microsoft Docs] (https://docs.microsoft.com/en-us/windows-insider/at-home/get-started#supported-languages)

설치하자

[amd ryzen - Can't activate hardware acceleration using windows 10 family and amd processor - Super User] (https://superuser.com/questions/1401671/cant-activate-hardware-acceleration-using-windows-10-family-and-amd-processor)

하이퍼-v 키면 e495는 에러 발생 못써먹겠음
어쨌든 프리뷰버전에서 현재 하이퍼-v키고 사용중

그러나 하이퍼-v 실행 중일 때 일부 가상화 앱들이 오류 발생
VMWare, Memu player 등
["VMware Workstation and Device/Credential Guard are not compatible" error in VMware Workstation on Windows 10 host (2146361)] (https://kb.vmware.com/s/article/2146361)
[Windows Defender Credential Guard 관리(Windows 10) | Microsoft Docs] (https://docs.microsoft.com/ko-kr/windows/security/identity-protection/credential-guard/credential-guard-manage)

## Hyper-v 끄기 / 켜기
[Hyper-V 와 vmware 의 공존( 하나의 PC에서 두가지 동시 사용) :: 잡스러운 것의 집합] (https://crazyits.tistory.com/entry/Hyper-V-와-vmware-의-공존-하나의-PC에서-두가지-동시-사용)

### 끄기
```
bcdedit /set hypervisorlaunchtype off
```
### 켜기
```
bcdedit /set hypervisorlaunchtype auto
```