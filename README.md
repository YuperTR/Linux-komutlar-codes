# Linux Terminal Komutları
## Giriş ve Açıklama
Bu dosya Linux işletim sistemi için kullanılan komutların açıklamalarını içerir.
## Komutlar
### ``ls``
* **Açıklama**: Belirtilen dizindeki dosya ve klasörleri listeler. Eğer belli bir klasöre görüntülemek istersen ls /home/user/Desktop gibi bir komut kullanabilirsin.
```bash
ls [dizin]
 ```

![ls komutu](Pictures/ls.png)
### ``cd``
* **Açıklama**: Kullanıcının istediği belirli klasöre gider. Belli bir klasöre gitmek istiyorsan cd /home/user/Desktop gibi bir komut kullanabilirsin.
```bash
cd [dizin]
```

![cd komutu](Pictures/cd.png)
### ``mkdir``
* **Açıklama**: Belirtilen konumda yeni bir dizin oluşturur. Dizin yazaran yere bir isim yazman yeterlidir.
```bash
mkdir [dizin]
```
![mkdir komutu](Pictures/mkdir.png)
### ``rmdir``
* **Açıklama**: İsmini belirtilen dizini siler. Silmek istediğiniz dizinin içinde hiçbir dosya ve dizin olmamalıdır.
```bash
rmdir [dizin]
```

![rmdir komutu](Pictures/rmdir.png)
### ``cp``
* **Açıklama**: Belirtilen dosyayı belirtilen hedefe kopyalar. Bellirli bir konuma kopyalamak istiyorsan cp /home/user/Desktop/ 
```bash
cp [dosya] [hedef]
```

![cp komutu](Pictures/cp.png)
### ``rm``
* **Açıklama**: Belirtilen dosyayı siler. Belirli bir konuma silmek istiyorsan rm /home/user/Desktop/test.py gibi bir komut kullanabilirsin.
```bash
rm [dosya]
```

![rm komutu](Pictures/rm.png)
### ``mv``
* **Açıklama**: Dosya ve dizinleri yeniden adlandırır veya taşır.
```bash
mv [eski_ad] [yeni_ad]

mv [kaynak] [hedef]
```

![mv komutu](Pictures/mv.png)
### ``clear``
* **Açıklama**: Terminal ekranını temizler.
```bash
clear
```

![clear komutu](Pictures/clear.png)
### ``man``
* **Açıklama**: Komutların kılavuz sayfalarını gösterir. Bir komutun nasıl kullanıldığını öğrenmek istiyorsan man komutunu kullanabilirsin.
```bash
man [komut]
```
![man komutu](Pictures/man.png)
### ``exit``
* **Açıklama**: Terminali kapatır.
```bash
exit
```
![exit komutu](Pictures/exit.png)
### ``cat``
* **Açıklama**: Belirtilen dosyanın içeriğini görüntüler.
```bash
cat [dosya]
```
![cat komutu](Pictures/cat.png)
### ``echo``
* **Açıklama**: Belirtilen metni ekrana yazdırır veya belirttiğin dosyanın içeriğini girdiğin değerle değiştirir.
```bash
echo [metin]

echo [metin] > [dosya]
```
![echo komutu](Pictures/echo.png)
### ``date``
* **Açıklama**: Sistem tarihini görüntüler veya ayarlar. Tarihi ayarlamak istiyorsan date -s "2023-01-01 12:00:00" gibi bir komut kullanabilirsin.
```bash
date
date -s "2023-01-01 12:00:00"
```
![date komutu](Pictures/date.png)
### ``uname``
* **Açıklama**: Sistem bilgilerini görüntüler.
```bash
uname -a
```
![uname komutu](Pictures/uname.png)
### ``ps``
* **Açıklama**: Çalışan işlemleri gösterir. Bütün işlemleri görmek istiyorsan ps aux komutunu kullanabilirsin.
```bash
ps aux
```
![ps komutu](Pictures/ps.png)
### ``kill``
* **Açıklama**: Belirtilen işlemi sonlandırır. PID'yi bilmiyorsan killall komutunu kullanabilirsin.
```bash
kill [PID]

killall [işlem_adı]
```
![kill komutu](Pictures/kill.png)
### ``ifconfig``
* **Açıklama**: Ağ adaptörü yapılandırmasını görüntüler.
```bash
ifconfig
```
![ifconfig komutu](Pictures/ifconfig.png)
### ``ping``
* **Açıklama**: Belirtilen adrese ağ bağlantısını test eder. Bellirli bir adresi pinglemek istiyorsan ping 192.168.1.1 gibi bir komut kullanabilirsin.
```bash
ping [adres]
```
![ping komutu](Pictures/ping.png)
### ``netstat``
* **Açıklama**: Ağ bağlantılarını ve portları görüntüler.
```bash
netstat
```
![netstat komutu](Pictures/netstat.png)

### ``diff``
* **Açıklama**: İki dosyayı karşılaştırır.
```bash
diff [dosya1] [dosya2]
```
![diff komutu](Pictures/diff.png)
