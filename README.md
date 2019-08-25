## Demo Solusi Mengakses Database Lokal (IP Private) Secara Online Bagian #1

Terdiri dari 3 aplikasi:

1. [WebSocketService](https://github.com/k4m4r82/demo-websocket-signalr/releases/download/v1.0.0/01.WebSocketService.zip) – Aplikasi ini bisa diinstall secara terpisah atau satu mesin dengan database. Jadi aplikasi ini berfungsi seperti pintu belakang untuk mengakses database. Aplikasi ini dibuat menggunakan WinForm atau bisa juga berbasis windows service, intinya disesuaikan dengan kebutuhan Anda. Karena aplikasi ini menggunakan library SignalR Core untuk berkomunikasi dengan aplikasi WebSocketGateway yang ada di VPS, maka untuk menjalankan aplikasi ini minimal windows yang dibutuhkan adalah Windows 7 SP1 (.NET Framework 4.6.x).
2. [DesktopApp](https://github.com/k4m4r82/demo-websocket-signalr/releases/download/v1.0.0/02.DesktopApp.zip) - Aplikasi klien desktop
3. [MobileApp](https://github.com/k4m4r82/demo-websocket-signalr/releases/download/v1.0.0/03.MobileApp.zip) - Aplikasi klien mobile. Untuk menginstall aplikasi mobile Anda harus mengaktifkan setting `install unknown apps`.

Download aplikasi di https://github.com/k4m4r82/demo-websocket-signalr/releases