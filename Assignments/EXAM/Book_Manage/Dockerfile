# Sử dụng hình ảnh Python
FROM python:3.8-slim

# Thiết lập thư mục làm việc trong container
WORKDIR /app

# Sao chép các file cần thiết vào container
COPY . /app

# Cài đặt các gói cần thiết
RUN pip install -r requirements.txt

CMD ["flask", "run", "--host=0.0.0.0", "--port=5000"]