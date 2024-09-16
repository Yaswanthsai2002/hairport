// comrade_s_application7

Built with AndroidX Support

Requires Android Studio Arctic Fox | 2020.3.1 or higher.

Current Kotlin Version 1.7.20

### SDK Versions
compileSdkVersion 33
buildToolsVersion "30.0.3"
minSdkVersion 23
targetSdkVersion 33

### Libraries

1. Retrofit - REST API Call
   https://square.github.io/retrofit/

2. Glide - Image Loading and caching.
   https://github.com/bumptech/glide

3. Material Design Components - Google's latest Material Components.
   https://material.io/develop/android

4. Koin - Dependency Injection
   https://insert-koin.io/

### Figma design guideline for better accuracy

Read our guidelines to increase the accuracy of design conversion to code by optimizing Figma designs.
https://docs.dhiwise.com/docs/Designguidelines/intro

### App Navigation

Check your app's UI from the AppNavigation screens of your app.

### Package Structure

appcomponents
├── di                        - Dependency Injection Components
│   └── MyApp.kt              - DI setup
├── network                   - REST API Call setup
│   ├── ResponseCode.kt
│   └── RetrofitProvider.kt
├── ui                        - Data Binding Utilities
│   └── CustomBindingAdapter.kt
constants
├── IntegerConstants.kt        - Constant Files
└── StringConstants.kt
extensions
└── Strings.kt                 - Kotlin Extension Function Files
modules
├── example                    - A module of Application
│   ├── ui                     - UI handling classes
│   └── data                   - Data Handling classes
│       ├── viewmodel          - ViewModels for the UI
│       └── model              - Model for the UI
network
├── models                     - Request/Response Models
├── repository                 - Network repository
resources
└── RetrofitService.kt         - Common classes for API
