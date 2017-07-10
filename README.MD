react-native-session-length
==================================
# Why

If you want to timeout people's sessions or show something when they have opened the app for the first time in a while. This covers the both use-cases of :
- Bringing the app to the foreground.
- Opening the app from force close.

# Installation 
```
npm i react-native-session-length
```

# Usage

```
import SessionLength from 'react-native-session-length';

SessionLength((milliseconds)=>{
  console.log(`It has been ${milliseconds}ms since you last opened the app.`;
});
```
