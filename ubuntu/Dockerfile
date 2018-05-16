FROM ubuntu:latest
WORKDIR "/application"

# Update
RUN apt-get -y update

# Install Tesseract with portuguese data
RUN apt-get install -y tesseract-ocr
RUN apt-get install -y tesseract-ocr-por

# Install ImageMagick
RUN apt-get install -y imagemagick

# Keep Container Alive
RUN tail -f /dev/null