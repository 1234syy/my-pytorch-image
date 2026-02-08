FROM pytorch/pytorch:2.0.1-cuda11.7-cudnn8-devel

RUN conda install -y faiss-gpu scikit-learn pandas flake8 yapf isort yacs gdown future -c conda-forge

RUN pip install opencv-python tb-nightly

RUN apt-get update && apt-get install -y libgl1-mesa-glx libpci-dev curl nano psmisc
