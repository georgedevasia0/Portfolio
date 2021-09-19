***firebase login***
georgedevasia987@gmail.com


***In firebase.json file***

{
  "hosting": {
    "target": "george",
    "public": "public",
    ...
  }
}


***Set the target***

(firebase target:apply hosting *target-in-firebase.json-file* *website-name*)
firebase target:apply hosting george george-devasia

***deploy the project***

firebase deploy --only hosting:george