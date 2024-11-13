# ICN node
pastikan kalian menggunakan wallet baru dan ambil 'privatekey' kalian
lalu hapus bagian '<private_key>' dan paste 'privatekey' kalian

## Untuk linux/mac

```


curl -o- https://console.icn.global/downloads/install/start.sh | bash -s -- -p <private_key>


```

## Untuk windows

```

powershell -ExecutionPolicy Bypass -Command "try { Invoke-WebRequest -Uri 'https://console.icn.global/downloads/install/start.ps1' -OutFile '.\start.ps1' -UseBasicParsing; & '.\start.ps1' -PrivateKey '<private_key>'} finally { Remove-Item .\start.ps1 -ErrorAction SilentlyContinue }"

```
