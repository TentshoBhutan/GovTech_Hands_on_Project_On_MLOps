FROM python:3.9-slim
WORKDIR /app
COPY . /app
RUN python -m pip install --upgrade pip
RUN pip install -r requirements.txt
EXPOSE 5001
CMD ["streamlit", "run", "app.py", "--server.address=0.0.0.0"]
