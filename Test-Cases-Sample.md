# Sample Test Cases – QASE

## TC-LOGIN-NEG-01
**Title:** Login gagal dengan password salah  
**Layer:** E2E  
**Priority:** High  
**Type:** Functional  

### Precondition
- User terdaftar dan aktif

### Test Steps
1. Masukkan email valid
2. Masukkan password salah
3. Klik tombol "Masuk"

### Expected Result
- Sistem menolak login
- Pesan error tampil
- User tetap di halaman login

### Post-condition (WSBH)
- User tidak memiliki session login
