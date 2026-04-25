# Gunakan base image python yang ringan
FROM python:3.9-slim

# Set working directory
WORKDIR /app

# Copy file aplikasi kita ke dalam container
COPY app.py .

# Jalankan aplikasinya saat container dijalankan
CMD ["python", "app.py"]
