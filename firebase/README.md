## Firebase

### Firebase Authentication

project-level `build.gradle`
```gradle
...
buildscript {
    ...
    dependencies {
        ...
        classpath 'com.google.gms:google-services:4.2.0'
    }
}
...
```

app-level `build.gradle`
```gradle
implementation 'com.google.firebase:firebase-core:16.0.6'
implementation 'com.google.firebase:firebase-auth:16.1.0'
```

### Versions

Firebase Auth | Firebase Core | Google Services
--- | --- | ---
16.1.0 | 16.0.6 | 4.2.0
