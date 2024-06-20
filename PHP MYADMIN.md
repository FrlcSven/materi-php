
# Struktur Pegawai
![strukturpegawai.png]

# Data Pegawai
![pegawai.png](ASET%20PHPMYADMIN/pegawai.png)
## Before
![](ASET%20PHPMYADMIN/before.png)
## After
![strukturpegawai.png](ASET%20PHPMYADMIN/strukturpegawai.png)
# Cabang
## Before 

![cabang.png](ASET%20PHPMYADMIN/cabang.png)

## After
![cabang2.png](ASET%20PHPMYADMIN/cabang2.png)

# Relasi 

![RELASII.png](ASET%20PHPMYADMIN/RELASI.png)

![nilai.png](ASET%20PHPMYADMIN/nilai.png)

```mysql
SELECT m.nama AS Nama_Murid, n.nilai AS Nilai FROM nilai AS n INNER JOIN murid AS m ON m.nis = n.id_siswa WHERE n.nilai > 75;
```