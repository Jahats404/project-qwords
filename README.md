## Cara Instalasi Website

1. **Clone Repositori:**

    ```bash
    git clone <URL_REPOSITORI>
    ```

    Gantilah `<URL_REPOSITORI>` dengan URL repositori Laravel yang ingin Anda clone.

2. **Pindah ke Direktori Proyek:**

    ```bash
    cd nama-proyek
    ```

3. **Instal Dependensi:**

    ```bash
    composer install
    ```

4. **Konfigurasi Lingkungan:**

    - Duplikat file `.env.example` dan ganti namanya menjadi `.env`.
    - Buka file `.env` dan atur konfigurasi database, seperti nama database, pengguna, dan kata sandi.

5. **Migrasi dan Penyemaian Basis Data:**

    ```bash
    php artisan migrate
    ```

6. **Kunci Aplikasi dan Persiapan:**

    ```bash
    php artisan key:generate
    ```

7. **Jalankan Server Pembangunan:**

    ```bash
    php artisan serve
    ```

8. **Buka Aplikasi dalam Browser:**

    Buka browser dan akses [http://localhost:8000](http://localhost:8000) (sesuaikan port jika perlu) untuk melihat aplikasi Laravel yang baru saja diunduh.

9. **Selesai:**

    Selamat! Laravel sekarang diinstal dan berjalan di lingkungan lokal Anda.

---

## Informasi Proyek

-   **Framework:** Laravel
-   **Bahasa Pemrograman:** PHP
-   **UI Framework:** Bootstrap
-   **JavaScript Libraries:** Swiper, Isotope, AOS, Lightbox
-   **Font Scripts:** Google Montserrat, Roboto+Slab

---

## Informasi Sumber Template

-   **Template Name:** Agency
-   **Updated:** Sep 27 2023 with Bootstrap v5
-   **Template URL:** [Agency - StartBootstrap](https://startbootstrap.com/theme/agency/)
-   **Author:** StartBootstrap.com
-   **License:** [License](StartBootstrap.com/)

---
