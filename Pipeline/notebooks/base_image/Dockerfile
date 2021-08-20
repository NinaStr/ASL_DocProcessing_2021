#FROM python:3.7
FROM gcr.io/deeplearning-platform-release/base-cpu
RUN pip install -U kfp google-cloud-storage pdf2image opencv-contrib-python
RUN apt-get update && apt-get install poppler-utils && apt-get install poppler-data
RUN apt-get install ffmpeg libsm6 libxext6 -y && apt-get install -y python3-opencv