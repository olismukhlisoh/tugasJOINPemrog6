# tugasJOINPemrog6
SELECT kn.nama_kendaraan, pl.nama_type, pn.nama_jenis, mn.nama_mesin
FROM type pl 
LEFT OUTER JOIN kendaraan kn on pl.kendaraan_id = kn.id_kendaraan
JOIN jenis pn ON pl.jenis_id = pn.id_jenis
JOIN mesin mn ON pl.mesin_di = mn.id_mesin;
