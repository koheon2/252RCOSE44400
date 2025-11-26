FROM python:3.10-slim
WORKDIR /app
RUN pip install flask requests
COPY app.py .
COPY templates/ templates/
EXPOSE 5000
ENTRYPOINT ["python"]
CMD ["app.py"]