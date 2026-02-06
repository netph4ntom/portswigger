## Authentication
### LAB: Username enumeration via different responses
> Lab yang mempunyai kerentanan dengan username dan password yang mudah ditebak. Disini kita disediakan wordlist username dan password yang akan digunakan untuk burtforce login page.

1. Intercept Request Login
   ![alt text](src/IMG/image.png)
2. Send to Intruder
   ![alt text](src/IMG/image-1.png)
3. Set parameter bruteforce pada username
   ![alt text](src/IMG/image-2.png)
4. Paste Wordlist username pada payload configuration, lalu start attack
   ![alt text](src/IMG/image-3.png)
5. Cari respont yang menunjukan incorrect password, karena kita sedang brute force username berarti telah berhasil dengan username itu
   ![alt text](src/IMG/image-4.png)
6. Lakukan hal yang sama pada password tapi dengan usename yang sudah terisi dengan yang valid.
   ![alt text](src/IMG/image-5.png)
