typescript-settings(React)

1. 웹팩 설치
   npm install --save-dev webpack webpack-cli
2. 리액트 설치
   npm install --save react react-dom
3. 타입스크립트를 위한 리액트 타입 설치
   npm install --save-dev @types/react @types/react-dom
4. 타입스크립트를 자바스크립트로 컴파일 하기 위한 로더와
   타입스크립트 소스를 디버깅하기 위한 소스맵 설치
   npm install --save-dev typescript ts-loader source-map-loader
5. 타입스크립트 환경 설정을 위한 tsconfig.json 설정
6. webpack 설정을 위한 webpack.config.js 생성
7. 번들한 css, js 파일들을 html에 자동으로 추가하기 위한 플러그인 설정
   npm i --save-dev html-webpack-plugin
8. 하위버전 자바스크립트 지원을 위한 Bable 설치
   npm install @babel/cli @babel/core @babel/preset-typescript --save-dev
9. Babel 설정을 위한 .babelrc 셋팅
   npm install @babel/preset-env @babel/preset-react --save-dev
   npm install babel-loader --dev
10. 환경 별 Webpack 사용을 위한 webpack-merge 설치(tools)
    npm i webpack-merge(미사용)
12. 환경변수 설정을 위한 cross-env 설치
    npm install --save-dev cross-env
