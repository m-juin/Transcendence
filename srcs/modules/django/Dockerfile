FROM python:3.10-alpine

RUN apk update && apk add postgresql-client
RUN apk add py-configobj
RUN apk add py-pip

RUN mkdir -p /var/site_files
RUN mkdir -p /var/log/gunicorn/

WORKDIR /usr/src/app

COPY ft_transcendence.sh .
COPY gunicornConf.py .

RUN pip install --upgrade pip
RUN pip install --no-cache-dir pyotp "uvicorn[standard]" gunicorn psycopg2-binary Django==4.2.6 requests channels==4.0.0 web3 Pillow pyjwt

ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=TRUE
ENV DJANGO_SETTINGS_MODULE=ft_transcendence.settings
ENV WATCHFILES_FORCE_POLLING=true
CMD [ "sh", "ft_transcendence.sh" ]
