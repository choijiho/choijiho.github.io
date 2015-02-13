---
layout: post
title:  "express application 생성"
categories: nodejs 
---
웹 프레임워크인 express를 설치했으면 이제 애플리케이션을 만들면 된다.
application을 만들기 위해서는  express-generator를 사용하면 된다.

    $ npm install -g express-generator

express 2014년도 버전에는 별도로 express-generator를 설치하지 않아도 
애플리케이션생성이 가능했으나 변경되어 express-generator를 통해서 애플리케이션을 설치할 수 있다.

설치가 완료 되었으면 `microblog`  애플리케이션을 생성한다.

    $ express microblog

위와같이 입력하면 아래와 같이 여러가지 파일과 폴더가 생성된다.

- app.js
- bin/
- package.json
- public/
- routes/
- views/

