
  "latitude": 19.679616666666668,
  "longitude": -99.08435,
  "altitude": 2271.2,
  "accuracy": 4.699999809265137,
  "vertical_accuracy": 57.900001525878906,
  "bearing": 31.459999084472656,
  "speed": 0.302141934633255,
  "elapsedMs": 167,
  "provider": "gps"termux-setup-storagels /mnt/media_rw/
termux-setup-storage -f
mkdir -p /mnt/usb
mount -o rw,umask=000 /dev/block/$(find /dev/block/ -name "*usb*" | head -n1) /mnt/usb 2>/dev/null || echo "LISTO, YA ESTÁ DENTRO"
cd /mnt/usb
44794478447444734471openssl.cnf70244704166473https://mirror.csclub.uwaterloo.ca/termux/termux-mainhttp://mirror.mephi.ru/termux/termux-main:https://mirrors.middlendian.com/termux/termux-main:https://repository.su/termux/termux-main/:https://mirror.fcix.net/termux/termux-main:https://mirror.csclub.uwaterloo.ca/termux/termux-main:https://dl.kcubeterm.com/termux-main:https://termux.danyael.xyz/termux/termux-main:https://mirror.vern.cc/termux/termux-main:https://plug-mirror.rcac.purdue.edu/termux/termux-main:https://mirror.quantum5.ca/termux/termux-main:https://mirrors.utermux.dev/termux/termux-main:https://gnlug.org/pub/termux/termux-main:https://mirrors.de.sahilister.net/termux/termux-main:https://ftp.fau.de/termux/termux-main:https://mirrors.cfe.re/termux/termux-main:https://ftp.agdsn.de/termux/termux-main:https://packages.termux.dev/apt/termux-main:https://mirror.autkin.net/termux/termux-main:https://mirror.sunred.org/termux/termux-main:https://termux.librehat.com/apt/termux-main:https://mirror.bouwhuis.network/termux/termux-main:https://termux.cdn.lumito.net/termux-main:https://mirror.leitecastro.com/termux/termux-main:https://nl.mirror.flokinet.net/termux/termux-main:https://termux.mentality.rip/termux-main:https://is.mirror.flokinet.net/termux/termux-main:https://mirror.termux.dev/termux-main:https://md.mirrors.hacktegic.com/termux/termux-main:https://ro.mirror.flokinet.net/termux/termux-main:https://mirror.mwt.me/termux/main:https://mirror.accum.se/mirror/termux.dev/termux-main:https://termux.3san.dev/termux/termux-main:https://mirrors.medzik.dev/termux/termux-main:https://mirror.polido.pt/termux/termux-main:https://grimler.se/termux/termux-main:https://mirrors.zju.edu.cn/termux/apt/termux-main:https://mirrors.nju.edu.cn/termux/apt/termux-main:https://mirrors.nju.edu.cn/termux/apt/termux-main:https://mirrors.ustc.edu.cn/termux/termux-main:https://mirror.nyist.edu.cn/termux/apt/termux-main:https://mirrors.tuna.tsinghua.edu.cn/termux/apt/termux-main:https://mirror.sjtu.edu.cn/termux/termux-main/:https://mirrors.hust.edu.cn/termux/apt/termux-main:https://mirrors.pku.edu.cn/termux/termux-main/:https://mirrors.sustech.edu.cn/termux/apt/termux-main:https://mirrors.bfsu.edu.cn/termux/apt/termux-main:https://mirrors.cqupt.edu.cn/termux/termux-main:https://mirrors.sdu.edu.cn/termux/termux-main:https://mirrors.aliyun.com/termux/termux-main:https://mirror.iscas.ac.cn/termux/apt/termux-main:https://mirrors.sau.edu.cn/termux/apt/termux-main:https://mirrors.in.sahilister.net/termux/termux-main/:https://mirror.freedif.org/termux/termux-main:https://mirror.meowsmp.net/termux/termux-main:https://mirror.nevacloud.com/applications/termux/termux-main:https://mirror.twds.com.tw/termux/termux-main:https://mirror.albony.in/termux/termux-main:https://mirrors.cbrx.io/apt/termux/termux-main:https://tmx.xvx.my.id/apt/termux-main:https://mirrors.nguyenhoang.cloud/termux/termux-main:https://mirror.rinarin.dev/termux/termux-main:https://mirrors.krnk.org/apt/termux/termux-main:https://mirror.jeonnam.school/termux/termux-main:https://mirror.textcord.xyz/termux/termux-main:https://mirrors.saswata.cc/termux/termux-main:https://mirror.bardia.tech/termux/termux-main:https://mirrors.ravidwivedi.in/termux/termux-main:https://termux.niranjan.co/termux-main:https://linux.domainesia.com/applications/termux/termux-main:https://packages-cf.termux.dev/apt/termux-main:All mirrors selected
[*] pkg --check-mirror update
Testing the available mirrors:
[*] (10) https://packages-cf.termux.dev/apt/termux-main: ok
[*] (1) https://linux.domainesia.com/applications/termux/termux-main: ok
[*] (1) https://termux.niranjan.co/termux-main: ok
[*] (1) https://mirror.bardia.tech/termux/termux-main: bad
[*] (1) https://mirrors.saswata.cc/termux/termux-main: bad
[*] (1) https://mirrors.ravidwivedi.in/termux/termux-main: ok
[*] (1) https://mirror.textcord.xyz/termux/termux-main: ok
[*] (1) https://mirrors.krnk.org/apt/termux/termux-main: ok
[*] (1) https://mirror.rinarin.dev/termux/termux-main: ok
[*] (1) https://mirror.jeonnam.school/termux/termux-main: ok
[*] (1) https://mirrors.nguyenhoang.cloud/termux/termux-main: ok
[*] (1) https://mirrors.cbrx.io/apt/termux/termux-main: ok
[*] (1) https://tmx.xvx.my.id/apt/termux-main: ok
[*] (1) https://mirror.albony.in/termux/termux-main: ok
[*] (1) https://mirror.twds.com.tw/termux/termux-main: ok
[*] (1) https://mirror.nevacloud.com/applications/termux/termux-main: ok
[*] (1) https://mirror.meowsmp.net/termux/termux-main: bad
[*] (1) https://mirror.freedif.org/termux/termux-main: ok
[*] (1) https://mirrors.in.sahilister.net/termux/termux-main/: ok
[*] (1) https://mirror.iscas.ac.cn/termux/apt/termux-main: bad
[*] (1) https://mirrors.sau.edu.cn/termux/apt/termux-main: ok
[*] (1) https://mirrors.sdu.edu.cn/termux/termux-main: ok
[*] (1) https://mirrors.aliyun.com/termux/termux-main: ok
[*] (1) https://mirrors.cernet.edu.cn/termux/apt/termux-main: ok
[*] (1) https://mirrors.cqupt.edu.cn/termux/termux-main: ok
[*] (1) https://mirrors.sustech.edu.cn/termux/apt/termux-main: ok
[*] (1) https://mirrors.bfsu.edu.cn/termux/apt/termux-main: ok
[*] (1) https://mirrors.pku.edu.cn/termux/termux-main/: ok
[*] (1) https://mirrors.hust.edu.cn/termux/apt/termux-main: ok
[*] (1) https://mirrors.tuna.tsinghua.edu.cn/termux/apt/termux-main: ok
[*] (1) https://mirror.sjtu.edu.cn/termux/termux-main/: ok
[*] (1) https://mirror.nyist.edu.cn/termux/apt/termux-main: ok
[*] (1) https://mirrors.ustc.edu.cn/termux/termux-main: ok
[*] (1) https://mirrors.zju.edu.cn/termux/apt/termux-main: ok
[*] (1) https://mirrors.nju.edu.cn/termux/apt/termux-main: ok
[*] (4) https://grimler.se/termux/termux-main: ok
[*] (1) https://mirror.polido.pt/termux/termux-main: bad
[*] (1) https://termux.3san.dev/termux/termux-main: ok
[*] (1) https://mirrors.medzik.dev/termux/termux-main: bad
[*] (1) https://mirror.accum.se/mirror/termux.dev/termux-main: ok
[*] (1) https://mirror.mwt.me/termux/main: ok
[*] (1) https://ro.mirror.flokinet.net/termux/termux-main: ok
[*] (1) https://md.mirrors.hacktegic.com/termux/termux-main: bad
[*] (1) https://is.mirror.flokinet.net/termux/termux-main: ok
[*] (1) https://mirror.termux.dev/termux-main: bad
[*] (1) https://termux.mentality.rip/termux-main: bad
[*] (1) https://nl.mirror.flokinet.net/termux/termux-main: ok
[*] (1) https://termux.cdn.lumito.net/termux-main: ok
[*] (1) https://mirror.leitecastro.com/termux/termux-main: bad
[*] (1) https://mirror.bouwhuis.network/termux/termux-main: ok
[*] (1) https://termux.librehat.com/apt/termux-main: ok
[*] (1) https://mirror.autkin.net/termux/termux-main: ok
[*] (1) https://mirror.sunred.org/termux/termux-main: ok
[*] (1) https://packages.termux.dev/apt/termux-main: ok
[*] (1) https://ftp.agdsn.de/termux/termux-main: ok
[*] (1) https://ftp.fau.de/termux/termux-main: ok
[*] (1) https://mirrors.cfe.re/termux/termux-main: bad
[*] (1) https://mirrors.de.sahilister.net/termux/termux-main: ok
[*] (1) https://gnlug.org/pub/termux/termux-main: ok
[*] (1) https://mirror.mwt.me/termux/main: ok
[*] (1) https://mirror.quantum5.ca/termux/termux-main: ok
[*] (1) https://mirrors.utermux.dev/termux/termux-main: ok
[*] (1) https://plug-mirror.rcac.purdue.edu/termux/termux-main: ok
[*] (1) https://mirror.vern.cc/termux/termux-main: ok
[*] (1) https://dl.kcubeterm.com/termux-main: bad
[*] (1) https://termux.danyael.xyz/termux/termux-main: ok
[*] (1) https://mirror.csclub.uwaterloo.ca/termux/termux-main: ok
[*] (1) https://mirror.fcix.net/termux/termux-main: ok
[*] (1) https://mirrors.middlendian.com/termux/termux-main: ok
[*] (1) https://repository.su/termux/termux-main/: ok
[*] (1) http://mirror.mephi.ru/termux/termux-main: ok
Picking mirror: (66) /data/data/com.termux/files/usr/etc/termux/mirrors/north_america/mirror.csclub.uwaterloo.ca
Get:1 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable InRelease [14.0 kB]
Get:2 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 Packages [547 kB]
Fetched 561 kB in 3s (173 kB/s)
Reading package lists... Done
Building dependency tree... Done
73 packages can be upgraded. Run 'apt list --upgradable' to see them.
~ $ pwd
/data/data/com.termux/files/home
~ $ ls
~ $ pkg update -y && pkg upgrade -y
Checking availability of current mirror:
[*] https://mirror.csclub.uwaterloo.ca/termux/termux-main: ok
Hit:1 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable InRelease
Reading package lists... Done
Building dependency tree... Done
73 packages can be upgraded. Run 'apt list --upgradable' to see them.
Checking availability of current mirror:
[*] https://mirror.csclub.uwaterloo.ca/termux/termux-main: ok
Hit:1 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable InRelease
Reading package lists... Done
Building dependency tree... Done
73 packages can be upgraded. Run 'apt list --upgradable' to see them.
Reading package lists... Done
Building dependency tree... Done
Calculating upgrade... Done
The following NEW packages will be installed:
  attr libacl libandroid-posix-semaphore libngtcp2
The following packages will be upgraded:
  apt bash bzip2 ca-certificates command-not-found
  coreutils curl dash debianutils dialog diffutils
  dos2unix dpkg ed findutils gawk gpgv grep gzip
  inetutils less libandroid-glob libandroid-selinux
  libandroid-support libassuan libbz2 libc++
  libcap-ng libcurl libevent libgcrypt libgmp
  libgnutls libgpg-error libiconv libidn2 liblz4
  liblzma libmd libmpfr libnettle libnghttp2
  libnghttp3 libnpth libsmartcols libssh2 libtirpc
  libunbound libunistring lsof nano ncurses
  net-tools openssl patch pcre2 procps psmisc
  readline sed tar termux-am termux-am-socket
  termux-core termux-exec termux-keyring
  termux-tools unzip util-linux xxhash xz-utils
  zlib zstd
73 upgraded, 4 newly installed, 0 to remove and 0 not upgraded.
Need to get 21.1 MB of archives.
After this operation, 4166 kB of additional disk space will be used.
Get:1 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 ca-certificates all 1:2026.03.19 [125 kB]
Get:2 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 zlib aarch64 1.3.2 [62.8 kB]
Get:3 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 openssl aarch64 1:3.6.2 [2478 kB]
Get:4 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 pcre2 aarch64 10.47 [961 kB]
Get:5 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libandroid-selinux aarch64 14.0.0.11-1 [59.6 kB]
Get:6 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libiconv aarch64 1.18-1 [561 kB]
Get:7 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libandroid-support aarch64 29-1 [10.9 kB]
Get:8 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libc++ aarch64 29 [335 kB]
Get:9 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libgmp aarch64 6.3.0-2 [328 kB]
Get:10 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 coreutils aarch64 9.11 [814 kB]
Get:11 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libbz2 aarch64 1.0.8-8 [26.1 kB]
Get:12 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 bzip2 aarch64 1.0.8-8 [26.2 kB]
Get:13 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 diffutils aarch64 3.12-2 [163 kB]
Get:14 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 gzip aarch64 1.14-1 [87.5 kB]
Get:15 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 ncurses aarch64 6.6.20260307+really6.5.20250830 [558 kB]
Get:16 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 less aarch64 702 [139 kB]
Get:17 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 liblzma aarch64 5.8.3 [193 kB]
Get:18 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 xz-utils aarch64 5.8.3 [71.2 kB]
Get:19 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libmd aarch64 1.1.0-1 [40.6 kB]
Get:20 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 attr aarch64 2.5.2-1 [52.6 kB]
Get:21 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libacl aarch64 2.3.2 [116 kB]
Get:22 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libandroid-glob aarch64 0.6-3 [7032 B]
Get:23 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 tar aarch64 1.35-2 [345 kB]
Get:24 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 zstd aarch64 1.5.7-1 [360 kB]
Get:25 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 dpkg aarch64 1.22.6-5 [308 kB]
Get:26 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 findutils aarch64 4.10.0-1 [251 kB]
Get:27 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libgpg-error aarch64 1.58 [121 kB]
Get:28 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libassuan aarch64 3.0.2-1 [73.9 kB]
Get:29 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libgcrypt aarch64 1.11.2-1 [500 kB]
Get:30 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libnpth aarch64 1.6-3 [11.2 kB]
Get:31 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 gpgv aarch64 2.5.17 [188 kB]
Get:32 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 grep aarch64 3.12-3 [128 kB]
Get:33 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libnettle aarch64 4.0+really3.10.2 [406 kB]
Get:34 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libunistring aarch64 1.3-1 [551 kB]
Get:35 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libidn2 aarch64 2.3.8-1 [105 kB]
Get:36 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libngtcp2 aarch64 1.22.1 [167 kB]
Get:37 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libevent aarch64 2.1.12-3 [203 kB]
Get:38 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libnghttp2 aarch64 1.69.0 [95.6 kB]
Get:39 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libunbound aarch64 1.25.1 [385 kB]
Get:40 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libgnutls aarch64 3.8.11 [729 kB]
Get:41 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 liblz4 aarch64 1.10.0-1 [84.7 kB]
Get:42 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 sed aarch64 4.9-2 [118 kB]
Get:43 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libnghttp3 aarch64 1.15.0 [67.8 kB]
Get:44 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libssh2 aarch64 1.11.1-1 [218 kB]
Get:45 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libcurl aarch64 8.20.0 [1006 kB]
Get:46 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 curl aarch64 8.20.0 [240 kB]
Get:47 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 dash aarch64 0.5.12-2 [65.8 kB]
Get:48 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libmpfr aarch64 4.2.1-1 [272 kB]
Get:49 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 readline aarch64 8.3.3 [294 kB]
Get:50 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 gawk aarch64 5.3.2 [873 kB]
Get:51 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 procps aarch64 3.3.17-6 [143 kB]
Get:52 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 psmisc aarch64 23.7-1 [41.2 kB]
Get:53 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 termux-am all 0.8.0-2 [577 kB]
Get:54 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 termux-am-socket aarch64 1.5.0-1 [16.1 kB]
Get:55 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 termux-core aarch64 0.4.0-1 [198 kB]
Get:56 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 termux-exec aarch64 1:2.4.0-1 [288 kB]
Get:57 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libandroid-posix-semaphore aarch64 0.1-4 [4076 B]
Get:58 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libsmartcols aarch64 2.42.1 [103 kB]
Get:59 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libcap-ng aarch64 2:0.9.3 [38.9 kB]
Get:60 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 util-linux aarch64 2.42.1 [774 kB]
Get:61 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 dialog aarch64 1.3-20260107-1 [101 kB]
Get:62 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 termux-tools aarch64 1.46.0+really1.45.0-1 [33.6 kB]
Get:63 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 termux-keyring all 3.13 [39.8 kB]
Get:64 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 xxhash aarch64 0.8.3-1 [76.6 kB]
Get:65 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 apt aarch64 2.8.1-2 [1031 kB]
Get:66 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 bash aarch64 5.3.9 [955 kB]
Get:67 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 command-not-found aarch64 3.4.1-11 [111 kB]
Get:68 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 debianutils aarch64 5.23.2-1 [16.8 kB]
Get:69 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 dos2unix aarch64 7.5.6 [65.3 kB]
Get:70 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 ed aarch64 1.22.5 [42.9 kB]
Get:71 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 inetutils aarch64 2.7 [240 kB]
Get:72 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 libtirpc aarch64 1.3.7-1 [124 kB]
Get:73 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 lsof aarch64 4.99.6 [122 kB]
Get:74 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 nano aarch64 9.0 [233 kB]
Get:75 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 net-tools aarch64 2.10.0-1 [118 kB]
Get:76 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 patch aarch64 2.8-1 [74.0 kB]
Get:77 https://mirror.csclub.uwaterloo.ca/termux/termux-main stable/main aarch64 unzip aarch64 6.0-10 [117 kB]
Fetched 21.1 MB in 32s (660 kB/s)
(Reading database ... 4470 files and directories currently installed.)
Preparing to unpack .../ca-certificates_1%3a2026.03.19_all.deb ...
Unpacking ca-certificates (1:2026.03.19) over (1:2025.02.25) ...
Setting up ca-certificates (1:2026.03.19) ...
(Reading database ... 4470 files and directories currently installed.)
Preparing to unpack .../zlib_1.3.2_aarch64.deb ...
Unpacking zlib (1.3.2) over (1.3.1) ...
Setting up zlib (1.3.2) ...
(Reading database ... 4470 files and directories currently installed.)
Preparing to unpack .../openssl_1%3a3.6.2_aarch64.deb ...
Unpacking openssl (1:3.6.2) over (1:3.4.1) ...
Setting up openssl (1:3.6.2) ...

Configuration file '/data/data/com.termux/files/usr/etc/tls/openssl.cnf'
 ==> File on system created by you or by a script.
 ==> File also in package provided by package maintainer.
   What would you like to do about it ?  Your options are:
    Y or I  : install the package maintainer's version
    N or O  : keep your currently-installed version
      D     : show the differences between the versions
      Z     : start a shell to examine the situation
 The default action is to keep your current version.
*** openssl.cnf (Y/I/N/O/D/Z) [default=N] ? N
(Reading database ... 4471 files and directories currently installed.)
Preparing to unpack .../pcre2_10.47_aarch64.deb ...
Unpacking pcre2 (10.47) over (10.45) ...
Setting up pcre2 (10.47) ...
(Reading database ... 4473 files and directories currently installed.)
Preparing to unpack .../libandroid-selinux_14.0.0.11-1_aarch64.deb ...
Unpacking libandroid-selinux (14.0.0.11-1) over (14.0.0.11) ...
Setting up libandroid-selinux (14.0.0.11-1) ...
(Reading database ... 4473 files and directories currently installed.)
Preparing to unpack .../libiconv_1.18-1_aarch64.deb ...
Unpacking libiconv (1.18-1) over (1.18) ...
Setting up libiconv (1.18-1) ...
(Reading database ... 4473 files and directories currently installed.)
Preparing to unpack .../libandroid-support_29-1_aarch64.deb ...
Unpacking libandroid-support (29-1) over (29) ...
Setting up libandroid-support (29-1) ...
(Reading database ... 4473 files and directories currently installed.)
Preparing to unpack .../archives/libc++_29_aarch64.deb ...
Unpacking libc++ (29) over (27c) ...
Setting up libc++ (29) ...
(Reading database ... 4473 files and directories currently installed.)
Preparing to unpack .../libgmp_6.3.0-2_aarch64.deb ...
Unpacking libgmp (6.3.0-2) over (6.3.0-1) ...
Setting up libgmp (6.3.0-2) ...
(Reading database ... 4473 files and directories currently installed.)
Preparing to unpack .../coreutils_9.11_aarch64.deb ...
Unpacking coreutils (9.11) over (9.6-1) ...
Setting up coreutils (9.11) ...
update-alternatives: using /data/data/com.termux/files/usr/libexec/coreutils/cat to provide /data/data/com.termux/files/usr/bin/pager (pager) in auto mode
(Reading database ... 4474 files and directories currently installed.)
Preparing to unpack .../libbz2_1.0.8-8_aarch64.deb ...
Unpacking libbz2 (1.0.8-8) over (1.0.8-6) ...
Setting up libbz2 (1.0.8-8) ...
(Reading database ... 4474 files and directories currently installed.)
Preparing to unpack .../bzip2_1.0.8-8_aarch64.deb ...
Unpacking bzip2 (1.0.8-8) over (1.0.8-6) ...
Setting up bzip2 (1.0.8-8) ...
(Reading database ... 4474 files and directories currently installed.)
Preparing to unpack .../diffutils_3.12-2_aarch64.deb ...
Unpacking diffutils (3.12-2) over (3.11) ...
Setting up diffutils (3.12-2) ...
(Reading database ... 4474 files and directories currently installed.)
Preparing to unpack .../gzip_1.14-1_aarch64.deb ...
Unpacking gzip (1.14-1) over (1.13) ...
Setting up gzip (1.14-1) ...
(Reading database ... 4474 files and directories currently installed.)
Preparing to unpack .../ncurses_6.6.20260307+really6.5.20250830_aarch64.deb ...
Unpacking ncurses (6.6.20260307+really6.5.20250830) over (6.5.20240831-2) ...
Setting up ncurses (6.6.20260307+really6.5.20250830) ...
(Reading database ... 4478 files and directories currently installed.)
Preparing to unpack .../archives/less_702_aarch64.deb ...
Unpacking less (702) over (668) ...
Setting up less (702) ...
update-alternatives: using /data/data/com.termux/files/usr/bin/less to provide /data/data/com.termux/files/usr/bin/pager (pager) in auto mode
(Reading database ... 4479 files and directories currently installed.)
Preparing to unpack .../liblzma_5.8.3_aarch64.deb ...
Unpacking liblzma (5.8.3) over (5.8.0) ...
Setting up liblzma (5.8.3) ...
(Reading database ... 4479 files and directories currently installed.)
Preparing to unpack .../xz-utils_5.8.3_aarch64.deb ...# Kai 9000

<img src="https://img.shields.io/badge/Platform-Web-f7df1c?logo=javascript" alt="Web"> <img src="https://img.shields.io/badge/Platform-Android-34a853.svg?logo=android" alt="Android" /> <img src="https://img.shields.io/badge/Platform-iOS-lightgrey.svg?logo=apple" alt="iOS" /> <img src="https://img.shields.io/badge/Platform-Windows/macOS/Linux-e10707.svg?logo=openjdk" alt="Platform JVM" />
<div align="center">

<br>
<img src="site/img/logo_animation.gif" height="80">
<br>
<br>

An **open-source AI assistant with persistent memory** that runs on **Android, iOS, Windows, Mac, Linux, and Web**.

**[Website](https://kai9000.com)** - **[Documentation](https://kai9000.com/docs/)**
</div>

<div align="center">
<br>

**Sponsor: [Atlas Cloud](https://www.atlascloud.ai)**

<a href="https://www.atlascloud.ai"><img src="https://www.atlascloud.ai/logo.svg" height="36" alt="Atlas Cloud"></a>


</div>

## Installation

[![App Store](https://raw.githubusercontent.com/SimonSchubert/Kai/main/screenshots/app_store_badge.png)](https://apps.apple.com/us/app/kai-ai/id6758148023)
[![Play Store](https://raw.githubusercontent.com/SimonSchubert/Kai/main/screenshots/play_store_badge.png)](https://play.google.com/store/apps/details?id=com.inspiredandroid.kai)
[![F-Droid](https://raw.githubusercontent.com/SimonSchubert/Kai/main/screenshots/fdroid_badge.png)](https://f-droid.org/en/packages/com.inspiredandroid.kai/)
[![Web](https://raw.githubusercontent.com/SimonSchubert/Kai/main/screenshots/web_badge.png)](https://kai9000.com/app/)

Homebrew (macOS):

```
brew install --cask simonschubert/tap/kai
```

AUR (Arch Linux):

```
yay -S kai-bin
```

Winget (Windows):

```
winget install SimonSchubert.Kai
```

### Direct Downloads

| Platform | Format | Download |
|----------|--------|----------|
| Android | APK | [GitHub Releases](https://github.com/SimonSchubert/Kai/releases) |
| macOS | DMG | [GitHub Releases](https://github.com/SimonSchubert/Kai/releases) |
| Windows | MSI | [GitHub Releases](https://github.com/SimonSchubert/Kai/releases) |
| Linux | DEB | [GitHub Releases](https://github.com/SimonSchubert/Kai/releases) |
| Linux | RPM | [GitHub Releases](https://github.com/SimonSchubert/Kai/releases) |
| Linux | AppImage | [GitHub Releases](https://github.com/SimonSchubert/Kai/releases) |

## AI That Builds Screens, Not Just Text

Kai 9000's Interactive UI lets the AI generate full interactive screens — quizzes, dashboards, recipes, brainstorms, and more. Navigate by tapping buttons instead of scrolling through chat.

<img src="screenshots/interactive-survival.png" alt="Survival Game" height="300"> <img src="screenshots/interactive-recipe.png" alt="Recipe Card" height="300"> <img src="screenshots/interactive-ecopulse.png" alt="EcoPulse Brainstorm" height="300"> <img src="screenshots/interactive-memories.png" alt="Memories" height="300">

## Features

- **Persistent memory** — Kai remembers important details across conversations and uses them automatically
- **Customizable soul** — Define the AI's personality and behavior with an editable system prompt
- **Multi-service fallback** — 24 LLM providers with automatic failover
- **On-device inference** — Run AI models locally on Android using LiteRT, no internet needed
- **Tool execution** — Web search, notifications, calendar events, shell commands, and more
- **MCP server support** — Connect to remote tool servers via the Model Context Protocol
- **Autonomous heartbeat** — Periodic self-checks that surface anything needing attention
- **Settings export/import** — Backup and restore all settings as a JSON file
- **Encrypted storage** — Conversations stored locally with encryption
- **Text to speech** — Listen to AI responses
- **Linux Sandbox** — On Android, the AI can run shell commands, scripts, and tools in a secure sandboxed Linux environment
- **Image attachments** — Attach images to any conversation

## Linux Sandbox (Android)

On Android, Kai includes a built-in Linux environment that the AI can use to execute shell commands, run scripts, and operate tools on your behalf. This turns Kai from a chat-only assistant into one that can take real action — installing packages, processing data, running Python scripts, and more.

- **Powered by Alpine Linux** — A lightweight ~3 MB download sets up a full Linux userland via [proot](https://proot-me.github.io/), no root required
- **Optional packages** — One tap installs bash, curl, wget, git, jq, python3, pip, and Node.js
- **Interactive terminal** — A built-in terminal lets you run commands manually alongside the AI
- **Secure** — Everything runs sandboxed inside the app with no access to the host system

Enable it in **Settings > Linux Sandbox**.

<img src="screenshots/mobile-7.png" alt="Linux Sandbox" height="300">

## Screenshots

### Desktop

<img src="screenshots/desktop-1.png" alt="Desktop App" height="300">

### Web

<img src="screenshots/web-1.png" alt="Web App" height="300">

### Mobile

<img src="screenshots/mobile-1.png" alt="Mobile Screenshot 1" height="300"> <img src="screenshots/mobile-2.png" alt="Mobile Screenshot 2" height="300"> <img src="screenshots/mobile-3.png" alt="Mobile Screenshot 3" height="300"> <img src="screenshots/mobile-4.png" alt="Mobile Screenshot 4" height="300"> <img src="screenshots/mobile-5.png" alt="Mobile Screenshot 5" height="300"> <img src="screenshots/mobile-6.png" alt="Mobile Screenshot 6" height="300">

## How It Works

```
                        ┌────────┐
                        │  User  │
                        └───┬────┘
                            │ message
                            ▼
               ┌─────────────────────────┐
               │          Chat           │
               │                         │
               │  prompt + memories      │
               │        │                │
               │        ▼                │
               │    ┌────────┐           │
               │    │   AI   │◀─┐        │
               │    └───┬────┘  │        │
               │        │   tool calls   │
               │        │   & results    │
               │        ▼      │        │
               │    ┌────────┐ │        │
               │    │ Tools  │─┘        │
               │    └───┬────┘          │
               │        │               │
               └────────┼───────────────┘
                        │ store / recall
                        ▼
               ┌─────────────────┐    hitCount >= 5
               │     Memory      │───────────────────┐
               │                 │                   │
               │  facts, prefs,  │                   ▼
               │  learnings      │          ┌────────────────┐
               │                 │◀─delete──│ Promote into   │
               └─────────────────┘          │ System Prompt  │
                        ▲                   └────────────────┘
                        │ reviews
                        │
               ┌─────────────────┐
               │    Heartbeat    │
               │                 │
               │  autonomous     │
               │  self-check     │
               │  every 30 min   │
               │  (8am–10pm)     │
               │                 │
               │  all good?      │
               │  → stays silent │
               │  needs action?  │
               │  → notifies user│
               └─────────────────┘
```

- **Chat** — User sends a message. The AI responds, calling tools (memory, web search, shell, etc.) in a loop until it has a final answer.
- **Memory** — The AI stores and recalls facts, preferences, and learnings. Memories that prove useful (5+ hits) can be promoted into the system prompt permanently.
- **Heartbeat** — A background self-check runs every 30 minutes. It reviews memories, pending tasks, and emails. If something needs attention, it notifies the user. Otherwise, it stays silent.

## Supported Services

**[Atlas Cloud](https://www.atlascloud.ai)** · [Anthropic](https://console.anthropic.com) · [OpenAI](https://openai.com) · [Gemini](https://aistudio.google.com) · [DeepSeek](https://www.deepseek.com) · [Mistral](https://mistral.ai) · [xAI](https://x.ai) · [OpenRouter](https://openrouter.ai) · [Groq](https://groq.com) · [NVIDIA](https://developer.nvidia.com) · [Cerebras](https://cerebras.ai) · [Ollama Cloud](https://ollama.com) · [LongCat](https://longcat.chat) · [Together AI](https://together.ai) · [Hugging Face](https://huggingface.co) · [Venice AI](https://venice.ai) · [Moonshot AI](https://moonshot.cn) · [Z.AI](https://z.ai) · [MiniMax](https://minimax.io) · [AIHubMix](https://aihubmix.com) · [Deep Infra](https://deepinfra.com) · [Fireworks AI](https://fireworks.ai) · [OpenCode](https://opencode.ai) · OpenAI-Compatible API · LiteRT On-Device (Android) · Free tier (no API key needed)

## MCP Servers

Kai supports the [Model Context Protocol](https://modelcontextprotocol.io/) for connecting to external tool servers. Go to **Settings > Tools > Add MCP Server** to connect to any Streamable HTTP MCP endpoint, or pick from a curated list of popular free servers:

| Server | Description |
|--------|-------------|
| Fetch | Fetch web content and convert HTML to markdown |
| DeepWiki | AI-powered docs for any GitHub repo |
| Sequential Thinking | Structured step-by-step problem-solving |
| Context7 | Up-to-date library and framework docs |
| Globalping | Ping, traceroute, DNS from global probes |
| CoinGecko | Real-time crypto prices and market data |
| Manifold Markets | Prediction market data and odds |
| Find-A-Domain | Domain availability across 1,444+ TLDs |

All popular servers are free and require no API key. MCP servers auto-reconnect on app startup.

## Integrations

### Splinterlands Auto-Battle (Android & Desktop)

Kai can automatically play [Splinterlands](https://splinterlands.com) Wild Ranked battles. Configure one or more LLM services in priority order, add your Hive account, and hit Start -- Kai will continuously find matches, pick teams using LLM-powered strategy, and submit them on-chain. Falls back to a simple greedy picker if all LLM services fail. Available in **Settings > Integrations**.

## Supported Languages

Afrikaans, Albanian, Amharic, Arabic, Belarusian, Bengali, Bulgarian, Chinese (Simplified), Chinese (Traditional), Croatian, Czech, Danish, Dutch, English, Estonian, Filipino, Finnish, French, German, Greek, Gujarati, Hebrew, Hindi, Hungarian, Indonesian, Italian, Japanese, Kazakh, Korean, Latvian, Lithuanian, Malay, Marathi, Norwegian, Persian, Polish, Portuguese, Punjabi, Romanian, Romansh, Russian, Serbian, Slovak, Slovenian, Spanish, Swahili, Swedish, Tamil, Telugu, Thai, Turkish, Ukrainian, Urdu, Vietnamese, Zulu

## Contributing

### Screenshot Automation

Two separate screenshot pipelines exist, both using Compose screenshot tests:

**README screenshots** — Used for this README. CI runs this automatically on every push and auto-commits any changes.

```bash
./gradlew :screenshotTests:updateScreenshots
```

**Store screenshots** — Generates localized screenshots for the Play Store in all supported locales. Upload via fastlane.

```bash
./gradlew :screenshotTests:generateStoreScreenshots
bundle exec fastlane android upload_screenshots
```

**Kai UI component screenshots** — Records golden images for `KaiUiScreenshotTest` only. Faster than recording the full suite when iterating on Kai UI components.

```bash
./gradlew :screenshotTests:recordKaiUiScreenshots
```

## Sponsors

This project is open-source and maintained by a single developer. If you find this app useful, please consider sponsoring to help take it to the next level with more features and faster updates.

## Credits

- Mistral: https://mistral.ai/
