FROM python:3.6
LABEL maintainer="aakashkapur29@gmail.com"
ENV ENNVIRONMENT_NAME=Developement
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
EXPOSE 8080
ENTRYPOINT ["python"]
CMD ["app/app.py"]
