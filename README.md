# androidKotlinFirebaseTemanrendy

apply plugin: 'com.android.application'

apply plugin: 'kotlin-android'

apply plugin: 'kotlin-android-extensions'

apply plugin: 'com.google.gms.google-services'

apply plugin: 'androidx.navigation.safeargs'

  //Your setting dependecies
    androidTestImplementation 'androidx.test.ext:junit:1.1.2'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.3.0'
    implementation 'com.google.firebase:firebase-analytics:17.5.0'

    def nav_version = "2.3.0"
    implementation "androidx.navigation:navigation-fragment-ktx:$nav_version"
    implementation "androidx.navigation:navigation-ui-ktx:$nav_version"

    implementation 'de.hdodenhof:circleimageview:3.1.0'

    implementation 'com.squareup.picasso:picasso:2.71828'
