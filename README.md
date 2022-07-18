
<!--
**chlrkdgml77/chlrkdgml77** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# joseph0926
## chlrkdgml77 gitHub



개발 관련 공부 기록을 남기는 gitHub입니다.

- 프론트엔드
- 백엔드
- 그 외(DB, 서버, 알고리즘..)

## History

- 단국대학교(천안) 공공정책학과 재학 (2019 ~)
- KH 정보교육원 국비과정 수료(2022.03 ~ 2022.09)
- 추가
- 추가
- 추가

2021.11부터 개발에 관심을 갖게 되었고, 자바의 정석을 시작으로 웹 관련 공부를 시작하였습니다.
2022.03부터 KH 정보교육원 국비 과정을 듣기 시작하였습니다.
시작부터 지금까지 공부는 [인프런](https://www.inflearn.com/), [유데미](https://www.udemy.com/ko/), 구글검색등을 이용하고 있습니다.

> 추가



## Tech

### Back-End

- Java - 자바의 기본문법과, 최신 경향을 학습
    - [자바의 정석](http://www.yes24.com/Product/Goods/24259565)
    - [모던 자바 인 액션]
    - [이펙티브 자바]
- Spring - 다양한 미니프로젝트 진행
   - [스프링-기본](https://github.com/chlrkdgml77/spring_basic)
   - [모든 개발자를 위한 HTTP 웹 기본 지식](https://github.com/chlrkdgml77/HTTP)
   - [스프링 MVC 1, 2]
   - [스프링 DB 1, 2]
   - [JPA]
- NodeJS - 프로젝트(나중에 추가)
    - [NodeJS 완벽 가이드]


### Front-End

- [HTML, CSS](https://github.com/chlrkdgml77/HTML-CSS)
- JavaScript - HTML+CSS+JS를 이용해 웹 사이트 구현
    - [JavaScript](https://github.com/chlrkdgml77/JavaScript)
- TypeScript - (나중에 수정)
    - [Typescript]
- React - (나중에 수정)
    - [React 완벽 가이드](https://github.com/chlrkdgml77/React_Practice)




## Project

추가 예정

Dillinger requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
cd dillinger
npm i
node app
```

For production environments...

```sh
npm install --production
NODE_ENV=production node app
```

## Plugins

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:

```sh
node app
```

Second Tab:

```sh
gulp watch
```

(optional) Third:

```sh
karma test
```

#### Building for source

For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

## Docker

Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on
your host. In this example, we simply map port 8000 of the host to
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=dillinger <youruser>/dillinger:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
