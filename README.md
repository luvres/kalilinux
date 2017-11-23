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

##### Base system (297 MB)
```
docker build -t izone/kalilinux:base ./base/
```
##### All packages (3410 MB)
```
docker build -t izone/kalilinux:all ./all/
```
##### Forensic tools (606 MB)
```
docker build -t izone/kalilinux:forensic ./forensic/
```
##### Complete system (1854 MB)
```
docker build -t izone/kalilinux:full ./full/
```
##### GPU tools (301 MB)
```
docker build -t izone/kalilinux:gpu ./gpu/
```
##### Nethunter tools (652 MB)
```
docker build -t izone/kalilinux:nethunter ./nethunter/
```
##### Password cracking tools (806 MB)
```
docker build -t izone/kalilinux:pwtools ./pwtools/
```
##### RFID tools (302 MB)
```
docker build -t izone/kalilinux:rfid ./rfid/
```
##### SDR tools (500 MB)
```
docker build -t izone/kalilinux:srd ./srd/
```
##### Top 10 tools (833 MB)
```
docker build -t izone/kalilinux:top10 ./top10/
```
##### VoIP tools (387 MB)
```
docker build -t izone/kalilinux:voip ./voip/
```
##### Webapp assessment tools (1260 MB)
```
docker build -t izone/kalilinux:web ./web/
```
##### Wireless tools (804 MB)
```
docker build -t izone/kalilinux:wireless ./wireless/
```
-----
```
docker build -t izone/kalilinux:base ./base/ \
&& docker build -t izone/kalilinux:all ./all/ \
&& docker build -t izone/kalilinux:forensic ./forensic/ \
&& docker build -t izone/kalilinux:full ./full/ \
&& docker build -t izone/kalilinux:gpu ./gpu/ \
&& docker build -t izone/kalilinux:nethunter ./nethunter/ \
&& docker build -t izone/kalilinux:pwtools ./pwtools/ \
&& docker build -t izone/kalilinux:rfid ./rfid/ \
&& docker build -t izone/kalilinux:sdr ./sdr/ \
&& docker build -t izone/kalilinux:top10 ./top10/ \
&& docker build -t izone/kalilinux:voip ./voip/ \
&& docker build -t izone/kalilinux:web ./web/ \
&& docker build -t izone/kalilinux:wireless ./wireless/
```

