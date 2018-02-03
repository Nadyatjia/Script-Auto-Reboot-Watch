# Script-Auto-Reboot+Watch
Cara Pemakaian :
------
- `Copy File nadya Ke Dalam Folder Bot Kalian`
- `Buka File nadya Dan Ubah python2 Nadya.py, Jadi python2 (Nama File.py Kalian)`
- while (( running )); do
-    python2 Nadya.py <<- `Nama File.py Kalian`
-    echo "Restarting server on crash.."
-    sleep 2 <<- `Waktu Delaynya`
- `Lalu Save`
- `Open Terminal, Ketik->> "cd NamaFolder" >> "chmod +x nadya" >> "./nadya"`

Pakai Waktu (Auto Restart Bot Pakai Waktu Yang Kita Tentukan)
------
1. Run Botnya. . .
- `screen -R Nadya`
- `cd Chuckyfix`
- `./nadya`

2. Tambah Sesion Di Terminal. . .
- `Tekan Ctrl + B, Lepas, Dan Tekan C (Buat Nambah Session)`
- `Nb : Ctrl + B, Lepas, Dan Tekan Angka Sesion Kamu (Buat Pindah Ke Session Yang Kamu Mau)`

3. 
- `Kemudian, Setelah Ctrl + B, Lepas, Dan Tekan C Ketik:` watch -n 14000 killall -9 python2
- `Nb : 14000, Adalah Waktu Detik Bot Akan Restart Otomatis`
