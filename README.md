# Ultra Valuable UV - Traditional Python Repository

Companion Repository for Ultra Valuable UV - Traditional Python Repository



Initialize the Repository (in directory)

```bash
claudiadeluna in ~/Indigo Wire Networks Dropbox/Claudia de Luna/scripts/python/2025/uv_repo 
% tree   
.

0 directories, 0 files
claudiadeluna in ~/Indigo Wire Networks Dropbox/Claudia de Luna/scripts/python/2025/uv_repo 
% uv init
Initialized project `uv-repo`
claudiadeluna in ~/Indigo Wire Networks Dropbox/Claudia de Luna/scripts/python/2025/uv_repo on main
% tree
.
├── README.md
├── main.py
└── pyproject.toml

1 directory, 3 files
claudiadeluna in ~/Indigo Wire Networks Dropbox/Claudia de Luna/scripts/python/2025/uv_repo on main
% 
```



Variable Precedence

In the repository, with `.python-version` set to 3.12 and inline metadata python set to 3.11.12, and pyproject.toml set to >=3.11, note the warning.

inline requests version is 2.29.0 and pyproject.toml version is 2.30.0 so inline wins.

```bash
% cat .python-version 
3.12
```



```ini
[project]
name = "uv-repo"
version = "0.1.0"
description = "Add your description here"
readme = "README.md"
requires-python = ">=3.11"
dependencies = [
    "requests==2.30.0",
]
```



```bash
% uv run cc3_info.py
warning: The Python request from `.python-version` resolved to Python 3.12.9, which is incompatible with the script's Python requirement: `==3.11.12`
Installed 7 packages in 12ms

----- Dynamic On-demand Virtual Environment Details -----
        Python version: 3.12.9
        Virtual environment path: /Users/claudiadeluna/.cache/uv/environments-v2/cc3-info-ba3ff7f3a4472319

        requests==2.29.0
        idna==3.10
        urllib3==1.26.20
        python-dotenv==1.1.0
        charset-normalizer==3.4.1
        certifi==2025.1.31
        pycountry==24.6.1
<snip>
```



# 



```bash
claudiadeluna in ~/Indigo Wire Networks Dropbox/Claudia de Luna/scripts/python/2025/uv_repo on main
% ls -al
total 48
drwxr-xr-x@ 10 claudiadeluna  staff  320 Apr 21 09:00 .
drwxr-xr-x@ 24 claudiadeluna  staff  768 Apr 21 05:17 ..
-rw-r--r--@  1 claudiadeluna  staff   69 Apr 21 06:56 .env_sample
drwxr-xr-x@  9 claudiadeluna  staff  288 Apr 21 08:59 .git
-rw-r--r--@  1 claudiadeluna  staff  109 Apr 21 08:59 .gitignore
drwxr-xr-x@  9 claudiadeluna  staff  288 Apr 21 08:57 .idea
-rw-r--r--@  1 claudiadeluna  staff    5 Apr 21 08:59 .python-version
-rw-r--r--@  1 claudiadeluna  staff  745 Apr 21 09:00 README.md
-rw-r--r--@  1 claudiadeluna  staff   85 Apr 21 08:59 main.py
-rw-r--r--@  1 claudiadeluna  staff  153 Apr 21 08:59 pyproject.toml
claudiadeluna in ~/Indigo Wire Networks Dropbox/Claudia de Luna/scripts/python/2025/uv_repo on main
% cat .python-version 
3.11


```
