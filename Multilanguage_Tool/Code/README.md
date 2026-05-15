# environment
1. enable sqlite extensions

apt-get install libsqlite3-dev
./configure --enable-loadable-sqlite-extensions && make && make install

2. python libs install
pip install progressbar
pip install nltk
pip install textblob
pip install sklearn
pip install matplotlib
pip install plotly
