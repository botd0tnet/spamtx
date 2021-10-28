<b>SPAM TX BATTLE GAMINGHUB</b>
<br/>
<br/>

Run:
apt install -y expect git && sudo git clone https://github.com/botd0tnet/spamtx && cd spamtx && nano spam.sh<br/>
<br/>
Change $WALLET.<br/>
Save.<br/>

chmod 777 spam.sh spam.exp<br/>
cd<br/>

screen -S sapamtx<br/>
<br/>
cd autostake<br/>
for(( i=1; i <=99999; i++ ))<br/>
do<br/>
./spam.exp<br/>
done
