|                                  Command                                 |                                                                                                 Explanation                                                                                                 |
|:------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|                                 - hardisk                                |                                                                                           perintah tentang hardisk                                                                                          |
|                                   df -a                                  |                                                                             perintah melihat filesystem hardisk yang di gunakan                                                                             |
|                                   df -h                                  |                                                                                  perintah melihat semua filesystem hardisk                                                                                  |
|                                   df -k                                  |                                                                            perintah melihat filesystem hardisk berdasarkan bytes                                                                            |
|                                   df -m                                  |                                                                          perintah melihat filesystem hardisk berdasarkan megabytes                                                                          |
|                             - kompresi file                              |                                       perintah kompresi file di linux 1. c – untuk membuat file .tar bar 2. v – untuk deskripsi file proses kompresi 3. f – nama file                                       |
|   - tar -cvjf   data.tar.bz2 /home/belajarlinux  tar -xvf data.tar.bz2   |                   membuat file kompresi linux dengan ekstensi tar.bz2 /home/belajar/linux adalah mengarahkan file kompresi ke direktori belajar/linux  untuk extract file kompresi tar.bz2                  |
| - tar.gz  tar -cvzf data.tar.gz /home/belajarlinux  tar -xvf data.tar.gz |                    membuat file kompresi linux dengan ekstensi tar.gz /home/belajar/linux adalah mengarahkan file kompresi ke direktori belajar/linux  untuk extract file kompresi tar.gz                   |
|                             - kompresi linux                             |                                             membuat file kompresi linux c – untuk membuat file .tar v – menunjukkan deskripsi dari proses kompresi f – nama file                                            |
|                 tar -cvzf data.tar.gz /home/belajarlinux                 |                                                                    membuat kompresi file tar.gz dan mengarahkan ke direktori belajarlinux                                                                   |
|                 tar -cvjf data.tar.bz2 /home/belajarlinux                |                                                                   membuat kompresi file tar.bz2 dan mengarahkan ke direktori belajarlinux                                                                   |
|                   tar -cvf data.tar /home/belajarlinux                   |                                                                     membuat kompresi file tar dan mengarahkan ke direktori belajarlinux                                                                     |
|                   zip -r arsipku.zip /home/belajarlinux                  |                                                                     membuat kompresi file zip dan mengarahkan ke direktori belajarlinux                                                                     |
|                             tar -xvf data.tar                            |                                                                                      untuk extract file tar, tar.gz bz2                                                                                     |
|                            unzip arsipku.zip                             |                                                                                            untuk extract file zip                                                                                           |
|                         - hak akses izin di linux                        |                                                                  hak akses di linux terbagi 3 kategori  1.user 2.group 3.other/orang lain                                                                   |
|                       sudo chmod 744 belajar linux                       |       membuat hakses di folder linux dimana angka 744 7 angka = bisa membaca dan menulis dan eksekusi khusus owner 4 angka = bisa membaca khusus group 4 angka = bisa membaca khusus other/orang lain       |
|                        sudo chmod 764 belajarlinux                       | membuat hakses di folder linux dimana angka 764 7 angka = bisa membaca dan menulis dan eksekusi khusus owner 6 angka = bisa membaca dan menulis khusus group 4 angka = bisa membaca khusus other/orang lain |
|                        sudo chmod 700 belajarlinux                       |                   membuat hakses di folder linux dimana angka 700 7 angka = bisa membaca dan menulis dan eksekusi khusus owner 0 angka = tidak ngapa ngapain 0 angka = tidak ngapa ngapain                  |
|                                 add user                                 |                                                                               menambahkan user di linux ada 2  adduser useradd                                                                              |
|                        sudo adduser rickybrainware                       |                                                                                       menambahkan user dengan adduser                                                                                       |
|                           sudo useradd rickycoy                          |                                                                                       menambahkan user dengan useradd                                                                                       |
|                                add group                                 |                                                                                          menambahkan group di linux                                                                                         |
|                            sudo addgroup ricky                           |                                                                                            membuat group di linux                                                                                           |
|                                mkdir ricky                               |                                                                                    membuat folder linux dengan nama ricky                                                                                   |
|                                 cd /ricky                                |                                                                                            pindah folder ke ricky                                                                                           |
|                                   cd ..                                  |                                                                                    pindah direktori dengan relative path                                                                                    |
|                                   ls -R                                  |                                                                                      melihat isi file serta sub folder                                                                                      |
|                                    ls                                    |                                                                                            melihat isi direktori                                                                                            |
|                                   cat                                    |                                                                                               melihat isi file                                                                                              |
|                                    ps                                    |                                                                                       melihat proses aplikasi berjalan                                                                                      |
|                                    top                                   |                                                                              melihat proses kinerja sistem seperti cpu, memory                                                                              |
|                    pkill firefox atau killall firefox                    |                                                                                          mematikan aplikasi firefox                                                                                         |
|                             grep l server.php                            |                                                                                          mencari file dengan kata l                                                                                         |
|                                rm data.txt                               |                                                                                  menghapus file linux dengan nama data.txt                                                                                  |
|                            rmdir belajarlinux                            |                                                                               menghapus folder linux dengan nama belajar linux                                                                              |
|                 cp fileku.txt /home/ricky/Documents/data2                |                                                                                    mengcopy fileku.txt ke direktori data2                                                                                   |
|                        mv fileku.txt filesaya.txt                        |                                                                              menganti nama file fileku.txt menjadi filesaya.txt                                                                             |
|                             mv data2 datake2                             |                                                                                  menganti nama folder data2 menjadi datake2                                                                                 |


# Remote Server

|           - remote server           |   untuk meremote server mengunakan telnet dan ssh   |
|:-----------------------------------:|:---------------------------------------------------:|
|          telnet ip address          |                 telnet 192.168.10.2                 |
| SSH username@ip-address or hostname | ssh admin@192.168.10.2 ssh admin@rickybrainware.com |

# Hak akses linux

| no | permissions           | symbol |
|----|-----------------------|--------|
| 0  | no permissions        | ---    |
| 1  | Execute               | --x    |
| 2  | Write                 | -w-    |
| 3  | Execute + Write       | -wx    |
| 4  | Read                  | r--    |
| 5  | Read + Execute        | r-x    |
| 6  | Read + Write          | rw-    |
| 7  | Read + Write +Execute | rwx    |

# banner
membuat banner di linux 
install package sudo apt install sysvbanner

banner abc
```
 ##    #####    ####
  #  #   #    #  #    #
 #    #  #####   #
 ######  #    #  #
 #    #  #    #  #    #
 #    #  #####    ####
```
