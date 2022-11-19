FROM python:3.10.7
WORKDIR /app
ADD . /app
COPY requi.txt /app
RUN python3 -m pip install -r requi.txt
RUN python3 -m pip install ibm_db
EXPOSE 5000
CMD ["python","app.py"]
