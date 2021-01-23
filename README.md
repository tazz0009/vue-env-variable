# vue 실행 모드와 환경 변수 설정

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### index.html 파일에서 다음과 같이 호출합니다.

...

<p><%= VUE_APP_VARIABLE %></p>
...

### 설정한 변수를 스크립트에서 호출하고 싶다면 다음과 같은 형태로 호출합니다.

```
process.env.VUE_APP_VARIABLE //"test variable"
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
