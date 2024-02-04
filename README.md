SKRIP INSTAL CARA:
download aplikasi termux di playstore lalu buka aplikasinya ketikan perintah dibawah ini.
$pkg update && pkg upgrade
$pkg install git
$pkg install python -y
$git clone https://github.com/king-uzi/CIG
$cd CIG
$pkg install clang python binutils libffi openssl libsodium
$SODIUM_INSTALL=system pip3 install pynacl
$pip install -r requirements.txt
$python run.py
