FROM python:3-alpine
COPY . /python
WORKDIR /python
RUN pip install -r requirements.txt
EXPOSE 8000
CMD python /python/app.py
