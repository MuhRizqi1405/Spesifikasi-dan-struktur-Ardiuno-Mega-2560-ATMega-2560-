## **NAMA : M.RIZQI**
## **NIM : 09011382429146**
# Spesifikasi-dan-struktur-control-unit-Arduino Mega (ATmega2560)
## Arduino Mega (ATmega2560) adalah salah satu microcontroller board yang populer, terutama untuk proyek yang membutuhkan lebih banyak pin I/O dan memori dibandingkan Arduino Uno
# **Spesifikasi Arduino Mega (ATmega2560):**
- Mikrokontroler: ATmega2560
- Clock Speed: 16 MHz
- Memori Flash: 256 KB (8 KB digunakan oleh bootloader)
- SRAM: 8 KB
- EEPROM: 4 KB
- Jumlah Pin I/O Digital: 54 (15 di antaranya dapat digunakan sebagai PWM)
- Pin Analog: 16
- Port Serial: 4 UART hardware
- Tegangan Operasional: 5V
- Tegangan Input (Direkomendasikan): 7-12V
- Konektivitas: USB, I2C, SPI
- Dimensi: 101.52 mm x 53.3 mm
# **Kelebihan Arduino Mega 2560:**
- ✅ Banyak Pin I/O → Cocok untuk proyek yang membutuhkan banyak sensor atau aktuator.
- ✅ Banyak Memori → Bisa menjalankan program yang lebih kompleks dibandingkan Uno.
- ✅ Banyak Port Serial (UART) → Memudahkan komunikasi dengan banyak perangkat sekaligus.
- ✅ Kompatibel dengan Banyak Shield → Bisa digunakan dengan berbagai modul dan ekspansi Arduino.
# **Kekurangan Arduino Mega 2560:**
- ❌ Ukuran Lebih Besar → Kurang cocok untuk proyek kecil atau portable.
- ❌ Kecepatan Tidak Tinggi → Masih berjalan di 16 MHz, kurang untuk aplikasi pemrosesan berat seperti AI atau vision processing.
  
# ** Struktur Arduino Mega (ATmega2560) : **
- Power Unit

Menyediakan suplai daya untuk board dari USB, adaptor DC, atau sumber eksternal.
Terdapat regulator tegangan untuk menyesuaikan daya ke 5V atau 3.3V.
- Komunikasi (Serial)

UART (Serial Hardware) → 4 port untuk komunikasi dengan komputer atau modul lain.
I2C (SDA, SCL) → Untuk komunikasi dengan sensor seperti OLED, RTC, dll.
SPI (MOSI, MISO, SCK, SS) → Untuk komunikasi ke SD card, modul RF, dan perangkat lain.
- Mikrokontroler (ATmega2560)

Otak utama yang menjalankan kode dan mengendalikan seluruh fungsi board.
Berjalan dengan clock 16 MHz untuk mengatur kecepatan eksekusi.
- Memory (Penyimpanan Data & Program)

Flash Memory (256 KB): Menyimpan kode program yang diunggah ke board.
SRAM (8 KB): Menyimpan variabel dan data yang sedang digunakan program.
EEPROM (4 KB): Memori permanen untuk menyimpan data yang tetap ada meskipun daya mati.
- Input / Output (I/O Pins)

Digital I/O (54 pin): Bisa digunakan sebagai input (sensor, tombol) atau output (LED, relay).
PWM (15 pin): Digunakan untuk mengontrol kecepatan motor atau kecerahan LED.
Analog Input (16 pin): Membaca sensor analog seperti suhu, tegangan, dan lainnya.
Interrupts: Pin khusus untuk menangani interupsi eksternal (contoh: sensor gerak).
- Reset Button

Menyetel ulang program tanpa harus mencabut daya.
# **Kegunaan Arduino Mega (ATmega2560):**
Contoh Penggunaan:
🔹 Robotika → Digunakan untuk robot dengan banyak motor atau sensor.
🔹 Automasi → Cocok untuk sistem kendali rumah pintar, industri, dll.
🔹 Proyek IoT → Bisa dihubungkan dengan modul Wi-Fi seperti ESP8266/ESP32.
🔹 Kontrol LED dan Motor → Cocok untuk proyek dengan banyak LED atau motor servo.
