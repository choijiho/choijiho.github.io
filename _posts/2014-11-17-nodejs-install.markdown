---
layout: post
title:  "Node.js 설치"
categories: nodejs 
---
Node.js 설치는 간단하다.


설치방법은 Windows와 Mac OS X 는 [Node.js 홈페이지에][nodejs]에서 제공하는 설치프로그램(Installer)를 다운받아 쉽게 설치 가능하다. Linux는 [Package Manager를 통해서 설치하는 방법][ubuntu_install]을 추천한다. Package Manager를 몰라도 된다. 아래 코드를 따라하면 된다.

**[Windows Installer][nodejs_download]**

**[Max OS X Installer][nodejs_download]**

**Ubuntu Package Manager로 Node.js 설치**

    curl -sL https://deb.nodesource.com/setup | sudo bash -
    sudo apt-get install -y nodejs



[ionic]:              http://ionicframework.com/
[sass]:               http://sass-lang.com/
[angular]:            https://angularjs.org/
[state_of_hybrid]:    http://developer.telerik.com/featured/the-state-of-hybrid-mobile-development/
[performance_example]:https://www.polymer-project.org/components/core-list/demo.html
[nodejs]:             http://nodejs.org/
[nodejs_download]:    http://nodejs.org/download/
[ubuntu_install]:     https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager#debian-and-ubuntu-based-linux-distributions
