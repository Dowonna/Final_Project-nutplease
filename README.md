# ๐2021 Playdata Final Project | Nutplease(Netflix Clone + Content-Based Movie Recommendation System)

![Python](https://img.shields.io/badge/Python-3.8-blue)
![PaaS](https://img.shields.io/badge/PaaS-Heroku-blueviolet)
![Framework](https://img.shields.io/badge/Framework-Flask-black)
![Frontend](https://img.shields.io/badge/Frontend-HTML/CSS/JS-green)
![API](https://img.shields.io/badge/API-Netflix/TMDB-red)

## ๐งญOutline / ๊ฐ์

### ์ฃผ์  ์ ์  ๋ฐฐ๊ฒฝ, ๊ธฐํ ๋ฐฐ๊ฒฝ

์ฝ 3๊ฐ์์ด ๋๋ ์๊ฐ๋์ Java ๋ฑ์ ์ธ์ด๋ฅผ ์ด์ฉํ ํ๋ก๊ทธ๋๋ฐ์ ๋ฐฐ์ฐ๊ณ  ๊ด๋ จ ํ๋ก์ ํธ๋ง ํ๋ค ์ฒ์๋ง๋ Python์ ์ด์ฉํ ๋ฐ์ดํฐ ๋ถ์์ ๋๋ถ๋ถ์ ํ์๋ค์๊ฒ ๋ฏ์  ์กด์ฌ์์ต๋๋ค. ํ์ง๋ง ๋ณต์กํ ๋ณด์ด๊ธฐ๋ง ํ๋ ๋ฐ์ดํฐ๋ฅผ ๋ค๋ฃจ๊ณ  ์๊ฐํํ๋ ๊ณผ์ ์์ ํฅ๋ฏธ๋ฅผ ๋๊ปด ๋ฐ์ดํฐ ๋ถ์์ ์ ์  ์ฌ๋ฏธ๋ฅผ ๋ถํ๊ธฐ ์์ํ๊ณ  ๋ค๋ฅธ ํ์๋ค์๊ฒ๋ ์ด๋ฅผ ๊ณต์ ํ๊ณ  ์ถ๋ค๋ ์๊ฐ์์ ์ฃผ์  ์ ์ ์ด ์์๋์์ต๋๋ค. 

### ๋ชฉํ ๋ฐ ์ํ ์ ์ ์๋ ๊ทธ๋ฆฌ๊ณ  ์ปจ์

์ ํฌ์ ์ฒซ๋ฒ์งธ ๋ชฉํ๋ '๋ฐ์ดํฐ ๋ถ์์ D์๋ ๋ชจ๋ฅด๋ ์ด์ง๋ค๋ ์ฝ๊ฒ ์ดํดํ  ์ ์๋ ์๋ฃ๋ฅผ ๋ง๋ค์!' ์๋๋ค. ์ฒ์์ ๋ฐ์ดํฐ ๋ถ์์ ๊ธฐ์ด์ ์ธ ๊ฒ๋ค์ ๋ํด ๋ฐฐ์ฐ๊ณ  ๋ค์ ํํธ์์๋ ์ฐ๋ฆฌ์๊ฒ ์น์ํ [๋ทํ๋ฆญ์ค(Netflix Movies and TV Shows)](https://www.kaggle.com/shivamb/netflix-shows)์ ๋ฐ์ดํฐ๋ฅผ ์ด์ฉํ์ฌ ๋ฐ์ดํฐ ๋ถ์ ์ค์ต์ ์งํํ์์ต๋๋ค.

### ๊ณํ

* Notion์ ๋ฐ์ดํฐ ๋ถ์์ ๊ธฐ์ด์ ์ธ ์ง์์ ์ํ ๊ต์ก์๋ฃ๋ฅผ ์์ฑ

* ๋ทํ๋ฆญ์ค ๋ฐ์ดํฐ ๋ถ์ ํ, ์ค๋ช๊ณผ ํด์ ์์ฑ

* ๋ฒ ์ด์ค๋ผ์ธ(Baseline) ๋ชจ๋ธ ์์ฑ ํ, ์ถ์ฒ ์๊ณ ๋ฆฌ์ฆ ๊ตฌํ

---

## ๐Getting Started / Flask ์ ํ๋ฆฌ์ผ์ด์ ๋ฐ Docker์ ๊ฐ๋จํ ์ฌ์ฉ๋ฒ

Python Flask ์ ํ๋ฆฌ์ผ์ด์์ Heroku์ ์ง์  ๋ฐฐํฌํ๋ ๊ฒ์ด ๊ฐ๋ฅํฉ๋๋ค. ํ์ง๋ง ๋ฐฐํฌ๋ฅผ ๋ ๋ง์ด ์ ์ดํ๊ฑฐ๋ Heroku์๋ง ์์กดํ๊ณ  ์ถ์ง ์์ ๊ฒฝ์ฐ์๋ Docker๋ฅผ ์ฌ์ฉํ์ฌ Python ์ ํ๋ฆฌ์ผ์ด์์ ์ปจํ์ด๋ํ ํ ํ, ๋ง๋ค์ด์ง ์ปจํ์ด๋๋ฅผ Heroku์ ๋ฐฐํฌํ  ์ ์์ต๋๋ค. ์ด๋ ๊ฒ Docker๋ฅผ ์ฌ์ฉํ๋ฉด ์ ํ๋ฆฌ์ผ์ด์์ ๋ชจ๋  ํด๋ผ์ฐ๋ ์ ๊ณต ์์ฒด(AWS, GCP ๋ฑ)์์๋ ์ฌ์ฉํ  ์ ์๋ค๋ ์ฅ์ ์ด ์์ต๋๋ค.

์๋ก ์ด ๋ค์ ๊ธธ์๋๋ฐ, ์ค์น ๋ฐฉ๋ฒ์ ๊ฐ๋จํ๊ฒ ๋ค์๊ณผ ๊ฐ์ด ์ ๋ฆฌํ  ์ ์์ต๋๋ค(Windows ์ฌ์ฉ์ ๊ธฐ์ค).

* **[Heroku ๊ฐ์](https://www.heroku.com)**
* **[Hekoku ์ ์ฉ CLI ์ค์น](https://devcenter.heroku.com/articles/heroku-cli#download-and-install)**
* **[Docker Desktop for Windows ์ค์น](https://hub.docker.com/editions/community/docker-ce-desktop-windows)**

์์ ์ค์น ๋ฐฉ๋ฒ์ ๋ฐ๋ผ ์ค์น๋ฅผ ์๋ฃํ์ผ๋ฉด ๋ค์์ผ๋ก ๊ฐ์ํ๊ฒฝ์ ๊ตฌ์ฑํ๋๋ก ํ๊ฒ ์ต๋๋ค.

### ๊ฐ์ํ๊ฒฝ ์์ฑ

๊ฐ์ํ๊ฒฝ์ ๊ตฌ์ฑํ๋ ๊ฐ์ฅ ํฐ ์ด์ ๋ ํ๋ก์ ํธ๋ง๋ค ํ์ํ ํจํค์ง๋ค์ ๋ฒ์ ์ด ๋ค๋ฅผ ์ ์๋๋ฐ, ๋ณด๋ค ํจ๊ณผ์ ์ผ๋ก ์ฒ๋ฆฌํ๊ธฐ ์ํด์์๋๋ค.

๋ค์์ ๋ช๋ น์ด๋ฅผ ๋ช๋ น ํ๋กฌํํธ์ ์๋ ฅํ๋ฉด ์ฌ์ฉ ์ค์ธ Python ๋ฒ์ ์ ๋ง๊ฒ ๊ฐ์ํ๊ฒฝ์ด ์์ฑ๋ฉ๋๋ค.

```
$ python -m venv py38  # ๋๋ถ๋ถ์ ํ๋ก์ ํธ์์ ์ฌ์ฉํ๋ ์ด๋ฆ์ธ .venv๋ก ํ๋ ๊ฒ์ ๊ถ์ฅํฉ๋๋ค.
```

๊ฐ์ํ๊ฒฝ์ ๊ตณ์ด Git ๋ฑ์ ์์ค ๋ฒ์  ๊ด๋ฆฌ ์์คํ์ ์๋ก๋ํ  ํ์๋ ์์ผ๋ฏ๋ก "py38" ๋๋ ํ ๋ฆฌ๋ฅผ **_.gitignore_** ํ์ผ์ ์ถ๊ฐํด ์ค๋๋ค.

```
$ echo py38 >> .gitignore
```

### ๊ฐ์ํ๊ฒฝ ํ์ฑํ

๊ฐ์ํ๊ฒฝ์ ํ์ฑํํ๊ธฐ ์ํด์๋ ํ๋ก์ ํธ ํด๋์ ์ง์ํ ํ ๋ค์์ ๋ช๋ น์ด๋ฅผ ๋ช๋ น ํ๋กฌํํธ์ ์๋ ฅํ๋๋ก ํฉ๋๋ค.

```
$ py38\Scripts\activate
```

๊ฐ์ํ๊ฒฝ์ด ํ์ฑํ๋ ๊ฒ์ ํ์ธํ๋ ค๋ฉด ๋ช๋ น ํ๋กฌํํธ  ์์ `(py38)`์ด๋ผ๊ณ  ๋ถ์ผ๋ฉด ๊ฐ์ํ๊ฒฝ์ด ํ์ฑํ๋ ๊ฒ์๋๋ค.

### Flask ํจํค์ง ์ค์น

๋ค์์ผ๋ก Flask ์ ํ๋ฆฌ์ผ์ด์์ ์ค์น ๋ฐฉ๋ฒ์ ์์๋ณด๊ฒ ์ต๋๋ค.

๋จผ์  `pip`๋ฅผ ์ด์ฉํด Flask๋ฅผ ์ค์นํฉ๋๋ค. 

```
$ pip install Flask==1.1.2
```

๊ทธ๋ฆฌ๊ณ  ๋ชจ๋  ์ข์์ฑ(Dependencies)์ ๋ณด๊ดํ  **_requirements.txt_** ํ์ผ์ ์์ฑํ๊ธฐ ์ํด `pip freeze > requirements.txt` ๋ช๋ น์ด๋ฅผ ๋ช๋ น ํ๋กฌํํธ์ ์๋ ฅํ๋ฉด ํด๋น ํ์ผ์ด ํ๋ก์ ํธ ํด๋ ๋ด์ ์๋์ผ๋ก ์์ฑ๋ฉ๋๋ค.

```
$ pip freeze > requirements.txt
Flask==1.1.2
Jinja2==2.11.3
itsdangerous==1.1.0
MarkupSafe==1.1.1
click==7.1.2
Werkzeug==1.0.1
```

๋ง์ฝ ๊ฐ๋ฐ ํ๊ฒฝ์ ๋ณต๊ตฌํ๊ณ  ์ถ์ ๊ฒฝ์ฐ์๋ ๋ค์์ ๋ช๋ น์ด๋ฅผ ๋ช๋ น ํ๋กฌํํธ์ ์๋ ฅํ๋ฉด **_requirements.txt_** ์ ์๋ ํจํค์ง๋ฅผ ์๋์ ์ค์นํด ์ค๋๋ค.

```
$ pip install -r requirements.txt  # -r : requirements.txt ํ์ผ์์ ํจํค์ง๋ฅผ ์ค์นํ๊ธฐ ์ํ ์ต์์๋๋ค.
```

### Flask ํจํค์ง ๊ฐ๋จ ์ฌ์ฉ๋ฒ

Python Flask ์ ํ๋ฆฌ์ผ์ด์ ์คํฌ๋ฆฝํธ ํ์ผ์ธ **_main.py_** ๋ฅผ ์์ฑํด ์ค๋๋ค.

```python
from flask import Flask

import os

app = Flask(__name__)

@app.route('/', methods=['GET'])
def index():
        return 'Welcome to Nutplease Movie Recommendation System :)'  # Index Page

if __name__ == '__main__':
        port = int(os.environ.get("PORT", 5000))  # ํด๋น ์ฝ๋๋ฅผ ์๋ ฅํ์ง ์์ผ๋ฉด Heroku์์ ํฌํธ๋ฅผ ๋ฐ์ธ๋ฉํ  ์ ์์ต๋๋ค.
        app.run(host="0.0.0.0", port=port, debug=True)
```

### Docker ์ค์น ๋ฐ ๊ฐ๋จ ์ฌ์ฉ๋ฒ

๋ค์์ผ๋ก Heroku๋ Flask๋ฅผ ๋ฐ๋ก ์ธ์ํ์ง ๋ชปํ๊ธฐ ๋๋ฌธ์ **[gunicorn](https://gunicorn.org/#quickstart)** ์ด๋ผ๋ ๋ชจ๋์ ์ค์นํด์ผ ํ๋๋ฐ, Windows ๊ธฐ๋ฐ ๋ฐ์ด๋๋ฆฌ๋ฅผ ์ ๊ณตํ์ง ์์ผ๋ฏ๋ก Docker๋ฅผ ์ฌ์ฉํด์ผ ํฉ๋๋ค. ์ฌ๊ธฐ์๋ <u>์ฐ๋ถํฌ(Ubuntu)</u>๋ฅผ ์ปจํ์ด๋ ์ด๋ฏธ์ง๋ก ๊ตฌ์ถํ  ๊ฒ์ด๋ฉฐ, **_Dockerfile_** ์ด๋ผ๋ ์ด๋ฆ์ ์๋ก์ด ํ์ผ์ ์์ฑํ๊ณ  ๋ค์๊ณผ ๊ฐ์ด ์์ฑํ๋๋ก ํฉ๋๋ค.

```
FROM ubuntu:latest
RUN apt-get update -y
RUN apt-get install -y python3-pip python3-dev build-essential  # python3.+ ๋ฒ์  ์ฌ์ฉ ์ ์ธ.
COPY . /app
WORKDIR /app
RUN pip3 install -r requirements.txt
ENTRYPOINT ["python3"]
CMD ["main.py"]
```

Docker ์ด๋ฏธ์ง๋ฅผ ๋น๋ํ๊ธฐ ์ํด ๋ค์์ ๋ช๋ น์ด๋ฅผ ๋ช๋ น ํ๋กฌํํธ์ ์๋ ฅํฉ๋๋ค.

`docker build` ํน์ `docker run`์ ๊ดํ ์ต์์ ์๊ณ  ์ถ๋ค๋ฉด **[Develop with Docker Engine API](https://docs.docker.com/engine/api/)** ์ ์ ์ํ์๋ฉด ๋ฉ๋๋ค.

```
$ docker build -t flask-heroku:latest .  # 'flask-heroku' ๋ถ๋ถ์ ๋ค๋ฅธ ์ด๋ฆ์ผ๋ก ๋์ฒดํด๋ OK
```

๋ก์ปฌ ์๋น์ค๋ฅผ ์คํํ๊ธฐ ์ํด ๋ค์์ ๋ช๋ น์ด๋ฅผ ๋ช๋ น ํ๋กฌํํธ์ ์๋ ฅํฉ๋๋ค.

```
$ docker run -d -p 5000:5000 flask-heroku
```

<u>http://localhost:5000</u>์ ์ ์ํด ๋ณด๋ฉด ๋ก์ปฌ ํ๊ฒฝ์์ ์ ์์ ์ผ๋ก ์คํ์ด ๋๋ ๊ฒ์ ํ์ธํ  ์ ์์ต๋๋ค.

![localhost ์คํ ์์](https://user-images.githubusercontent.com/17983434/114894350-87053a00-9e49-11eb-83d2-05f8dc864bfe.JPG)

## ๐Deployment / ๋ฐฐํฌํ์ ๋ฐฐํฌ!
๋ก์ปฌ ํ๊ฒฝ์์ ์ ์์ ์ผ๋ก ์คํ์ด ๋์๋ค๋ฉด, ์ด์  Heroku์ ๋ฐฐํฌํ๋ ์ผ๋ง ๋จ์์ต๋๋ค.

๋จผ์  Heroku ์ปจํ์ด๋์ ๋ก๊ทธ์ธํด์ผ ํฉ๋๋ค. ๋ค์์ ๋ช๋ น์ด๋ฅผ ๋ช๋ น ํ๋กฌํํธ์ ์๋ ฅํ๋ฉด ์๋ก์ด ๋ธ๋ผ์ฐ์  ์ฐฝ์ด ์ด๋ฆฌ๊ฒ ๋๊ณ  ๋ก๊ทธ์ธ์ ์ฑ๊ณตํ๋ฉด ์ฐฝ์ ๋ซ๋๋ก ํฉ๋๋ค.

```
$ heroku container:login
```

๋ค์์ผ๋ก ์๋ก์ด Heroku ์ ํ๋ฆฌ์ผ์ด์์ ์์ฑํ๊ธฐ ์ํด ๋ค์์ ๋ช๋ น์ด๋ฅผ ๋ช๋ น ํ๋กฌํํธ์ ์๋ ฅํฉ๋๋ค.

```
$ heroku create nutplease  # ์ด๋ฆ์ ์์ ๋กญ๊ฒ ์ง์ ํ  ์ ์์ต๋๋ค.
```

Heroku ์ ํ๋ฆฌ์ผ์ด์์ด ์์ฑ๋์์ผ๋ฉด Heroku์ ์ปจํ์ด๋๋ฅผ ๋ง๋ค๊ธฐ ์ํด ๋ค์์ ๋ช๋ น์ด๋ฅผ ๋ช๋ น ํ๋กฌํํธ์ ์๋ ฅํฉ๋๋ค.

๊ทธ ์ ์ ํ์ธํด์ผํ  ๋ถ๋ถ์ด ์๋๋ฐ, **_main.py_**, **_Dockerfile_**, **_requirements.txt_** ํ์ผ๋ค์ด ๊ฐ์ ํด๋ ๋ด์ ์์นํด์ผ๋ง ์ ์์ ์ผ๋ก ์ค์นํ  ์ ์์ต๋๋ค.

```
$ heroku container:push web --app nutplease
```

์ฑ๊ณต์ ์ผ๋ก ํธ์๋์๋ค๋ฉด ๋ง์ง๋ง์ผ๋ก ๋ฐฐํฌํ๋ ์ผ๋ง ๋จ์์ต๋๋ค.

```
$ heroku container:release web --app nutplease
```

๋ฐฐํฌ์ ์ฑ๊ณตํ๋ค๋ ๋ฉ์์ง๊ฐ ์ถ๋ ฅ๋์๋ค๋ฉด...

```
$ heroku run
```

๋ช๋ น์ด๋ฅผ ์๋ ฅํ๊ฑฐ๋ <u>https://nutplease.herokuapp.com</u>์ ์ ์ํ๋ฉด ์์ ๋ก์ปฌ ํ๊ฒฝ์์ ๋ดค๋ ๊ฒฐ๊ณผ๋ฌผ์ด ์ถ๋ ฅ๋  ๊ฒ์๋๋ค.

## ๐กAcknowledgments / ๋งบ์ผ๋ฉฐ

### ์์ฐ ์์

1.  Docker ์ปจํ์ด๋๊ฐ ์คํ ์ค์ผ ๋ <u>https://nutplease.herokuapp.com</u> ์ฌ์ดํธ์ ์ ์ํ๋ ๋ชจ์ต

![nutplease_example1](https://user-images.githubusercontent.com/17983434/114926150-f8091980-9e6a-11eb-9072-5bcc9937b0ae.gif)

2. ๊ฒ์์ฐฝ์ ์ํ '์ธ์์(Inception)'๋ฅผ ๊ฒ์ํ ํ ์ ์ฌํ ์ํ๋ฅผ ์์ธกํ๋ ๋ชจ์ต

![nutplease_example2](https://user-images.githubusercontent.com/17983434/114926887-d65c6200-9e6b-11eb-91c4-dc1af63d40e4.gif)

### ๋๋ ์ 

1. ์ต์ขํ๋ก์ ํธ ์์์ ์์

๋ฐ์ดํฐ ๋ถ์์ด๊ฑด ์ฝ๋ฉ์ด๊ฑด ๋งค๋ฒ ๋๋ผ๋ ๊ฒ์ด ์์ต๋๋ค. ํ ๋จ์์ ํ๋ก์ ํธ๋ฅผ ์งํํ  ๋๋ง๋ค ๋ณธ์ธ์ด ๋ชปํด์(์์ ์ด ์์ด์) ๋ค๋ฅธ ํ์์๊ฒ ๋ฏผํ๊ฐ ๋ ๊น ํ๋ ๋ถ๋ถ์๋๋ค. ๋ง์ฝ ํ ๋จ์์ ํ๋ก์ ํธ๊ฐ ์๋๋ผ๋ฉด ๋ณธ์ธ์ ํ์ด์ค์ ๋ง์ถฐ ์งํํ๋ฉด ๋๋๋ฐ ๋ฐ๋๋ผ์ธ๋ 4์ฃผ๋ผ๋ ๊ฒฐ์ฝ ์ ์ง ์์ ์๊ฐ์์ ํด๊ฒฐํด์ผ ํ๊ธฐ ๋๋ฌธ์๋๋ค.

2. ์์ฌ์ ๋ ๋ถ๋ถ

์ฌ์ค ์ ํฌ ํ์ ๋ฐ์ดํฐ ๋ถ์์ ์ค์ฌ์ผ๋ก ๊พธ๋ ค์ง ํ์์ธ ๊ด๊ณ๋ก ๋ฐฑ์๋ ๊ฐ๋ฐ์ ํ์ง ์์๋ค๋ ์ ์๋๋ค. ๋ฐ์ดํฐ ์์ง์ด ์ค์ํ ์๋์ ๋ฐ์ดํฐ๋ฅผ ์์งํ๊ธฐ ์ํ ์๋จ์ด ์กด์ฌํ์ง ์๋๋ค๋ ๊ฒ์๋๋ค. ๊ทธ๋ผ์๋ ๋ถ๊ตฌํ๊ณ  ์์ฑ๋ ๋์ ํ๋ก์ ํธ ๊ฒฐ๊ณผ๋ฌผ์ ๋ง๋ค์ด๋ด์ง ๋ชปํ ๊ฒ ๋ํ ์ฌ์ค์๋๋ค. PM์ธ ์ ๋ก์จ ๋งค์ฐ ๋ถ๋๋ฌ์ด ์ผ์๋๋ค. ๋ค๋ฅธ ํ์๋ค๊ฐ ์ํต์ ๋ณด๋ค ์ ๊ทน์ ์ผ๋ก ์ค์ฒํ์ง ์์์ ๋ฐ์ํ ๋ฌธ์ ๋ผ๊ณ  ์๊ฐ๋ฉ๋๋ค.

์ธ์  ๊ฐ ์ ์๊ฒ ํ๋ก์ ํธ๊ฐ ์ฃผ์ด์ง์ง๋ ๋ชจ๋ฅด๊ฒ ์ง๋ง, ์ง๋ ํ๋ก์ ํธ๋ค์ ๋์ด์ผ ๋ณด๋ฉด์ ์ข์ ๋ชจ์ต ๋ฐ ๊ฒฐ๊ณผ๋ฅผ ์ป์ ์ ์๋๋ก ์ฌ๋์ ํ๊ณ  ์ถ์ต๋๋ค.

### ๊ฐ์  ์ฌํญ?

์ด๋ฒ ํ๋ก์ ํธ๋ฅผ ์งํํ๋ฉด์ ์๋น์ค ๋ฐฐํฌํ๊ฒฝ์ผ๋ก AWS์ GCP(Google Cloud Platform) ๊ทธ๋ฆฌ๊ณ  Heroku ์ค ๋ง์ ๊ณ ๋ฏผ์ ํ์์ต๋๋ค. ์์ง ์ด๋ฌํ ๋ฐฐํฌ ๊ณผ์ ์ ๊ฒฝํํด ๋ณธ์ ์ด ์๋ํฐ๋ผ ์ ํฉ์ฑ ํ๋จ ๊ธฐ์ค์ผ๋ก ๋ค์๊ณผ ๊ฐ์ด ์กฐ๊ฑด์ ๋ถ์ฌํ ํ ํ๋จํ๊ฒ ๋์์ต๋๋ค.

```
- ์ฑ๋ฅ
- ๋น์ฉ(๋ฌด๋ก ์ฌ์ฉ ๊ฐ๋ฅ ์ฌ๋ถ ์ค์)
- ํธ์์ฑ(๊ด๋ฆฌ, ๋ฐฐํฌ ์ธก๋ฉด์์)
```

Heroku์ AWS ๊ทธ๋ฆฌ๊ณ  GCP ๋ชจ๋ ๋ฌด๋ฃ๋ก(์ ํ์ ์ด์ง๋ง) ์ฌ์ฉ ๊ฐ๋ฅํ๊ธฐ ๋๋ฌธ์ `๋น์ฉ` ๋ถ๋ถ์ ํฌ๊ฒ ๊ณ ๋ ค๋์ง ์์์ผ๋ฉฐ, `์ฑ๋ฅ`์ ๊ฒฝ์ฐ ์ญ์ ํฌ๊ฒ ๊ณ ๋ คํ์ง ์์๋๋ฐ ์์ง ์ ๋๋ก ๋ ๋น๋ฐ์ดํฐ๋ฅผ ๋ค๋ค๋ณด์ง ๋ชปํ๊ธฐ ๋๋ฌธ์ด๊ธฐ๋ ํ์ง๋ง ์ด๋ฒ ํ๋ก์ ํธ๋ง์ผ๋ก๋ ์ฑ๋ฅ์ ์ฒด๊ฐํ  ๋งํ ๋ถ๋ถ์ด ์ ์๊ธฐ ๋๋ฌธ์๋๋ค.

๊ฐ์ฅ ๋ง์ด ๊ณ ๋ คํ ๋ถ๋ถ์ด `ํธ์์ฑ`์ธ๋ฐ ์์ง ์ธํ๋ผ ํ๊ฒฝ์ ๊ตฌ์ถํ๊ธฐ ์ํ ์ค๋น๋ ๋ง์ด ๋ถ์กฑํ๊ธฐ ๋๋ฌธ์ AWS์ GCP๋ Heroku์ ๋นํด ์๋์ ์ผ๋ก ๋ฎ๊ฒ ํ๊ฐํ์์ต๋๋ค. ๋ฐ๋ผ์ Heroku๋ฅผ ์ฌ์ฉํ๊ฒ ๋์์ง๋ง ๊ธฐํ๊ฐ ๋๋ฉด ๋ค๋ฅธ ์ธํ๋ผ ํ๊ฒฝ ๋ํ ๊ตฌ์ถํ๋ ๋ฐฉ๋ฒ์ ํฐ๋ํด ๋๊ฐ ์์ ์๋๋ค.

### ์ง์ง ๋ง์ง๋ง์ผ๋ก...

์์ง ์ต์ข ํ๋ก์ ํธ๊ฐ ์ข๋ฃ๋ ๊ฒ์ ์๋์ง๋ง(์์ฑ ์ผ์ ๊ธฐ์ค์ผ๋ก 4์ผ ๋จ์), ์ ์  ์๋ ์๊ฐ๋์ ์๊ณ ํด ์ฃผ์  ํ์ ๋ถ๋ค, ๊ทธ๋ฆฌ๊ณ  ํ๋ ์ด๋ฐ์ดํฐ ๊ด๊ฒ์ ์ฌ๋ฌ๋ถ ๋ชจ๋์๊ฒ ์ง์ฌ์ผ๋ก ๊ฐ์ฌ์ ์ธ์ฌ๋ฅผ ์ ํฉ๋๋ค.

## ๐ฅBuilt With / ํ๋ก์ ํธ์ ์ฐธ์ฌํ ํ์๋ค
* [์ด๋ฏผ์ฌ](https://github.com/Dowonna) - PM 
* [๊ณ ์๋น]()
* [์ฅ๋ฌธํฌ]()
* [์กฐ์คํ](https://github.com/YUNHYE-0107)
* [์ต์ง์]()
