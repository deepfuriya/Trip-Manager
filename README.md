
# Trip Manager

The app provides trip management features using Google location services API and Google Firestore

![New Project (2)](https://github.com/deepfuriya/Trip-Manager/assets/79759607/fac4e0d1-c71c-4684-bf1c-9365dd1caabf)



## Features

- Secure Login and Signup using Firebase Authentication 
- Accurate Location Tracking using GPS
- Data stored securely over Google Firebase Cloud
- Live Maps Preview of Trip Details


## API Reference

#### Get [Google Maps API Key]((https://console.cloud.google.com/)) and replace in the manifest file 


```
  Android -> app/manifests/AndroidManifest.xml
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `${MAPS_API_KEY}` | `string` | **Required**. Your API key |

#### Get google-services.json from [Google Firebase](https://console.firebase.google.com/)  and paste it in the below path

```
   Project -> app
```

| File      | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `google-services.json` | `json` | **Required**. Firebase config file |




## Documentation

- [Google Firebase Authentication](https://firebase.google.com/docs/auth/android/password-auth?authuser=0#java_3)
- [Google Firebase Cloud](https://firebase.google.com/docs/firestore/quickstart?authuser=0#java)
- [Google Maps for Android](https://developers.google.com/maps/documentation/android-sdk)


