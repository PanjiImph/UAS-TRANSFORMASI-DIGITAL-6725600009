# PRAKTIKUM DEPLOY SERVER LAYANAN INTERNAL
---

## Deskripsi Project

Project ini bertujuan untuk membangun server layanan internal menggunakan **Ubuntu Server**. Layanan yang diimplementasikan meliputi **Web Server (Nginx)**, **Database Server (MySQL)**, **File Server (Samba)**, serta **Backup Server (Rsync)** untuk mendukung penyimpanan data, berbagi file, layanan web, dan pencadangan data pada jaringan lokal.

---

## Teknologi yang Digunakan

- Ubuntu Server 24.04 LTS
- Oracle VirtualBox
- Nginx
- MySQL Server
- Samba
- Rsync
- UFW Firewall
- Linux CLI

---

## Cara Menjalankan

1. Install Ubuntu Server.
2. Update repository sistem.
3. Install Nginx.
4. Install MySQL Server.
5. Install Samba.
6. Konfigurasi File Server dan Web Server.
7. Jalankan seluruh service menggunakan:

```bash
sudo systemctl start nginx
sudo systemctl start mysql
sudo systemctl start smbd
```

8. Cek status service:

```bash
sudo systemctl status nginx
sudo systemctl status mysql
sudo systemctl status smbd
```

9. Pastikan seluruh service berstatus:

```text
Active: active (running)
```

---

## Hasil

Deploy Server Layanan Internal berhasil dijalankan menggunakan Ubuntu Server. Seluruh layanan seperti **Nginx**, **MySQL**, **Samba**, dan **Backup Server** dapat berjalan dengan baik sehingga server mampu melayani kebutuhan web, database, file sharing, dan backup data.

---

## Screenshot

Screenshot proses deployment dapat dilihat pada folder:

```
docs/Screenshot/
```

---

# UAS-TransformasiDigital-NIM

Deploy Server Layanan Internal menggunakan Ubuntu Server sebagai implementasi tugas mata kuliah **Transformasi Digital**.
