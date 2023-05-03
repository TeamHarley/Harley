# Harley
<p align="center">𝐋𝐨𝐜𝐚𝐥 𝐃𝐞𝐩𝐥𝐨𝐲𝐦𝐞𝐧𝐭 ✅</p>

```sh
sudo apt update && apt upgrade -y
apt-get install git curl python3-pip ffmpeg -y
pip3 install -U pip
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
source ~/.bashrc
nvm install v18
git clone https://github.com/TeamHarley/Harley # clone the repo.(Before Cloning Make Sure uh have Filled Your Vars in config.ini)
cd Telegram
pip3 install -U -r requirements.txt
nano .env # use vim to edit ENVs (if uh have already filled then Run start command
# fill up the ENVs (Steps: press i to enter in insert mode then edit the file. Press Esc to exit the editing mode then type :wq! and press Enter key to save the file).
python3 -m Telegram # start the bot.
```
