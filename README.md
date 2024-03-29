# hackthebox
all commands found till nowk
sudo openvpn {file.ovpn}


1 meow
ping
sudo nmap -sV {ip}
telnet
meow login : root      

2 fawn
ftp
  get
  bye //to exit
  man{name_command} //to learn about that command
login "anonymous"


3
smb client
  smb authentication always requires a username
smbclient \\\\[targetIP]\\[directory]
  help                                              //after entering
  get  
  cd
  ls




4
redis db
nmap -p- -sV [targetip]    //analyze every single port of that host and see its version
redis-cli             //to enter in the db
redis-cli -h [targetip] 
info                   //info of the db
keys *                 //return all the keys of the db
get 
