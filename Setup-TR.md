![openvpn-logo](https://github.com/user-attachments/assets/7d10c333-3b13-45cf-ab6b-5278e9bd03a2)



#### Sistem paketlerini güncellemek ve yükseltmek için aşağıdaki komutu çalıştırın:

```bash
sudo apt update -y && sudo apt upgrade -y
```
## 2. Gerekli paketleri kurun:

```bash
sudo apt install htop ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev tmux iptables curl nvme-cli git wget make jq libleveldb-dev build-essential pkg-config ncdu tar clang bsdmainutils lsb-release libssl-dev libreadline-dev libffi-dev jq gcc screen unzip lz4 -y
```

#### OpenVPN Server Kurulumu : 

```bash
curl -O https://raw.githubusercontent.com/FurkanL0/openvpn-install/refs/heads/master/openvpn-install.sh
```
```bash
chmod +x openvpn-install.sh
```
```bash
./openvpn-install.sh
```

#### Kurulum Başladı : 

![resim](https://github.com/user-attachments/assets/763ae24c-f71c-4982-8ccc-1778f9b48378)

##### İp Adresimiz gözükecek - enterliyoruz.

![resim](https://github.com/user-attachments/assets/1093897c-8909-4bdd-b0ac-1768b40374e4)

##### İPV6 Desteği istiyormusunuz ? soruyor biz "n"'yi enterliyoruz. Hayır.

![resim](https://github.com/user-attachments/assets/82dbf92a-9bb7-43fe-b6c5-f004b93e5645)

##### Port Seçeneği soruyor - Ben Custom için 1'i silip 2 yazıyorum Enterliyoruz.

![resim](https://github.com/user-attachments/assets/9eb2bf40-0b4f-4ea6-8607-16234cc6bdd2)

##### Portumu 443 yapıp enterliyorum.

![resim](https://github.com/user-attachments/assets/11fbfda1-eee9-4529-810d-d68275739661)

##### UDP'mi TCP'mi ? diye soruyor protokol olarak. UDP daha hızlı udp seçiyoruz. 1.

![resim](https://github.com/user-attachments/assets/b4b9ef2a-1145-43f1-94bd-21e6bc03cadd)

##### DNS Seçimi yaptırıyor. 9. Google'ı seçiyoruz.

![resim](https://github.com/user-attachments/assets/cb544c7d-bc05-4b33-bcf0-1343481bbea6)

##### N yazıp enterliyoruz.


![resim](https://github.com/user-attachments/assets/1f5d9bf1-c831-4187-9a73-bf2056b0bfda)

##### N yazıp enterliyoruz.

![resim](https://github.com/user-attachments/assets/b52a48bc-3b9f-46ca-8864-5e6cb34352c3)

##### Enter'e basıyoruz - onaylıyoruz.

![resim](https://github.com/user-attachments/assets/f23dce74-246f-4097-9a40-dc62ebd8cbd4)

##### İndirmeleri yapacak.

![resim](https://github.com/user-attachments/assets/d367ba68-47fb-44cb-980f-c0470ba28247)

##### Bu soruyu sorar ise 1 yazıp enterliyoruz.

![resim](https://github.com/user-attachments/assets/8fbf22d3-692d-42bb-b2a7-8d9fe51ad76d)


##### Burada Client'e isim veriyoruz ben sunucu lokasyonu ismi verdim HongKong - sonra enterliyoruz.

![resim](https://github.com/user-attachments/assets/3989ff07-769e-4892-b5dc-107713b6e042)

##### 1.yi Seçip enterliyoruz.

![resim](https://github.com/user-attachments/assets/c7fbddc9-343a-4f3c-8479-148d8cb16743)

##### Artık VPN'inimiz hazır - ls ile dosyaları listeleyin xxx.ovpn dosyası oluştu.
##### Sunucunuzdan bu dosyayı SFTP İle alabilirsiniz. İstediğiniz server'a yada SFTP ile istediğiniz yere yollayabilirsiniz.






