# is-ramen-frontend

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

### install 
- setting > workspace > json파일에 다음을 입력
  ₩₩₩
  {
	// 빨간줄로 이제 에러를 빨간줄로 보여줌.
	"eslint.enable": true,
	"editor.codeActionsOnSave": {
		// 저장할 때마다 린트가 자동으로 코드를 고쳐줌.
		"source.fixAll.eslint": true,
		// import 되지 않은 파일들을 자동으로 import 구문을 추가해줍니다.
		"source.addMissingImports": true
	},
	// 파일을 저장할 때마다 포맷팅 실행
	"editor.formatOnSave": true
}
₩₩₩

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
