# Menentukan Image
FROM node:18.16

# Perintah yang dijalankan
RUN apt update -y && npm install

# Copy file to image
ADD . /app

# Perintah yang dijalankan ketika container sudah up
CMD {"npm", "start"}

# Describe expose port
EXPOSE 3000
