# webpack
https://joshua1988.github.io/webpack-guide/

npm init -y : package.json 기본값 
[지역설치]
npm install packagename : 프로젝트 내 node_modules에 설치 
npm uninstall packagename : 프로젝트 내 node_modules에서 제거 
--save-prod >> 로직과 연관되는 모듈들 (jquery, react, angular 등)
--save-dev [or -D] 옵션 추가 시  "devDependencies"에 포함 >> 개발 단계에서 필요한 모듈들 (webpack, js-compression 등)

[전역설치]
npm install gulp --global : %USERPROFILE%\appdata\roaming\npm\node_modules (윈도우) /usr/local/lib/node_modules (맥)
> 시스템레벨에서 사용할 JS LIB을 설치할 때 사용

