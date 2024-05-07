### 2.1. Original code of broadcast chat

![alt text](image.png)
Run menggunakan
`cargo run --bin server` untuk server dan
`cargo run --bin client` untuk masing-masing client.
Tiap client dan tiap server mendapatkan chat broadcast dari tiap clientnya. Tiap kali suatu client mengirim pesan, pesan dikirimkan ke server, yang memforwardnya ke semua client yang terhubung.