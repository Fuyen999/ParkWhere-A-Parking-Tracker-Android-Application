# ParkWhere-A-Parking-Tracker-Android-Application
CE2006 Software Engineering AY21/22 project, completed in a group of 7, original version can be found at https://github.com/ryuichi1998/ParkWhere.git

## Development Requirement
- Android Studio

### SDK Platform
For consistency, we are using `Android 9.0 (Pie)`

### SDK Tools
- Android SDK Build-Tools 31
- Android Emulator
- Android SDK Platform-Tools
- Google Play services

### Dependencies 
    // GOOGLE API
    implementation 'com.google.android.gms:play-services-location:18.0.0'
    implementation 'com.google.android.gms:play-services-maps:17.0.1'

    // ROOM
    implementation 'androidx.room:room-runtime:2.4.0-alpha05'
    annotationProcessor 'androidx.room:room-compiler:2.4.0-alpha05'

    // DEXTER
    // for permissions
    implementation 'com.karumi:dexter:6.2.3'

    // RETROFIT API
    implementation 'com.squareup.retrofit2:retrofit:2.9.0'
    implementation 'com.google.code.gson:gson:2.8.8'
    implementation 'com.squareup.retrofit2:converter-gson:2.9.0'
    
    // CIRCLE IMAGE VIEW
    implementation 'de.hdodenhof:circleimageview:3.1.0'