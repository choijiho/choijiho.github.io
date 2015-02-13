---
layout: post
title:  "express application 구조" 
categories: nodejs 
---
[express application을 생성](/nodejs/2015/02/05/create-express-application.html/)하면 기본적으로 만들어지는 파일과 폴더에 대해 알아보자.


- app.js : c, java로 치면 main 같은 함수다. 필요한 모듈을 불러오고, 설정을 한다.
- bin/ : 실행파일이 있는 디렉토리다. 
- package.json : application 정보를 담고 있는 파일이며, 가장 중요한 내용은  application에 필요한 모듈을 정의하고 npm install 명령으로 해당 모듈을 설치 할 수 있다.
- public/ : front-end 파일(html, javascript, stylesheet, images)이 보관되는 디렉토리다.
- routes/ : 사용자가 입력한 URL에 따라 처리해야 하는 경로를 정의하는 파일을 관리하는 디렉토리다.
- views/ : 화면을 표현해주는 템플릿 엔진인 jade파일이 저장되어 있다.



