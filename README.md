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
git clone https://github.com/hamitrader/Followers.git
cd Followers
git pull 
python Run.py
