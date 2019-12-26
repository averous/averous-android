# averous

averous Android SDK enables mobile app performance monitoring and user behavior tracking.

### Integration Instructions

1. You can install the SDK through *build.gradle* file:

```
dependencies {
  ...
  implementation 'com.averous:averous-android:1.0.0'
  ...
}
```

2. Initialise averous in every activity that is an entry point your app:

```
@Override
protected void onCreate(Bundle savedInstanceState) {
    super.onCreate(savedInstanceState);
    ...
    Averous.start("YOUR_API_KEY");
}
```
