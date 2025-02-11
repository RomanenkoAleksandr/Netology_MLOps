# В качестве основы, берём образ continuumio/miniconda3:latest
FROM continuumio/miniconda3:latest

# Добавляем и делаем рабочей папкой /app
WORKDIR /app

# Надо скопировать этот файл внутрь контейнера и выдать ему права на исполнение.
COPY ./1.sh /1.sh
RUN chmod 755 /1.sh

# Запустить установку пакетов python mlflow boto3 pymysql.
RUN pip install mlflow boto3 pymysql

# В конце запустить на вывод файл 1.sh.
CMD ["/1.sh"]
