### Reference Official Kali Linux Docker
-----
https://github.com/offensive-security/kali-linux-docker

##### Run
```
docker run --rm --name Kali -h kali -ti izone/kalilinux bash
```
##### Search metapackages
```
apt-cache search kali-linux
```
-----
### Builds
```
docker build -t izone/kalilinux .
```

##### Kali Linux base system (297 MB)
```
docker build -t izone/kalilinux:base ./base/
```
##### Kali Linux all packages (3410 MB)
```
docker build -t izone/kalilinux:all ./all/
```
##### Kali Linux forensic tools (606 MB)
```
docker build -t izone/kalilinux:forensic ./forensic/
```
##### Kali Linux complete system (1854 MB)
```
docker build -t izone/kalilinux:full ./full/
```
##### Kali Linux GPU tools (301 MB)
```
docker build -t izone/kalilinux:gpu ./gpu/
```
##### Kali Linux Nethunter tools (652 MB)
```
docker build -t izone/kalilinux:nethunter ./nethunter/
```
##### Kali Linux password cracking tools (806 MB)
```
docker build -t izone/kalilinux:pwtools ./pwtools/
```
##### Kali Linux RFID tools (302 MB)
```
docker build -t izone/kalilinux:rfid ./rfid/
```
##### Kali Linux SDR tools (500 MB)
```
docker build -t izone/kalilinux:srd ./srd/
```
##### Kali Linux Top 10 tools (833 MB)
```
docker build -t izone/kalilinux:top10 ./top10/
```
##### Kali Linux VoIP tools (387 MB)
```
docker build -t izone/kalilinux:voip ./voip/
```
##### Kali Linux webapp assessment tools (1260 MB)
```
docker build -t izone/kalilinux:web ./web/
```
##### Kali Linux wireless tools (804 MB)
```
docker build -t izone/kalilinux:wireless ./wireless/
```

