[Cloud Functions 위치  |  Firebase] (https://firebase.google.com/docs/functions/locations)

https://firebase.google.com/docs/functions/manage-functions#modify-region

[google cloud functions - firebase deploy to custom region (eu-central1) - Stack Overflow] (https://stackoverflow.com/questions/43569595/firebase-deploy-to-custom-region-eu-central1)

```
const functions = require('firebase-functions');

exports.webhookEurope = functions
    .region('europe-west1')
    .https.onRequest((req, res) => {
            res.send("Hello");
    });
```
체인메서드로 디플로이 리전 설정하기.

현재 한국 서비스를 위해서는 일본 리전이 가장 좋을듯?

asia-northeast1