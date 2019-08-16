# Elements

Elements Library provide you a custom set of Android Elements that have custom views and properties. 

1. `CircularImageView` is a custom android element of ImageView with circular shape. It also provide you border properties with three custom calls like border, width and overlays.

2. `CircularNetworkImageView` is a another custom android element class which extend volley NetworkImageView and provide circular shape. It also provide you border properties with three custom calls like border, width and overlays. And the most important feature can be able to cache your image just like NetworkImageView do.

Both can be accessible with the help of Java class calls and via xml. Both can handle vectors easily and can be used in Glide and in Download image.

### What's New? {Latest Version}

* Stable official Version for Rapid Development.
* Custom UI function to provide circular shapes.
* Easy Calling mechanism with vector handling features.
* Can enhance your view using Border feature.

### Quality Measures? for{Latest Version}

The following apps are using this library without facing any kind of Bugs.

* **[SimplyBlood](https://play.google.com/store/apps/details?id=com.simplyblood)**
* **[ZINI](https://play.google.com/store/apps/details?id=ai.zini)**,
* **[RentalBazar](https://play.google.com/store/apps/details?id=com.rentalbazaar)** 
* **[DoubtCrusher](https://play.google.com/store/apps/details?id=com.doubtcrusher)**
* **[BookAGround](https://play.google.com/store/apps/details?id=com.bookaground)**
* **[PeyFree](https://play.google.com/store/apps/details?id=com.peyfree)**
* **[ClueRace](https://play.google.com/store/apps/details?id=com.cluerace)**
* **[CIS-Connect In Single](https://play.google.com/store/apps/details?id=com.connectinsingle)**
* **[QR/Barcode Scanner](https://play.google.com/store/apps/details?id=com.scanner.android)** 
* **[Wall-E](https://play.google.com/store/apps/details?id=com.walle.android)**

------
# Why this library?

* This Elements don't have any compatibilty and OS version Issues.
* Elements support both orientation that is portrait and landscape.
* Its simple and easy to use.
* Its Customizable with both xml and java code functions calls. 

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
```
Latest Version : 0.0.8

Android
dependencies {
     compile 'tk.jamun.elements:elements:{Latest Version}'
}

AndroidX
dependencies {
     compile 'tk.jamunx.elements:elements:{Latest Version}'
}

Kotlin
dependencies {
     compile 'tk.jamun-ktx.elements:elements:{Latest Version}'
}
```

### Maven Config

```xml
<dependency>
 Android
  <groupId>tk.jamun.ui</groupId>
AndroidX
  <groupId>tk.jamunx.ui</groupId>
Kotlin
  <groupId>tk.jamun-ktx.ui</groupId>
 <artifactId>elements</artifactId>
  <version>{Latest Version}</version>
  <type>aar</type>
</dependency>
```
------

# Types of Elements

## CircularNetworkImageView

This element provide you Google volley NetworkImageView in a circular shape, with border color features. Simple ways to add this into your project by adding : 

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
Latest Version : 0.0.8

Android
dependencies {
     compile 'tk.jamun.elements:circularnetworkimageview:{Latest Version}'
}

AndroidX
dependencies {
     compile 'tk.jamunx.elements:circularnetworkimageview:{Latest Version}'
}

Kotlin
dependencies {
     compile 'tk.jamun-ktx.elements:circularnetworkimageview:{Latest Version}'
}
```
#### Maven
```xml
<dependency>
 Android
  <groupId>tk.jamun.ui</groupId>
AndroidX
  <groupId>tk.jamunx.ui</groupId>
Kotlin
  <groupId>tk.jamun-ktx.ui</groupId>
  <version>{Latest Version}</version>
  <type>aar</type>
  <artifactId>circularnetworkimageview</artifactId>
  <type>aar</type>
</dependency>
```


## CircularImageView

This element provide you Android ImageView in a circular shape, with border color features. Simple ways to add this into your project by adding : 

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
Android
dependencies {
     compile 'tk.jamun.elements:circularimageview:{Latest Version}'
}

AndroidX
dependencies {
     compile 'tk.jamunx.elements:circularimageview:{Latest Version}'
}

Kotlin
dependencies {
     compile 'tk.jamun-ktx.elements:circularimageview:{Latest Version}'
}

```

#### Maven

```xml
<dependency>
  Android
  <groupId>tk.jamun.ui</groupId>
AndroidX
  <groupId>tk.jamunx.ui</groupId>
Kotlin
  <groupId>tk.jamun-ktx.ui</groupId>
  <version>{Latest Version}</version>
  <artifactId>circularimageview</artifactId>
  <type>aar</type>
</dependency>
```

# How to Implement

Once the project has been added to gradle, You can use these lines of code to configure pickers....

## 1. Using XML

XML example explain you implementation of CircularImageView and CircularNetworkImageView :  

```
// CircularNetworkImageView

<tk.jamun.elements.circularnetworkimageview.CircularNetworkImageView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        app:srcCompat="vector drawable"
                        android:src="normal drawables"
                       />

//OR CircularImageView

<tk.jamun.elements.circularimageview.CircularImageView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        app:srcCompat="vector drawable"
                        android:src="normal drawables"
                        android:scaleType="centerCrop"// Only centerCrop is available
                      //  android:adjustViewBounds="" // Not available
                       />


```

Implement Border and there properties : 

XML example explain you implementation of CircularImageView and CircularNetworkImageView :  

```
                        app:library_border_color="color"
                        app:library_border_width="dimen in dp"
                        app:library_border_overlay="true or false"
                        
```

## 2. Using Java Code

JAVA example explain you implementation of CircularImageView and CircularNetworkImageView :  

First CircularNetworkImageView class : 
```     
        CircularNetworkImageView circularNetworkImageView = new CircularNetworkImageView(getContext());
        circularNetworkImageView.setBorderColor(); // to set border color
        circularNetworkImageView.setBorderColorResource(); // to set color resource directlu
        circularNetworkImageView.setBorderOverlay(); // set overlay true and false
        circularNetworkImageView.setBorderWidth(); // border width
        circularNetworkImageView.setColorFilter(); // color filter options
        circularNetworkImageView.setImageBitmap(); // Set image as bitmap
        circularNetworkImageView.setImageDrawable();// Set image as Drawable
        circularNetworkImageView.setImageResource();// Set image as Resource
        circularNetworkImageView.setImageURI();// Set image as UrI
        circularNetworkImageView.setScaleType();// Set image ScaleType only centerCrop
```

First CircularImageView class : 
```     
        CircularImageView circularImageView = new CircularImageView(getContext());
        circularImageView.setBorderColor(); // to set border color
        circularImageView.setBorderColorResource(); // to set color resource directlu
        circularImageView.setBorderOverlay(); // set overlay true and false
        circularImageView.setBorderWidth(); // border width
        circularImageView.setColorFilter(); // color filter options
        circularImageView.setImageBitmap(); // Set image as bitmap
        circularImageView.setImageDrawable();// Set image as Drawable
        circularImageView.setImageResource();// Set image as Resource
        circularImageView.setImageURI();// Set image as UrI
        circularImageView.setScaleType();// Set image ScaleType only centerCrop
```

>**Note : AdjustBound Not Available in this. and in ScaleType only centerCrop**

> **To understand more how the library works, please take a look at the sample app.**

------

# Dependency

* Android Support Fragment Library ``v27.1.1``
* Jamun Volley Library **[Volley](https://github.com/Lib-Jamun/Volley.git)**

## Credits

Desgin & Developed by : **[Jatin Sahgal](https://www.linkedin.com/in/jatinsahgal/)**
 (**[Linkedin](https://www.linkedin.com/in/jatinsahgal/)** & **[Website](http://androidcodelab.com/)** & **[Github](https://github.com/Lib-Jamun)**) 

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
Library have splendid UI Components with Single and Multi files Selection Mode for android Developers to give there app a A Rich look With with custom picker functionality to cover up maximum media type like Audio, Files (Docs, Text etc) and Images.

* **[UI](https://github.com/Lib-Jamun/ui.git)**
library is a set of UI Views, Custom Component and Collection of Helper Classes which help Developer for making quality Product. Such as Camera, Gallery, Number of Pickers, Calendar, Date Pickers, Dialogs and many more Heler UI and Backend Component.

* **[Elements](https://github.com/Lib-Jamun/elements.git)**
Library provide you a custom set of Android Elements that have custom views and properties like CircularImageView or CircularNetworkImageView and many more.

* **[Browser](https://github.com/Lib-Jamun/Browser.git)**
Library provide you two type Single Pager and Multi Pager In-APP Browser Functionality with Event Handling and Functions to Customize Views. It also provide you Copy to clipboard, Open in Browser and share link feature in-Bulit.

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
