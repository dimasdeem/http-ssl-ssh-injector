HTTP-SSH-SSL-INJECTOR

 termux + root 

Download toolnya ngab

https://codeload.github.com/abdoxfox/http-ssl-ssh-injector/zip/refs/heads/main

extrack, teros ganti nama folder toolnya ngab biar mudah dipindahin ke termux

example : ssh

taro di /sdcard

buka SSH terus edit redsocks.conf pakai editor text

edit seperti di gambar dibawah, lalu save. Next

Buka termux

$ termux-setup-storage

$ apt update && apt upgrade && pkg install root-repo

$ apt install -y openssh sshpass netcat-openbsd corkscrew screen python3 tsu

$ tsu

# mv /sdcard/ssh $PWD

# chmod +x -R ssh/*

# cd ssh

buat edit ssh dan payloadnya

# nano *.ini

lalu save

 

Jalankan injectornya

# ./*.sh

close

Ctrl +C

y/n = n

Source:

github.com/abdoxfox/http-ssl-ssh-injector
# updated 
waiting for your opinions 

# http-ssl-ssh-tunneling
http ssl ssh tunneling vpn for android and linux devices

# whats new!

* Now support combination ssl + payload 

# packages :

[+] - apt install -y git openssh sshpass netcat-openbsd corkscrew screen python3

[+] - pip install certifi


# configuration :

past your data into file settings.ini 

![image](https://user-images.githubusercontent.com/46646744/122469251-9f621400-cfb4-11eb-9d64-f5dbfa2dffa9.png)


# how it works!

(root is required in android )

[+] - git clone https://github.com/abdoxfox/http-ssl-ssh-injector.git

# steps :

* setup your custom payload and proxy (proxy not required)

[+] - cd http-ssl-ssh-injector

[+] - sudo  or tsu for termux  #run as root

[+] - chmod +x runvpn.sh

[+] - ./runvpn.sh

* choose your connection mode:

![image](https://user-images.githubusercontent.com/46646744/122469828-48a90a00-cfb5-11eb-8b2b-48e9870618b2.png)


# screenshots 

![image](https://user-images.githubusercontent.com/46646744/121225010-00853b80-c881-11eb-8cb6-4fcea95f8f88.png)

* note : to stop the script press CTRL + C

![image](https://user-images.githubusercontent.com/46646744/121225175-2c082600-c881-11eb-9c82-27fc2f4200a1.png)


