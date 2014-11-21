---
layout: post
title:  "Ionic 과의 첫만남"
categories: hybrid 
---

####**안녕?**
node.js와 AngularJS기반으로 프로젝트를 하다 보니 밥줄인 Android는 뒤로 하고 javascript에 빠져 지내게 되었다.
그러던 중 알게된 [Ionic framework][ionic]. 홈페이지 소개에 의하면 `Ionic`은 [Sass][sass]와 [AngularJS][angular] 로 만들어진 오픈소스로 모바일에 최적화된 HTML, CSS, JS 컴포넌트와 제스처, 그리고 높은 수준으로 앱과 상호작용할 수 있도록 만드는 툴을 제공한다.  그렇다. 하이브리드 앱 프레임워크 이다.

______

####**하이브리드 앱**
하이브리드 앱은 Facebook, LinkedIn에서 이미 쓴맛을 보고 갈아치운 개발방법인데 다시금 관심을 갖는 이유는 SNS에서 누군가 Ionic을 써본 사람이 있냐는 글을 보게 된 이후부터이다. Ionic에 대해 알아보기 전에 현재 [하이브리드 앱 상황에 대해 잘 정리해놓은 글][state_of_hybrid]을 보고 깊이 알아보게 되었다. 하이브리드 앱 하면 가장 문제가 많았던 부분이 `성능`이였다. 성능 부분에 대해 얼마나 발전이 되었는지 찾아보니 [괜찮은 예][performance_example]를 몇개 찾아 볼 수 있었다.

______

####**채택**
그럼.. 지금 하고있는 프로젝트도 하이브리드 앱을 고려해 볼까? 라는 생각을 하며.. 발을 들여놨다. 현재 나홀로.. 기획, Front-End, Back-End, Server관리, DB, Android App을 하고 있는데 아직까지 iOS개발자를 찾지 못했다. 모바일을 하이브리드 앱으로 진행하면 iOS도 커버되니 좋지 아니한가. 우선 오늘의 목표는 mac에서 개발환경을 세팅하고, ionic으로 hello world 앱을 만드는 것이다. 

______

####**시작..**

순서는 이러하다. 

1. 개발을 위해 필요한 것 들 설치 
  - Android 개발환경 
  - Node.js
  - Cordova
  - Ionic

2. 앱 개발 

Node.js는 npm을 사용하기 위해 설치가 필요하다. npm을 사용해서 Cordova와 Ionic을 설치한다.
근데 [Cordova][cordova]는 무엇?  홈페이지 설명에 따르면 모바일 개발 오픈소스 프레임워크 이다. 뭥뮈? Ionic도 Cordova도 둘다 프레임워크?  간단하게 말하면 Cordova가 기본이 되는 프레임워크 이고 그 위에 Ionic이 올라간다고 생각하면 쉬울 것 같다.  PhoneGap은 무엇? 비유를 하자면 webkit과 chrome의 관계가 Cordova와 PhoneGap의 관계라고 생각할 수 있다. Cordova, PhoneGap모두 여러가지 모바일 플랫폼에 HTML, CSS, JS기반으로 앱을 만들고자 할 때 뼈대를 만들어 주는 프레임워크이다.  
그럼 설치해보자. 

______


#### [Android 개발환경 구축](/android/2014/11/18/android-install.html/)

#### [Node.js 설치](/nodejs/2014/11/17/nodejs-install.html/)

#### [Cordova 설치](/hybrid/2014/11/18/cordova-install.html/)

#### [Ionic 설치](/hybrid/2014/11/18/ionic-install.html/)

#### 환경변수 세팅 



[ionic]:              http://ionicframework.com/
[sass]:               http://sass-lang.com/
[angular]:            https://angularjs.org/
[state_of_hybrid]:    http://developer.telerik.com/featured/the-state-of-hybrid-mobile-development/
[performance_example]:https://www.polymer-project.org/components/core-list/demo.html
[cordova]:            http://cordova.apache.org/
