<h1 align="center">Shardeum Sphinx 1.1 Beta Testneti

## Shardeum'un Sphinx ağında validator kuruyoruz. Sağ üstten yıldızlayıp forklamayı unutmayalım. Sorularınız olursa: <a href="https://t.me/CoinHuntersTR/34102" target="_blank" rel="Coin Hunters TR" >Coin Hunters TR</a>

![image](https://user-images.githubusercontent.com/101462877/216376207-8a54c853-8e4c-42bc-b2df-3622c0f2fcd9.png)

## Sistem gereksinimleri:
NODE TİPİ | CPU     | RAM      | SSD     |
| ------------- | ------------- | ------------- | -------- |
| Sphinx 1.1 | 2-4          | 8         | 200  |
  
  
  
# Sphinx (Betanet) ağını metamask'e eklemek için: https://docs.shardeum.org/network/endpoints
  
  <img width="1440" alt="Ekran Resmi 2023-02-02 19 47 45" src="https://user-images.githubusercontent.com/101462877/216388297-d9b47afc-c5e6-4245-9bd9-1171a05fa77d.png">

  

## Shardeum için önemli linkler:
- <a href="https://shardeum.org" target="_blank">Website</a>
- <a href="https://explorer-sphinx.shardeum.org" target="_blank">Explorer</a>
- <a href="https://twitter.com/shardeum" target="_blank">Twitter</a>
- <a href="https://discord.gg/shardeum" target="_blank">Discord</a>



# 1) Kütüphanelerin kurulumu.

```
sudo apt update && sudo apt upgrade -y
```

```
sudo apt-get install curl
```
```
sudo apt install docker.io -y
```

```
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```

# 2) Shardeum Validator kurulumu.

```
curl -O https://gitlab.com/shardeum/validator/dashboard/-/raw/main/installer.sh && chmod +x installer.sh && ./installer.sh
```

## Sırasıyla `y` diyin, bir şifre belirleyin, port sorduğunda `8080` girin, base directory sorduğunda direkt `Enter` basın ki .shardeum konumuna kaydetsin.

<img width="1440" alt="Ekran Resmi 2023-02-02 19 12 16" src="https://user-images.githubusercontent.com/101462877/216379061-943482d3-1f8e-4d11-9241-8a39be09065b.png">

<img width="1440" alt="Ekran Resmi 2023-02-02 19 13 12" src="https://user-images.githubusercontent.com/101462877/216379370-a8568c65-85ca-477a-a8e1-2a4e3f2c424f.png">

![image](https://user-images.githubusercontent.com/101462877/216380082-8c616ccd-8f60-4ec4-9324-ff1097c20eba.png)

# 3) Aşağıdaki görseldeki gibi bir çıktı gördükten sonra devam ediyoruz.

![image](https://user-images.githubusercontent.com/101462877/216381866-e840b39c-1e87-4403-a0d2-32289e206ad4.png)

```
$HOME/.shardeum/shell.sh
```

```
operator-cli gui start
```


# 4) Bilgisayarımızda herhangi bir tarayıcıyı açıyoruz.

## Arama çubuğuna `https://SUNUCUIP:8080` şeklinde yazıyoruz. Örneğin, sunucunuzun IP'si 10.11.12.13 ise https://10.11.12.13:8080 yazıyoruz. GÜVENLİ DEĞİL DERSE GELİŞMİŞ, SİTEYE İLERLE DİYORUZ.

<img width="578" alt="Ekran Resmi 2023-02-02 19 27 01" src="https://user-images.githubusercontent.com/101462877/216383216-0c28fabd-ba14-41a5-b886-dd87f775911e.png">

## Yukarıda belirlemiş olduğumuz şifreyi giriyoruz.

<img width="1440" alt="Ekran Resmi 2023-02-02 19 28 13" src="https://user-images.githubusercontent.com/101462877/216383365-30973dbc-43a5-48cb-a916-6c1a013d4aec.png">
  
 
## `Maintenance` kısmına gelerek `start node` diyoruz.
  
<img width="1440" alt="Ekran Resmi 2023-02-02 22 36 51" src="https://user-images.githubusercontent.com/101462877/216432476-13ee3ec7-9381-4bf2-acb1-09baa8d75ad6.png">

  
## Metamask'ı  SPHINX AĞINDA bağlıyoruz. Sphinx ağı nasıl eklerim dersen yukarıda var.
  
  <img width="1440" alt="Ekran Resmi 2023-02-02 22 36 51" src="https://user-images.githubusercontent.com/101462877/216432965-714c474d-a742-4032-b6ca-bea7972962e1.png">
  
  
## Faucet alıyoruz. Buradan: <a href="https://chaindrop.org/?chainid=8082&token=0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee" target="_blank">Faucet</a> 
  
  ![image](https://user-images.githubusercontent.com/101462877/216433395-0940fe21-6806-4a62-8d71-8b42330341ff.png)


## Stakeliyoruz.
  
  <img width="1440" alt="Ekran Resmi 2023-02-02 22 43 18" src="https://user-images.githubusercontent.com/101462877/216433614-73f58204-608f-419e-9901-7eb80590a577.png">


 ## Terminale geri dönerek aşağıdaki komutu giriyoruz.

```
operator-cli start
```
  

# Aşağıdaki komut ile durumu görüntüleyebilirsiniz.
  

```
pm2 list
```
  
  ![image](https://user-images.githubusercontent.com/101462877/216434539-6bcf7343-fcb3-423a-a7ee-d1cb8f1dde68.png)



# Sorularınız ve merak ettikleriniz için : <a href="https://t.me/CoinHuntersTR/34102" target="_blank">Coin Hunters TR</a>



