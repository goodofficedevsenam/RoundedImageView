# RoundedImageView
An advanced image view to display images with rounded corners and in circle

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
