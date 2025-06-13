# 🎵 Equaliter - El Takibi ile Müzik Hızı ve Frekans Kontrolü 🎶

---

## 🇹🇷 Türkçe

### 📌 Proje Hakkında
Equaliter, MediaPipe kullanarak kameradan el hareketlerini algılayan ve parmaklar arasındaki mesafeye göre MP3 dosyalarının hız, frekans(şu an aktif değil) ve ses yüksekliğini gerçek zamanlı olarak değiştiren bir Windows uygulamasıdır. Kullanıcılar el hareketleriyle müziği kontrol ederek interaktif ve yenilikçi bir deneyim yaşar.

### ✨ Özellikler
- 🤚 Gerçek zamanlı el takibi (MediaPipe)
- 🎵 MP3 dosyalarının ses yüksekliği, hız ve frekansını (şu an aktif değili) el hareketleriyle kontrol
- 🖥️ Basit ve kullanıcı dostu arayüz
- 🐍 Python ve Pygame tabanlı uygulama

### 📋 Gereksinimler
- Python 3.8 veya üzeri
- Gerekli Python kütüphaneleri (`requirements.txt` dosyasında)
  - mediapipe
  - opencv-python
  - pygame
  - keyboard
  - numpy

### 🚀 Kurulum
1. Depoyu klonlayın veya indirin:
    ```bash
    git clone https://github.com/sedatoneer/equaliter.git
    cd equaliter
    ```

2. Sanal ortam oluşturun ve aktif edin (önerilir):
    ```bash
    python -m venv venv
    # Windows için:
    venv\Scripts\activate
    # Mac/Linux için:
    source venv/bin/activate
    ```

3. Gerekli kütüphaneleri yükleyin:
    ```bash
    pip install -r requirements.txt
    ```

### ▶️ Kullanım
```bash
python main.py
```
Uygulama açıldığında, kameranızı kullanarak el hareketlerinizi algılayacak ve müzik ses yüksekliği/hız kontrolü yapabileceksiniz.


## 🇬🇧 English
---

### 📌 About Project
Equaliter is a Windows application that uses MediaPipe to track hand movements from the camera and changes the speed, frequency(not currently active), and pitch of MP3 files in real-time based on the distance between fingers. Users can control music interactively with hand gestures.

### ✨ Features
- 🤚 Real-time hand tracking (MediaPipe)
- 🎵 Control the volume, speed and frequency(not currently active) of MP3 files with gestures.
- 🖥️ Simple and user-friendly interface
- 🐍 Python and Pygame based application

### 📋 Requirements
- Python 3.8 or higher
- Required Python libraries (`requirements.txt`):
  - mediapipe
  - opencv-python
  - pygame
  - keyboard
  - numpy

### 🚀 Installation
1. Clone or download the repository:
    ```bash
    git clone https://github.com/sedatoneer/equaliter.git
    cd equaliter
    ```

2. Create and activate a virtual environment (recommended):
    ```bash
    python -m venv venv
    # On Windows:
    venv\Scripts\activate
    # On Mac/Linux:
    source venv/bin/activate
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### ▶️ Usage
```bash
python main.py
```
The application will open and use your camera to detect hand gestures and control music volume/speed.
