Dataset: Hybrid Workspace Preferences

Deskripsi
Dataset ini berisi informasi preferensi karyawan terhadap coworking spaces berdasarkan fitur, fasilitas, dan lokasi. Dataset ini cocok untuk mendukung pengembangan sistem rekomendasi berbasis konten (content-based), kolaboratif (collaborative), maupun gabungan (hybrid), dengan menggunakan data preferensi pengguna terhadap atribut spesifik dari coworking spaces.

Kolom Dataset
1. employee_id: ID unik untuk setiap karyawan yang menunjukkan pengguna atau reviewer yang memberi rating pada coworking space tertentu.
2. coworking_space_id: ID unik untuk setiap coworking space yang diulas atau diberi rating oleh karyawan.
3. rating: Rating atau penilaian yang diberikan oleh karyawan terhadap coworking space tersebut, dalam bentuk numerik (biasanya skala 1-5).
4. Feature: Fitur utama yang tersedia di coworking space, seperti "Conference Rooms" atau "Virtual Office".
5. Amenity: Fasilitas tambahan yang disediakan oleh coworking space, misalnya "24/7 Access", "Printing Services", atau "Event Spaces".
6. Location: Lokasi coworking space, yang menunjukkan area atau tipe lingkungan (misalnya, "Suburb" atau "Business District").

Tujuan Dataset
Dataset ini dirancang untuk mengembangkan sistem rekomendasi yang bertujuan:
- Mengidentifikasi coworking spaces yang paling sesuai dengan preferensi individual karyawan berdasarkan fitur, fasilitas, dan lokasi.
- Memberikan rekomendasi coworking space yang relevan untuk setiap karyawan berdasarkan pola rating yang ada.
- Memungkinkan eksperimen dengan pendekatan filtering berbasis konten, kolaboratif, atau kombinasi keduanya.

Format File
Format: CSV, Jumlah Entitas: 307 entri

Penggunaan
Dataset ini dapat digunakan untuk membangun, menguji, dan memvalidasi berbagai model rekomendasi, baik yang berbasis konten, kolaboratif, maupun hibrid. Dataset ini juga berguna untuk analisis preferensi mengenai fitur dan fasilitas coworking spaces yang disukai karyawan.
