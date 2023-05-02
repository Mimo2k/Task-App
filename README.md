
# Task App

Modern CRUD app using kotlin for storing Task according to priority


## Demo

![Demo](https://media4.giphy.com/media/WRucPNhn0732e1p5lh/giphy.gif?cid=790b76111840860e1bf486af63048f57935f1279ab590936&rid=giphy.gif&ct=g)

## Dependency
**Step 1: Add the following dependencies to your root build.gradle file**
```dependency
    dependencies {
        classpath 'com.android.tools.build:gradle:7.2.2'
        classpath "org.jetbrains.kotlin:kotlin-gradle-plugin:1.7.10"
        classpath "androidx.navigation:navigation-safe-args-gradle-plugin:2.5.1"
    }
```

**Step 2: Add the following dependencies to your module's build.gradle file**

&nbsp;&nbsp;&nbsp;&nbsp;**1. Navigation Components:** 

```dependency
    implementation 'androidx.navigation:navigation-fragment-ktx:2.5.1'
    implementation 'androidx.navigation:navigation-ui-ktx:2.5.1'
```
&nbsp;&nbsp;&nbsp;&nbsp;**2. Room Components:**

```dependency
    implementation 'androidx.room:room-runtime:2.4.3'
    kapt 'androidx.room:room-compiler:2.4.3'
    implementation 'androidx.room:room-ktx:2.4.3'
    androidTestImplementation 'androidx.room:room-testing:2.4.3'
```
&nbsp;&nbsp;&nbsp;&nbsp;**3. Lifecycle Components:**

```dependency
    implementation 'androidx.lifecycle:lifecycle-extensions:2.2.0'
    implementation 'androidx.lifecycle:lifecycle-common-java8:2.5.1'
    implementation 'androidx.lifecycle:lifecycle-viewmodel-ktx:2.5.1'
```
&nbsp;&nbsp;&nbsp;&nbsp;**4. Kotlin Components:**

```dependency
    implementation 'org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.7.10'
    api 'org.jetbrains.kotlinx:kotlinx-coroutines-core:1.6.1'
    api 'org.jetbrains.kotlinx:kotlinx-coroutines-android:1.6.1'
```
&nbsp;&nbsp;&nbsp;&nbsp;**5. Recycler View Animations:**
```dependency
    implementation 'jp.wasabeef:recyclerview-animators:4.0.2'
```
**Step 3: Apply plugins to your module's build.gradle file**
```dependency
    plugins {
        id 'com.android.application'
        id 'org.jetbrains.kotlin.android'
        id 'kotlin-android'
        id 'kotlin-android-extensions'
        id 'kotlin-kapt'
        id 'androidx.navigation.safeargs.kotlin'
    }
```

## Documentation

[Room Documentation](https://developer.android.com/training/data-storage/room)


## Authors

- [@Mimo2k](https://www.github.com/Mimo2k)

