FROM python:3.12
WORKDIR /app
COPY . .
RUN pip install -r requirements.txt
RUN pip install rich
RUN pip install requests
RUN pip install setuptools
CMD ["python", "__main__.py"]