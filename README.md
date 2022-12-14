# Expandable text with Read More



## Step by Step Implementation

### Step 1: Add dependency of Expandable text with Read More library in build.gradle file

```
implementation 'com.borjabravo:readmoretextview:2.1.0'
```

### Step 2: Add Maven in setting.gradle file

```
maven {url ("https://jcenter.bintray.com")}
```

### Step 3: Add Maven in gradle.properties file

```
android.enableJetifier=true
```


### now click on Sync now it will sync your all files

### Step 4: Create a new Expandable text with Read More in your activity_main.xml file

```
<com.borjabravo.readmoretextview.ReadMoreTextView
        android:id="@+id/text_view"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="This is Expandable text this is a simple text, this is a testing text"
        android:textSize="20sp"
        app:trimExpandedText="@string/read_less"
        app:trimCollapsedText="@string/read_more"
        app:trimMode="trimModeLength"
        app:trimLength="25"
        app:colorClickableText="#039BE5"
        />
```

#### Now click on the run option it will take some time to build Gradle. After that, you will get output on your device as given below.


_© All Right Reserved by Innovative Programmer ❤️_
