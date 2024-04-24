# HadijaHumaira_2108107010084_TugasKpl
### Pada tugas ini Terdapat 2 test yaitu instrumental test dan local test

## 1. Instrumental Test
instrumental test yang ada pada file "InstrumentalTest" terdapat 3 test didalamnya yaitu
- Test 1: Test Case: testAddTask()
Mengujikan fungsi penambahan tugas baru. Metode ini memasukkan teks "Tugas Baru" ke dalam EditText, menekan tombol "Tambah", dan memeriksa apakah tugas tersebut telah ditampilkan di daftar.

- Test 2: Test Case: testEditTask()
Mengujikan fungsi pengeditan tugas. Metode ini menemukan tugas yang telah ditambahkan sebelumnya ("Tugas Edit & Hapus"), melakukan klik untuk membuka dialog edit, mengubah teks menjadi "Tugas Diedit", menekan tombol "Simpan", dan memeriksa apakah tugas tersebut berhasil diubah menjadi "Tugas Diedit".

- Test 3: Test Case: testAddButtonEnabled()
Mengujikan keadaan tombol "Tambah". Metode ini memastikan bahwa tombol "Tambah" dalam keadaan aktif sebelum dan setelah teks dimasukkan ke dalam EditText.

## 2. Local Test
Local test yang ada pada file "MainActivityUnitTest" terdapat 3 test didalamnya yaitu
- Test 1: Test Case: testAddTask()
Menguji fungsi penambahan tugas. Metode ini menambahkan satu tugas ke dalam daftar, kemudian memeriksa apakah ukuran daftar sesuai dengan yang diharapkan (1), dan memeriksa apakah tugas yang ditambahkan memiliki nama yang benar.

- Test 2: Test Case: testEditTask()
Menguji fungsi pengeditan tugas. Metode ini menambahkan satu tugas ke dalam daftar, kemudian memeriksa apakah tugas tersebut berhasil ditambahkan dan memiliki nama yang benar. Selanjutnya, metode ini mengubah nama tugas tersebut menjadi "Membeli Makanan" dan memeriksa apakah perubahan tersebut berhasil dilakukan.

- Test 3: Test Case: testDeleteTask()
Menguji fungsi penghapusan tugas. Metode ini menambahkan satu tugas ke dalam daftar, kemudian memeriksa apakah tugas tersebut berhasil ditambahkan. Selanjutnya, metode ini menghapus tugas tersebut dan memeriksa apakah tugas tersebut berhasil dihapus sehingga ukuran daftar menjadi 0.
