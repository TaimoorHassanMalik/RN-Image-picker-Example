# Example of Image Picker in React Native

For picking the image we will use a very good library called react-native-image-picker. 
Which provides ImagePicker component to in which you can provide the image picking option
from Gallery or Camera.

## Installation of Dependency
To use ImagePicker we need to install react-native-image-picker dependency.
* npm install react-native-image-picker --save

# Android Permission to use the Camera and to Read the Storage
We are using a Native API Camera and also going to choose the image from the gallery so we need to add some permission to the AndroidManifest.xml file.
### Please add the following permissions in the AndroidManifest.xml
#### android > app > src > main > AndroidManifest.xml 

uses-permission android:name="android.permission.CAMERA"/

uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/

## Output like this

<img src="Screenshot/2.png" width="300" >
<img src="Screenshot/1.png" width="300" >
