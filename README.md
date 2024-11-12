#  $${\color{red}İŞLEVSEL\space LİNUX\space KOMUTLARI}$$
## :red_circle:  $${\color{darkblue}Klosör\space oluşturma}$$
:point_right: `mkdir` komutu ile klosör oluşturulur.
```
mkdir DosyaAdi
```
*dosya1 adlı klosörün oluşturulması*:point_down:	<br>
![mkdir](https://github.com/user-attachments/assets/67a90701-e2f9-440b-80d2-b49a183af563)

## :orange_circle:  $${\color{darkblue}Boş\space bir\space klosörü\space silme}$$
:point_right: `rmdir` eski boş klosörü silmeye yarayan komuttur.
```
rmdir DosyaAdi
```
*dosya1 adlı klosörün silinmesi*:point_down:<br>
![rmdir](https://github.com/user-attachments/assets/ba1ed91a-166a-43a4-9840-bd8ccfa0e9da)

## :yellow_circle:  $${\color{darkblue}Dosya,\space metin\space belgesi\space oluturma}$$
:point_right: `touch` komutu ile yeni metin belgesi, dosya oluşturulur.
```
touch DosyaAdi
```
*metin isimli dosyanın oluşturulması*:point_down:<br>
![touch](https://github.com/user-attachments/assets/6c901653-d267-408c-9796-3c89f2e3f499)


## :green_circle: $${\color{darkblue}Dosyayı\space yeniden\space adlandırma}$$
:point_right: `mv` komutunu yazdıktan sonra eski dosyamızın adnı ardından yeni koyacağımız ismi yazarak yeniden adlandırmış oluruz.
```
mv eski_isim yeni_isim
```
*metin isimli dosyanın yeniad isimli dosya olarak adlandırılması*:point_down:<br>
![mv](https://github.com/user-attachments/assets/98eee4d0-34e7-40cf-bc84-91c5d3be7aeb)

## 	:large_blue_circle: $${\color{darkblue}Dosyayı\space silme}$$
:point_right: `rm` dosyayı silmeye yarayan komuttur.
```
rm dosyaadi.txt
```
*yeniad isimli dosyanın silinmesi*:point_down:<br>
![rm](https://github.com/user-attachments/assets/03eb4097-9eb1-40e7-9f4b-0636c6f2e045)

## 	:purple_circle:  $${\color{darkblue}Dosyanın\space içeriğini\space ekrana\space aktarma}$$
:point_right: `cat` komutu ile dosyanın içeriği komut ekranında görüntülenir.
```
cat dosyaadi.txt
```
*Dosya isimli dosyanın içeriğinin görüntülenmesi*:point_down:<br>
![cat](https://github.com/user-attachments/assets/e8af3cbd-de23-4d26-a18d-6651c9b35ff7)

## 	:brown_circle: $${\color{darkblue}Sistemdeki\space kullanıcı\space adını\space gösterme}$$
:point_right: `whoami` komutu ile sistem kullanıcı adınız gözükür.
```
whoami
```
*Sistem kullanıcı adının gösterilmesi*:point_down:<br>
![whoami](https://github.com/user-attachments/assets/63ca6bd7-a590-4cfa-8c81-4bb4e522e551)

## 	:black_circle: $${\color{darkblue}Sistem\space bilgilerini\space gösterme}$$
:point_right: `uname -a` sistem bilgilerinizi ekrana döken komuttur
```
uname -a
```
*Sistem bilgilerinin ekranda gösterilmesi*:point_down:<br>
![uname](https://github.com/user-attachments/assets/e0024337-1c89-42dc-b159-9caefa2ea2e3)

## :white_circle:  $${\color{darkblue}Disk\space kullanımının\space ekranda\space gösterilmesi}$$
:point_right: `df -h` disk kullanımını gösteren komuttur.
```
df -h
```
*disk kullanımının ekranda gösterilmesi*:point_down:<br>
![df-h](https://github.com/user-attachments/assets/01c06b7b-7a4a-4c3e-b293-faea859d0df7)

## :red_square: $${\color{darkblue}Klosör\space boyutunu\space gösterme}$$
:point_right: `du -sh` komutu ardından belirtilen klosörün boyutunu ekrana yazar.
```
du -sh KlosörAdi
```
*Resimler adlı klosörün boyutunu gösterme*:point_down:<br>
![du-sh](https://github.com/user-attachments/assets/11211b6d-9161-4815-bde3-f399e80071ca)

## :orange_square: $${\color{darkblue}Sistemde\space çalışan\space işlemleri\space ve\space kaynak\space kullanımını\space gösterme}$$
:point_right: `top` komutu sistemde çalışan işlemleri ve kaynak kullanımını ekrana yazar.
```
top
```
*İşlemlerin ve kaynak kullanımının ekran yazılması*:point_down:<br>
![top](https://github.com/user-attachments/assets/1c288dde-450e-4e2f-9711-a29aa4a66e80)

## :yellow_square: $${\color{darkblue}RAM\space kullanımını\space gösterme}$$
:point_right: `free -m` komutu bellek kullanımınızı ekrana yazar.
```
free -m
```
*Bellek kullanımın ekrana yazılması*:point_down:<br>
![free-m](https://github.com/user-attachments/assets/43c3feec-bc00-4eb9-a548-2877bff59837)

## :green_square: $${\color{darkblue}Tüm\space çalışan\space işlemleri\space listeleme}$$
:point_right: `ps -aux` Linux sistemlerinde çalışan süreçleri listelemek için kullanılan bir komuttur.
```
ps -aux
```
*Çalışan işlemlerin ekrana yazılması*:point_down:<br>
![ps aux](https://github.com/user-attachments/assets/e13303f9-2e05-4350-aa60-b2799107fe15)

## :blue_square:  $${\color{darkblue}Dosyada\space belirli\space bir\space kelimeyi\space arama}$$
:point_right: `grep` komutu ile arama yapılır. bu komuttan sonra tırnak içinde kelime ve tırnaksız dosyanın adı yazılır.
```
grep "kelime" DosyaAdi.txt
```
*metin kelimesinin dosya adlı dosyada aranması*:point_down:<br>
![grep](https://github.com/user-attachments/assets/b4c5bb53-5861-4592-b098-ec1a3a86ed72)

## :purple_square: $${\color{darkblue}Dosyadaki\space satır,\space kelime\space ve\space karakter\space sayısını\space görüntüleme}$$
:point_right: `wc` komutu ile ardından adı yazılan dosyanın sırasıyla satır,kelime ve karakter sayısı ekrana yazılır.
```
wc dosya.txt
```
*dosya adlı dosyanın satır,kelime ve karakter sayısının görüntülenmesi*:point_down:<br>
![uptime](https://github.com/user-attachments/assets/eee8915a-742a-41be-aa14-97a898062fe8)

## :brown_square: $${\color{darkblue}Tarih\space ve\space saati\space gösterme}$$
:point_right: `date` mevcut tarih ve saati gösteren komuttur.
```
date
```
*tarih ve saatin gösterilmesi*:point_down:<br>
![date](https://github.com/user-attachments/assets/fcc3a08a-60a5-443b-93a7-dd1cefcefe7e)

## :black_large_square: $${\color{darkblue}Bilgisayarı\space kapatma}$$
:point_right: `shutdown -h now`bilgisayarı anında kapatmaya yarayan koddur.
```
shutdown -h now
```
*Kapatma komutunun gösterilmesi*:point_down:<br>
![kapama](https://github.com/user-attachments/assets/62f70914-2d84-4744-a0cc-e6537af90313)

## :white_large_square:  $${\color{darkblue}Komut\space geçmişini\space görüntüleme}$$
:point_right: `history` kullanılan komutların geçmişini ekrana listeleyen komuttur.
```
history
```
*Komut geçmişinin ekranda listelenmesi*:point_down:<br>
![tarih](https://github.com/user-attachments/assets/bb5c5cea-d67f-4634-aee0-c5c23c9ae3f9)

## 	:large_orange_diamond: $${\color{darkblue}Terminal\space ekranını\space temizleme}$$
:point_right: `clear` komutu ile terminal ekranına yazdıklarımız silinir.
```
clear
```
*Terminal ekranının silinmesi*:point_down:<br>
![clear](https://github.com/user-attachments/assets/113c54b7-99f2-4789-89c3-ebaff35f04b7)

## :large_blue_diamond: $${\color{darkblue}Sistemin\space ne\space kadardır\space süre\space çalıştığını\space ve\space yük\space durumunu\space gösterme}$$
:point_right: `uptime` sistemin ne zamandır çalıştığını ve yük durumunu gösteren koddur.
```
uptime
```
*Sistemin çalışma süresi ve yük durumunun gösterilmesi*:point_down:<br>
![uptime](https://github.com/user-attachments/assets/3494eeea-a126-49c6-890b-9df2fad5d0a2) 






