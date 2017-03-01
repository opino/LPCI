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

