# ベースイメージとしてpython公式
FROM python:latest
# Linux環境を整えるパッケージインストール
# お好みで必要なパッケージを追加してください
RUN apt-get update && \
    apt-get install -y \
    build-essential \
    cmake \
    git \
    sudo \
    wget \
    vim
# pipの更新
RUN pip install --upgrade pip
# python libraryのリストをホストから取得
COPY ./requirements.txt /requirements.txt
# requirements.txt内のライブラリーを一括インストール
RUN pip install -r /requirements.txt
WORKDIR /work
CMD ["/bin/bash"] 
