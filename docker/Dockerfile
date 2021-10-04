FROM python:3.6
RUN mkdir /usr/src/myapp -p
COPY .. /usr/src/myapp
WORKDIR /usr/src/myapp
RUN pip install -r requirements.txt -i  https://mirrors.aliyun.com/pypi/simple/
WORKDIR /usr/src/myapp/Web
CMD python manage.py runserver 0:7979