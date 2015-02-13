---
layout: post
title:  "Cordova 설치"
categories: hybrid 
---
####**서론**


[Cordova 홈페이지][cordova]에 들어가 보면 .zip파일을 제공하고 있긴 하지만 Cordova CLI(Command-Line Interface)로 설치하는 것을 권장한다. CLI란 무엇있가..?
Cordova CLI는 다양한 모바일 플랫폼의 어플리캐이션을 만들고 빌드하고 실행하고 배포할 수 있다. 
CLI를 설치해 보자.

******

####**CLI 설치**
Cordova CLI설치를 위해서는 [Node.js](/nodejs/2014/11/17/nodejs-install.html/)가 미리 설치되어 있어야 한다.
Cordova CLI는 npm(Node Packaged Module) 패키지에 배포되어 있으므로 npm으로 설치할 수 있다.
git은 직접적으로 사용하지는 않지만 CLI는 새로운 프로젝트를 만들 때 뒤에서 필요한 자료들을 git을 이용해 다운로드 한다.

Linux & Mac OS X
   
     sudo npm install -g cordova

****** 

####**환경변수 등록**
Cordova의CLI를 사용하여 Android 플랫폼 기본 코드를 만들기 위해서는 안드로이드 SDK의 platform-tools와 tools폴더가 PATH 에 잡혀 있어야 한다. 
그리고 빌드를 하기 위해서는 apache ant 가 설치되어 있어야 하며 ant의 bin폴더가 PATH에 잡혀 있어야 한다.
그래서 필자의 경우 Mac OS x 기준으로 .bash_profile 파일에 아래와 같이 잡혀있다.(Android 기준)
    export PATH=${PATH}:/Users/choijiho/Desktop/Android/android-sdk-macosx/platform-tools:/Users/choijiho/Desktop/Android/android-sdk-macosx/tools:/Users/choijiho/Desktop/Android/apache-ant-1.9.4/bin

******

####**AVD(Android Virture Device) 설정**
eclipse에서 AVD를 설정해야 corvado emulate android 명령을 실행 할 수 있다.








[cordova]:            http://cordova.apache.org/ 
[android_download]:   http://developer.android.com/sdk/index.html
