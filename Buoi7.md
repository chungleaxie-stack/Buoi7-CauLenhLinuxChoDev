\# BÀI 1



```bash

chungle@chungle-VMware-Virtual-Platform:\~$ pwd

/home/chungle

chungle@chungle-VMware-Virtual-Platform:\~$ mkdir dev-practice

chungle@chungle-VMware-Virtual-Platform:\~$ cd dev-practice/

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice$ mkdir backend frontend scripts

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice$ cd backend/

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice/backend$ touch app.log config.txt README.md

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice/backend$ cd ..

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice$ cd frontend/

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice/frontend$ touch package.json note.txt

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice/frontend$ cd ..

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice$ cd scripts/

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice/scripts$ touch deploy.sh

```



\# BÀI 2



```bash

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice/scripts$ cd ..

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice$ cd backend/

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice/backend$ mv README.md guide.md

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice/backend$ cp config.txt config.backup.txt

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice/backend$ rm -rf config.backup.txt

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice/backend$ touch error.log

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice/backend$ ls -la

total 8

drwxrwxr-x 2 chungle chungle 4096 Jul 23 11:08 .

drwxrwxr-x 5 chungle chungle 4096 Jul 23 10:50 ..

\-rw-rw-r-- 1 chungle chungle    0 Jul 23 10:51 app.log

\-rw-rw-r-- 1 chungle chungle    0 Jul 23 10:51 config.txt

\-rw-rw-r-- 1 chungle chungle    0 Jul 23 11:08 error.log

\-rw-rw-r-- 1 chungle chungle    0 Jul 23 10:51 guide.md

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice/backend$

```



\# BÀI 3



```bash

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice/backend$ nano app.log

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice/backend$ cat app.log

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice/backend$ head -n 2 app.log

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice/backend$ tail -n 2 app.log

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice/backend$ grep ERROR app.log

```



\# BÀI 4



```bash

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice/backend$ cd ..

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice$ find . -name "\*.txt"

./frontend/note.txt

./backend/config.txt

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice$ find . -name "\*.log"

./backend/error.log

./backend/app.log

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice$ find . -name "package.json"

./frontend/package.json

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice$ grep -r "port" .

./backend/app.log:INFO Server running on port 8080

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice$

```



\# BÀI 5



```bash

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice$ sudo apt install -y git curl vim

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice$ git --version

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice$ vim --version

chungle@chungle-VMware-Virtual-Platform:\~/dev-practice$ curl --version

```



\# BÀI 6



```bash

chungle@chungle-VMware-Virtual-Platform:\~/Desktop$ ping google.com

chungle@chungle-VMware-Virtual-Platform:\~/Desktop$ curl https://example.com

chungle@chungle-VMware-Virtual-Platform:\~/Desktop$ ss -tuln

```

