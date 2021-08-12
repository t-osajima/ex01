FROM python:latest

# メタ情報の付与 

#LABEL maintainer="gerityu@hotmail.com" 
#LABEL version="1.0" 
#LABEL description="シンプルなPythonイメージです。" 

# 作業ディレクトリを変更 
WORKDIR /tmp/work

COPY requirements.txt ${PWD} 

RUN pip install -r requirements.txt