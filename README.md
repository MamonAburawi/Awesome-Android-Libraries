# These are the most libraries that I see as useful for any Android project.


# 1- Glide

Glide is a fast and efficient open-source media management and Image loading framework for Android that simplifies the process of fetching, decoding, and displaying images in your app. It offers easy-to-use APIs, automatic memory and disk caching, and supports a range of image formats and transformations, including resizing, cropping, and center-crop. Glide is designed to handle large images and image lists, and offers additional features such as GIF and video support, as well as integration with popular networking libraries like Volley and OkHttp.

link: https://github.com/bumptech/glide 


# 2- AppIntro

The AppIntro library is an open-source Android library that provides a simple and easy-to-use way to create onboarding or introduction screens for your app. It allows you to create a series of slides that can contain text, images, and buttons, and provides built-in animations and transitions between slides. The library offers a range of customization options, including support for custom fonts, colors, and styles, as well as the ability to add custom animations and layouts.

link: https://github.com/AppIntro/AppIntro



# 3- Sdp Android 

It is used for implementing a responsive layout in Android apps by providing a way to set view dimensions in a size-independent way, which ensures that the layout looks consistent across different screen sizes and resolutions. This is achieved by using a unit of measurement called "scalable dp" (sdp), which is similar to the "dp" unit used in Android but takes into account the device's screen density.

link: https://github.com/intuit/sdp

for jetpack compose use this

link: https://github.com/Kaaveh/sdp-compose



# 4- PRDownloader

It is used for downloading files in Android apps and provides a simple and easy-to-use API for managing downloads, including features such as pause, resume, and retry. The library also supports downloading files in parallel, which can improve download speeds.

link: https://github.com/amitshekhariitbhu/PRDownloader



# 5- TimeAgo

It is a simple Java library for displaying dates as relative time ago language. The library provides a way to display dates in a human-friendly format, such as "4 days ago", "15 years ago", "a minute ago", or "just now", instead of the full date and time. It comes with support for multiple languages, including Spanish, English, Dutch, German, French, Italian, Portuguese, Indonesian, Czech, and Arabic. The library can be imported as a dependency in a Gradle or Maven project and used in code by calling a simple API.

link: https://github.com/marlonlom/timeago



# 6- Shimmer

It provides an easy way to add a shimmering effect to an Android app's UI elements, such as text or images. The shimmer effect is similar to a loading animation and can be used to indicate that content is being loaded or to add a visual effect to the UI. The library provides a simple API for configuring the shimmer effect, including options for controlling the animation speed, direction, and color.

link: https://github.com/facebook/shimmer-android



# 7- Epoxy

It is used for building complex and flexible RecyclerView-based user interfaces in Android apps. It provides a way to separate the concerns of data modeling and view rendering by defining reusable "models" that encapsulate both the data and the view logic. The models can be easily composed and reused to build complex layouts, and the library provides built-in support for common use cases such as multiple view types, nested RecyclerViews, and animations. The version "5.1.3" indicates the specific version of the library being used.

implementation "com.airbnb.android:epoxy:5.1.3"
  
kapt "com.airbnb.android:epoxy-processor:5.1.3"
  
implementation "com.airbnb.android:epoxy-databinding:4.3.1"

implementation "androidx.paging:paging-runtime-ktx:3.2.0-rc01"
   
implementation "com.airbnb.android:epoxy-paging3:5.1.3"
    
link: https://github.com/airbnb/epoxy



# 8- CircleImageView

It is used for displaying circular images in Android apps. The library extends the standard ImageView class and provides a way to round the corners of an image into a circular shape. It handles scaling and centering of the image within the circular bounds, as well as providing attributes for configuring the border color and width. 

link: https://github.com/hdodenhof/CircleImageView



# 9- Gson

It is used for serializing and deserializing Java objects to and from JSON format. It provides a simple and flexible API for converting Java objects to JSON and vice versa, with support for handling complex object graphs, custom type adapters, and more. The library is widely used in Android development for working with REST APIs and other network data sources that use JSON as the data format.

link: https://github.com/google/gson



# 10- Kotlin Coroutines Play Services

It provides an integration between Kotlin coroutines and Google Play Services APIs, allowing developers to use coroutines to perform asynchronous operations with these APIs in a more concise and readable way. The library includes support for common Google Play Services APIs such as Location, Maps, and Firebase, and provides a set of extension functions and utility classes for working with these APIs using coroutines.

implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-play-services:1.6.4'


# 11- Swiper Refresh Layout

The swiperefreshlayout library provides a simple and easy-to-use SwipeRefreshLayout widget for Android apps. The widget allows users to quickly refresh the contents of a view via a vertical swipe gesture, making it ideal for use in apps that display dynamic content such as news feeds, social media feeds, and more. The library is part of the AndroidX library package, which provides backward-compatibility for newer Android features and components on older Android versions.

implementation "androidx.swiperefreshlayout:swiperefreshlayout:1.1.0"


# 12- Country Code Picker

This widget allows users to select a country code from a list and automatically formats the selected country code in the correct format for phone number input. It is commonly used in Android apps that require phone number input from users.

link: https://github.com/hbb20/CountryCodePickerProject 



# 13- TedImagePicker

This library enables users to select images from their device's gallery or camera, and provides various customization options such as maximum image selection limit, image compression, and more. It is commonly used in Android apps that require image selection and uploading functionality.

link: https://github.com/ParkSangGwon/TedImagePicker



# 14- Super Bottom Sheet

This library provides an implementation of a customizable bottom sheet for Android apps. This library allows developers to create bottom sheets with various customization options such as background color, animation style, and more. It is commonly used in Android apps that require a bottom sheet UI, such as for displaying additional options or information.

link: https://github.com/andrefrsousa/SuperBottomSheet



# 15- Dexter 

Dexter is an Android library that simplifies the process of requesting permissions at runtime.

link: https://github.com/Karumi/Dexter



# 16- PageIndicatorView

PageIndicatorView is light library to indicate ViewPager's selected page with different animations and ability to customise it as you need.

link: https://github.com/romandanylyk/PageIndicatorView



# 17- PhotoView

PhotoView aims to help produce an easily usable implementation of a zooming Android ImageView.

link: https://github.com/Baseflow/PhotoView



# 18- Chip navigation bar

A navigation bar widget inspired on Google Bottom Navigation mixed with Chips component.

link: https://github.com/ismaeldivita/chip-navigation-bar



# 19- Progress button

Progress Button is an android library for handling different types states like active, finished, enabled, disabled, and reset with a single line of code.

link: https://github.com/hellosagar/ProgressButton



# 20- Lottile 

Lottie is a mobile library for Android and iOS that parses Adobe After Effects animations exported as json with Bodymovin and renders them natively on mobile

link: https://github.com/airbnb/lottie-android



# 21- Custom QR Generator

Android library for creating QR-codes with logo, custom pixel/eyes shapes, background image. Powered by ZXing.

link: https://github.com/alexzhirkevich/custom-qr-generator



# 22- Quickie 

quickie is a Quick Response (QR) Code scanning library for Android that is based on CameraX and ML Kit on-device barcode detection. It's an alternative to ZXing based libraries and written in Kotlin

link: https://github.com/G00fY2/quickie








