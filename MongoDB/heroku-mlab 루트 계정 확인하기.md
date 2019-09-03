[heroku - Connecting to MongoDB database on mLab fails authentication - Stack Overflow] (https://stackoverflow.com/questions/36082423/connecting-to-mongodb-database-on-mlab-fails-authentication)
```
heroku config | grep MONGODB_URI
```
heroku 브랜치로 이동해서 확인하기.

### 문제 발생
heroku-mlab 애드온 설치 후 기본 .env 설정에 따른 MONGODB_URI의 비밀번호가 파싱이 제대로 되지 않음

특수문자에 이스케이프 적용이 안되어서 발생

현재는 임시로 파일에 하드코딩하여 encodedURIComponent 적용

[node.js - Can not connect to the databaseMongoParseError: Unescaped at-sign in authority section - Stack Overflow] (https://stackoverflow.com/questions/52632830/can-not-connect-to-the-databasemongoparseerror-unescaped-at-sign-in-authority-s)

.env 환경변수에 적용하여 정보 노출을 줄이는게 좋을 듯