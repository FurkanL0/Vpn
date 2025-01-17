![openvpn-logo](https://github.com/user-attachments/assets/7d10c333-3b13-45cf-ab6b-5278e9bd03a2)



#### Run the following command to update and upgrade system packages:

```bash
sudo apt update -y && sudo apt upgrade -y
```
## 2. Install the required packages:

```bash
sudo apt install htop ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev tmux iptables curl nvme-cli git wget make jq libleveldb-dev build-essential pkg-config ncdu tar clang bsdmainutils lsb-release libssl-dev libreadline-dev libffi-dev jq gcc screen unzip lz4 -y
```

#### OpenVPN Server Setup :

```bash
curl -O https://raw.githubusercontent.com/FurkanL0/openvpn-install/refs/heads/master/openvpn-install.sh
```
```bash
chmod +x openvpn-install.sh
```
```bash
./openvpn-install.sh
```

#### Installation Started :

![resim](https://github.com/user-attachments/assets/763ae24c-f71c-4982-8ccc-1778f9b48378)

##### Our ip address will appear - enter.

![resim](https://github.com/user-attachments/assets/1093897c-8909-4bdd-b0ac-1768b40374e4)

##### Do you want IPV6 Support? asks, we enter "n". No.

![resim](https://github.com/user-attachments/assets/82dbf92a-9bb7-43fe-b6c5-f004b93e5645)

##### It asks for Port Option - I delete 1 for Custom and enter 2.

![resim](https://github.com/user-attachments/assets/9eb2bf40-0b4f-4ea6-8607-16234cc6bdd2)

##### I'm write my port 443 and enter.

![resim](https://github.com/user-attachments/assets/11fbfda1-eee9-4529-810d-d68275739661)

##### It asks whether UDP or TCP is the protocol. We choose UDP faster udp. 1.

![resim](https://github.com/user-attachments/assets/b4b9ef2a-1145-43f1-94bd-21e6bc03cadd)

##### It makes you choose DNS. 9. We choose Google.

![resim](https://github.com/user-attachments/assets/cb544c7d-bc05-4b33-bcf0-1343481bbea6)

##### Type N and enter.


![resim](https://github.com/user-attachments/assets/1f5d9bf1-c831-4187-9a73-bf2056b0bfda)

##### Type N and enter.

![resim](https://github.com/user-attachments/assets/b52a48bc-3b9f-46ca-8864-5e6cb34352c3)

##### We press Enter - we confirm.

![resim](https://github.com/user-attachments/assets/f23dce74-246f-4097-9a40-dc62ebd8cbd4)

##### It will make the downloads.

![resim](https://github.com/user-attachments/assets/d367ba68-47fb-44cb-980f-c0470ba28247)

##### If it asks this question, we type 1 and enter.

![resim](https://github.com/user-attachments/assets/8fbf22d3-692d-42bb-b2a7-8d9fe51ad76d)


##### Here we name the Client, I named the server location HongKong - then enter.

![resim](https://github.com/user-attachments/assets/3989ff07-769e-4892-b5dc-107713b6e042)

##### Select 1 and enter.

![resim](https://github.com/user-attachments/assets/c7fbddc9-343a-4f3c-8479-148d8cb16743)

##### Now our VPN is ready - list the files with ls and the file xxx.ovpn has been created.
##### You can get this file from your server via SFTP. You can send it to the server you want or anywhere you want with SFTP.

## Phone / Windows / Mac / Iphone : 

- Android / Winodws / Mac / Iphone We download the application and upload the file we received with SFTP to this section, then press connect and connect.


![resim](https://github.com/user-attachments/assets/4a6d745e-40e1-4c3f-8923-1bebad759229)


## Linux : 

```bash
sudo apt install openvpn
```

- Upload the .ovpn file to your server via SFTP.

## Screen ; 

```bash
sudo openvpn --config client.ovpn
```

- Now your VPN will work. You can exit the screen with CTRL A + D.

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=FurkanL0&style=flat-square&color=brightgreen&label=Profile+Views+/+Repo+Views+" alt="Repo / Profile Views" />
</p>





