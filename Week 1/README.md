# Pengenalan API dan Tools
Disini akan digunakan beberapa tools

# git scm
Download git-scm dari https://git-scm.com/downloads

## Get SSH Key 
to get ssh key in your computer, and put in your github or gitlab ssh key setting.

```sh
cat ~/.ssh/id_rsa.pub
```
if there is no key appears, plese generate the key also set global config of git in next section and please add the public key to your github profile.

## Generate RSA Key
Just One time for first instalation of git scm.
```sh
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

## Set config global
Just One time for first instalation of git scm.

```sh
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```



## Tugas

1. Buat presentasi mengenai Web Service (Pengertian, cara kerja, fungsi, contoh) & JSON (Pengertian, fungsi, jenis nilai / value beserta contohnya), 

2. Dibuat dalam format ppt kemudian yang dikumpulkan pada repository ini adalah file pdf.

3. Buat folder dengan format Kelompok_NPM (contoh : Kelompok1_1204001_1204002_1204003) di dalam folder Week 1 --> folder Site,

4. Pull Request Dengan Subjek : 1-KELAS-KELOMPOK.
