FROM python:3.7
RUN apt update && install python3-pip -y
COPY .
RUN pip install requirements.txt
EXPOSE 5001
ENTRYPOINT ["python","app.py"]
