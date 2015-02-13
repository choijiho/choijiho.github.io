---
layout: post
title:  "Ionic Hello World!"
categories: hybrid 
---
####**프로젝트 시작**

간단한 명령어로 Ionic에서 제공하는 템플릿으로 프로젝트를 생성한다.  
(템플릿은 blank, tab, sidemenu가 있다.)

    $ ionic start myApp tabs


위의 명령어를 실행하면 github와 cordova 사이트에서 여러가지 파일들을 받아와 프로젝트에 필요한 파일들을 만든다.
파일이 만들어 지면 해당 프로젝트 폴더로 들어가 플랫폼을 설정하고 빌드하고 실행해보자.
(여기 예제는 android를 기준으로 한다 ios에서 하고 싶으면 android 만 ios로 변경하면 된다.)

    $ ionic platform add adnroid
    $ ionic build android
    $ ionic emulate android

위의 명령어를 실행하면 AVM이 실행되면서 Ionic 인트로 이미지가 보일 것이다.
cordova 설치 포스팅에 언급했지만 위의 명령어를 실행하기 위한 조건은 아래와 같다.

    $ ionic platform add adnroid  : Android SDK 디렉토리의 platform-tools, tools디렉토리 PATH등록
    $ ionic build android         : apache ant 디렉토리의 bin 디렉토리 PATH등록
    $ ionic emulate android       : AVD(Android Virture Device)등록

설치가 완료 되었으면 eclipse에서 생성된 프로젝트를 import하고 Eclipse Marketplace에서 HTML Editor를 설치한다.

