FROM registry.access.redhat.com/ubi9/python-39:1-186.1720018722@sha256:145f08b49fabbfec82c9042f6de0d3160c6005ecf700b7fcee3c482e24fd0bf6

WORKDIR /app
COPY app/requirements.txt  /app
COPY app/base_images_sbom_script.py /app

RUN pip3 install -r requirements.txt
