#!/bin/bash

# update git
sudo yum install -y git

# install devel package
sudo yum install -y gcc-c++ python-devel.x86_64 cyrus-sasl-devel.x86_64

# install vim pathogen
mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim

# install vim solarized colorscheme
cd ~/.vim/bundle
git clone https://github.com/altercation/vim-colors-solarized.git
mv vim-colors-solarized ~/.vim/bundle/

cd ~/env
cp ./.vimrc ~/.vimrc

# install anaconda2
#wget https://repo.continuum.io/archive/Anaconda2-4.2.0-Linux-x86_64.sh
bash Anaconda2-4.2.0-Linux-x86_64.sh

# install python2.7 package
pip install --upgrade pip
pip install pymssql
sudo yum install -y mysql-devel.x86_64
pip install mysql-python
pip install pyhs2
pip install pymongo
pip install httplib2

pip install jieba
pip install nltk
pip install gensim
