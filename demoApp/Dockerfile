FROM python:3.10-slim
WORKDIR /code
COPY . /code
ENV FLASK_APP=app.py
ENV FLASK_RUN_HOST=0.0.0.0
RUN pip install -r requirements.txt
EXPOSE 5000
EXPOSE 8001
CMD ["flask", "run"]