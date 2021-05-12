# Node.js란?
Chrome V8 JavaScript 엔진으로 빌드된 `JavaScript 런타임`</br>(프로그래밍 언어가 동작하는 환경, 즉 `js가 동작하는 프로그래밍 환경을 의미`)  
설치 시 NPM 자동 설치
</br>
</br>
>Node.js가 작동하는 환경
- Node.js가 설치된 컴퓨터
- 브라우저 (Chrome)   
---  
</br>

>NPM(Node Package Manager)
- 전세계 개발자들이 만든 다양한 기능(패키지모듈)들을 관리
- $ npm install xxx
---
</br>

>유의적 버전
- Major.Minor.Patch
- 12.14.1
---
</br>

>npm install xxx
- lodash 같은 프로젝트 내부에서 사용하는 패키지 설치
- 설치된 내용들은 node_modules로 들어가게 됨
- 그 내역은 package.json의 devDependencies랑 dependencies에 명시되게 됨
- 걔들이 내부적으로 사용하는 또다른 패키지들은 lock.json에 기재
--- 