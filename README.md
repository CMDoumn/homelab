# Homelab and Hardware Documentation

Documentation for my home IT lab: a repurposed server running Proxmox, a custom-built PC, two Raspberry Pis, and backup storage. Each project has its own write-up covering the specs, why I made each choice, what broke, and how I fixed it. Documented October 2026.

## Projects

| Project | What it covers |
|---|---|
| [Proxmox homelab server](server/README.md) | An HP EliteDesk 800 G1 TWR (i5-4590, 16GB RAM) turned into a Proxmox VE virtualization host. Includes BIOS setup, drive health checks, and a failed 4TB drive that I retired. |
| [Custom-built PC](custom-pc/README.md) | A Ryzen 7 7800X3D gaming PC that is also my admin workstation. Includes my reasons for each part and an incompatible motherboard I returned. |
| [Raspberry Pi 4 and Pi Zero 2 W](raspberry-pi/README.md) | Two Pis that support the lab. The Pi 4 is documented. The Zero 2 W's software details are still to come. |
| [Backup storage](backup-storage/README.md) | Two external drives holding my media, copied and verified after the server's 4TB drive failed. |

## Status

This is a work in progress. The hardware is documented. The lab projects that run on the server, such as Active Directory, a help desk, firewalling, and monitoring, are planned and not built yet, so they aren't listed here.

## How I document

Every project gets a README with the specs, the reasons behind each choice, and the problems I hit. Serial numbers, hardware addresses, and labels are covered in the images. IP addresses are private (home network) addresses.
