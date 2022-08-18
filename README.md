## Dev Environment Setting


[Django 개발 참고](https://github.com/Jihyun-Choi/TIL/blob/master/django/Dev%20Summary.md)
[git 명령어](https://github.com/Jihyun-Choi/TIL/blob/master/git/command.md)

### 환경 설정
1. 프로젝트 폴더 바로 아래에 .env-sample 파일을 복사하여 .env 파일로 만들기


### 라이브러리 설정하기
```shell
# 가상환경 만들기
> python -m venv venv
# 가상환경 활성화
## Windows
> .\venv\Scripts\activate
## Mac
> source venv/bin/activate
## 라이브러리 설치하기
> pip install -r requirements.txt
## django 실행하기
> python manage.py migrate
> python manage.py runserver
```

### Tip! venv exit하는법
```shell
> deactivate
```

### Third party 설치하는 법

```shell
# 가상환경 활성화 후에!
# 설치
> pip intall blahblah
# 다른 작업자가 이를 알 수 있게, requirements.txt에 반영하기
> pip freeze > requirements.txt
``` 

