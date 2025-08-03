FROM nvcr.io/nvidia/tritonserver:22.06-py3

COPY models/ /models

CMD ["tritonserver", "--model-repository=/models"]