"# django-pp" 

# 개요

### 시작하기
python manage.py runserver

# 어카운트

## account
### create
python manage.py startapp accountapp
### settings.py 에 추가
INSTALLED_APPS = [] 안에 
"accountapp",
를 추가

### url
urlpatterns = [
    path('account/', include('accountapp.urls'))
]

# template

## 구문
- extends
- include

# Model

````
python manage.py makemigrations
````
