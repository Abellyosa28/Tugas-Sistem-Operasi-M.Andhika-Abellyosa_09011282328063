1.) Buatlah laporan proses instalasi di komputer mahasiswa dan tampilkan screenshotannya!	

= Cara menginstall Linux, untuk foto langkah-langkah nya ada di https://github.com/Abellyosa28/Tugas-Sistem-Operasi-M.Andhika-Abellyosa_09011282328063/blob/main/M.Andhika_Abellyosa_09011282328063_Cara%20menginstall%20linux.docx
1. Download Linux Mint dan Oracle Virtual Box terlebih dahulu pada website :
https://linuxmint.com/ 
https://www.virtualbox.org/wiki/Downloads

2. Buka Oracle Virtual Box, dan pilih menu new

3. Beri nama, kemudian isi ISO image dengan file ISO yang telah kita download, lalu klik “Skip unatted instalation” kemudian pilih next

4. Setting Base memory dan Processor sesuai kebutuhan (disarankan mengikuti saran yang disesuaikan agar lancar)

5. Setting storage disk minimal 20GB

6. Cek kembali pilihan kalian, jika selesai maka pilih finish dan pilih start untuk menjalankan

7. Pilih menu Linux Mint, lalu tunggu proses boot selesai

8. Setelah boot selesai, pilih menu install linux

9. Pilih bahasa yang diinginkan

10. Centang “Install Multimedia codecs” untuk memutar video dan merender website

11. Pilih Erase disk dan install linux untuk menimpa OS dengan linux

12. Pilih tempat tinggal dan isi data yang diperlukan, lalu klik continue

13. Tunggu proses instalasi hingga selesai

14. Ketika instalasi selesai pilih menu “Restart now” dan tunggu hingga proses restart selesai

15. Setelah selesai maka akan muncul menu seperti ini, klik menu “Let’s go!” untuk menjalankan dan OS Linux siap untuk dipakai
__________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

2.) Analisislah kenapa saat instalasi perlu dipilih “/” pada opsi Mount Point ?

= Simbol "/" digunakan untuk menandai direktori root dari suatu partisi, yang merupakan partisi paling utama dalam sistem operasi Linux. 
Dalam hal ini, partisi root berfungsi mirip dengan drive C: pada Windows, terutama terkait dengan pengaturan titik mount. Simbol "/" ini akan secara langsung membawa Anda ke pilihan seperti "Use As Ext4" serta berbagai pengaturan terkait lainnya.
__________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

3.) Berikan penjelasan tentang ext4, ext3, swap, ntfs, fat32, btrfs, Ext4 (4th Extended Filesystem) ?
=
1. Ext4 (4th Extended Filesystem) adalah evolusi dari Ext3, yang dirancang untuk mengatasi keterbatasan dari pendahulunya dan untuk mendukung penggunaan penyimpanan yang lebih besar serta performa yang lebih baik. Ext4 mendukung pengalamatan 48-bit, memungkinkan ukuran filesystem mencapai hingga 1 exabyte (1EB) dan ukuran file maksimum sebesar 16 terabyte (TB). Beberapa fitur unggulannya termasuk delayed allocation yang meningkatkan efisiensi penulisan data, fast fsck yang mempercepat pengecekan integritas filesystem, journal checksumming yang menambah keamanan data, serta dukungan defragmentasi untuk menjaga performa tetap optimal.

2. Ext3 (3rd Extended Filesystem) adalah sistem berkas yang banyak digunakan pada distribusi Linux sebelum Ext4 hadir. Dibandingkan dengan Ext2, Ext3 menambahkan fitur journaling, yang secara signifikan meningkatkan keandalan dan kecepatan pemulihan setelah terjadinya kegagalan sistem. Journaling memastikan bahwa sistem dapat kembali ke kondisi yang konsisten tanpa perlu melakukan pengecekan integritas penuh (fsck) yang memakan waktu lama. Ext3 juga mendukung ukuran filesystem hingga 32 terabyte dan ukuran file maksimum hingga 2 terabyte. Meskipun stabil dan handal, performa Ext3 mulai dianggap kurang memadai untuk kebutuhan modern, sehingga banyak pengguna yang kemudian beralih ke Ext4.

3. Swap adalah ruang pada hard drive yang digunakan oleh sistem operasi untuk memperluas memori fisik (RAM). Ketika RAM hampir penuh, sistem operasi akan memindahkan sebagian data dari RAM ke partisi swap atau file swap di hard drive, sehingga memori utama dapat digunakan untuk tugas-tugas yang lebih mendesak. Swap memungkinkan sistem untuk menangani lebih banyak proses daripada kapasitas RAM yang tersedia, namun dengan kecepatan yang lebih lambat karena akses ke hard drive jauh lebih lambat dibandingkan dengan RAM. Penggunaan swap sangat penting pada sistem dengan RAM terbatas atau saat menjalankan aplikasi yang membutuhkan banyak memori, seperti aplikasi pengolahan data yang besar atau virtualisasi.

4. NTFS (New Technology File System) pertama kali diperkenalkan pada Windows NT dan merupakan file system yang benar-benar berbeda dibandingkan dengan teknologi FAT. NTFS menawarkan tingkat keamanan yang lebih tinggi, kemampuan kompresi file, pengelolaan cluster, dan bahkan dukungan untuk enkripsi data. NTFS menjadi standar file system untuk Windows XP, dan saat Anda melakukan upgrade dari versi Windows sebelumnya, Anda akan diberikan pilihan untuk beralih ke NTFS atau tetap menggunakan FAT. Jika Anda sudah meng-upgrade ke Windows XP dan belum beralih ke NTFS, tidak perlu khawatir karena Anda bisa mengonversinya ke NTFS kapan saja.

5. Fat32 adalah sistem berkas yang diperkenalkan oleh Microsoft dan digunakan secara luas karena kompatibilitasnya dengan banyak sistem operasi dan perangkat, seperti Windows, macOS, Linux, serta perangkat elektronik seperti kamera dan konsol game. FAT32 mendukung partisi hingga 2 terabyte dan file hingga 4 gigabyte. Meskipun mudah digunakan dan sangat kompatibel, FAT32 memiliki batasan pada ukuran file dan tidak mendukung fitur keamanan atau journaling, membuatnya kurang ideal untuk penyimpanan yang membutuhkan perlindungan data yang lebih baik. FAT32 biasanya digunakan untuk media penyimpanan portabel, seperti flash drive atau kartu SD.

6. B-Tree File System (BTRFS) yang kadang disebut juga sebagai BuTteR FS atau BeTteR FS, adalah sebuah file system yang dikembangkan di bawah lisensi General Public License (GPL). Chris Mason, Direktur Linux Kernel Engineering di Oracle, adalah tokoh utama di balik pengembangan BTRFS. Salah satu fitur unggulan BTRFS adalah kemampuannya untuk memelihara checksum dari semua file data dan metadata.

