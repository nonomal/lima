---
title: Experimental features
weight: 10
---


The following features are experimental and subject to change:

- `mountType: virtiofs` on Linux
- `vmType: wsl2` and relevant configurations (`mountType: wsl2`)
- `arch: riscv64`
- `video.display: vnc` and relevant configuration (`video.vnc.display`)
- `audio.device`
- `arch: armv7l`
- `mountInotify: true`
- `base:` and variations like `base[]:` and `base[].url`
- `provision[].file:` and alternative `provision[].file.url:`  
- `probes[].file:` and alternative `probes[].file.url:`

The following commands are experimental and subject to change:

- `limactl snapshot *`
- `limactl tunnel`
- `limactl template *`

## Graduated

The following features were experimental in the past:

### Until v1.0

- `mountType: 9p`
- `vmType: vz` and relevant configurations (`mountType: virtiofs`, `rosetta`, `[]networks.vzNAT`)
- `mode: user-v2` in `networks.yml` and relevant configuration in `lima.yaml`
