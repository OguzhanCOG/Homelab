# Homelab Specifications

Thank you for checking out my specifications.

There are always updates to my configuration to meet my needs, but this is a fairly general overview.

## Dell PowerEdge

### R Series:

- **740: 2x Xeon Platinum 8160, 1536GB, 200TB.**  \
GAN Training, LLM Training, Model Architecture Playground, Ollama Host. Raspberry Pi Zero 2 W embedded in the chassis, as a QDevice/quorum controller.

- **720: 2x Xeon E5-2667 v2, 128GB, 40TB.**  \
Main Windows VM, Minecraft Servers, Model Inference, Ubuntu Docker VM.

- 610 (Rev. II): 2x Xeon L5620, 64GB, 4TB.**  \
macOS VM(s), QEMU, PPC VM(s), pfSense, Plex in Debian VM.
  
- **210 II: Xeon E3-1220L, 8GB, 500GB.**  \
pfSense.

### T Series:

- **320: Xeon E5-2470 v2, 32GB, 2TB.**  \
Exception: VMware ESXi host instead; General computing.

## Hewlett-Packard Enterprise, ProLiant

### DL Series:

- **360 (G9): 2x Xeon E5-2620 v3, 128GB, 10TB.**  \
Pool with the rest of the servers + additional storage + failsafe (NFS shares attached + HA grouped VMs).

## Miscellaneous Information

Clustered homelab. With Ceph & ZFS. 3x UniFi Standard 24's and an old APC UPS.
