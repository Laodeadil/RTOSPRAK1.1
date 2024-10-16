Proyek STM32 - ADC, Tombol, dan UART

Deskripsi Proyek
Proyek ini adalah implementasi dari sistem berbasis STM32 yang mengukur tegangan menggunakan ADC dan menampilkan hasil pengukuran melalui antarmuka UART. Sistem ini juga memungkinkan interaksi melalui tombol fisik untuk mengendalikan fungsi tertentu.

Diagram Node/Task
Berikut adalah diagram alur kerja dari task-task utama dalam sistem ini:

1. Inisialisasi: Mengatur GPIO, ADC, dan UART.
2. Task ADC: Membaca nilai tegangan dari input ADC.
3. Task UART: Mengelola komunikasi dan input dari pengguna melalui antarmuka UART.
4. Task Tombol: Memantau status tombol fisik untuk fungsi tertentu.

Foto Hardware
Berikut adalah foto perangkat keras yang digunakan dalam proyek ini, yang mencakup STM32 dan dua tombol fisik:

![WhatsApp Image 2024-10-15 at 19 01 55](https://github.com/user-attachments/assets/699aa046-6a6a-4831-8c6d-24529735212c)

Demo Video/GIF
Berikut adalah demo video proyek ini yang menunjukkan cara kerja sistem dalam membaca nilai tegangan dan menampilkannya melalui UART, serta bagaimana pengguna dapat berinteraksi melalui tombol.


https://github.com/user-attachments/assets/249136f9-7f3c-4e76-a981-d7c4db7aa285


Daftar Perangkat Keras
- STM32 Microcontroller: STM32F103C8T6
- Tombol: Dua tombol fisik
- Variabel Resistor : Trimpot 10k
- Kabel Jumper: Untuk sambungan

Daftar Perangkat Lunak
- IDE: STM32CubeIDE
