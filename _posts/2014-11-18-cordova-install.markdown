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
Cordova CLI설치를 위해서는 [Node.js](/nodejs/2014/11/17/nodejs-install.html/)와 [git client][git_install] 가 미리 설치되어 있어야 한다.
Cordova CLI는 npm(Node Packaged Module) 패키지에 배포되어 있으므로 npm으로 설치할 수 있다.
git은 직접적으로 사용하지는 않지만 CLI는 새로운 프로젝트를 만들 때 뒤에서 필요한 자료들을 git을 이용해 다운로드 한다.

Linux & Mac OS X
   
     sudo npm install -g cordova
    

[cordova]:            http://cordova.apache.org/ 
[android_download]:   http://developer.android.com/sdk/index.html
