wget --no-check-certificate -O tgbot.sh https://raw.githubusercontent.com/nameless3721/nash/master/tgbot.sh && chmod +x tgbot.sh && ./tgbot.sh

vi $Path/Telegram-chatbot/config.json

wget --no-check-certificate -O sc.sh https://raw.githubusercontent.com/nameless3721/nash/master/sc.sh && chmod +x sc.sh && ./sc.sh

```
wget --no-check-certificate -O rustss.sh https://raw.githubusercontent.com/nameless3721/nash/master/rustss.sh
chmod +x rustss.sh
./rustss.sh
nano /etc/rustss/rustss-server.json
systemctl restart rustss
systemctl status rustss

wget --no-check-certificate -O uninstall-rustss.sh https://raw.githubusercontent.com/nameless3721/nash/master/uninstall-rustss.sh
chmod +x uninstall-rustss.sh
./uninstall-rustss.sh
```
```
wget https://github.com/pymumu/smartdns/releases/download/Release33/smartdns.1.2020.09.08-2235.x86_64-debian-all.deb
dpkg -i smartdns*.deb
wget https://raw.nameless13.com/api/public/dl/5E_72S7J/smartdns.conf
mv -f smartdns.conf /etc/smartdns/
apt-get -y install resolvconf
echo "nameserver 127.0.0.1" >>/etc/resolvconf/resolv.conf.d/head
nano /etc/smartdns/smartdns.conf
systemctl start smartdns
systemctl enable smartdns
```
