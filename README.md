# Keras-OCR-Server
This repository contains the implementation of a RESTful API using Python that leverages the Keras-OCR model for Optical Character Recognition (OCR). This API allows clients to send images to the server, which processes the images and extracts text using Keras-OCR models.

STEP1 Install Conda and Python.
Download Miniconda. 
https://docs.anaconda.com/miniconda/
Download Visual Studio Code
https://code.visualstudio.com/
Download Python
https://www.python.org/downloads/

STEP2 Create environment for keras_ocr server.
    conda env create -f environment.yml

STEP3 Start jupyter notebook on the terminal.
    jupyter notebook

STEP4 Start Keras_OCR Server.
On the jupyter notebook, double click on file keras_ocr_server.ipynb. And then click on Run >> Run All Cell to start Flask the server.

STEP5 Test the server by sending the image as post request to the server.
On the jupyter notebook, double click on file pose_request_image.ipynb. And then click on Run >> Run All Cell to send the post request to the server.


