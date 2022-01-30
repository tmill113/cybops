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
4. `echo 'VGhlIHBhc3N3b3JkIGlzIElGdWt3S0dzRlc4TU9xM0lSRnFyeEUxaHhUTkViVVBSCg=='  |base64 -d
5. password for bandit11: IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR	

**Level 11**

1. `ssh bandit11@bandit.labs.overthewire.org -p 2220` and enter password
2. `cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'  
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

1.  `ssh bandit15@bandit.labs.overthewire.org -p 2220` and enter password
2. 
