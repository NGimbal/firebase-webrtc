# firebase-webrtc
Automerge + Firebase + simplepeer

## Firebase Realtime Database Rules:
```javascript
{
  "rules": {
    "peerID": {
    // Allow the request if the condition for each method is true.
      ".read": true,
      ".write": true,
      ".validate": true
    },
    "automergeDoc": {
    // Allow the request if the condition for each method is true.
      ".read": true,
      ".write": true,
      ".validate": true
    }
  }
}
```
