# ETL-with-Airflow-part-3
op_mysql dan op_postgresql adalah operator Airflow yang digunakan untuk berinteraksi dengan database MySQL dan PostgreSQL, masing-masing. Operator ini memungkinkan Anda untuk menjalankan perintah SQL terhadap database dan mengambil hasil yang dapat digunakan dalam DAG.

Sebelum dijalankan:

op_mysql:
    * Menyambungkan ke database MySQL yang ditentukan.
    * Menyiapkan pernyataan SQL yang akan dijalankan.
 op_postgresql:
    * Menyambungkan ke database PostgreSQL yang ditentukan.
    * Menyiapkan pernyataan SQL yang akan dijalankan.

Sesudah dijalankan:

op_mysql:
    * Menjalankan pernyataan SQL terhadap database MySQL.
    * Mengambil hasil query (jika ada).
    * Menyimpan hasil query ke dalam variabel Airflow.
op_postgresql:
    * Menjalankan pernyataan SQL terhadap database PostgreSQL.
    * Mengambil hasil query (jika ada).
    * Menyimpan hasil query ke dalam variabel Airflow.

Perbedaan:

Perbedaan utama antara op_mysql dan op_postgresql adalah jenis database yang sedang dipakai.. 

op_mysql: Digunakan untuk database MySQL.
op_postgresql:Digunakan untuk database PostgreSQL.

Kedua operator memiliki sintaks dan fungsionalitas yang serupa, dengan beberapa perbedaan kecil dalam cara mereka menangani jenis data dan fitur database tertentu.
Perbaikan untuk op_mysql dan op_postgresql
