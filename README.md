# Homelab and Hardware Documentation

Documentation for my home IT lab: a repurposed server running Proxmox, a custom-built PC, two Raspberry Pis, and backup storage. Each project has its own write-up covering the specs, why I made each choice, what broke, and how I fixed it. Documented October 2026.

## Projects

| Project | What it covers |
|---|---|
| [Proxmox homelab server](server/README.md) | An HP EliteDesk 800 G1 TWR (i5-4590, 16GB RAM) turned into a Proxmox VE virtualization host. Includes BIOS setup, drive health checks, and a failed 4TB drive that I retired. |
| [Windows Server Active Directory lab](windows-server-ad/README.md) | A Windows Server 2025 domain controller and a Windows 11 client running as VMs. Includes an OU and group structure, delegated password resets, a Group Policy, and a domain-join failure caused by missing DNS records. |
| [Help desk (GLPI)](help-desk/README.md) | A GLPI 12 help desk on Ubuntu Server with tickets for my build problems, an asset inventory, runbooks, an SLA, and a hardened install. |
| [File server](file-server/README.md) | File shares on the Windows Server 2025 domain controller, with access controlled by Active Directory groups (Staff, Help-Desk, IT-Admins). Includes both share and NTFS permissions, tests from a client as each role, and a note that running it on the domain controller is a deliberate lab shortcut. |
| [Custom-built PC](custom-pc/README.md) | A Ryzen 7 7800X3D gaming PC that is also my admin workstation. Includes my reasons for each part and an incompatible motherboard I returned. |
| [Raspberry Pi 4 and Pi Zero 2 W](raspberry-pi/README.md) | Two Pis that support the lab, with their specs, operating systems, network addresses, and idle temperatures. |
| [Backup storage](backup-storage/README.md) | Two external drives holding my media, copied and verified after the server's 4TB drive failed. |

## Status

This is a work in progress. The hardware is documented, the Windows Server Active Directory lab is built and written up, Help Desk (GLPI) is set up and tested, and the file server is built and tested from a client as each role. The other lab projects I have planned, such as endpoint management, firewalling, and monitoring, are not built yet, so they aren't listed here.

## How I document

Every project gets a README with the specs, the reasons behind each choice, and the problems I hit. Serial numbers, hardware addresses, and labels are covered in the images. IP addresses are private (home network) addresses.
