FROM python:alpine
RUN pip install redis requests
COPY worker.py /
CMD ["python", "worker.py"]
