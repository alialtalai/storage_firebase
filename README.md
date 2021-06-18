# storage_firebase

 This flutter app allow you to learn how you can upload image to Firebase Storage with simple UI to easy to understand

<p float="left">
   <img src="https://user-images.githubusercontent.com/34947914/122567689-fc63d580-d059-11eb-9744-b20b8b0eca3e.png" width="200" height="400"/>
  <img src="https://user-images.githubusercontent.com/34947914/122567818-25846600-d05a-11eb-8637-ed66fdd3f7e3.png" width="200" height="400" />
</p>


## Getting Started

Requirement:
1. You have to connect to Firebase and add GoogleServices-Info file to your project
2. in Firebase website open your project and go to Storage and make sure in the 'rule' you allow read and write 
 ```javaScript
 allow read, write: if true;
 ```
3. add plugin to pubspec.yaml 
- [image_picker: ^0.7.2+1](https://pub.dev/packages/image_picker) or latest, Read Configuratoin of the plugin
- [flutter_animation_progress_bar: ^1.0.6](https://pub.dev/packages/flutter_animation_progress_bar) or latest
- [firebase_storage: ^8.1.0](https://pub.dev/packages/firebase_storage) or latest
- [firebase_core: ^1.2.0](https://pub.dev/packages/firebase_core) or latest


