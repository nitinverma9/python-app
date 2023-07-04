FROM python:3.11.1
WORKDIR /code
ADD ./app /code/
RUN pip install --no-cache-dir --upgrade -r /code/requirements.txt
CMD ["uvicorn", "app:app", "--host", "0.0.0.0", "--port", "80"]
