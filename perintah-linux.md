+-------------------------------------------------------+---------------------------------------------------------------------------------+
|                        Command                        |                                   Explanation                                   |
+-------------------------------------------------------+---------------------------------------------------------------------------------+
|                       - hardisk                       |                             perintah tentang hardisk                            |
+-------------------------------------------------------+---------------------------------------------------------------------------------+
|                         df -a                         |               perintah melihat filesystem hardisk yang di gunakan               |
+-------------------------------------------------------+---------------------------------------------------------------------------------+
|                         df -h                         |                    perintah melihat semua filesystem hardisk                    |
+-------------------------------------------------------+---------------------------------------------------------------------------------+
|                         df -k                         |              perintah melihat filesystem hardisk berdasarkan bytes              |
+-------------------------------------------------------+---------------------------------------------------------------------------------+
|                         df -m                         |            perintah melihat filesystem hardisk berdasarkan megabytes            |
+-------------------------------------------------------+---------------------------------------------------------------------------------+
|                    - kompresi file                    |                         perintah kompresi file di linux                         |
|                                                       |                        1. c – untuk membuat file .tar bar                       |
|                                                       |                   2. v – untuk deskripsi file proses kompresi                   |
|                                                       |                                 3. f – nama file                                |
+-------------------------------------------------------+---------------------------------------------------------------------------------+
|                      - tar -cvjf                      |               membuat file kompresi linux dengan ekstensi tar.bz2               |
|                                                       | /home/belajar/linux adalah mengarahkan file kompresi ke direktori belajar/linux |
|            data.tar.bz2 /home/belajarlinux            |                                                                                 |
|                                                       |                       untuk extract file kompresi tar.bz2                       |
|                 tar -xvf data.tar.bz2                 |                                                                                 |
+-------------------------------------------------------+---------------------------------------------------------------------------------+
|                        - tar.gz                       |                membuat file kompresi linux dengan ekstensi tar.gz               |
|                                                       | /home/belajar/linux adalah mengarahkan file kompresi ke direktori belajar/linux |
|        tar -cvzf data.tar.gz /home/belajarlinux       |                                                                                 |
|                                                       |                        untuk extract file kompresi tar.gz                       |
|                  tar -xvf data.tar.gz                 |                                                                                 |
+-------------------------------------------------------+---------------------------------------------------------------------------------+
|                    - kompresi linux                   |                           membuat file kompresi linux                           |
|                                                       |                           c – untuk membuat file .tar                           |
|                                                       |                  v – menunjukkan deskripsi dari proses kompresi                 |
|                                                       |                                  f – nama file                                  |
+-------------------------------------------------------+---------------------------------------------------------------------------------+
| tar -cvzf data.tar.gz /home/belajarlinux              | membuat kompresi file tar.gz dan mengarahkan ke direktori belajarlinux          |
+-------------------------------------------------------+---------------------------------------------------------------------------------+
| tar -cvjf data.tar.bz2 /home/belajarlinux             | membuat kompresi file tar.bz2 dan mengarahkan ke direktori belajarlinux         |
+-------------------------------------------------------+---------------------------------------------------------------------------------+
| tar -cvf data.tar /home/belajarlinux                  | membuat kompresi file tar dan mengarahkan ke direktori belajarlinux             |
+-------------------------------------------------------+---------------------------------------------------------------------------------+
| zip -r arsipku.zip /home/belajarlinux                 | membuat kompresi file zip dan mengarahkan ke direktori belajarlinux             |
+-------------------------------------------------------+---------------------------------------------------------------------------------+
| tar -xvf data.tar                                     | untuk extract file tar, tar.gz bz2                                              |
+-------------------------------------------------------+---------------------------------------------------------------------------------+
| unzip arsipku.zip                                     | untuk extract file zip                                                          |
+-------------------------------------------------------+---------------------------------------------------------------------------------+
| - hak akses izin di linux                             | hak akses di linux terbagi 3 kategori                                           |
|                                                       |                                                                                 |
| Number   Permission Type       Symbol                 | 1.user 2.group 3.other/orang lain                                               |
| 0        No Permission                     ---        | angka 0 = tidak dapat akses mengubah kecuali owner/yang buat                    |
| 1        Execute                                --x   | angka 1 = bisa akses file                                                       |
| 2        Write                                    -w- | angka 2 = bisa menulis file                                                     |
| 3        Execute + Write                   -wx        | angka 3 = bisa eksekusi file dan menulis file                                   |
| 4        Read                                     r-- | angka 4 = bisa membaca file                                                     |
| 5        Read + Execute                    r-x        | angka 5 = bisa membaca file dan menulis                                         |
| 6        Read +Write                         rw-      | angka 6 = bisa membaca file dan menulis                                         |
| 7        Read + Write +Execute       rwx              | angka 7 = bisa membaca dan menulis dan eksekusi                                 |
+-------------------------------------------------------+---------------------------------------------------------------------------------+
|                                                       |                                                                                 |
+-------------------------------------------------------+---------------------------------------------------------------------------------+