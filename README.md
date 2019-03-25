# ArchLinux-Python
##### https://wiki.archlinux.org/index.php/Python/Virtual_environment

 - Python 3.3+: `python` (Python 3.3+ has `venv`)
    - `python -m venv .python`
    - `source .python/bin/activate`
    - Oneliner: `bash <(curl -s https://raw.githubusercontent.com/codemodify/ArchLinux-Python/master/venv-python3_3_up.sh)`

 - Python 3: `python-virtualenv`
    - `virtualenv .python`
    - `source .python/bin/activate`
    - Oneliner: `bash <(curl -s https://raw.githubusercontent.com/codemodify/ArchLinux-Python/master/venv-python3.sh)`

 - Python 2: `python2-virtualenv`
    - `virtualenv2 .python`
    - `source .python/bin/activate`
    - Oneliner: `bash <(curl -s https://raw.githubusercontent.com/codemodify/ArchLinux-Python/master/venv-python2.sh)`
