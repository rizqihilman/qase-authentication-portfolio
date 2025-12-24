# Smoke Test Suite – Authentication

Smoke test digunakan untuk memastikan fitur utama dapat berjalan setelah build baru.

## Smoke Test Coverage
1. Login dengan kredensial valid
2. Register dengan data valid
3. Forgot Password dengan email terdaftar
4. Validasi field wajib
5. Redirect setelah login
6. Error message tampil dengan benar
7. Logout berhasil
8. Session expired handling

## Execution Rule
- Dijalankan setiap ada deployment
- Jika gagal → testing dihentikan
