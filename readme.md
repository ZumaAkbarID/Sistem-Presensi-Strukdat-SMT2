
# Sistem Presensi C++

Tiruan dari sistem presensi AMIKOM Yogyakarta namun yang manual menggunakan NIM via CLI.


## Installation

Pastikan sudah menginstall compiler versi 10+. Compile Plugin terlebih dahulu
```bash
  gcc -c lib/fort.c -o lib/fort.o
```
Selanjutnya compile main file
```bash
  g++ presensiMahasiswa.cpp lib/fort.o -o program.exe
```
    
## Usage
Klik 2x hasil compile atau jalankan melalui CLI
```bash
    ./program (enter)
```