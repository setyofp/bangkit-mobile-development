
## Mobile Development Documentation
The source code of Android app of Travens using Kotlin in order to complete Bangkit Capstone Project.

 - ### Architecture for this project  
![topologi android](https://user-images.githubusercontent.com/69189062/172676880-dc62cf1c-b8ca-409f-8a1a-3e801603ecb4.png)

 - ### Feature
      * **Splash Screen**, There is logo screen before into the login page

      * **Login**, Allows a user to gain access to an application by entering their username and password

      * **SignUp**, Enables users to independently register and gain access to the system

      * **Home**, The start page that is displayed when you have logged in on your device

      * **Pick Image From Gallery**, You can select an image from the gallery in preparation for uploading an image to detect the landmark.
 
      * **Take Image From Camera**, You can take image from camera in preparation for uploading an image to detect the landmark.

      * **Send image to server to detect a Landmark**, After you prepare the image, you can click the process button to send the image and detect the image and get the detail about the landmark

      * **Article About Travelling**,  in this application you can read articles about travelling


* #### Dependencies :
  - [Jetpack Compose](https://developer.android.com/jetpack/compose)
  - [Lifecycle & Livedata](https://developer.android.com/jetpack/androidx/releases/lifecycle)
  - [Navigation Component](https://developer.android.com/jetpack/androidx/releases/navigation)
  - [kotlinx-coroutines](https://developer.android.com/kotlin/coroutines)    
  - [Retrofit 2](https://square.github.io/retrofit/)   
  - [Firebase](https://firebase.google.com/docs/)    
  - [Ok Http 3](https://square.github.io/okhttp/) 
  - [Lottie Files](https://lottiefiles.com/) 
  - [Google Play services Maps](https://developers.google.com/maps/documentation/android-sdk/get-api-key) 

## Getting Started Application

  - ### Prerequisites
      - ##### Tools Sofware
        1. [Android Studio](https://developer.android.com/studio)
        2. JRE (Java Runtime Environment) or JDK (Java Development Kit).

  - ### Installation
      1. Get an API Key at [Google Maps Platform](https://developers.google.com/maps/documentation/android-sdk/get-api-key)
      2. Connect Android Studio with Firebase [Connect to Firebase](https://developer.android.com/studio/write/firebase)
      3. Clone this repository and import into Android Studio    
          ```
             https://github.com/Widi-ps/bangkit-mobile-development.git
          ``` 
      4. Enter your API in buildConfigField `build.graddle`
         ``` defaultConfig {
            buildConfigField("String", "MAPS_TOKEN", '"Your Api Key"')}

  ## Acknowledgements
  * [Clean Architecture Guide](https://developer.android.com/jetpack/guide)
  * [Android Application Fundamental](https://developer.android.com/guide/components/fundamentals)
  * [Android Jetpack Pro](https://developer.android.com/jetpack)
  * [Dependency injection](https://developer.android.com/training/dependency-injection)
