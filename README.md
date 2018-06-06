# RoundedImageView


![Image of RoundImageView](http://infinityandroid.com/chirag/repo_imgs/rounded_image_view.png)

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

### For Round Image
in xml:

```xml
<com.infinityandroid.roundedimageview.RoundedImageView
        android:layout_width="130dp"
        android:layout_height="130dp"
        android:layout_margin="10dp"
        android:src="@drawable/tony_stark"
        app:make_circle="true" />
```

> You can meke image round by 'app:make_circle' attribute with 'true' value.

> When using round image make sure width and height both are same for better result.
