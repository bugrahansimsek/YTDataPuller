# **YTDataPuller 🎥📊**

Bu proje, **YouTube kanalındaki videoların verilerini çekmek ve CSV dosyasına aktarmak için geliştirilen bir masaüstü uygulamasıdır**. Arka planda **Python** ile YouTube Data API kullanılırken, uygulamanın arayüzü **C++ ve Qt Framework** ile geliştirilmiştir.

---

## 📌 **Proje Özellikleri**

- ✅ Kullanıcıdan YouTube API anahtarı ve kanal URL’si alır.
- ✅ YouTube Data API ile:
  - Kanal ID'si
  - Uploads playlist ID'si
  - Kanal videolarının tüm verileri otomatik olarak çekilir.
- ✅ Python scriptleri C++ Qt arayüzüyle tetiklenir.
- ✅ Tüm veriler CSV formatında dışa aktarılır.
- ✅ Progress bar ile işlem ilerlemesi izlenebilir.

---

## 📊 **Çekilen YouTube Video Verileri**

| Alan Adı        | Açıklama                                                                 |
|-----------------|--------------------------------------------------------------------------|
| `Video_ID`      | Videonun benzersiz kimliği (ID)                                          |
| `Title`         | Videonun başlığı                                                         |
| `Published_At`  | Yayınlanma tarihi (`Gün/Ay/Yıl - Saat` formatında)                       |
| `Views`         | İzlenme sayısı                                                           |
| `Likes`         | Beğeni sayısı                                                            |
| `Comments`      | Yorum sayısı                                                             |
| `Duration`      | Video süresi (saniye cinsinden)                                          |
| `Video_Type`    | Video türü: `SHORTS` (≤60 saniye) veya `VİDEO` (>60 saniye)              |
| `Category`      | Videonun ait olduğu kategori (örnek: Education, Gaming, vs.)             |
| `Video_URL`     | Doğrudan video bağlantısı                                                |

---

## 🛠 **Kullanılan Teknolojiler**

- **C++ (OOP)** – Ana arayüz, kullanıcı girişi ve API çağrıları tetikleme
- **Qt Framework** – GUI oluşturmak için (Qt Widgets, QProcess, ProgressBar vs.)
- **Python** – YouTube API ile veri çekme
- **YouTube Data API v3** – Video ve kanal verilerine erişim
- **QProcess** – Qt ile Python scriptlerini çalıştırmak için
- **CSV** – Verilerin dışa aktarım formatı

---

## 🔍 **Gelecek Geliştirmeler**

📌 Excel (.xlsx) dışa aktarım desteği  
📌 YouTube kanal görseli ve adı bilgilerini çekme  
📌 Grafiksel özet ve analiz ekranı ekleme (views/likes trendleri gibi)

---

## 📃 **Lisans**

Bu proje **MIT Lisansı** ile lisanslanmıştır. Açık kaynak olarak kullanılabilir. Ticari projelerde kullanırken referans verilmesi rica edilir.

---

## 🖼 **Uygulama Görseli (GIF)**

![YTDataPuller](https://github.com/bugrahansimsek/YTDataPuller/blob/main/YTDataPuller.gif)

---

# **YTDataPuller 🎥📊**

**YTDataPuller** is a **desktop application designed to retrieve and export video data from any YouTube channel into a CSV file**. The backend uses **Python and YouTube Data API**, while the user interface is built using **C++ and the Qt Framework**.

---

## 📌 **Project Features**

- ✅ Takes YouTube API key and channel URL as input
- ✅ Automatically retrieves:
  - Channel ID
  - Uploads playlist ID
  - All video data from the channel
- ✅ Executes Python scripts via the Qt C++ GUI
- ✅ Exports all data into a `.csv` file
- ✅ Includes progress bar for real-time tracking

---

## 📊 **Extracted YouTube Video Data**

| Field Name      | Description                                                              |
|----------------|--------------------------------------------------------------------------|
| `Video_ID`      | Unique ID of the video                                                  |
| `Title`         | Title of the video                                                      |
| `Published_At`  | Published date (`DD/MM/YYYY - HH:MM` format)                            |
| `Views`         | View count                                                              |
| `Likes`         | Like count                                                              |
| `Comments`      | Comment count                                                           |
| `Duration`      | Duration of the video (in seconds)                                      |
| `Video_Type`    | `SHORTS` (≤60 sec) or `VIDEO` (>60 sec)                                 |
| `Category`      | Video category (e.g., Gaming, Education, etc.)                          |
| `Video_URL`     | Direct video link                                                       |

---

## 🛠 **Technologies Used**

- **C++ (OOP)** – Core UI and logic
- **Qt Framework** – GUI (Qt Widgets, QProcess, ProgressBar)
- **Python** – Backend data extraction
- **YouTube Data API v3** – Access to YouTube video and channel metadata
- **QProcess** – To run Python scripts from Qt
- **CSV** – Output format

---

## 🔍 **Future Improvements**

📌 Excel (.xlsx) export support  
📌 Channel image and metadata fetching  
📌 Visual analytics & summary view (e.g., likes/views over time)

---

## 📃 **License**

This project is licensed under the **MIT License**. Free to use, attribution recommended for commercial usage.
