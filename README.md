
<!--
**chlrkdgml77/chlrkdgml77** is a โจ _special_ โจ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- ๐ญ Iโm currently working on ...
- ๐ฑ Iโm currently learning ...
- ๐ฏ Iโm looking to collaborate on ...
- ๐ค Iโm looking for help with ...
- ๐ฌ Ask me about ...
- ๐ซ How to reach me: ...
- ๐ Pronouns: ...
- โก Fun fact: ...
-->

# joseph0926
## chlrkdgml77 gitHub



๊ฐ๋ฐ ๊ด๋ จ ๊ณต๋ถ ๊ธฐ๋ก์ ๋จ๊ธฐ๋ gitHub์๋๋ค.

- ํ๋ก ํธ์๋
- ๋ฐฑ์๋
- ๊ทธ ์ธ(DB, ์๋ฒ, ์๊ณ ๋ฆฌ์ฆ..)

## History

- ๋จ๊ตญ๋ํ๊ต(์ฒ์) ๊ณต๊ณต์ ์ฑํ๊ณผ ์ฌํ (2019 ~)
- KH ์ ๋ณด๊ต์ก์ ๊ตญ๋น๊ณผ์  ์๋ฃ(2022.03 ~ 2022.09)
- ์ถ๊ฐ
- ์ถ๊ฐ
- ์ถ๊ฐ

2021.11๋ถํฐ ๊ฐ๋ฐ์ ๊ด์ฌ์ ๊ฐ๊ฒ ๋์๊ณ , ์๋ฐ์ ์ ์์ ์์์ผ๋ก ์น ๊ด๋ จ ๊ณต๋ถ๋ฅผ ์์ํ์์ต๋๋ค.
2022.03๋ถํฐ KH ์ ๋ณด๊ต์ก์ ๊ตญ๋น ๊ณผ์ ์ ๋ฃ๊ธฐ ์์ํ์์ต๋๋ค.
์์๋ถํฐ ์ง๊ธ๊น์ง ๊ณต๋ถ๋ [์ธํ๋ฐ](https://www.inflearn.com/), [์ ๋ฐ๋ฏธ](https://www.udemy.com/ko/), ๊ตฌ๊ธ๊ฒ์๋ฑ์ ์ด์ฉํ๊ณ  ์์ต๋๋ค.

> ์ถ๊ฐ



## Tech

### Back-End

- Java - ์๋ฐ์ ๊ธฐ๋ณธ๋ฌธ๋ฒ๊ณผ, ์ต์  ๊ฒฝํฅ์ ํ์ต
    - [์๋ฐ์ ์ ์](http://www.yes24.com/Product/Goods/24259565)
    - [๋ชจ๋ ์๋ฐ ์ธ ์ก์]
    - [์ดํํฐ๋ธ ์๋ฐ]
- Spring - ๋ค์ํ ๋ฏธ๋ํ๋ก์ ํธ ์งํ
   - [์คํ๋ง-๊ธฐ๋ณธ](https://github.com/chlrkdgml77/spring_basic)
   - [๋ชจ๋  ๊ฐ๋ฐ์๋ฅผ ์ํ HTTP ์น ๊ธฐ๋ณธ ์ง์](https://github.com/chlrkdgml77/HTTP)
   - [์คํ๋ง MVC 1, 2]
   - [์คํ๋ง DB 1, 2]
   - [JPA]
- NodeJS - ํ๋ก์ ํธ(๋์ค์ ์ถ๊ฐ)
    - [NodeJS ์๋ฒฝ ๊ฐ์ด๋]


### Front-End

- [HTML, CSS](https://github.com/chlrkdgml77/HTML-CSS)
- JavaScript - HTML+CSS+JS๋ฅผ ์ด์ฉํด ์น ์ฌ์ดํธ ๊ตฌํ
    - [JavaScript](https://github.com/chlrkdgml77/JavaScript)
- TypeScript - (๋์ค์ ์์ )
    - [Typescript]
- React - (๋์ค์ ์์ )
    - [React ์๋ฒฝ ๊ฐ์ด๋](https://github.com/chlrkdgml77/React_Practice)




## Project

### ๋จํก ํ๋ก์ ํธ

[GroupTalk_project](https://github.com/chlrkdgml77/GroupTalk_project.git)

๋จํก์ ์ํ ์น ์ฌ์ดํธ๋ฅผ ์ ์ํ๋ ํ๋ก์ ํธ์๋๋ค.

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
