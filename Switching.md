Switch

![1 sw](https://github.com/Chioaji/Switch/assets/126127582/07012684-a991-4074-944b-11e0cb92bb6c)

Show ip vlan pada Switch Perintah ini tidak secara eksplisit ada dalam perangkat Cisco IOS; yang lebih umum adalah show vlan atau show vlan brief untuk switch yang menggunakan Cisco IOS. Perintah ini menampilkan informasi tentang VLAN yang dikonfigurasi pada switch, termasuk ID VLAN, nama VLAN, dan port apa saja yang termasuk dalam VLAN tertentu


![2 sw](https://github.com/Chioaji/Switch/assets/126127582/7e94a19d-590a-4789-bde7-c165609b1248)

Perintah show running-config menampilkan konfigurasi aktif (yang sedang berjalan) pada switch. Ini mencakup semua pengaturan dan konfigurasi yang telah diterapkan, termasuk konfigurasi VLAN, pengaturan port, konfigurasi trunk, dan lain-lain. Pada ROUTER_1: Perintah yang sama pada router akan menampilkan konfigurasi aktif dari router tersebut, termasuk antarmuka jaringan, rute statis atau dinamis, pengaturan protokol routing, konfigurasi NAT, DHCP, ACLs

![3 sw](https://github.com/Chioaji/Switch/assets/126127582/84ebb592-0b40-43d9-a34a-cc661383e703)

Menampilkan detail tentang pool DHCP yang telah dikonfigurasi, termasuk range alamat IP yang tersedia untuk disewakan, mask subnet, default gateway, DNS server, lease time, dan lainnya. Ini membantu dalam memahami dan memverifikasi konfigurasi DHCP di jaringan.

![4 sw](https://github.com/Chioaji/Switch/assets/126127582/15024e16-e0e2-4f40-b3c7-f38eef00c865)

Termasuk jumlah translasi aktif, jumlah hitungan untuk translasi NAT, dan sumber daya yang 
digunakan. Ini penting untuk memahami seberapa efektif NAT bekerja dan mendiagnosis masalah 
koneksi.

![5 sw](https://github.com/Chioaji/Switch/assets/126127582/2ab03075-8a52-48fc-b2cb-a09f0991d148)


Membutuhkan router atau switch layer 3 untuk melakukan routing antar VLAN (InterVLAN routing). Paket dari sumber akan dikirim ke gateway (router atau switch L3), yang kemudian akan meneruskannya ke VLAN tujuan. Konfigurasi NAT: Jika tujuannya berada di luar jaringan lokal (misalnya, Internet), router akan melakukan NAT pada paket tersebut, mengganti alamat IP sumber internal dengan alamat IP publik router sebelum mengirimkannya ke jaringan eksternal. Untuk setiap skenario, perangkat di jaringan harus dikonfigurasi dengan benar, termasuk VLAN, routing, dan NAT, agar komunikasi data berjalan sesuai dengan harapan
