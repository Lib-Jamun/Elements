# Elements

Elements Library provide you a custom set of Android Elements that have custom views and properties. 

1. `CircularImageView` 

2. `CircularNetworkImageView` 


### What's New? (0.0.1)

* Stable official Version for Rapid Development.
* Custom UI components with Single and Multi Selection Mode in Country and Language Pickers.
* Easy Calling mechanism with instant reply via Listeners
* Optimized code with Api integration for Country Picker for Flags Images
* Country and Language Pickers have four modes you can optout from these Four mode (i.e. Bottom Sheet, Dialog, Activity, Navigation View)
* All the views in the library are Screen compatible i.e. You can execute this library on different android screens including tabs.

### Quality Measures? for (0.0.1)

The following apps are using this library without facing any kind of Bugs.

* **[SimplyBlood](https://play.google.com/store/apps/details?id=com.simplyblood)**
* **[ZINI](https://play.google.com/store/apps/details?id=ai.zini)**,
* **[Jumboo](https://play.google.com/store/apps/details?id=ai.jumboo)**
* **[USEonRENT](https://play.google.com/store/apps/details?id=com.useonrent)**
* **[Wall-E](https://play.google.com/store/apps/details?id=ai.hdwallpapers)**
* **[SaveBloodIndia](https://play.google.com/store/apps/details?id=com.savebloodindia)**
* **[Rectangle India](https://play.google.com/store/apps/details?id=com.rectangleindia.blooddonation)**
* **[Jeevan Rakshak](https://play.google.com/store/apps/details?id=com.jeevanrakshak)**

# Why this library?

* This library Pickers competible with all screen sizes and device (Tab with 7' inches and 10'inches).
* Library support both orientation that is portrait and landscape.
* Its simple and easy to use.
* Its Customizable (Support Custom Themes). 
* Minimum API is 15, but it'll probably work in API 9 and above, just make sure you test it out (we use `Support Fragment Manager`).  

### All-in-One Setup

The easiest way to add **Elements** library to your project is by adding it as a dependency to your `build.gradle`. To add picker library you just need to append few lines into your `build.gradle`.
These lines are provided in Integration Part given Below

### Gradle Configuration

**Add the dependency**

Step 1\. Add the jCenter repository to your build file. Add it in your root build.gradle at the end of repositories:

```java
allprojects {
  repositories {
        mavenCentral()
  }
}
```
Step 2\. Add the dependency
```java
dependencies {
        compile 'tk.jamun.elements:elements:0.0.1'
}
```

### Maven Config

```xml
<dependency>
  <groupId>tk.jamun.elements</groupId>
  <artifactId>elements</artifactId>
  <version>0.0.1</version>
  <type>aar</type>
</dependency>
```
------

# Types of Pickers

## Utility Pickers


#### Gradle Setup

Step 1\. Add the jCenter repository to your build file. Add it in your root build.gradle at the end of repositories:

```java
allprojects {
  repositories {
        mavenCentral()
  }
}
```
Step 2\. Add the dependency

```java
dependencies {
        compile 'tk.jamun.elements:circularimageview:0.0.1'
}
```
#### Maven
```xml
<dependency>
  <groupId>tk.jamun.elements</groupId>
  <artifactId>circularimageview</artifactId>
  <version>0.0.1</version>
  <type>aar</type>
</dependency>
```


## Country-Pickers

`Country Pickers` 

#### Gradle Setup

Step 1\. Add the jCenter repository to your build file. Add it in your root build.gradle at the end of repositories:

```java
allprojects {
  repositories {
        mavenCentral()
  }
}
```
Step 2\. Add the dependency

```java
dependencies {
        compile 'tk.jamun.elements:circularnetworkimageview:0.0.1'
}
```
#### Maven
```xml
<dependency>
  <groupId>tk.jamun.elements</groupId>
  <artifactId>circularnetworkimageview</artifactId>
  <version>0.0.1</version>
  <type>aar</type>
</dependency>
```

# How to Implement

Once the project has been added to gradle, You can use these lines of code to configure pickers....

## 1.

**1. **

```
```
------


> **To understand more how the library works, please take a look at the sample app.**

------

# Dependency

* Android Support Fragment Library ``v27.1.1``
* Jamun Volley Library **[Volley](https://github.com/Lib-Jamun/Volley.git)**

## Credits

Desgin & Developed by : **[Jatin Sahgal](https://www.linkedin.com/in/jatinsahgal/)**
 (**[Linkedin](https://www.linkedin.com/in/jatinsahgal/)** & **[Website](https://jatin.techcruzers.com)**) 

Content Writer : **[Achal Garg](https://www.linkedin.com/in/techgarg/)**
 (**[Linkedin](https://www.linkedin.com/in/techachal/)** & **[Website](https://achal.techcruzers.com)**) 

Company : **[Techcruzers](https://www.techcruzers.com)**

## More Library under Jamun 
* **[Pickers](https://github.com/Lib-Jamun/Pickers.git)**
Pickers Library provide you a set of Pickers like Country, Language, Share and Intent Chooser.

* **[Country-Pickers](https://github.com/Lib-Jamun/Pickers.git)**
allow you to access Country picking functionality with great UI/UX design, and there are numberous of function which help you to modify picker as per your requirements. Library has been provided with four custom UI initate mode you can decide how the view of picker can be initate. You can also decide weather picker inheriate Single or Multi Selection property. Library consists of updated collection of country name, code and there flags. We are using APIs base structure to avoid increase in the size of apk due to flag Images. This module Maintain the database so that you don't need to call APIs again and again rather than you can choose when to refresh the Database and fetch new real time data.

* **[Language-Pickers](https://github.com/Lib-Jamun/Pickers.git)**
provides you read-made Language picker  which is easy to use and comes with great UI/UX, and there are numberous of function which help you to modify picker as per your requirements. Library has been provided with four custom UI initate mode you can decide how the view of picker can be initate. You can also decide weather picker inheriate Single or Multi Selection property.

* **[Share-Dialog-Pickers](https://github.com/Lib-Jamun/Pickers.git)**
provide you Intent Chooser with great UI/UX. It automatically retrive the sort list of all the apps which can share the file. This functionality saves much of your task. You can also share dialog Picker for sending Large files. For this you just need to call a single function with file as Argument.

* **[Volley](https://github.com/Lib-Jamun/Volley.git)**
Library is a set of Custom Classes with UI components for network programming, integration and transaction handling in a better and standard way. This will help developers for making quality use of volley library. 

* **[Scanner](https://github.com/Lib-Jamun/scanner.git)** is a collection of Beautiful Activity which help others to make there own Custom QR/Barcode Scanner. 

* **[Calendar](https://github.com/Lib-Jamun/calendar.git)**
is a collection of Beautiful Activities which help others to make there Fully Custom Calendar View with Single and Multi Date Picker Functionality 

* **[Camera](https://github.com/Lib-Jamun/Camera.git)**
library provide you Custom Complete Camera view with full features like Flash, Rotation, Gallery Picker, Focus, Tap to capture, Confirmation window and last but not least croping feature. It also provide you file path in return so that developer can feel a friendly handy way to Deal After. 

* **[Gallery](https://github.com/Lib-Jamun/Gallery.git)**
have some Beautiful UI Components and Multi files Mode for android Developers to give there app a A Rich look With single and Multi picker Functionality.

* **[UI](https://github.com/Lib-Jamun/ui.git)**
library is a set of UI Views, Custom Component and Collection of Helper Classes which help Developer for making quality Product. Such as Camera, Gallery, Number of Pickers, Calendar, Date Pickers, Dialogs and many more Heler UI and Backend Component.

## License
    Copyright (c) 2018 Jatin Sahgal

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
