# php-iii-day-10-2023
📚 Show Data From Database

## Query Tambah Data 
    INSERT INTO `makanan` (`id_makanan`, `nama_makanan`, `harga_makanan`, `warung`, `alamat`) VALUES (NULL, 'Papeda', '500000', 'Rumah Makan Papua Food', 'Waena'), (NULL, 'Ulat Sagu Bakar', '100000', 'Rumah Makan Pace Papua', 'Sentani Dekat Danau');

## Query tampilkan semua data dari table
    SELECT * FROM `makanan`

## Query tampailkan satu data berdasarkan id
    SELECT * FROM `makanan` WHERE id_makanan = '1';
