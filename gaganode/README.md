<p align="center">
  <img height="300" height="auto" src="https://i.ibb.co/r7g8wn6/photo-2021-05-18-09-00-47.jpg">
</p>

Thanks to:
>- [marketgogreen](https://github.com/mggnet)

# Meson Network node setup for Testnet
>- Register : https://dashboard.gaganode.com/register?referral_code=rnobguvcdq

## 1️⃣ Go Shell Console
Link : https://shell.cloud.google.com/ <br>
Login with Your Email <br><br>
<img height="200" height="auto" src="https://i.ibb.co/vDbPNVp/install.png" alt="1" border="0" /></a>
```python
curl -o app-linux-amd64.tar.gz https://assets.coreservice.io/public/package/22/app/1.0.3/app-1_0_3.tar.gz && tar -zxf app-linux-amd64.tar.gz && rm -f app-linux-amd64.tar.gz && cd ./app-linux-amd64 && sudo ./app service install
```
## 2️⃣ Start App
<img height="200" height="auto" src="https://i.ibb.co/bgjyk2v/1.png" alt="1" border="0" /></a>
```python
./app
```
```python
start
```
### AND WAIT 30 SEC
After that you can <i>CRTL + C</i>

## 3️⃣ Setup Your Token
<img height="200" height="auto" src="https://i.ibb.co/886FRKZ/2.png" alt="1" border="0" /></a>
```python
./apps/gaganode/gaganode config set --token=YOUR_TOKEN
```
*Fill Node Token to <b><i>YOUR_TOKEN</i></b> <br>
U can find it here : https://dashboard.gaganode.com/install_run

## 4️⃣ Restart App
<img height="200" height="auto" src="https://i.ibb.co/7QrTm46/3.png" alt="1" border="0" /></a>
```python
./app
```
```python
restart
```

## Check Your Node Status
Go to : https://dashboard.gaganode.com/user_node <br>
<img height="500" height="auto" src="https://i.ibb.co/p39GvwD/4.png" alt="1" border="0" /></a>






