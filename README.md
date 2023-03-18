# Tentang
- Limit bandwidth for openwrt router device
- Versi CLI dari [MulImiter - OpenWrt bandwidth limiter through iptables firewall with PHP GUI](https://github.com/tegohsx/mulimiter)

### Paket pendukung
- `bash`
- `iptables`
- `iptables-mod-hashlimit`
- `iptables-mod-iprange`

### Improve 
- Pengaturan akan otomatis dijalankan saat reboot.
- Pengaturan bandwith yang tersimpan tidak akan hilang saat reboot.

### Instalasi

Jalankan perintah dibawah ini ke terminal untuk instalasi:

```
wget --no-check-certificate "https://raw.githubusercontent.com/vitoharhari/limitbw/main/installer" -O /tmp/installer && chmod +x /tmp/installer && sh /tmp/installer && limitbw
```

### Pemakaian
 
- Jalankan `limitbw` untuk menampilkan menu.
- Jalankan `limitbw 1` untuk mengatur batasan bandwidth.
- Jalankan `limitbw 2` untuk melihat pengaturan yang tersimpan.
- Jalankan `limitbw 3` untuk menghapus pengaturan.
- Jalankan `limitbw 4` untuk menonaktifkan pengaturan limit saat startup.
- Jalankan `limitbw u` untuk update limitbw.

### Multi IP / Multi IPRANGE

- Ketika menjalankan `limitbw 1` akan muncul beberapa pertanyaan
- `IMPORTANT!!` ketika menjalankan `limitbw 1` pengisian nama rule `WAJIB` diisi dan `WAJIB` berbeda

### Support Multi IP dan Multi IPRANGE

- Sudah support untuk per IP unlimited rule
- Sudah support untuk multi IPRange dengan unlimited rule

### Spesial Thanks
- [Mbah Teguh](https://github.com/tegohsx)
- [Mbah Rayhanbone](https://github.com/rayhanbone)
- [Mbah Helmi](https://github.com/helmiau)
- [Mbah Wegare](https://github.com/wegare123)

> mohon ijin ya master-master ku sekalian, ijin remod hehehe

### Spesial Thanks to Master Guru
- [Mbah Teguh Surya Mungaran/Alkhanet](https://github.com/alkhanet26)
yang selalu saya tanya dan ngajarin saya setiap hari 


