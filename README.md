```
# wget https://raw.githubusercontent.com/poiuty/keys/master/poiuty.gpg
# sudo apt-key add poiuty.gpg
# wget https://raw.githubusercontent.com/poiuty/keys/master/message.asc
# gpg --verify message.asc

gpg --verify message.asc
gpg: Signature made Tue 24 Jan 2017 01:38:04 AM MSK using RSA key ID 0FCAD97E
gpg: Good signature from "poiuty <poiuty@lepus.su>"
```