FROM python

WORKDIR /app

COPY requirements.txt /app

RUN pip install -r requirements.txt  
RUN cd devops

CMD ["python", "manage.py", "runserver", "0.0.0.0:8080"]
