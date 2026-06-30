# Logical View

## Diagram Logical View

```text
                +-------------+
                | Pelanggan   |
                +-------------+
                      |
                      v
                +-----------+
                |   Login   |
                +-----------+
                      |
                      v
              +----------------+
              |   Dashboard    |
              +----------------+
        /-----------|------------\
       /            |             \
      v             v              v
Data Pelanggan  Booking Servis  Data Kendaraan
       |             |              |
       |             v              |
       |        Data Servis         |
       |             |              |
       \-------------|--------------/
                     |
                     v
            Stok Suku Cadang
                     |
                     v
          Transaksi Pembayaran
                     |
                     v
                 Database
```

## Penjelasan

Setelah login, admin dapat mengelola data pelanggan, data kendaraan, booking servis, pencatatan servis, stok suku cadang, serta transaksi pembayaran. Seluruh data disimpan pada database.
