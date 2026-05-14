# multi-lang-github-study

Project artifact for:

**How are Multilingual Systems Constructed: Characterizing Language Use and Selection in Open-Source Multilingual Software**

- Original artifact URL: <https://bitbucket.org/wsucailab/multilangstudy/>
- Imported via `pubs2github` from the publications page
- Downloader: `git` — Cloned https://bitbucket.org/wsucailab/multilangstudy.git (340 files)


## Other papers using the same artifact

- Understanding Language Selection in Multi-Language Software Projects on GitHub

This repository was created automatically. The contents under this
directory mirror what was downloaded from the original artifact link
above; refer to that source for the authoritative version, licensing,
and any updates.

---

## Original `README.md` (from the upstream artifact)

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
