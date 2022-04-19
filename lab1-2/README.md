
# Labs 1 & 2 — Command Line Interface
## Assignment:

-   Go to the IoT [repository](https://github.com/kevinwlu/iot), Study Lessons 1 and 2
-   Open a terminal

```console
    $ hostname
    $ env
    $ ps
    $ pwd
    $ git clone https://github.com/kevinwlu/iot.git
    $ cd iot
    $ ls
    $ cd
    $ df
    $ mkdir demo
    $ cd demo
    $ nano file
    $ cat file
    $ cp file file1
    $ mv file file2
    $ rm file2
    $ clear
    $ man uname
    $ uname -a
    $ ifconfig
    $ ping localhost
    $ netstat
```

## Output from my Raspberry Pi:

    ![hostname](link)
```console
    SHELL=/bin/bash
    COLORTERM=truecolor
    XDG_CONFIG_DIRS=/etc/xdg
    XDG_MENU_PREFIX=lxde-pi-
    HOSTNAME=ctmpi
    LANGUAGE=en_US.UTF-8
    _LXSESSION_PID=1056
    SSH_AUTH_SOCK=/tmp/ssh-fC6q8Mqt5ZQJ/agent.1056
    XDG_CONFIG_HOME=/home/pi/.config
    DESKTOP_SESSION=LXDE-pi
    SSH_AGENT_PID=1104
    NO_AT_BRIDGE=1
    DISPLAYNUM=1
    PWD=/home/pi
    LOGNAME=pi
    QT_QPA_PLATFORMTHEME=qt5ct
    XDG_SESSION_TYPE=x11
    GPG_AGENT_INFO=/run/user/1000/gnupg/S.gpg-agent:0:1
    XAUTHORITY=/home/pi/.Xauthority
    HOME=/home/pi
    LANG=en_
    LS_COLORS=rs=0:di=01;34:ln=01;36:mh=00:pi=40;33:so=01;35:do=01;35:bd=40;33;01:cd=40;33;01:or=40;31;01:mi=00:su=37;41:sg=30;43:ca=30;41:tw=30;42:ow=34;42:st=37;44:ex=01;32:*.tar=01;31:*.tgz=01;31:*.arc=01;31:*.arj=01;31:*.taz=01;31:*.lha=01;31:*.lz4=01;31:*.lzh=01;31:*.lzma=01;31:*.tlz=01;31:*.txz=01;31:*.tzo=01;31:*.t7z=01;31:*.zip=01;31:*.z=01;31:*.dz=01;31:*.gz=01;31:*.lrz=01;31:*.lz=01;31:*.lzo=01;31:*.xz=01;31:*.zst=01;31:*.tzst=01;31:*.bz2=01;31:*.bz=01;31:*.tbz=01;31:*.tbz2=01;31:*.tz=01;31:*.deb=01;31:*.rpm=01;31:*.jar=01;31:*.war=01;31:*.ear=01;31:*.sar=01;31:*.rar=01;31:*.alz=01;31:*.ace=01;31:*.zoo=01;31:*.cpio=01;31:*.7z=01;31:*.rz=01;31:*.cab=01;31:*.wim=01;31:*.swm=01;31:*.dwm=01;31:*.esd=01;31:*.jpg=01;35:*.jpeg=01;35:*.mjpg=01;35:*.mjpeg=01;35:*.gif=01;35:*.bmp=01;35:*.pbm=01;35:*.pgm=01;35:*.ppm=01;35:*.tga=01;35:*.xbm=01;35:*.xpm=01;35:*.tif=01;35:*.tiff=01;35:*.png=01;35:*.svg=01;35:*.svgz=01;35:*.mng=01;35:*.pcx=01;35:*.mov=01;35:*.mpg=01;35:*.mpeg=01;35:*.m2v=01;35:*.mkv=01;35:*.webm=01;35:*.ogm=01;35:*.mp4=01;35:*.m4v=01;35:*.mp4v=01;35:*.vob=01;35:*.qt=01;35:*.nuv=01;35:*.wmv=01;35:*.asf=01;35:*.rm=01;35:*.rmvb=01;35:*.flc=01;35:*.avi=01;35:*.fli=01;35:*.flv=01;35:*.gl=01;35:*.dl=01;35:*.xcf=01;35:*.xwd=01;35:*.yuv=01;35:*.cgm=01;35:*.emf=01;35:*.ogv=01;35:*.ogx=01;35:*.aac=00;36:*.au=00;36:*.flac=00;36:*.m4a=00;36:*.mid=00;36:*.midi=00;36:*.mka=00;36:*.mp3=00;36:*.mpc=00;36:*.ogg=00;36:*.ra=00;36:*.wav=00;36:*.oga=00;36:*.opus=00;36:*.spx=00;36:*.xspf=00;36:
    XDG_CURRENT_DESKTOP=LXDE
    VNCDESKTOP=x11
    VTE_VERSION=5402
    SSH_CONNECTION=192.168.1.157 54832 192.168.1.215 22
    XDG_SESSION_CLASS=user
    TERM=xterm-256color
    USER=pi
    DISPLAY=:1.0
    SHLVL=2
    XDG_SESSION_ID=1
    XDG_RUNTIME_DIR=/run/user/1000
    SSH_CLIENT=192.168.1.157 54832 22
    LC_ALL=en_US.UTF-8
    XDG_DATA_DIRS=/usr/share/fkms:/usr/local/share:/usr/share/raspi-ui-overrides:/usr/share:/usr/share/gdm:/var/lib/menu-xdg
    PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/local/games:/usr/games
    SAL_USE_VCLPLUGIN=gtk3
    DBUS_SESSION_BUS_ADDRESS=unix:path=/run/user/1000/session-fe0cfe605bd044fd/bus
    MAIL=/var/mail/pi
    SSH_TTY=/dev/pts/0
    PULSE_SERVER=/run/user/1000/session-fe0cfe605bd044fd/pulse/native
    TEXTDOMAIN=Linux-PAM
    _=/usr/bin/env
    OLDPWD=/home/pi/iot/lesson1
```
![photo](link1)

![photo](link2)

   **pi@ctmpi:~/iot $** netstat
```console
    Active Internet connections (w/o servers)
    Proto Recv-Q Send-Q Local Address               Foreign Address             State          
    tcp            0          0 raspberrypi:ssh             DESKTOP-9MK9DVQ:54832   ESTABLISHED
    tcp            0          0 raspberrypi:5901            DESKTOP-9MK9DVQ:54861   ESTABLISHED
    tcp            0          0 localhost:39905             localhost:38714             ESTABLISHED
    tcp            0          0 raspberrypi:59608           HPD8AF8B:ipp                CLOSE_WAIT
    tcp            0          0 localhost:38714             localhost:39905             ESTABLISHED
    Active UNIX domain sockets (w/o servers)
    Proto RefCnt Flags           Type           State             I-Node   Path
    unix  2          [ ]             DGRAM                        19211        /run/user/1000/systemd/notify
    unix  3          [ ]             DGRAM                        9178         /run/systemd/notify
    unix  2          [ ]             DGRAM                        9187         /run/systemd/journal/syslog
    unix  18         [ ]             DGRAM                        9194         /run/systemd/journal/dev-log
    unix  7          [ ]             DGRAM                        9201         /run/systemd/journal/socket
    unix  4          [ ]             DGRAM                        16633        /var/run/wpa_supplicant/wlan0
    unix  2          [ ]             DGRAM                        15264        /var/run/wpa_supplicant/p2p-dev-wlan0
    unix  2          [ ]             DGRAM                        21067        /tmp/dhcpcd-pi/libdhcpcd-wpa-1138.0
    unix  2          [ ]             DGRAM                        21068        /tmp/dhcpcd-pi/libdhcpcd-wpa-1138.1
    unix  2          [ ]             DGRAM                        18127        /tmp/.vncserver-license/0.605
    unix  2          [ ]             DGRAM                        20776        /tmp/.vncserver-license/1000.1024
    unix  3          [ ]             STREAM         CONNECTED         25184        /run/user/1000/session-fe0cfe605bd044fd/bus
    unix  3          [ ]             STREAM         CONNECTED         19334    
    unix  3          [ ]             STREAM         CONNECTED         27882    
    unix  3          [ ]             STREAM         CONNECTED         25501        /run/user/1000/session-fe0cfe605bd044fd/bus
    unix  3          [ ]             STREAM         CONNECTED         19357        /tmp/.X11-unix/X1
    unix  3          [ ]             STREAM         CONNECTED         15401    
    unix  3          [ ]             STREAM         CONNECTED         19398        /run/user/1000/session-fe0cfe605bd044fd/bus
    unix  3          [ ]             STREAM         CONNECTED         22023        /tmp/.X11-unix/X1
    unix  3          [ ]             STREAM         CONNECTED         22629    
    unix  3          [ ]             STREAM         CONNECTED         24262    
    unix  3          [ ]             STREAM         CONNECTED         19356    
    unix  3          [ ]             STREAM         CONNECTED         19397    
    unix  3          [ ]             DGRAM                        9180         
    unix  3          [ ]             STREAM         CONNECTED         25179        /tmp/.X11-unix/X1
    unix  3          [ ]             DGRAM                        9179         
    unix  3          [ ]             STREAM         CONNECTED         24267    
    unix  3          [ ]             STREAM         CONNECTED         19333    
    unix  2          [ ]             STREAM         CONNECTED         19270    
    unix  3          [ ]             STREAM         CONNECTED         22050    
    unix  3          [ ]             STREAM         CONNECTED         15407        /run/systemd/journal/stdout
    unix  3          [ ]             STREAM         CONNECTED         21940    
    unix  3          [ ]             STREAM         CONNECTED         23667    
    unix  3          [ ]             STREAM         CONNECTED         20698    
    unix  3          [ ]             STREAM         CONNECTED         15684        /var/run/dbus/system_bus_socket
    unix  3          [ ]             STREAM         CONNECTED         20697    
    unix  3          [ ]             STREAM         CONNECTED         22038    
    unix  3          [ ]             STREAM         CONNECTED         15518        /run/systemd/journal/stdout
    unix  3          [ ]             STREAM         CONNECTED         20766    
    unix  2          [ ]             DGRAM                        15670    
    unix  3          [ ]             STREAM         CONNECTED         12887    
    unix  3          [ ]             STREAM         CONNECTED         20987        /var/run/dbus/system_bus_socket
    unix  3          [ ]             STREAM         CONNECTED         20981        /run/user/1000/session-fe0cfe605bd044fd/bus
    unix  3          [ ]             STREAM         CONNECTED         12758    
    unix  2          [ ]             DGRAM                        17749    
    unix  3          [ ]             STREAM         CONNECTED         17504    
    unix  3          [ ]             STREAM         CONNECTED         23647    
    unix  3          [ ]             STREAM         CONNECTED         17491    
    unix  3          [ ]             STREAM         CONNECTED         15681        /var/run/dbus/system_bus_socket
    unix  3          [ ]             STREAM         CONNECTED         21060        /var/run/dbus/system_bus_socket
    unix  3          [ ]             STREAM         CONNECTED         21947        /tmp/.X11-unix/X1
    unix  2          [ ]             DGRAM                        20548    
    unix  3          [ ]             STREAM         CONNECTED         22646    
    unix  3          [ ]             STREAM         CONNECTED         22046    
    unix  3          [ ]             STREAM         CONNECTED         20765    
    unix  3          [ ]             STREAM         CONNECTED         15676    
    unix  3          [ ]             STREAM         CONNECTED         17751    
    unix  3          [ ]             STREAM         CONNECTED         20809    
    unix  3          [ ]             STREAM         CONNECTED         15677        /var/run/dbus/system_bus_socket
    unix  3          [ ]             STREAM         CONNECTED         21939    
    unix  3          [ ]             STREAM         CONNECTED         19303        /run/systemd/journal/stdout
    unix  3          [ ]             STREAM         CONNECTED         18397    
    unix  3          [ ]             STREAM         CONNECTED         15680    
    unix  2          [ ]             DGRAM                        13247    
    unix  3          [ ]             STREAM         CONNECTED         22666    
    unix  2          [ ]             DGRAM                        15586    
    unix  3          [ ]             STREAM         CONNECTED         20535    
    unix  3          [ ]             STREAM         CONNECTED         14312        /run/systemd/journal/stdout
    unix  3          [ ]             STREAM         CONNECTED         23668        /run/user/1000/session-fe0cfe605bd044fd/bus
    unix  3          [ ]             STREAM         CONNECTED         19389        /run/user/1000/session-fe0cfe605bd044fd/bus
    unix  2          [ ]             DGRAM                        6902         
    unix  3          [ ]             STREAM         CONNECTED         23673    
    unix  3          [ ]             STREAM         CONNECTED         19388        /tmp/.X11-unix/X1
    unix  3          [ ]             STREAM         CONNECTED         16375        /run/systemd/journal/stdout
    unix  3          [ ]             STREAM         CONNECTED         12760        /run/systemd/journal/stdout
    unix  3          [ ]             STREAM         CONNECTED         20829    
    unix  3          [ ]             STREAM         CONNECTED         15602    
    unix  3          [ ]             STREAM         CONNECTED         13023    
    unix  3          [ ]             STREAM         CONNECTED         23565        /tmp/.X11-unix/X1
    unix  3          [ ]             STREAM         CONNECTED         18856        /var/run/dbus/system_bus_socket
    unix  2          [ ]             STREAM         CONNECTED         15675    
    unix  2          [ ]             DGRAM                        12891    
    unix  3          [ ]             STREAM         CONNECTED         17745    
    unix  3          [ ]             STREAM         CONNECTED         23672    
    unix  3          [ ]             STREAM         CONNECTED         16768        /var/run/dbus/system_bus_socket
    unix  3          [ ]             STREAM         CONNECTED         22072        /run/user/1000/menu-cached-:1
    unix  3          [ ]             STREAM         CONNECTED         22043    
    unix  2          [ ]             STREAM         CONNECTED         16372    
    unix  3          [ ]             STREAM         CONNECTED         20999        /run/user/1000/session-fe0cfe605bd044fd/bus
    unix  3          [ ]             STREAM         CONNECTED         22662    
    unix  3          [ ]             STREAM         CONNECTED         20283    
    unix  3          [ ]             STREAM         CONNECTED         15603    
    unix  3          [ ]             STREAM         CONNECTED         21946    
    unix  3          [ ]             STREAM         CONNECTED         23666    
    unix  2          [ ]             DGRAM                        22018    
    unix  3          [ ]             STREAM         CONNECTED         20828    
    unix  3          [ ]             STREAM         CONNECTED         15671        /var/run/dbus/system_bus_socket
    unix  3          [ ]             STREAM         CONNECTED         20808    
    unix  3          [ ]             STREAM         CONNECTED         15281        /run/systemd/journal/stdout
    unix  2          [ ]             DGRAM                        15495    
    unix  3          [ ]             STREAM         CONNECTED         23612        /run/user/1000/session-fe0cfe605bd044fd/bus
    unix  3          [ ]             STREAM         CONNECTED         21008    
    unix  3          [ ]             STREAM         CONNECTED         11245    
    unix  3          [ ]             STREAM         CONNECTED         17059    
    unix  3          [ ]             STREAM         CONNECTED         15682        /var/run/dbus/system_bus_socket
    unix  2          [ ]             DGRAM                        11105    
    unix  3          [ ]             STREAM         CONNECTED         23602        /run/user/1000/session-fe0cfe605bd044fd/bus
    unix  3          [ ]             STREAM         CONNECTED         11246        /run/systemd/journal/stdout
    unix  3          [ ]             STREAM         CONNECTED         23618    
    unix  3          [ ]             STREAM         CONNECTED         21005    
    unix  3          [ ]             STREAM         CONNECTED         22022        /tmp/.X11-unix/X1
    unix  3          [ ]             STREAM         CONNECTED         11177    
    unix  3          [ ]             STREAM         CONNECTED         23607        /run/user/1000/session-fe0cfe605bd044fd/bus
    unix  3          [ ]             STREAM         CONNECTED         22067        @/dbus-vfs-daemon/socket-TXOmOTjI
    unix  3          [ ]             STREAM         CONNECTED         18586        /run/systemd/journal/stdout
    unix  3          [ ]             STREAM         CONNECTED         14933        /run/systemd/journal/stdout
    unix  3          [ ]             STREAM         CONNECTED         11107    
    unix  3          [ ]             STREAM         CONNECTED         11091    
    unix  3          [ ]             STREAM         CONNECTED         21021    
    unix  3          [ ]             STREAM         CONNECTED         20968    
    unix  3          [ ]             STREAM         CONNECTED         16597    
    unix  3          [ ]             STREAM         CONNECTED         11090    
    unix  3          [ ]             STREAM         CONNECTED         23555        /tmp/.X11-unix/X1
    unix  2          [ ]             DGRAM                        11089    
    unix  3          [ ]             STREAM         CONNECTED         21002    
    unix  3          [ ]             STREAM         CONNECTED         20469    
    unix  3          [ ]             STREAM         CONNECTED         21009        /var/run/dbus/system_bus_socket
    unix  3          [ ]             STREAM         CONNECTED         20990    
    unix  2          [ ]             STREAM         CONNECTED         23850    
    unix  3          [ ]             STREAM         CONNECTED         15410        /run/systemd/journal/stdout
    unix  3          [ ]             STREAM         CONNECTED         15661        /var/run/dbus/system_bus_socket
    unix  3          [ ]             STREAM         CONNECTED         22030        /run/user/1000/session-fe0cfe605bd044fd/bus
    unix  3          [ ]             STREAM         CONNECTED         11075    
    unix  3          [ ]             STREAM         CONNECTED         15606        /var/run/dbus/system_bus_socket
    unix  3          [ ]             STREAM         CONNECTED         23628        /run/user/1000/session-fe0cfe605bd044fd/pulse/native
    unix  3          [ ]             STREAM         CONNECTED         11098    
    unix  3          [ ]             STREAM         CONNECTED         14944        /run/systemd/journal/stdout
    unix  3          [ ]             STREAM         CONNECTED         20991        /run/user/1000/session-fe0cfe605bd044fd/bus
    unix  3          [ ]             STREAM         CONNECTED         16625    
    unix  3          [ ]             STREAM         CONNECTED         23554    
    unix  3          [ ]             DGRAM                        19212    
    unix  3          [ ]             STREAM         CONNECTED         22688        /var/run/dhcpcd.unpriv.sock
    unix  3          [ ]             STREAM         CONNECTED         15012    
    unix  3          [ ]             DGRAM                        10683    
    unix  3          [ ]             DGRAM                        20841    
    unix  2          [ ]             DGRAM                        14945    
    unix  3          [ ]             STREAM         CONNECTED         22007        /tmp/.X11-unix/X1
    unix  2          [ ]             DGRAM                        10680    
    unix  3          [ ]             STREAM         CONNECTED         21064    
    unix  3          [ ]             STREAM         CONNECTED         21063    
    unix  2          [ ]             DGRAM                        15148    
    unix  3          [ ]             STREAM         CONNECTED         10677    
    unix  3          [ ]             STREAM         CONNECTED         20934    
    unix  3          [ ]             STREAM         CONNECTED         19193    
    unix  2          [ ]             STREAM         CONNECTED         18130    
    unix  3          [ ]             STREAM         CONNECTED         15604        /var/run/dbus/system_bus_socket
    unix  3          [ ]             STREAM         CONNECTED         9781         /run/systemd/journal/stdout
    unix  3          [ ]             STREAM         CONNECTED         19332        /run/user/1000/session-fe0cfe605bd044fd/bus
    unix  3          [ ]             STREAM         CONNECTED         22689        /var/run/dhcpcd.unpriv.sock
    unix  3          [ ]             STREAM         CONNECTED         15254    
    unix  3          [ ]             DGRAM                        14280    
    unix  2          [ ]             STREAM         CONNECTED         20081    
    unix  3          [ ]             STREAM         CONNECTED         20885    
    unix  2          [ ]             DGRAM                        19200    
    unix  3          [ ]             STREAM         CONNECTED         19215    
    unix  3          [ ]             STREAM         CONNECTED         14300    
    unix  2          [ ]             DGRAM                        21191    
    unix  3          [ ]             STREAM         CONNECTED         20121        /var/run/dbus/system_bus_socket
    unix  2          [ ]             DGRAM                        20102    
    unix  3          [ ]             STREAM         CONNECTED         15015        /run/systemd/journal/stdout
    unix  2          [ ]             DGRAM                        19203    
    unix  3          [ ]             STREAM         CONNECTED         20924    
    unix  3          [ ]             STREAM         CONNECTED         19413        /run/user/1000/session-fe0cfe605bd044fd/bus
    unix  3          [ ]             STREAM         CONNECTED         14839    
    unix  3          [ ]             DGRAM                        10684    
    unix  3          [ ]             STREAM         CONNECTED         20884    
    unix  2          [ ]             DGRAM                        18125    
    unix  3          [ ]             STREAM         CONNECTED         15605        /var/run/dbus/system_bus_socket
    unix  2          [ ]             DGRAM                        9726         
    unix  3          [ ]             STREAM         CONNECTED         22633    
    unix  3          [ ]             STREAM         CONNECTED         15030    
    unix  3          [ ]             STREAM         CONNECTED         20925    
    unix  3          [ ]             STREAM         CONNECTED         15607        /var/run/dbus/system_bus_socket
    unix  3          [ ]             STREAM         CONNECTED         20539        /var/run/dbus/system_bus_socket
    unix  2          [ ]             DGRAM                        15133    
    unix  3          [ ]             STREAM         CONNECTED         20935        /var/run/dbus/system_bus_socket
    unix  3          [ ]             STREAM         CONNECTED         20679        /run/systemd/journal/stdout
    unix  3          [ ]             STREAM         CONNECTED         22008        /run/user/1000/session-fe0cfe605bd044fd/bus
    unix  3          [ ]             DGRAM                        14278    
    unix  3          [ ]             STREAM         CONNECTED         18064    
    unix  3          [ ]             STREAM         CONNECTED         16097        /run/systemd/journal/stdout
    unix  3          [ ]             STREAM         CONNECTED         10980    
    unix  3          [ ]             STREAM         CONNECTED         15141    
    unix  3          [ ]             STREAM         CONNECTED         15123    
    unix  3          [ ]             STREAM         CONNECTED         22031        /run/user/1000/session-fe0cfe605bd044fd/bus
    unix  3          [ ]             STREAM         CONNECTED         16517        /run/systemd/journal/stdout
    unix  3          [ ]             DGRAM                        14279    
    unix  3          [ ]             DGRAM                        14281    
    unix  3          [ ]             STREAM         CONNECTED         22025        /tmp/.X11-unix/X1
    unix  3          [ ]             STREAM         CONNECTED         18862    
    unix  3          [ ]             STREAM         CONNECTED         20900    
    unix  3          [ ]             STREAM         CONNECTED         23617        /run/user/1000/session-fe0cfe605bd044fd/bus
    unix  3          [ ]             STREAM         CONNECTED         15633        /var/run/dbus/system_bus_socket
    unix  3          [ ]             STREAM         CONNECTED         14258        /run/systemd/journal/stdout
    unix  2          [ ]             DGRAM                        14276    
    unix  3          [ ]             STREAM         CONNECTED         19387        /tmp/.X11-unix/X1
    unix  3          [ ]             STREAM         CONNECTED         20897    
    unix  3          [ ]             DGRAM                        19213    
    unix  3          [ ]             STREAM         CONNECTED         15689        /var/run/dbus/system_bus_socket
    unix  3          [ ]             DGRAM                        20842    
    unix  2          [ ]             DGRAM                        22767    
    unix  3          [ ]             STREAM         CONNECTED         20349
```
