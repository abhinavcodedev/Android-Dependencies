# Android-Dependencies

A curated collection of Android dependencies for modern Android app development.

**Retrofit**
```gradle
implementation("com.squareup.retrofit2:retrofit:2.11.0")
implementation("com.squareup.retrofit2:converter-gson:2.11.0")
implementation("com.squareup.okhttp3:logging-interceptor:5.0.0-alpha.14")
```
**Coroutines**
```gradle
implementation("org.jetbrains.kotlinx:kotlinx-coroutines-android:1.10.2")
```
**Hilt**
```gradle
implementation("com.google.dagger:hilt-android:2.56.2")
ksp("com.google.dagger:hilt-compiler:2.56.2")
implementation("androidx.hilt:hilt-navigation-compose:1.2.0")
implementation("androidx.hilt:hilt-work:1.2.0")
ksp("androidx.hilt:hilt-compiler:1.2.0")
```
**Room Database**
```gradle
implementation("androidx.room:room-runtime:2.7.2")
implementation("androidx.room:room-ktx:2.7.2")
ksp("androidx.room:room-compiler:2.7.2")
```
**Navigation (Compose)**
```gradle
implementation("androidx.navigation:navigation-compose:2.9.0")
```
**Coil**
```gradle
implementation("io.coil-kt:coil-compose:2.7.0")
```
**Glide**
```gradle
implementation("com.github.bumptech.glide:glide:4.16.0")
```
**Lottie**
```gradle
implementation("com.airbnb.android:lottie-compose:6.6.7")
```
**Timber**
```gradle
implementation("com.jakewharton.timber:timber:5.0.1")
```
**Paging 3**
```gradle
implementation("androidx.paging:paging-runtime:3.3.6")
implementation("androidx.paging:paging-compose:3.3.6")
```
**WorkManager**
```gradle
implementation("androidx.work:work-runtime-ktx:2.10.2")
```
**DataStore**
```gradle
implementation("androidx.datastore:datastore-preferences:1.1.7")
```
**Firebase**
```gradle
implementation(platform("com.google.firebase:firebase-bom:34.0.0"))
implementation("com.google.firebase:firebase-auth")
implementation("com.google.firebase:firebase-firestore")
implementation("com.google.firebase:firebase-messaging")
implementation("com.google.firebase:firebase-analytics")
implementation("com.google.firebase:firebase-crashlytics")
implementation("com.google.firebase:firebase-storage")
```
**Kotlin Serialization**
```gradle
implementation("org.jetbrains.kotlinx:kotlinx-serialization-json:1.9.0")
```
**Media3 (ExoPlayer)**
```gradle
implementation("androidx.media3:media3-exoplayer:1.8.0")
implementation("androidx.media3:media3-ui:1.8.0")
```
**Gson**
```gradle
implementation("com.google.code.gson:gson:2.13.1")
```
**Google Sign-In**
```gradle
implementation("androidx.credentials:credentials:1.5.0")
implementation("androidx.credentials:credentials-play-services-auth:1.5.0")
implementation("com.google.android.libraries.identity.googleid:1.1.1")
```
**Google Maps**
```gradle
implementation("com.google.maps.android:maps-compose:6.8.0")
implementation("com.google.android.gms:play-services-maps:19.2.0")
implementation("com.google.android.gms:play-services-location:21.3.0")
implementation("com.google.maps.android:android-maps-utils:3.19.0")
```
**CameraX**
```gradle
implementation("androidx.camera:camera-camera2:1.4.2")
implementation("androidx.camera:camera-lifecycle:1.4.2")
implementation("androidx.camera:camera-view:1.4.2")
```
**ML Kit**
```gradle
implementation("com.google.mlkit:barcode-scanning:17.3.0")
implementation("com.google.mlkit:text-recognition:16.0.1")
```
**Biometric**
```gradle
implementation("androidx.biometric:biometric:1.4.0-alpha04")
```
**Security Crypto**
```gradle
implementation("androidx.security:security-crypto:1.1.0")
```
**Chucker**
```gradle
debugImplementation("com.github.chuckerteam.chucker:library:4.2.0")
releaseImplementation("com.github.chuckerteam.chucker:library-no-op:4.2.0")
```
**LeakCanary**
```gradle
debugImplementation("com.squareup.leakcanary:leakcanary-android:2.14")
```
