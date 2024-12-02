# jualbeliLaptop
# Aplikasi Jual Beli Laptop dan PC

Aplikasi ini memungkinkan pengguna untuk membeli dan menjual laptop atau PC.

## Fitur Utama:
- Pengguna dapat menambah produk laptop/PC.
- Pengguna dapat melihat daftar produk yang dijual.
- Pengguna dapat membeli produk.

## Cara Menjalankan

### Backend
1. Masuk ke direktori `backend/`.
2. Bangun dan jalankan backend:
    ```bash
    cargo build --release
    cargo run
    ```

### Frontend
1. Masuk ke direktori `frontend/`.
2. Bangun frontend dengan WebAssembly:
    ```bash
    wasm-pack build --target web
    ```
3. Jalankan server lokal untuk mengakses aplikasi web:
    ```bash
    python3 -m http.server 8080
    ```

Akses aplikasi di `http://localhost:8080`.
