Ultimate Android App Template 2
==========================

This is a simple start-template to save you a little time.


![alt text](https://github.com/AndreiD/UltimateAndroidAppTemplate/blob/master/app/the_gif_1.gif "How the app looks 1")


#### How to use it:

* Create a new blank android project
* Download the zip file for this project
* Copy paste the app folder
* Copy paste the build.gradle and modify applicationId "com.andrei.template" to your package name
* Check the compileSdkVersion, and buildToolsVersion to be the latest
* Run it. Remove the libs that you don't need. Add those that you do. 
* Star this repository :)


#### What it contains:

~~~~

dependencies {
    compile fileTree(include: ['*.jar'], dir: 'libs')
    apt "org.androidannotations:androidannotations:$AAVersion"
    compile "org.androidannotations:androidannotations-api:$AAVersion"
    compile 'com.android.support:appcompat-v7:23.0.1'
    compile 'com.android.support:support-v4:23+'
    compile 'com.android.support:support-annotations:23+'
    compile 'com.android.support:recyclerview-v7:23+'
    compile 'com.android.support:design:23+'
    compile 'de.greenrobot:eventbus:2.4.0'
    compile 'com.squareup.retrofit:retrofit:1.9.0'
    compile 'com.squareup.okhttp:okhttp:2.3.0'
    compile 'com.squareup.picasso:picasso:2.5.2'
    compile 'com.android.support:recyclerview-v7:23+'
    compile 'com.android.support:design:23+'

    //-------- app fonts -----------
    compile 'uk.co.chrisjenx:calligraphy:2.1.0'

    //----- nice progress app ----
    compile 'com.akexorcist:RoundCornerProgressBar:2.0.3'

}

~~~~

- Powered by Android Annotations
- Retrofit API ready to be used
- Picasso for image loading
- Snackbar, RecyclerView, Pull to Refresh etc.
- Feedback contact by email for feedback / Settings Page with some dummy settings etc.


#### Updates, Questions, and Requests

Ping me here :)


#### TODO://

* proguard config
* login forms
* test cases
* database examples
* event bus

#### You like this library ? Check:
- https://github.com/AndreiD/surveylib - A very good looking survey library
- https://github.com/AndreiD/TSnackBar Snackbar from the top



#### License

~~~~
Copyright 2014 Henrique Boregio

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
~~~~
