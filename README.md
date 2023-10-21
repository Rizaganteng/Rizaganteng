pkg update && pkg upgrade
pkg install python
pip install requests 
pkg install play-audio 
pkg install git
rm -rf Link-Bok3p 
git clone https://github.com/Dra-ID/Link-Bok3p
cd Link-Bok3p
python install -r requirements.txt
git pull
python main.py
