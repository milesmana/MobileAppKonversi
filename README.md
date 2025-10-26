🔢 AppKonversi

**AppKonversi** adalah aplikasi **Android berbasis Java** yang berfungsi untuk melakukan berbagai **konversi satuan** seperti suhu, massa, luas, dan jarak.  
Dibangun menggunakan **Android Studio**, aplikasi ini memiliki tampilan sederhana, ringan, dan cocok untuk kebutuhan belajar logika konversi di Android.

---

📱 Tangkapan Layar

| Menu Utama | Contoh Hasil |
|-------------|--------------|
| ![Menu Utama](docs/images/menu.png) | ![Hasil Konversi](docs/images/result.png) |

---

🧠 Tentang Proyek

Aplikasi ini dikembangkan sebagai latihan dasar dalam pembuatan aplikasi Android dengan bahasa **Java**.  
AppKonversi membantu pengguna melakukan berbagai konversi umum secara cepat dan akurat — langsung dari smartphone Android.

---

✨ Fitur Utama

- 🔥 Konversi suhu (Celsius ↔ Fahrenheit ↔ Kelvin)  
- ⚖️ Konversi massa (gram, kilogram, pon, ons)  
- 📏 Konversi panjang/jarak (meter, kilometer, mil, yard)  
- 🧮 Konversi luas (m², cm², hektar, are)  
- 🖥️ Antarmuka modern berbasis Material Design  
- 💾 Tidak memerlukan koneksi internet (offline mode)  

---

🛠️ Teknologi yang Digunakan

| Komponen | Teknologi |
|-----------|------------|
| Bahasa Pemrograman | Java |
| Framework | Android SDK |
| Minimum SDK | 21 (Android 5.0 Lollipop) |
| Target SDK | 34 |
| IDE | Android Studio |
| Gradle | Build automation system |

---

📁 Struktur Folder

AppKonversi/
├── app/
│ ├── src/
│ │ ├── main/
│ │ │ ├── java/com/example/appkonversi/
│ │ │ │ ├── MainActivity.java
│ │ │ │ ├── converters/
│ │ │ │ │ ├── SuhuConverter.java
│ │ │ │ │ ├── MassaConverter.java
│ │ │ │ │ ├── LuasConverter.java
│ │ │ │ │ └── JarakConverter.java
│ │ │ ├── res/
│ │ │ │ ├── layout/
│ │ │ │ │ ├── activity_main.xml
│ │ │ │ │ └── fragment_converter.xml
│ │ │ │ ├── values/
│ │ │ │ └── drawable/
│ │ │ └── AndroidManifest.xml
│ │ ├── test/java/com/example/appkonversi/
│ │ └── androidTest/java/com/example/appkonversi/
│ ├── build.gradle
│ └── proguard-rules.pro
├── gradle/
├── build.gradle
├── settings.gradle
├── gradlew
├── gradlew.bat
├── local.properties
└── README.md


---

⚙️ Cara Menjalankan Proyek

1. **Clone repository ini**
   ```bash
   git clone [https://github.com/username/AppKonversi.git](https://github.com/milesmana/MobileAppKonversi)
   cd AppKonversi
2. Buka proyek di Android Studio
   - Pilih File → Open → AppKonversi
   - Pastikan Android SDK sudah terinstal (API Level 21 atau lebih tinggi)
3. Sinkronisasi Gradle
   - Android Studio akan otomatis melakukan sync dependensi
4. Jalankan di Emulator atau Perangkat Fisik
   - Pilih perangkat dan klik ▶️ Run
