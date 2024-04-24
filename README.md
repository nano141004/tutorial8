## Reflection

- what is amqp?
    AMQP adalah singkatan dari Advanced Message Queuing Protocol, sebuah protokol komunikasi yang memungkinkan pertukaran pesan antara aplikasi secara efisien. AMQP sering diterapkan dalam software architecture berbasis microservice.
- what it means? guest:guest@localhost:5672 , what is the first quest, and what is the second guest, and what is localhost:5672 is for?
    "guest:guest@localhost:5672" adalah format yang digunakan untuk menyatakan kredensial akses ke server AMQP. 
    "guest" pertama adalah username
    "guest" kedua adalah password
    "localhost:5672" adalah alamat server dan nomor port untuk server AMQP
- [ss1](images/ss1.png)
queue messages mencapai 60an karena dilakukan cargo run pada publisher berkali - kali secara cepat, sehingga subscriber tidak bisa memproses keseluruhan request dalam satu waktu, maka request harus menunggu untuk diproses atau harus masuk queue dulu.
