## Buatlah Algoritma untuk menyelesaikan problem ini

1. Amanda ingin memiliki aplikasi yang dapat menghitung harga tiket pesawat yang harus dibayar oleh Traveler.

2. Data yang akan diinput adalah:

   * Jumlah Traveler

   * Harga Tiket Pesawat

3. Cek apakah membeli tiket one way or two way

4. Misalnya jumlah traveler 2 orang. Per tiketnya seharga Rp 600.000.

5. Maka program akan memberikan nilai berupa harga yang harus dibayar sebesar Rp 1.200.000

## Jawab

        STORE "Jumlah Traveler" with any value

        STORE "Harga Tiket Pesawat" with any value

        STORE "Harga yang harus di bayar" without
        any value

        CALCULATE "Jumlah Traveler" times "Harga Tiket Pesawat"

        SET "Harga yang harus di bayar" value with calculation result

        DISPLAY "Harga yang harus dibayar"