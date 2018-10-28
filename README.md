# RoundedImageView


<img src="Screenshot_1540123539.png" width="250">

# Include In Your Project
Step 1. Add the JitPack repository to your build file.

Add it in your root build.gradle at the end of repositories:
```gradle
allprojects {
	repositories {
	  ...
		maven { url 'https://jitpack.io' }
	}
}
```
  
Step 2. Add the dependency
```gradle
dependencies {
	implementation 'com.github.chirag-kachhadiya:RoundedImageView:1.0'
}
```
  
# Usage
### For Rounded Corner Image
in xml:

```xml
<com.infinityandroid.roundedimageview.RoundedImageView
            android:layout_width="150dp"
            android:layout_height="wrap_content"
            android:layout_margin="10dp"
            android:adjustViewBounds="true"
            android:src="@drawable/the_hundred"
            app:corner_radius="10" />
```

> You can set corner radius by 'app:corner_radius' attribute.

> Of course supports adjustViewBound.

### For Circle Image
in xml:

```xml
<com.infinityandroid.roundedimageview.RoundedImageView
        android:layout_width="130dp"
        android:layout_height="130dp"
        android:layout_margin="10dp"
        android:src="@drawable/tony_stark"
        app:make_circle="true" />
```

> You can make image circle by 'app:make_circle' attribute with 'true' value.

> When using round image make sure width and height both are same for better result.

# Developed By
[Chirag Kachhadiya](http://infinityandroid.com/portfolio)

# License

```
Copyright 2018 Chirag Kachhadiya

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
