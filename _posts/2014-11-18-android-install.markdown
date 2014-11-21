---
layout: post
title:  "Android 개발환경 구축"
categories: android 
---
####**서론**


지금까지 Android 개발환경 구성을 50번정도는 해본 것 같다. 
이런 노가다성 경험들이 많은 도움이 되었다. 이제는 문제가 생기면 대충 어느부분에서 문제가 되니 어떻게 해결 해야겠군! 하며 눈에 보인다. 
처음에는 많이 삽질도 하고 다른사람 개발환경 세팅해주느라 여러가지 환경도 접해보니 그러한 노하우가 쌓인것 같다. 
자랑하려고 쓴 글이 아니라 개발환경도 중요하다는 말이 하고 싶었다. 

******

####**설치**


본론으로 들어가서 Android 개발환경은 Windows, Mac OX X가 거의 동일하다고 보면 된다.
우선 JDK를 설치하고, IDE인 Eclipse를 설치하고, ADT(Android Development Kit)을 설치하고, SDK Manager를 통해서 원하는 SDK버전을 다운받으면 된다. 
사실 이런 일련의 과정들이 이제는 [안드로이드 개발자 홈페이지][android_download]에 들어가면 파일하나 다운받아서 압축을 풀면 끝이다. 
나날이 발전하는 안드로이드 개발자 홈페이지에 2014년11월 현재 기준으로 `Download Eclipse ADT with the Android SDK for Windows`버튼을 누르면 신비의 파일이 다운로드 된다. 
이름하여 `Eclipse ADT bundle` 이다. 
여기에 포함된 것은 아래와 같다

  - Eclipse + ADT plugin
  - Android SDK Tools
  - Android platform-tools
  - A version of the android platform
  - A version of the android system image for the emulator

압축만 풀면 안드로이드 개발이 가능하다. 또한 IntelliJ 기반의 `Android Studio`도 간단하게 설치할 수 있지만 아직까지는 Beta버전이므로 Eclipse 기반의 개발환경을 구축 할 것을 권장한다.

******

####**한마디..**


웹에서 찾아보면 개발환경 구축과 관련된 글들이 많이 있다. 
이 블로그의 목적은 소프트웨어 개발에 포커스를 맞추도록 하겠으며 자세한 설치과정을 구체적으로 설명하지는 않겠다. 
단지 하고싶은 말은 우리가 공부를 하거나 회사에서 일을 할 때 책상 등 주변환경이 중요하듯 개발할때도 환경이 중요하므로 개발에 필요한 요소에 대해서는 어떤기능을 하는지 알아두는 편이 좋다는 것이다. 

[android_download]:   http://developer.android.com/sdk/index.html
