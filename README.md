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
##### Build
```
docker build -t izone/kalilinux .
```
