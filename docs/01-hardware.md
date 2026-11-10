# 01 Hardware

## Host-PC
| Komponente | Wert |
|---|---|
| Prozessor | Intel Core i7-10700 (8 Kerne, 16 Threads) |
| RAM | 16 GB |
| Speicher für VMs | (Laufwerk, SSD/HDD, freier Platz) |
| Betriebssystem | Windows 11 Home |
| Virtualisierung | im BIOS aktiviert |

## Entscheidung Hypervisor
VirtualBox, weil Windows Home kein Hyper-V enthält.

## Geplante VM-Aufteilung
| VM | RAM | CPU-Kerne | Festplatte |
|---|---|---|---|
| fw01 (OPNsense) | 2 GB | 1 | 20 GB |
| srv-dc01 (Windows Server 2022) | 3 GB | 2 | 60 GB |
| client01 (Windows 11) | 4 GB | 2 | 60 GB |
| srv-lin01 (Debian) | 1 GB | 1 | 20 GB |
