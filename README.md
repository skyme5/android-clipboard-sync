![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84.svg?style=for-the-badge&logo=android-studio&logoColor=white)
![MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge&logoColor=white)

# Android Clipboard Sync

A simple Android Service to send clipboard content from your device to Server

This will register a clipboardChange `ClipboardListener` and post any change to 
preconfigured url endpoint (defaults to `http://192.168.0.100/api/v2/clipboard/share`)