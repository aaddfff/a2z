# a2z
Language: Bahasa Melayu (Malaysia)

## intro
Bismillahirahmanirahim.
Alhamdulillah sempena cuti hari Kemerdekaan Malaysia yang ke 63, saya memikirkan satu alternatif untuk belajar Docker melalui git a to z. Kenapa A to Z? Adalah... hihihi

## komponen
- vmware workstation 15 player
- ubuntu server 20

## pekej
- docker

# a01
Episod pertama ini kita akan install OS dulu. saya gunakan vmware player dan iso ubuntu server

- [x] Install vmware
- [x] Create a new virtual machine
- [x] Use ubuntu server iso
- [ ] Run first docker container - phpmyadmin
- [x] Upload installed vm zip image to Gdrive

# z01
Setelah selesai install vm yang dilengkapi Docker, kita boleh remote OS tersebut menggunakan ssh. untuk melihat senarai container sila gunakan command berikut
``` sudo docker ps ```

untuk melihat senarai docker image pula
``` sudo docker images ```

ok masa yang ditunggu-tunggu, docker pertama kita jeng jeng jeng .. phpmyadmin. banyak command dan penerangan dalam hub.docker.com yang saya shortcutkan kat sini, kita just gunakan
``` sudo docker run phpmyadmin ```

dah run kita test dekat browser yer.

[![Run first docker container](https://img.youtube.com/vi/uWMMArw1iv4/0.jpg)](https://youtu.be/uWMMArw1iv4 "Run phpmyadmin using docker")

## result
[Ubuntu Server 20 vm-image by sir](https://drive.google.com/file/u/2/d/1VuqKiLdjnChREQvg2iOyZNGFb6HrShmg/view?usp=sharing "download from Gdrive")

episod seterusnya a02. 
