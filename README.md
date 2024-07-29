# 🚩 Project Name: Transportation Security Agent

🙋🏻‍♂️ Project Owner: Ahmad Dani Rifai  
🏁 Date Finished: April 2023  
📞 Contact: [LinkedIn](https://www.linkedin.com/in/ahmad-dhani-0b8b6a22b/); [E-mail](adhani866@gmail.com)

# **Business Problem Understanding**

**Pemecahan Masalah**

Saya akan menyelesaikan masalah menggunakkan SMART framework:

- Specific: Mengetahui perkembangan jumlah klaim penumpang pada rentang tahun 2002-2015
- Measurable: Memperbaiki pelayanan bandara yang memiliki jumlah klaim paling tinggi
- Achievable: Menurunkan angka klaim dan laporan keamanan bandara
- Relevant: Meningkatkan keamanan bandara dan mengurangi jumlah klaim yang diajukan oleh penumpang
- Time-bound: Dalam 1 tahun kedepan

**Latar Belakang**

**TSA** (Transportation Security Agent) merupakan sebuah badan pemerintah Amerika Serikat yang memiliki fokus utama dalam kemanan bandara. TSA bertanggung jawab untuk pemeriksaan penumpang dan bagasi di lebih dari 450 bandara Amerika Serikat. TSA mencatat klaim yang diajukan oleh para penumpang pesawat seperti kehilangan ataupun kerusakan barang. Data klaim yang diajukan kepada TSA tersebut dapat digunakan oleh TSA sebagai acuan untuk terus dapat meningkatkan kinerja keamanan di bandara.

**Dataset**

| **Feature**   | **Data Type** | **Description**                                                      |
| ------------- | ------------- | -------------------------------------------------------------------- |
| Claim Number  | Object        | Nomor unik dari setiap klaim yamg diajukan penumpang                 |
| Date Received | Datetime      | Tanggal diterimanya pengajuan klaim dari penumpang oleh TSA          |
| Incident Date | Datetime      | Tanggal kejadian atau kasus yang dialami oleh penumpang              |
| Airport Code  | Object        | Kode bandara                                                         |
| Airport Name  | Object        | Nama Bandara                                                         |
| Airline Name  | Object        | Nama maskapai penerbangan                                            |
| Claim Type    | Float         | Jenis klaim yang diajukan penumpang                                  |
| Claim Site    | Float         | Tempat/lokasi pengajuan klaim                                        |
| Item          | Float         | Jenis dari item dalam klaim yang diajukan penumpang                  |
| Claim Amount  | Float         | Harga dari klaim (ganti rugi) yang diajukan penumpang (dalam dollar) |
| Status        | Float         | Status dari klaim yang diajukan penumpang                            |
| Close Amount  | Float         | Harga klaim yang dibayarkan oleh TSA (dalam dollar)                  |
| Disposition   | Float         | Disposisi terhadap klaim yang telah diajukan penumpang               |

### **Data Source**

- [Klik disini (Kaggle)](https://www.kaggle.com/datasets/terminal-security-agency/tsa-claims-database)

### **Data Visualitation**

- [Klik disini (Tableau)](https://public.tableau.com/app/profile/ahmad.dani.rifai/viz/TSAClaim_17175983116520/TSA)
