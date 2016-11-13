#Library is under constructing
## we're building something very cool :) Be tuned

# react-native-video-editor [![Build Status](https://travis-ci.org/shahen94/react-native-video-editor.svg?branch=master)](https://travis-ci.org/shahen94/react-native-video-editor)

[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg?style=plastic)](https://github.com/semantic-release/semantic-release)


## Getting started

`$ npm install react-native-video-editor --save`

### Mostly automatic installation

`$ react-native link react-native-video-editor`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-video-editor` and add `RNVideoEditor.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNVideoEditor.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.shahenlibrary.RNVideoEditorPackage;` to the imports at the top of the file
  - Add `new RNVideoEditorPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-video-editor'
  	project(':react-native-video-editor').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-video-editor/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-video-editor')
  	```


## Usage
```javascript
import RNVideoEditor from 'react-native-video-editor';

// TODO: What do with the module?
RNVideoEditor;
```