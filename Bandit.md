### Documentation for OverTheWire Bandit


**Level 0**  

1. `ssh bandit0@bandit.labs.overthewire.org -p 2220`
1.  `ls`
2.  `cat readme`
3.  password for bandit1: boJ9jbbUNNfktd78OOpsqOltutMc3MY1

**Level 1**  

1.  `ssh bandit1@bandit.labs.overthewire.org -p 2220`  and enter password
2. `cat ./-`
3. password for bandit2: CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9

**Level 2**

1. `ssh bandit2@bandit.labs.overthewire.org -p 2220`  and enter password
2. `cat spaces in this filename`
3. `cat 'spaces in this filename'`
4. password for bandit3: UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK`

**Level 3**

1. `ssh bandit3@bandit.labs.overthewire.org -p 2220` and enter password
2. `cd inhere`
3.  `ls`
4.  `ls -la`
5.  `cat .hidden`
6. password for bandit4: pIwrPrtPN36QITSp3EQaw936yaFoFgAB

**Level 4**

1. `ssh bandit4@bandit.labs.overthewire.org -p 2220` and enter password
2. `cd inhere`
3. `cat -file07`
4. `strings ./-file00`
5. `strings ./-file01`
6. `strings ./-file02`
7. `strings ./-file03`
8. `strings ./-file04`
9. `strings ./-file05`
10. `strings ./-file06`
11. `strings ./-file07`
12. password for bandit5: koReBOKuIDDepwhWk7jZC0RTdopnAYKh

**Level 5**

1. `ssh bandit5@bandit.labs.overthewire.org -p 2220` and enter password
2. `ls`
3. `cd inhere`
4. `ls`
5. `man find`
6. `find -size 1033c -type f`
7. `cd maybehere07`
8. `ls`
9. `cat -file2`
10. `ls -la`
11. `cat .file2`
12. password for bandit6: DXjZPULLxYr17uwoI01bNLQbtFemEgo7

**Level 6**

1.  `ssh bandit6@bandit.labs.overthewire.org -p 2220` and enter password
2. `find / -user bandit7 -group bandit6 -size 33c`
3. `find / -user bandit7 -group bandit6 -size 33c | grep -F -v Permission`
4. `find / -user bandit7 -group bandit6 -size 33c | grep -F -v Permission | grep -F -v directory`
5. `find / -user bandit7 -group bandit6 -size 33c 2>&1 | grep -F -v Permission | grep -F -v directory`
6. `cat /var/lib/dpkg/info/bandit7.password`
7. password for bandit7: HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs

**Level 7**

1. `ssh bandit7@bandit.labs.overthewire.org -p 2220` and enter password
2. `ls`
3. `grep data.txt millionth`  
4.  `grep millionth data.txt`  
5. password for bandit8: cvX2JJa4CFALtqS87jk27qwqGhBM9plV

**Level 8**

1. `ssh bandit8@bandit.labs.overthewire.org -p 2220` and enter password
2. `ls`
3. `cat data.txt | sort | uniq -u'  
4.password for bandit9: UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

**Level 9**

1. `ssh bandit9@bandit.labs.overthewire.org -p 2220` and enter password
2. `ls`
3. `cat data.txt`
4. `strings data.txt`
5. password for bandit10: truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk

**Level 10**

1. `ssh bandit10@bandit.labs.overthewire.org -p 2220` and enter password
2. `ls`
3. `cat data.txt`
4. `echo 'VGhlIHBhc3N3b3JkIGlzIElGdWt3S0dzRlc4TU9xM0lSRnFyeEUxaHhUTkViVVBSCg=='  |base64 -d `
5. password for bandit11: IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR	

**Level 11**

1. `ssh bandit11@bandit.labs.overthewire.org -p 2220` and enter password
2. `cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'` 
3. password for bandit12: 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu

**Level 12**

1. `ssh bandit12@bandit.labs.overthewire.org -p 2220` and enter password
2. `cd /`  
3. `cd tmp`
4. `mkdir copiedfile`  
5. `cd copiedfile`  
6. `cp ~/data.txt .`
7. `mv data.txt moveddata`
8. `ls`
9. `xxd -r moveddata xxdmoveddata`
10. `file xxdmoveddata`
11. `gzip -h`
12. `gzip -d xxdmoveddata`
13. `mv xxdmoveddata xxdgzip.gz`
14. `gzip -d xxdgzip.gz`
15. `cat xxdgzip`
16. `file xxdgzip`
17. `mv xxdgzip xxdgzip.gz`
18. `gzip -d xxdgzip.gz`
19. `mv xxdgzip.gz xxdgzip`
20.  `cat xxdgzip`
21.  `file gzip`
22.  `file xxdgzip`
23.  `bzip2 -h`
24.  `gzip2 -d xxdgzip`
25.  `bzip2 -d xxdgzip`
26.  `mv xxdgzip xxdbzip.bz2`
27.  `cat xxdgzip.out`
28.  `mv xxdgzip.out xxdbzip.bz2`
29.  `bzip2 -d xxdbzip.bz2`
30.  `file xxdbzip.bz2`
31.  `cat xxdbzip.bz2`
32. `mv xxdbzip.bz2 xxdbzip.gzip`
33. `gzip -d xxdbzip.gzip`
34. `mv xxdbzip.gzip xxdbzip.gz`
35. `gzip -d xxdbzip.gz`
36. `file xxdbzip`
37. `tar --help`
38. `tar -t xxdbzip`
39. `tar -t -f xxdbzip`
40. `cat data5.bin`
41.  `file xxdbzip`
42. `mv xxdbzip xxdbzip.tar.gz`
43. `tar -xvf xxdbzip.tar.gz`
44. `cat data5.bin`
45.  `file data5.bin`
46. `tar -xvf data5.bin`
47. `file data6.bin`
48.  `bzip2 -d data6.bin`
49. `mv data6.bin.out data6.gz2`
50.  `mv data6.gz2 data6.bz2`
51. `bzip2 -d data6.bz2`
52. `mv data6.bz2 data6.bin`
53. `file data6.bin`
54. `mv data6.bin data6.tar`
55. `tar -xvf data6.tar`
56. `file data8.bin`
57. `mv data9.bin data9.gz`
58. `mv data8.bin data8.gz`
59. `gzip -d data8.gz`
60. `file data8`
61. `cat data8`
62. password for bandit13: 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL

**Bandit 13**

1.  `ssh bandit13@bandit.labs.overthewire.org -p 2220` and enter password
2. `ssh -i sshkey.private bandit14@bandit.labs.overthewire.org -p 2220`
3. `bandit13@bandit:~$ ssh -i sshkey.private bandit14@localhost`
4. `cat /etc/bandit_pass/bandit14`
5. password for bandit14: 4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e

**Bandit 14**

1. `ssh bandit14@bandit.labs.overthewire.org -p 2220` and enter password
2. `nc localhost 30000`
3. copy paste `4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e`
4. password for bandit15: BfMYroe26WYalil77FoDi9qh59eK5xNr

**Bandit 15**

1.  `ssh bandit15@bandit.labs.overthewire.org -p 2220` and enter password
2. `openssl localhost -p 30001`
3. `man openssl`
4. `10  openssl s_client -connect localhost:30001`
5. `enter password for bandit 15 BfMYroe26WYalil77FoDi9qh59eK5xNr`
6. password for bandit16: cluFn7wTiGryunymYOu4RcffSxQluehd

**Bandit 16**

1.  `ssh bandit16@bandit.labs.overthewire.org -p 2220` and enter password
2. `nmap localhost`
3. `nc lvnp 31046`
4.  `nmap -sV -p 31000-32000 localhost`
5.  `openssl s_client -connect localhost:31518`
6. `paste password for bandit 16 cluFn7wTiGryunymYOu4RcffSxQluehd`
7. `openssl s_client -connect localhost:31790`
8. `paste password for bandit 16 cluFn7wTiGryunymYOu4RcffSxQluehd`
9. copy the rsa key that was found 

-----BEGIN RSA PRIVATE KEY-----
MIIEogIBAAKCAQEAvmOkuifmMg6HL2YPIOjon6iWfbp7c3jx34YkYWqUH57SUdyJ
imZzeyGC0gtZPGujUSxiJSWI/oTqexh+cAMTSMlOJf7+BrJObArnxd9Y7YT2bRPQ
Ja6Lzb558YW3FZl87ORiO+rW4LCDCNd2lUvLE/GL2GWyuKN0K5iCd5TbtJzEkQTuDSt2mcNn4rhAL+JFr56o4T6z8WWAW18BR6yGrMq7Q/kALHYW3OekePQAzL0VUYbWJGTi65CxbCnzc/w4+mqQyvmzpWtMAzJTzAzQxNbkR2MBGySxDLrjg0LWN6sK7wNXx0YVztz/zbIkPjfkU1jHS+9EbVNj+D1XFOJuaQIDAQABAoIBABagpxpM1aoLWfvDKHcj10nqcoBc4oE11aFYQwik7xfW+24pRNuDE6SFthOar69jp5RlLwD1NhPx3iBlJ9nOM8OJ0VToum43UOS8YxF8WwhXriYGnc1sskbwpXOUDc9uX4+UESzH22P29ovdd8WErY0gPxun8pbJLmxkAtWNhpMvfe0050vk9TL5wqbu9AlbssgTcCXkMQnPw9nCYNN6DDP2lbcBrvgT9YCNL6C+ZKufD52yOQ9qOkwFTEQpjtF4uNtJom+asvlpmS8AvLY9r60wYSvmZhNqBUrj7lyCtXMIu1kkd4w7F77k+DjHoAXyxcUp1DGL51sOmama+TOWWgECgYEA8JtPxP0GRJ+IQkX262jM3dEIkza8ky5moIwUqYdsx0NxHgRRhORT8c8hAuRBb2G82so8vUHk/fur85OEfc9TncnCY2crpoqsghifKLxrLgtT+qDpfZnxSatLdt8GfQ85yA7hnWWJ2MxF3NaeSDm75Lsm+tBbAiyc9P2jGRNtMSkCgYEAypHdHCctNi/FwjulhttFx/rHYKhLidZDFYeiE/v45bN4yFm8x7R/b0iE7KaszX+ExdvtSghaTdcG0Knyw1bpJVyusavPzpaJMjdJ6tcFhVAbAjm7enCIvGCSx+X3l5SiWg0AR57hJglezIiVjv3aGwHwvlZvtszK6zV6oXFAu0ECgYAbjo46T4hyP5tJi93V5HDiTtiek7xRVxUl+iU7rWkGAXFpMLFteQEsRr7PJ/lemmEY5eTDAFMLy9FL2m9oQWCgR8VdwSk8r9FGLS+9aKcV5PI/WEKlwgXinB3OhYimtiG2Cg5JCqIZFHxD6MjEGOiuL8ktHMPvodBwNsSBULpG0QKBgBAplTfC1HOnWiMGOU3KPwYWt0O6CdTkmJOmL8Niblh9elyZ9FsGxsgtRBXRsqXuz7wtsQAgLHxbdLq/ZJQ7YfzOKU4ZxEnabvXnvWkUYOdjHdSOoKvDQNWu6ucyLRAWFuISeXw9a/9p7ftpxm0TSgyvmfLF2MIAEwyzRqaM77pBAoGAMmjmIJdjp+Ez8duyn3ieo36yrttF5NSsJLAbxFpdlcgvtGCWW+9Cq0bdxviW8+TFVEBl1O4f7HVm6EpTscdDxU+bCXWkfjuRb7Dy9GOtt9JPsX8MBTakzh3vBgsyi/sN3RqRBcGU40fOoZyfAMT8s1m/uYv52O6IgeuZ/ujbjY=
									-----END RSA PRIVATE KEY-----`
1. `cd /`
2. `cd tmp`
3. `mkdir randomkeyssh`
4. `nano ssh.key`
5. paste found ssh key 
6. `ssh -i ssh.key bandit17@localhost`
7. `chmod 400 ssh.key`
8. `ssh -i ssh.key bandit17@localhost`
9. `ls`
10. `cat passwords.new`
11. `cat passwords.old`
12. `cd /`
13. `cd etc`
14. `cat passwd`
15. `ls`
16. `cd bandit_pass/`
17. `cat bandit17`
18. password for bandit17: xLYVMN9WE5zQ5vHacb0sZEVqbrp7nBTn
