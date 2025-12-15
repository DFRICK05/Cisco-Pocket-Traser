SIMMULASI JARINGAN MENGGUNAKAN CISCO BASIC 
MENGHUBUNGKAN LEBIH DARI 1 KOMPUTER

1. End Devices → PC
DRAG PC0
DRAG PC1

2.Network Devices → Switch
Tarik Switch 2960

🔌 3. Menghubungkan Kabel

Klik Connections (ikon petir ⚡)
Pilih Copper Straight-Through

Hubungkan:

PC0 FastEthernet0 → Switch FastEthernet0/1

PC1 FastEthernet0 → Switch FastEthernet0/2

👉 Tunggu lampu hijau (kalau masih kuning, tunggu ±5 detik)

🌐 4. Setting IP Address (INI PENTING)
🔹 PC0

Klik PC0 → Desktop → IP Configuration

IP Address: 192.168.1.1

Subnet Mask: 255.255.255.0

Default Gateway: (kosong dulu)

🔹 PC1

Klik PC1 → Desktop → IP Configuration

IP Address: 192.168.1.2

Subnet Mask: 255.255.255.0

Default Gateway: (kosong dulu)

📌 Kenapa gateway kosong?
Karena belum pakai router, masih satu jaringan (LAN).

🧪 5. Tes Koneksi (PING)
Dari PC0:

PC0 → Desktop → Command Prompt

ping 192.168.1.2

Hasil yang benar:
Reply from 192.168.1.2: bytes=32 time<1ms TTL=128


✅ Artinya jaringan BERHASIL

<img width="347" height="395" alt="image" src="https://github.com/user-attachments/assets/49daa341-300d-4151-bf30-a5ea5ff9fa68" />



