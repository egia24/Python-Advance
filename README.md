# Python OOP Exploration

Repo ini berisi latihan Python untuk memahami **Class, Object, Encapsulation, Inheritance, Polymorphism, dan Abstraction**. Latihan bersifat eksploratif.

---

## Latihan

### 1. Class & Object
- Buat class `Person` dengan atribut `nama` dan `usia`.
- Metode `info_person()` menampilkan informasi person.

### 2. Encapsulation
- Tambahkan atribut private `__saldo`.
- Metode: `deposit()`, `tarik()`, `cek_saldo()`.

### 3. Inheritance
- Subclass dari `Person`:
  - `Mahasiswa` → `nim`
  - `Pegawai` → `gaji`
  - `Dosen` → `mata_kuliah`

### 4. Polymorphism
- Metode `tabungan()` di-override tiap subclass dengan format sesuai tipe person.

### 5. Abstraction
- Class abstrak `TabunganInterface` dengan metode `tabung(amount)`.
- Subclass wajib implementasi untuk menambah saldo.

---
