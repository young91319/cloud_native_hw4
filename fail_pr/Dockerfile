FROM python:3.9-slim
WORKDIR /app
COPY app.py .

# 故意拼錯指令：原本應該是 pip install
RUN pipi install flask

CMD ["python", "app.py"]
