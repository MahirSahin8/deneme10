en-A013-35@K-A013-35 MINGW64 ~/Desktop
$ ssh 244562@wizard.uek.krakow.pl
The authenticity of host 'wizard.uek.krakow.pl (149.156.208.41)' can't be established.
RSA key fingerprint is SHA256:rGOmkGnJLoXFUfkelipMKRGqSo2kGexlvF1p2nFCj7A.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'wizard.uek.krakow.pl' (RSA) to the list of known hosts.
244562@wizard.uek.krakow.pl's password:
Linux Wizard 5.10.0-33-amd64 #1 SMP Debian 5.10.226-1 (2024-10-03) x86_64
                    ____
                  .'* *.'
               __/_*_*(_
              / _______ \
             _\_)/___\(_/_               WITAJ PANIE!
            / _((\- -/))_ \   ---   JESTEM DO TWYCH USŁUG
            \ \())(-)(()/ /
             ' \(((()))/ '           wizard@uek.krakow.pl
            / ' \)).))/ ' \
           / _ \ - | - /_  \
          (   ( .;''';. .'  )
          _\"__ /    )\ __"/_
            \/  \   ' /  \/
             .'  '...' ' )
              / /  |  \ \
             / .   .   . \
            /   .     .   \
           /   /   |   \   \
         .'   /    b    '.  '.
     _.-'    /     Bb     '-. '-._
 _.-'       |      BBb       '-.  '-.
(___________\____.dBBBb.________)____)
244562@Wizard:~$ ssh-keygen -t rsa^C
244562@Wizard:~$ ^C
244562@Wizard:~$ ssh-keygen -t rsa
Generating public/private rsa key pair.
Enter file in which to save the key (/home/studenci/r26/244562/.ssh/id_rsa):
Created directory '/home/studenci/r26/244562/.ssh'.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /home/studenci/r26/244562/.ssh/id_rsa
Your public key has been saved in /home/studenci/r26/244562/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:qCv8ipVsTaCLIDWX2FwI1SrX7+wdQFhNzqIVhroeQ1Y 244562@Wizard
The key's randomart image is:
+---[RSA 3072]----+
|  .o.o..+o.      |
|   +.oE+ +.      |
|  = ==. + o      |
| o.+* .= .       |
|+  =..o.S        |
|+o ++.  ..       |
|o.=.oo o  .      |
| +o ..  o. .     |
|. .+o  .. .      |
+----[SHA256]-----+
244562@Wizard:~$ cat .ssh/id_rsa.pub
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQC8GRPXpifnV+9iHkI1OnNulTkxCLR2ug1N0yzV85K/K1jFtU+XnjpRZP6PSRyvpVnYHc/r2qq0QA2PLgWz8NMgjWKepmdQRYtn8SqdecOjH4or5ljUeOcO6ODFfVGvnlG2sZ0kUIlElvmC1QZZfuAdu0O2WsbRXe+DHAwVriuilm3lxYxi8eOvZCahzAdWO9/HezyZHt26gv3/hava0vYb1fzynm8sNjDkN6X7e4lG93hSqVQr/iWRe9AqVkuAo35KVilZN+k+keEJiIazjyolxhkZYBUDxIsjZVWvlBEcPDrwlF8Q35vierpKoMIKDOyHv6L+hyX4s5ikCSjOEfJVWNXPZ66SLmFbBvn2WDrq41Mq0w+RgV81gX7RrFboctO8kJvFzfX73x8K6LTzMMeoLPH5FD6oule96XNtt7lp9RUWGf4fwBQlEY6yUNbFeDAF33xqW5Dug/B7ftmxaLoQx4wylQHD5wkTl0D67g+RR/5CdWre4krS7XhvW/QZQf8= 244562@Wizard
244562@Wizard:~$ mkdir public_html
244562@Wizard:~$ cd public_html
244562@Wizard:~/public_html$ git clone git@github.com:MahirSahin8/PanTadeusz.git
Klonowanie do „PanTadeusz”...
The authenticity of host 'github.com (140.82.121.3)' can't be established.
ECDSA key fingerprint is SHA256:p2QAMXNIC1TJYWeIOttrVc98/R1BUFWu3/LiyKgUfQM.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com,140.82.121.3' (ECDSA) to the list of known hosts.
remote: Enumerating objects: 42, done.
remote: Counting objects: 100% (42/42), done.
remote: Compressing objects: 100% (26/26), done.
remote: Total 42 (delta 15), reused 42 (delta 15), pack-reused 0 (from 0)
Pobieranie obiektów: 100% (42/42), 227.95 KiB | 890.00 KiB/s, gotowe.
Rozwiązywanie delt: 100% (15/15), gotowe.
244562@Wizard:~/public_html$ cd PanTadeusz
244562@Wizard:~/public_html/PanTadeusz$ mc

244562@Wizard:~/public_html/PanTadeusz$ ls
k11.html  k12.html  k1.html  k2.html  k3.html  k5.html  k6.html  k7.html  k9.html

244562@Wizard:~/public_html/PanTadeusz$ ls
k11.html  k12.html  k1.html  k2.html  k3.html  k5.html  k6.html  k7.html  k9.html

244562@Wizard:~/public_html/PanTadeusz$ ls -al
razem 436
drwxr-xr-x 3 244562 studenci  4096 03-09 14:20 .
drwxr-xr-x 3 244562 studenci  4096 03-09 14:20 ..
drwxr-xr-x 8 244562 studenci  4096 03-09 14:20 .git
-rw-r--r-- 1 244562 studenci 39936 03-09 14:20 k11.html
-rw-r--r-- 1 244562 studenci 51084 03-09 14:20 k12.html
-rw-r--r-- 1 244562 studenci 57106 03-09 14:20 k1.html
-rw-r--r-- 1 244562 studenci 49871 03-09 14:20 k2.html
-rw-r--r-- 1 244562 studenci 46589 03-09 14:20 k3.html
-rw-r--r-- 1 244562 studenci 53893 03-09 14:20 k5.html
-rw-r--r-- 1 244562 studenci 36575 03-09 14:20 k6.html
-rw-r--r-- 1 244562 studenci 34400 03-09 14:20 k7.html
-rw-r--r-- 1 244562 studenci 46038 03-09 14:20 k9.html
244562@Wizard:~/public_html/PanTadeusz$ cd , ,
-bash: cd: za dużo argumentów
244562@Wizard:~/public_html/PanTadeusz$ cd . .
-bash: cd: za dużo argumentów
244562@Wizard:~/public_html/PanTadeusz$ ls -al
razem 436
drwxr-xr-x 3 244562 studenci  4096 03-09 14:20 .
drwxr-xr-x 3 244562 studenci  4096 03-09 14:20 ..
drwxr-xr-x 8 244562 studenci  4096 03-09 14:20 .git
-rw-r--r-- 1 244562 studenci 39936 03-09 14:20 k11.html
-rw-r--r-- 1 244562 studenci 51084 03-09 14:20 k12.html
-rw-r--r-- 1 244562 studenci 57106 03-09 14:20 k1.html
-rw-r--r-- 1 244562 studenci 49871 03-09 14:20 k2.html
-rw-r--r-- 1 244562 studenci 46589 03-09 14:20 k3.html
-rw-r--r-- 1 244562 studenci 53893 03-09 14:20 k5.html
-rw-r--r-- 1 244562 studenci 36575 03-09 14:20 k6.html
-rw-r--r-- 1 244562 studenci 34400 03-09 14:20 k7.html
-rw-r--r-- 1 244562 studenci 46038 03-09 14:20 k9.html
244562@Wizard:~/public_html/PanTadeusz$ chmod 755 -R PanTadeusz
chmod: nie ma dostępu do 'PanTadeusz': Nie ma takiego pliku ani katalogu
244562@Wizard:~/public_html/PanTadeusz$ ls -al
razem 436
drwxr-xr-x 3 244562 studenci  4096 03-09 14:20 .
drwxr-xr-x 3 244562 studenci  4096 03-09 14:20 ..
drwxr-xr-x 8 244562 studenci  4096 03-09 14:20 .git
-rw-r--r-- 1 244562 studenci 39936 03-09 14:20 k11.html
-rw-r--r-- 1 244562 studenci 51084 03-09 14:20 k12.html
-rw-r--r-- 1 244562 studenci 57106 03-09 14:20 k1.html
-rw-r--r-- 1 244562 studenci 49871 03-09 14:20 k2.html
-rw-r--r-- 1 244562 studenci 46589 03-09 14:20 k3.html
-rw-r--r-- 1 244562 studenci 53893 03-09 14:20 k5.html
-rw-r--r-- 1 244562 studenci 36575 03-09 14:20 k6.html
-rw-r--r-- 1 244562 studenci 34400 03-09 14:20 k7.html
-rw-r--r-- 1 244562 studenci 46038 03-09 14:20 k9.html
244562@Wizard:~/public_html/PanTadeusz$ chmod 755 ~R PanTadeusz
chmod: nie ma dostępu do '~R': Nie ma takiego pliku ani katalogu
chmod: nie ma dostępu do 'PanTadeusz': Nie ma takiego pliku ani katalogu
244562@Wizard:~/public_html/PanTadeusz$ chmod 755 ~R PanTadeusz/
chmod: nie ma dostępu do '~R': Nie ma takiego pliku ani katalogu
chmod: nie ma dostępu do 'PanTadeusz/': Nie ma takiego pliku ani katalogu
244562@Wizard:~/public_html/PanTadeusz$ chmod 755 -R PanTadeusz/
chmod: nie ma dostępu do 'PanTadeusz/': Nie ma takiego pliku ani katalogu
244562@Wizard:~/public_html/PanTadeusz$ ls -al
razem 436
drwxr-xr-x 3 244562 studenci  4096 03-09 14:20 .
drwxr-xr-x 3 244562 studenci  4096 03-09 14:20 ..
drwxr-xr-x 8 244562 studenci  4096 03-09 14:20 .git
-rw-r--r-- 1 244562 studenci 39936 03-09 14:20 k11.html
-rw-r--r-- 1 244562 studenci 51084 03-09 14:20 k12.html
-rw-r--r-- 1 244562 studenci 57106 03-09 14:20 k1.html
-rw-r--r-- 1 244562 studenci 49871 03-09 14:20 k2.html
-rw-r--r-- 1 244562 studenci 46589 03-09 14:20 k3.html
-rw-r--r-- 1 244562 studenci 53893 03-09 14:20 k5.html
-rw-r--r-- 1 244562 studenci 36575 03-09 14:20 k6.html
-rw-r--r-- 1 244562 studenci 34400 03-09 14:20 k7.html
-rw-r--r-- 1 244562 studenci 46038 03-09 14:20 k9.html
244562@Wizard:~/public_html/PanTadeusz$ git branch
* main
244562@Wizard:~/public_html/PanTadeusz$ git branch index
244562@Wizard:~/public_html/PanTadeusz$ git branch
  index
* main
244562@Wizard:~/public_html/PanTadeusz$ git switch index
Przełączono na gałąź „index”
244562@Wizard:~/public_html/PanTadeusz$ git checkout index
Już jesteś na „index”
244562@Wizard:~/public_html/PanTadeusz$ git branch index
fatal: Gałąź o nazwie „index” już istnieje.
244562@Wizard:~/public_html/PanTadeusz$ git status
Na gałęzi index
nic do złożenia, drzewo robocze czyste
244562@Wizard:~/public_html/PanTadeusz$ git branch
* index
  main
244562@Wizard:~/public_html/PanTadeusz$ git status
Na gałęzi index
nic do złożenia, drzewo robocze czyste
244562@Wizard:~/public_html/PanTadeusz$ git branch index
fatal: Gałąź o nazwie „index” już istnieje.
244562@Wizard:~/public_html/PanTadeusz$ git status
Na gałęzi index
nic do złożenia, drzewo robocze czyste
244562@Wizard:~/public_html/PanTadeusz$ git list
git: „list” nie jest poleceniem gita. Zobacz „git --help”.

Najpodobniejsze polecenia to
        bisect
        rev-list
244562@Wizard:~/public_html/PanTadeusz$ git status
Na gałęzi index
nic do złożenia, drzewo robocze czyste
244562@Wizard:~/public_html/PanTadeusz$
244562@Wizard:~/public_html/PanTadeusz$ git list
git: „list” nie jest poleceniem gita. Zobacz „git --help”.

Najpodobniejsze polecenia to
        bisect
        rev-list
244562@Wizard:~/public_html/PanTadeusz$ list
-bash: list: nie znaleziono polecenia
244562@Wizard:~/public_html/PanTadeusz$ git diff
244562@Wizard:~/public_html/PanTadeusz$ chmod 644 PanTadeusz/
chmod: nie ma dostępu do 'PanTadeusz/': Nie ma takiego pliku ani katalogu
244562@Wizard:~/public_html/PanTadeusz$ ls al
ls: nie ma dostępu do 'al': Nie ma takiego pliku ani katalogu
244562@Wizard:~/public_html/PanTadeusz$ ls -al
razem 436
drwxr-xr-x 3 244562 studenci  4096 03-09 14:20 .
drwxr-xr-x 3 244562 studenci  4096 03-09 14:20 ..
drwxr-xr-x 8 244562 studenci  4096 03-09 14:44 .git
-rw-r--r-- 1 244562 studenci 39936 03-09 14:20 k11.html
-rw-r--r-- 1 244562 studenci 51084 03-09 14:20 k12.html
-rw-r--r-- 1 244562 studenci 57106 03-09 14:20 k1.html
-rw-r--r-- 1 244562 studenci 49871 03-09 14:20 k2.html
-rw-r--r-- 1 244562 studenci 46589 03-09 14:20 k3.html
-rw-r--r-- 1 244562 studenci 53893 03-09 14:20 k5.html
-rw-r--r-- 1 244562 studenci 36575 03-09 14:20 k6.html
-rw-r--r-- 1 244562 studenci 34400 03-09 14:20 k7.html
-rw-r--r-- 1 244562 studenci 46038 03-09 14:20 k9.html
244562@Wizard:~/public_html/PanTadeusz$ cd 644 PanTadeusz/"
>
> cd
> cd 644 PanTadeusz/*
> cd 644 PanTadeusz/"
-bash: cd: za dużo argumentów
244562@Wizard:~/public_html/PanTadeusz$ cd 644 PanTadeusz/*
-bash: cd: za dużo argumentów
244562@Wizard:~/public_html/PanTadeusz$ cd PanTadeusz/
-bash: cd: PanTadeusz/: Nie ma takiego pliku ani katalogu
244562@Wizard:~/public_html/PanTadeusz$ git status
Na gałęzi index
nic do złożenia, drzewo robocze czyste
244562@Wizard:~/public_html/PanTadeusz$ git add
Nic nie podano, nic nie dodano.
podpowiedź: Może chodziło o „git add .”?
podpowiedź: Wyłącz ten komunikat wykonując
podpowiedź: „git config advice.addEmptyPathspec false”
244562@Wizard:~/public_html/PanTadeusz$ git commit -m "Index file created"
Nieznana tożsamość autora

*** Powiedz mi, kim jesteś.

Wykonaj

  git config --global user.email "toja@example.com"
  git config --global user.name "Twoje Imię Nazwisko"

by ustawić domyślną tożsamość swojego konta.
Pomiń --global, żeby ustawić tożsamość tylko w tym repozytorium.

fatal: puste nazwisko (do <244562@wizard.uek.krakow.pl>) niedozwolone
244562@Wizard:~/public_html/PanTadeusz$
