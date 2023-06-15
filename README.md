# Customer_Hotel_Predict

# Capstone_Project_Modul_3

Project untuk pemenuhan tugas Capstone Project Module 3 Purwadhika by Abdurrahman Muttaqin

Pada project ini, saya memprediksi data hotel_booking_demand. Data terdiri dari 11 kolom, yaitu:

- country: Country of origin.
- market_segment: Market segment designation. 
- previous_cancellations: Number of previous bookings that were cancelled by the customer prior to the current booking.
- booking_changes: Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation.
- deposit_type: Indication on if the customer made a deposit to guarantee the booking. 
- days_in_waiting_list: Number of days the booking was in the waiting list before it was confirmed to the customer.
- customer_type: Type of booking.
- reserved_room_type: Code of room type reserved. Code is presented instead of designation for anonymity reasons.
- required_car_parking_space: Number of car parking spaces required by the customer.
- total_of_special_request: Number of special requests made by the customer (e.g. twin bed or high floor).
- is_canceled: Value indicating if the booking was canceled (1) or not (0).

## Latar Belakang Permasalahan
Industri pariwisata adalah salah satu sektor pendatapan terbesar suatu Negara, tak jarang pada suatu Kota pendapatan masyarakatnya hanya mengandalkan dari sektor pariwisata. Salah satu bidangnya adalah perhotelan. Namun hotel sering mengalami kerugian pendapatan karena pelanggan tiba-tiba membatalkan pemesanan kamar mereka sehingga kamar mereka menjadi kosong. Sebagai Data Scientist yang baru direkrut oleh sebuah hotel bintang 5, kita akan memprediksi kecendrungan pelanggan apakah akan menginap pada hotel kita atau tidak menginap melalui fitur-fitur yang sudah tersedia. Prediksi ini akan membantu divisi marketing dan divisi manajerial hotel untuk lebih bisa meningkatkan pendapatan dan menjaga nama baik hotel tersebut.

## Pernyataan Masalah
Proses pembatalan bisa merugikan hotel, karena kamar tidak jadi terjual. Proses pembatalan yang paling merugikan adalah dengan cara No-Show.

Ketika hotel mendapatkan customer yang melakukan pembatalan pada menit akhir, hotel tidak bisa melakukan apapun kecuali menjual kamar dengan harga yang jauh lebih rendah, dikarenakan hotel sudah mengeluarkan biaya untuk melakukan penyiapan kamar. Jadi saat hotel menjual kamar dengan harga yang jauh lebih rendah peluang untuk mendapatkan revenue yang maksimal sangatlah minim.

## Goals
Maka berdasarkan permasalahan tersebut, hotel ingin memiliki kemampuan untuk memprediksi kemungkinan apakah seorang customer akan melakukan pembatalan pesanan atau tidak.

Prediksi tersebut dapat membantu hotel untuk mendapatkan revenue maksimal dan dapat menjaga reputasi baik hotel. Selain itu dengan kita tahu customer mana yang akan melakukan pembatalan pesanan atau tidak, kita dapat melakukan penawaran eksklusif kepada potential customer untuk mendapatkan pendapatan tambahan.
