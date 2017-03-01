# LPCI

Fragen zu Quotas

Sie haben Quotas auf den Festplatten eines Systems eingerichtet. Ein Benutzer fragt Sie, wie er herausbekommen kann, wie viel Speicherplatz für ihn auf der Festplatte zur Verfügung steht. Welches Programm werden Sie dem Benutzer empfehlen? 

- edquota
- repquota
- quota
- df
- quotaon

## df 

Diehnt ausschließlich zur ermittlung des freien Speicherplatzes


# LPCI
Stupid Questions

Sie müssen einem Server eine Shellvariable hinzufügen. Diese Variable soll für alle Benutzer in jeder neu geöffneten Shell gültig sein, darf aber keine Neuanmeldung der Benutzer erfordern. In welcher der folgenden Konfigurationsdateien können Sie die neue Variable eintragen? 

- bashrc
- .profile
- .bashrc
- .bash_logout
- .bash_profile


# LPCI
Fragen zu Systemd

Sie arbeiten an einem Computer, der systemd zur Initialisierung verwendet. Welches der folgenden Kommandos ist geeignet, das System herunterzufahren?


- systemctl isolate runlevel3.target
- systemctl isolate reboot.target
- systemctl isolate poweroff.target
- sysctl isolate reboot.target
- sysctl isolate poweroff.target

## systemctl

Mit Hilfe von systemctl können Befehle an systemd gesendet werden, z.B. zum Steuern von Units, zum Abfragen des Status, zum Herunterfahren des Systems etc. 
https://wiki.ubuntuusers.de/systemd/systemctl/

## sysctl

sysctl is used to modify kernel parameters at runtime. The parameters available are those listed under /proc/sys/.


# LPCI
Stupid Questions

Welcher der folgenden Treiber (Kernelmodule) unterstützt die Verwendung von USB 2.0 Geräten? 

- usb-uhci.o
- usb-ohci.o
- usb-ehci.o
- usb_storage.o


# LPCI
Stupid Questions

Sie wollen herausbekommen, von welchen Bibliotheken (Librarys) die Shell bash abhängt. Welches Kommando wird Ihnen hier helfen? 

- ldconfig /bin/bash
- ldd /var/bash
- cat ld.so.conf
- ldd /bin/bash
- cat ld.so.cache

# LPCI
Stupid Questions

Sie wollen herausbekommen, von welchen Bibliotheken (Librarys) die Shell bash abhängt. Welches Kommando wird Ihnen hier helfen? 

- ldconfig /bin/bash
- ldd /var/bash
- cat ld.so.conf
- ldd /bin/bash
- cat ld.so.cache
