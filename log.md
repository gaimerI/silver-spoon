[SFX]    this is: copyparty 1.19.9
[SFX]  packed at: 2025-09-15, 00:23:51 UTC, 1757895831
[SFX] archive is: C:\Users\gaime\Desktop\Copyparty\copyparty-sfx.py
[SFX] python bin: C:\Users\gaime\AppData\Local\Programs\Python\Python313\python.exe
[SFX] python ver: CPython 3.13.7 (tags/v3.13.7:bcee1c3, Aug 14 2025, 14:15:11) [MSC v.1944 64 bit (AMD64)]

[SFX] found early
[SFX] jinja2: bundled
[SFX] pyftpd: bundled
[SFX] sfxdir: C:\Users\gaime\AppData\Local\Temp\pe-copyparty

copyparty v1.19.9 "usernames" (2025-09-15)
  CPython v3.13.7 on Windows64 10.0.26100 [MSC v.1944 64 bit (AMD64)]
   sqlite 3.50.4*1 | jinja 2.11.3 | pyftpd 1.5.10 | tftp 0.4.0

[+] opened logfile [C:\Users\gaime/Desktop/Copyparty/cpp-2025-09-22.xz.1]
2025-09-22
18:15:02.801 root                  opening sessions-db C:/Users/gaime/AppData/Roaming/copyparty\sessions.db
18:15:02.848 auth                  loaded 1 config files:
└C:\Users\gaime\Desktop\Copyparty\party.conf
18:15:02.866 auth                  volumes and permissions:

"/"  C:\Users\gaime\Desktop\Copyparty
|    read:  gaimerI17
|   write:  gaimerI17
|    move:  gaimerI17
|  delete:  gaimerI17
|    dots:  gaimerI17
|     get:  everybody
|   upGet:  --none--
|    html:  --none--
|  uadmin:  gaimerI17

18:15:02.867 auth                  hint: enable upload deduplication with --dedup (but see readme for consequences)
18:15:02.884 root                  max clients: 486
18:15:02.964 tcpsrv                available @  http://127.0.0.1:80/  (1-Software Loopback Interface 1)
18:15:02.965 tcpsrv                available @ https://127.0.0.1:443/  (1-Software Loopback Interface 1)
18:15:02.966 tcpsrv                available @  http://[::1]:80/  (1-Software Loopback Interface 1)
18:15:02.966 tcpsrv                available @ https://[::1]:443/  (1-Software Loopback Interface 1)
18:15:02.966 tcpsrv                available @  http://[fe80::dd43:394d:43c:7008]:80/  (12-Microsoft Wi-Fi Direct Virtual Adapter #3)
18:15:02.967 tcpsrv                available @ https://[fe80::dd43:394d:43c:7008]:443/  (12-Microsoft Wi-Fi Direct Virtual Adapter #3)
18:15:02.967 tcpsrv                available @  http://169.254.169.166:80/  (12-Microsoft Wi-Fi Direct Virtual Adapter #3)
18:15:02.968 tcpsrv                available @ https://169.254.169.166:443/  (12-Microsoft Wi-Fi Direct Virtual Adapter #3)
18:15:02.968 tcpsrv                available @  http://[fe80::210:4e37:89b1:cd5b]:80/  (13-Microsoft Wi-Fi Direct Virtual Adapter #4)
18:15:02.969 tcpsrv                available @ https://[fe80::210:4e37:89b1:cd5b]:443/  (13-Microsoft Wi-Fi Direct Virtual Adapter #4)
18:15:02.969 tcpsrv                available @  http://169.254.238.96:80/  (13-Microsoft Wi-Fi Direct Virtual Adapter #4)
18:15:02.969 tcpsrv                available @ https://169.254.238.96:443/  (13-Microsoft Wi-Fi Direct Virtual Adapter #4)
18:15:02.970 tcpsrv                available @  http://[fe80::cb64:3854:4472:b338]:80/  (3-Intel(R) Ethernet Connection (6) I219-V)
18:15:02.971 tcpsrv                available @ https://[fe80::cb64:3854:4472:b338]:443/  (3-Intel(R) Ethernet Connection (6) I219-V)
18:15:02.972 tcpsrv                available @  http://169.254.241.177:80/  (3-Intel(R) Ethernet Connection (6) I219-V)
18:15:02.973 tcpsrv                available @ https://169.254.241.177:443/  (3-Intel(R) Ethernet Connection (6) I219-V)
18:15:02.974 tcpsrv                available @  http://[fe80::47e2:b00f:bae0:14e8]:80/  (6-Intel(R) Wireless-AC 9560 160MHz)
18:15:02.975 tcpsrv                available @ https://[fe80::47e2:b00f:bae0:14e8]:443/  (6-Intel(R) Wireless-AC 9560 160MHz)
18:15:02.975 tcpsrv                available @  http://192.168.0.19:80/  (6-Intel(R) Wireless-AC 9560 160MHz, external)
18:15:02.976 tcpsrv                available @ https://192.168.0.19:443/  (6-Intel(R) Wireless-AC 9560 160MHz, external)

18:15:02.984 optional-dependencies OK: sqlite, NG: pillow, vips, pillow-webp, ffmpeg, ffprobe, mutagen, argon2, pyzmq, pillow-heif, pillow-avif, rawpy, psutil, see --deps (this is fine btw)
18:15:02.985 thumb                 decoder preference: (None available)
18:15:02.985 thumb                 need either Pillow, pyvips, or FFmpeg to create thumbnails; for example:
                                     python.exe -m pip install --user Pillow
                                     python.exe -m pip install --user pyvips
                                     apt install ffmpeg
18:15:02.986 thumb                 setting --no-acode because either FFmpeg or FFprobe is not available
18:15:02.986 thumb                 download FFmpeg to fix it: https://www.gyan.dev/ffmpeg/builds/ffmpeg-git-full.7z
18:15:03.434 tcpsrv                listening @ [::]:80  f300 p2640
18:15:03.435 hsrv                  subscribed @ [::]:80  f300 p2640
18:15:03.436 tcpsrv                listening @ 0.0.0.0:80  f784 p2640
18:15:03.436 root                  workers OK

18:15:03.437 hsrv                  subscribed @ 0.0.0.0:80  f784 p2640
18:15:03.440 tcpsrv                listening @ [::]:443  f764 p2640
18:15:03.441 hsrv                  subscribed @ [::]:443  f764 p2640
18:15:03.442 up2k                  / casechk:y
18:15:03.443 tcpsrv                listening @ 0.0.0.0:443  f296 p2640
18:15:03.444 hsrv                  subscribed @ 0.0.0.0:443  f296 p2640
18:15:03.485 up2k                    C:\Users\gaime\Desktop\Copyparty\.hist\up2k.db |3|
18:15:03.489 mtag                  could not load Mutagen, trying FFprobe instead
18:15:03.489 mtag                  need Mutagen or FFprobe to read media tags so please run this:
                                     python.exe -m pip install --user mutagen

18:15:03.490 up2k                  uploads temporarily blocked due to indexing
18:15:03.508 cert                  creating new ca ...
18:15:03.513 up2k                  commit 1 new files; 2 updates
18:15:03.514 up2k                  uploads are now possible
18:15:03.514 up2k                  online (reading tags) [C:\Users\gaime\Desktop\Copyparty]
18:15:03.519 cert                  could not create TLS certificates: [WinError 2] Määritettyä tiedostoa ei löydy
18:15:03.520 cert                  install cfssl if you want to fix this; https://github.com/cloudflare/cfssl/releases/latest  (cfssl, cfssljson, cfssl-certinfo)
18:15:03.522 cert                  using default TLS certificate; https will be insecure: C:/Users/gaime/AppData/Roaming/copyparty\cert.pem
18:15:03.525 up2k                  1 volumes in 0.09 sec
18:15:03.526 up2k                  could not read tags because no backends are available (Mutagen or FFprobe)
18:15:03.527 SSDP-1                announce failed on 3-Intel(R) Ethernet Connection (6) I219-V [169.254.241.177]:
multicast.py:193 <create_servers>: self.setup_socket(srv)
multicast.py:284 <setup_socket>: sck.setsockopt(socket.IPPROTO_IP, socket.IP_MULTICAST_IF, dev)
[OSError] [WinError 10049] Pyydetty osoite ei kelpaa tässä kontekstissa
18:15:03.527 mDNS-1                announce failed on 3-Intel(R) Ethernet Connection (6) I219-V [169.254.241.177]:
multicast.py:193 <create_servers>: self.setup_socket(srv)
multicast.py:284 <setup_socket>: sck.setsockopt(socket.IPPROTO_IP, socket.IP_MULTICAST_IF, dev)
[OSError] [WinError 10049] Pyydetty osoite ei kelpaa tässä kontekstissa
18:15:03.531 SSDP-1                announce failed on 12-Microsoft Wi-Fi Direct Virtual Adapter #3 [169.254.169.166]:
multicast.py:193 <create_servers>: self.setup_socket(srv)
multicast.py:284 <setup_socket>: sck.setsockopt(socket.IPPROTO_IP, socket.IP_MULTICAST_IF, dev)
[OSError] [WinError 10049] Pyydetty osoite ei kelpaa tässä kontekstissa
18:15:03.532 mDNS-1                announce failed on 12-Microsoft Wi-Fi Direct Virtual Adapter #3 [169.254.169.166]:
multicast.py:193 <create_servers>: self.setup_socket(srv)
multicast.py:284 <setup_socket>: sck.setsockopt(socket.IPPROTO_IP, socket.IP_MULTICAST_IF, dev)
[OSError] [WinError 10049] Pyydetty osoite ei kelpaa tässä kontekstissa
18:15:03.534 SSDP-1                announce failed on 13-Microsoft Wi-Fi Direct Virtual Adapter #4 [169.254.238.96]:
multicast.py:193 <create_servers>: self.setup_socket(srv)
multicast.py:284 <setup_socket>: sck.setsockopt(socket.IPPROTO_IP, socket.IP_MULTICAST_IF, dev)
[OSError] [WinError 10049] Pyydetty osoite ei kelpaa tässä kontekstissa
18:15:03.537 mDNS-1                announce failed on 13-Microsoft Wi-Fi Direct Virtual Adapter #4 [169.254.238.96]:
multicast.py:193 <create_servers>: self.setup_socket(srv)
multicast.py:284 <setup_socket>: sck.setsockopt(socket.IPPROTO_IP, socket.IP_MULTICAST_IF, dev)
[OSError] [WinError 10049] Pyydetty osoite ei kelpaa tässä kontekstissa
18:15:03.538 SSDP-1                listening
18:15:03.550 mDNS-1                new client on Intel(R) Wireless-AC 9560 160MHz (192.168.0.0/24): 192.168.0.19
18:15:05.599 mDNS-1                probe ok; announcing [DESKTOP-Q86L349.local]
18:15:18.553 192.168.0.19 52473    GET  / @gaimerI17
18:15:18.557 u2idx                 opened 'C:\\Users\\gaime\\Desktop\\Copyparty\\.hist\\up2k.db'
18:15:19.887 192.168.0.19 52473    GET  /favicon.ico @gaimerI17
18:15:19.891 192.168.0.19 52473    http400: client d/c while replying body, '/favicon.ico'
