<h4 align="center"><u>Ngrok Full Setup Cods</u></h4>

![Hack page and get images](https://raw.githubusercontent.com/Masterdas/Ngrok/refs/heads/main/PNG/Screenshot_2025_0219_165206.png)

### [NGROK] Install All Comments


```
pkg update && pkg upgrade -y
```
```
pkg install -y wget git
```
```
wget https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-linux-arm64.tgz
```
```
tar -xvzf ngrok-v3-stable-linux-arm64.tgz && rm -rf ngrok-v3-stable-linux-arm64.tgz
```
```
mv ngrok /data/data/com.termux/files/usr/bin/
```
```
chmod +x /data/data/com.termux/files/usr/bin/ngrok
```
```
ngrok version
```


### 📌 Ngrok add token
### 🔹 **Ngrok অটোকনফিগার করুন**
```
ngrok config add-authtoken <your_ngrok_token>
```

### ✅ **Ngrok চালু করুন**
```
ngrok http 8080
```

---

## 🔥 **Cloudflare Tunnel সেটআপ**

### 🔹 **Cloudflared ইনস্টল করুন**
```
pkg install cloudflared
```

### ✅ **Cloudflared টানেল চালু করুন**
```
cloudflared tunnel --url localhost:8080
```
---

## 📌 Contact Me  

<a href="https://youtube.com/@zerodarknexus">
  <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube">
</a>  


<a href="https://github.com/Masterdas?tab=repositories">
  <img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>  


<a href="https://t.me/ZeroHackNexus">
  <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
</a>    

<a href="https://chat.whatsapp.com/II35pNaN25rHqnUmqXK6ag">
  <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
</a>
