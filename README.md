# DUMP FOLLOWERS
```
UPDATE Version 
termux-setup-storage (Allow Permission)
apt update -y && apt upgrade -y
pkg install git -y
pkg install python -y
pip install requests
pip install bs4
pip install future
rm -rf Followers
git clone https://github.com/BABASEc1/Crown.git
cd Followers
git pull 
python Run.py
