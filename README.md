# Join Telegram  ♾︎ 
[![Static Badge](https://img.shields.io/badge/Telegram-Airdrop◾unlimited-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/UNLXairdop)


# ICN node
pastikan kalian menggunakan wallet baru dan ambil 'privatekey' kalian
lalu hapus bagian `<private_key` dan paste `private_key` kalian

## Untuk linux/mac

```


curl -o- https://console.icn.global/downloads/install/start.sh | bash -s -- -p <private_key>


```

## Untuk windows

```

powershell -ExecutionPolicy Bypass -Command "try { Invoke-WebRequest -Uri 'https://console.icn.global/downloads/install/start.ps1' -OutFile '.\start.ps1' -UseBasicParsing; & '.\start.ps1' -PrivateKey '<private_key>'} finally { Remove-Item .\start.ps1 -ErrorAction SilentlyContinue }"

```
