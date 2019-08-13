# NEMV 따라하기
[모던웹(NEMV) 제작 강좌 -] (https://fkkmemi.github.io/nemv/)
해당 강좌 내용을 바탕으로 View 영역만 React/React native 써서 사이트 구축하기

## NHN Toast + MongoDB Atlas 활용

MongoDB Atlas 무료 생성시 AWS/GCP/Azure 선택 가능
추후 확장 고려하여 AWS 선택 -> 가성비(표기된 서버 사양/가격)

AWS 리젼 싱가폴/뭄바이 중 싱가폴 선택
> [AWS Direct Connect Gateway와 일반 인터넷 망의 속도 비교 테스트 결과 - BESPIN GLOBAL] (https://www.bespinglobal.com/aws-direct-connect-gateway-speed-test/)

## 빠른 개발을 위한 React-native-element 적용
왜?
Write once, run everywhere 를 실현하기 위해

### React native 설치
[Getting Started · React Native] (https://facebook.github.io/react-native/docs/getting-started)
RN CLI 기반, chocolatey 설치 후 python2 설치

Chocolatey?
윈도우 기반 도커 같은 기능

### 기타 참고
[Expo Web(React Native for web) 튜토리얼 | Expo Web(React Native for web) 튜토리얼] (https://ui.toast.com/weekly-pick/ko_20190624/)

Expo Web의 경우 (현재 SDK34) 아직 베타, 프로덕션 지원 안함.
- React-native-web 베이스로 개발
- React-native 호환 버전 차이 존재 (0.55 : 0.59)
  - React hooks 사용 여부 차이?
    - 별도 모듈로 적용 가능, 추후 지원 가능성

Expo에서 지원하는 웹 기능 리스트
[web-examples/FEATURES.md at master · expo/web-examples] (https://github.com/expo/web-examples/blob/master/docs/FEATURES.md)
react-native-web의 컴포넌트 리스트
[Storybook] (https://necolas.github.io/react-native-web/storybook/?selectedKind=Components&selectedStory=ActivityIndicator&full=0&addons=0&stories=1&panelRight=0)


### CRNWA 모듈 설치 및 프로젝트 구성하기
[orYoffe/create-react-native-web-app: React Native Web CLI] (https://github.com/orYoffe/create-react-native-web-app)

최초 프로젝트 설치 후 rnw 모듈 버전 수정함 (0.11.4 > 0.11.5)
이 후 웹/안드로이드 테스트 빌드 정상 작동 확인


React-native-element 기반, React Native Web 활용하기
[react-native-training/react-native-elements: Cross Platform React Native UI Toolkit] (https://github.com/react-native-training/react-native-elements#react-native-web-support)




