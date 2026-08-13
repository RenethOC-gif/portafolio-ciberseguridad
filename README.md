# Portafolio de Ciberseguridad — René Ochoa

Especialista en Ciberseguridad, en formación hacia certificación en pentesting. Este repositorio contiene writeups documentados de máquinas resueltas en **TryHackMe** y en laboratorios de la certificación **PMJ (Hacker Mentor)**, cubriendo reconocimiento, explotación, escalada de privilegios y post-explotación.

📄 Actualmente en proceso de máster en Ciberseguridad en España.

## Habilidades técnicas

- **Reconocimiento:** Nmap, Gobuster, enumeración de servicios (SMB, FTP, HTTP, RPC)
- **Explotación web:** Drupalgeddon2, File Upload, RCE vía Jenkins Script Console, HFS RCE (CVE-2014-6287)
- **Post-explotación:** Metasploit / Meterpreter, pivoting (autoroute), token impersonation (Incognito)
- **Escalada de privilegios (Linux):** binarios SUID (GTFOBins), LinPEAS
- **Escalada de privilegios (Windows):** unquoted service paths, WinPEAS, PowerUp.ps1
- **Cracking de credenciales:** Hydra, John the Ripper, CrackStation
- **Persistencia:** SSH authorized_keys

## Writeups

| Máquina | Plataforma | SO | Técnica principal |
|---|---|---|---|
| [Alfred](writeups/alfred.md) | TryHackMe | Windows | Jenkins RCE + Token Impersonation |
| [Steel Mountain](writeups/steel-mountain.md) | TryHackMe | Windows | Rejetto HFS RCE (CVE-2014-6287) + Service Hijacking |
| [Mr. Robot](writeups/mr-robot.md) | TryHackMe | Linux | WordPress Bruteforce + SUID (nmap) |
| [Vulnuversity](writeups/vulnuversity.md) | TryHackMe | Linux | File Upload + SUID (systemctl) |
| [Pivot](writeups/pivot.md) | Academia (Hacker Mentor) | Linux | Drupalgeddon2 + Pivoting |

## Aviso

Todo el contenido de este repositorio es **exclusivamente para fines educativos**, realizado en entornos de laboratorio controlados y autorizados (TryHackMe, laboratorios de academia). No se incluye información sensible real ni se promueve el uso de estas técnicas contra sistemas sin autorización.

## Contacto

René Ochoa — Especialista en Ciberseguridad
