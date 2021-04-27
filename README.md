
# react-native-prevent-screenshot

## Getting started

`$ npm install react-native-prevent-screenshot --save`

### Mostly automatic installation

`$ react-native link react-native-prevent-screenshot`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-prevent-screenshot` and add `RNPreventScreenshot.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNPreventScreenshot.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.PerventScreenshot.RNPreventScreenshotPackage;` to the imports at the top of the file
  - Add `new RNPreventScreenshotPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-prevent-screenshot'
  	project(':react-native-prevent-screenshot').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-prevent-screenshot/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-prevent-screenshot')
  	```



## Usage
```javascript
import RNPreventScreenshot from 'react-native-prevent-screenshot';

// TODO: What to do with the module?
RNPreventScreenshot;
```
  