# 🔌 IoT Multi-Broker Dashboard dengan Voice Command

## 📌 Deskripsi
Proyek ini merupakan sistem Internet of Things (IoT) berbasis ESP32 yang mampu:
- Terhubung ke 3 MQTT Broker secara bersamaan
- Mengontrol 4 relay
- Memonitor suhu dan kelembapan (DHT11/DHT22)
- Menggunakan perintah suara (Voice Command)
- Menampilkan visualisasi 3D menggunakan Three.js

---

## 🚀 Fitur Utama
✅ Multi MQTT Broker (3 broker aktif)  
✅ Monitoring suhu & kelembapan real-time  
✅ Kontrol 4 relay + semua relay  
✅ Mode kombinasi (LEFT_RIGHT & STROBE)  
✅ Voice command bahasa Indonesia  
✅ Text-to-Speech (membacakan data sensor)  
✅ Visualisasi 3D sistem IoT  
✅ Log aktivitas sistem  

---

## 🧠 Teknologi yang Digunakan
- HTML5, CSS3, JavaScript
- MQTT.js (WebSocket)
- Three.js (3D Visualization)
- Web Speech API (Voice Recognition)
- SpeechSynthesis API (Text-to-Speech)
- ESP32 + Arduino IDE

---

## 🌐 MQTT Broker yang Digunakan
1. Mosquitto → `wss://test.mosquitto.org:8081/mqtt`  
2. Flespi → `wss://mqtt.flespi.io:443`  
3. XMqtt → `wss://broker.xmqtt.net:8081`  

---

## 📡 MQTT Topic
| Fungsi | Topic |
|------|------|
| Sensor | gusli/iot-multibroker/sensor |
| Relay Status | gusli/iot-multibroker/relay/status |
| Relay Control | gusli/iot-multibroker/relay/+/set |
| Mode | gusli/iot-multibroker/mode/set |

---

## 🖥️ Cara Menjalankan
1. Download / clone repository ini
2. Buka file `index.html` di browser
3. Pastikan ESP32 sudah aktif dan terkoneksi MQTT
4. Gunakan dashboard untuk monitoring & kontrol

---

## 🎤 Contoh Voice Command
- “Nyalakan relay satu”
- “Matikan semua relay”
- “Berapa suhu sekarang”
- “Jalankan mode strobo”

---

## 📸 Screenshot
### Dashboard
![Dashboard](screenshots/dashboard.png)

### Kontrol Relay
![Relay](screenshots/relay.png)

### Voice Command
![Voice](screenshots/voice.png)

---

## 🎥 Video Demo
🔗 (MASUKKAN LINK VIDEO DI SINI)

---

## 👨‍💻 Author
Nama: Tito Creydo Silitonga  
Proyek: IoT Multi-Broker dengan Voice Command
