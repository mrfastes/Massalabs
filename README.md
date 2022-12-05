# <p align="center"> Tutorial Massa Labs Incentivized Tesnet Round 17 </p>

<p style="font-size:14px" align="left">
<a href="https://t.me/Pepoy_Crypto" " target="_blank" rel="nofollow">Join Telegram kami <img width="20" height="auto" src="https://github.com/mrfastes/datablog/blob/main/photo_2022-09-17_07-05-40.jpg" </a>
</p>
<p style="font-size:14px" align="left">
<a href="https://twitter.com/mrfastes" target="_blank"> Follow My twitter
</p>
<p style="font-size:14px" align="left">
<a href="https://medium.com/@massacaptain/tutorial-praktis-testnet-berinsentif-massa-eps-13-d7d5f19f1462" target="_blank">Source by Captain Massa
</p>
<p style="font-size:14px" align="left">
<a href="https://massa.net/" target="_blank"> Massa Web
</p>
 
<p body style="background-color:black;"> 
   <img width="50%" height="auto" background-color:"black" src="https://github.com/mrfastes/datablog/blob/main/logo_massa.989057b.webp">
</p>                                                                                                                                      


# Massa Incentivized Tesnet

|  Komponen |  Persyaratan Minimum |
| ------------ | ------------ |
| CPU  | 4 core  |
| RAM | 8 GB  |
| Penyimpanan  | 200 GB HDD |

## Download Paket Massa 
### Ikuti Step by Step

```
apt update && apt upgrade
```
 
```
wget -O massa-testnet.sh https://raw.githubusercontent.com/mdlog/testnet-mdlog/main/massa/massa-testnet.sh && chmod +x massa-testnet.sh && ./massa-testnet.sh
```
>Input IP address Vps kalian 
                                                                                                                                       
>Input Password kalian bebas lalu simpan dengan baik                                                                                                                  
                                                                                                                                       
                                                                                                                                       
### Setelah instalasi selesai masuk ke follder massa-client
```
cd massa/massa-client
```
```
./massa-client
```
>Masukan Password yg tadi kita gunakan                                                                                                                                 
                                                                                                                                       
                                                                                                                                       
## Jika sudah memiliki wallet dan mengikuti tesnet pada episode sebelumnya, maka bisa di skip tahap ini, jika belum silahkan buat wallet baru                                                                                                                                       
```
wallet_generate_secret_key
```
```                                                                                                                                       
wallet_info
```                                                                                                                                       
                                                                                                                                       
## untuk mengimport wallet yg sebelumnya digunakan 
```
wallet_add_secret_keys <secret_key_kamu>
```
```                                                                                                                                       
wallet_info
```     
> Silahkan salin alamat address wallet kalian, lalu minta faucet di discord dengan mempastekanya pada #tesnet-faucet 

> Cek kembali <b>wallet-info</b> apakah faucet sudah masuk
                                                                                                                                       
```
buy_rolls <address kalian> <roll count> <fee>
```
>contoh <b>buy_rolls VkUQ5MA4niNBhAEP7uVf89tvPfUHcbgy6BrdLM9SAuFSyy9DE 1 0</b>
                                                                                                                                       

```
node_add_staking_secret_keys <secretkey_kamu>
```
