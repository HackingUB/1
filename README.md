rm -rf 1

git clone https://github.com/HackingUB/1

cd 1

rm -rf Dark_Hunter

python3 -m venv Dark_Hunter

source Dark_Hunter/bin/activate

pip install --upgrade pip

pip install bs4

pip install urllib3

pip install rich

pip install requests

python api.py
