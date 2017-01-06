# LYS Edebiyat Yazar Kitap Bilgi Yarışması Android App  
This is the Cordova project of the game *LYS Edebiyat Yazar Kitap Bilgi Yarışması*. The application is available on both **iOS** and **Android** platforms.
  
In Turkey, there are different kinds of university exams to be taken in order to get into the university. The university exam procedure is a 2-layer mechanism: in the first layer, called YGS, everyone takes the same exam which consists of 4 parts, *Turkish*, *Mathematics*, *Science* and *Social Science*. Those who are successful in the first exam, scored at least 180 points, are allowed to take the second layer exams, called LYS, which are specialized seperate exams for Literature, Mathematics, Physics, etc..

In the Literature part of this exam contains a lot of information about the books, their authors, types of the books and the literary period of the book. In order to simplfy this process, we created an app called **LYS Edebiyat Yazar Kitap Bilgi Yarışması** - translated as *LYS Literature Book & Author Quiz*.

This repository is the **Android** version of the application, created using the amazing [**Apache Cordova**](http://cordova.apache.org/) with *HTML*, *CSS* and *JavaScript*. The iOS version is a *native* app, where the Android version is a *hybrid* app. This is our first experiment on building a hybrid application, therefore any help or suggestion will be welcomed.

The app is a single *HTML* file with all the *JavaScript* libraries used are embedded into the *HTML* file with their minified versions. The application simply queries an embedded *JSON* dataset and generates questions based on that data. We wanted the application **to be able to work offline**, this is why the dataset is embedded into the application directly.

[View on AppStore](https://itunes.apple.com/tr/app/lys-edebiyat-yazar-kitap-bilgi/id1174623916?l=tr&mt=8)  
[View on Google Play](https://play.google.com/store/apps/details?id=io.cordova.lysedebiyat&hl=tr)

# Currently Used Libraries
The libraries that are used while developing the Android application is as follows:
- [jQuery](https://github.com/jquery/jquery)
- [SweetAlert](https://github.com/t4t5/sweetalert)
- [FastClick](https://github.com/ftlabs/fastclick)
