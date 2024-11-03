# System Configuration Report

## CPU Information
- **Architecture**: x86_64
- **CPU op-mode(s)**: 32-bit, 64-bit
- **Byte Order**: Little Endian
- **CPU(s)**: 12
- **On-line CPU(s) list**: 0-11
- **Thread(s) per core**: 2
- **Core(s) per socket**: 6
- **Socket(s)**: 1
- **NUMA node(s)**: 1
- **Vendor ID**: GenuineIntel
- **CPU family**: 6
- **Model**: 79
- **Model name**: Intel(R) Core(TM) i7-6850K CPU @ 3.60GHz
- **Stepping**: 1
- **CPU MHz**: 1716.609
- **CPU max MHz**: 4000.0000
- **CPU min MHz**: 1200.0000
- **BogoMIPS**: 7195.83
- **Virtualization**: VT-x
- **L1d cache**: 32K
- **L1i cache**: 32K
- **L2 cache**: 256K
- **L3 cache**: 15360K
- **NUMA node0 CPU(s)**: 0-11
- **Flags**:
  - fpu, vme, de, pse, tsc, msr, pae, mce, cx8, apic, sep, mtrr, pge, mca, cmov, pat, pse36, clflush, dts, acpi, mmx, fxsr, sse, sse2, ss, ht, tm, pbe, syscall, nx, pdpe1gb, rdtscp, lm, constant_tsc, arch_perfmon, pebs, bts, rep_good, nopl, xtopology, nonstop_tsc, aperfmperf, pni, pclmulqdq, dtes64, ds_cpl, vmx, est, tm2, ssse3, sdbg, fma, cx16, xtpr, pdcm, pcid, dca, sse4_1, sse4_2, x2apic, movbe, popcnt, tsc_deadline_timer, aes, xsave, avx, f16c, rdrand, lahf_lm, abm, 3dnowprefetch, epb, invpcid_single, intel_pt, ssbd, ibrs, ibpb, stibp, kaiser, tpr_shadow, vnmi, flexpriority, ept, vpid, fsgsbase, tsc_adjust, bmi1, hle, avx2, smep, bmi2, erms, invpcid, rtm, cqm, rdseed, adx, smap, xsaveopt, cqm_llc, cqm_occup_llc, cqm_mbm_total, cqm_mbm_local, dtherm, ida, arat, pln, pts, md_clear, flush_l1d

## GPU Information
### Overview
- **Driver Version**: 530.30.02
- **CUDA Version**: 12.1

### GPU Configuration
| GPU | Name                   | Bus-Id         | Temp | Perf | Pwr:Usage/Cap | Memory-Usage   | GPU-Util | Compute M. |
|-----|------------------------|----------------|------|------|---------------|----------------|----------|------------|
| 0   | NVIDIA GeForce GTX 1080 Ti | 00000000:05:00.0 | 41C  | P8   | 21W / 250W    | 2MiB / 11264MiB | 0%       | Default    |
| 1   | NVIDIA GeForce GTX 1080 Ti | 00000000:06:00.0 | 40C  | P8   | 14W / 250W    | 2MiB / 11264MiB | 0%       | Default    |
| 2   | NVIDIA GeForce GTX 1080 Ti | 00000000:09:00.0 | 41C  | P8   | 14W / 250W    | 2MiB / 11264MiB | 0%       | Default    |
| 3   | NVIDIA GeForce GTX 1080 Ti | 00000000:0A:00.0 | 35C  | P8   | 12W / 250W    | 2MiB / 11264MiB | 0%       | Default    |

### Processes
- **No running processes found**

## Memory Information
- **Total**: 62 GB
- **Used**: 2.6 GB
- **Free**: 12 GB
- **Shared**: 637 MB
- **Buff/cache**: 48 GB
- **Available**: 55 GB

## Swap Information
- **Total**: 1.0 GB
- **Used**: 33 MB
- **Free**: 1.0 GB

## Disk Space
| Filesystem      | Size | Used  | Avail | Use% | Mounted on     |
|-----------------|------|-------|-------|------|-----------------|
| none            | 3.6T | 3.4T  | 101G  | 98%  | /               |
| tmpfs           | 64M  | 0     | 64M   | 0%   | /dev            |
| tmpfs           | 32G  | 0     | 32G   | 0%   | /sys/fs/cgroup  |
| tmpfs           | 32G  | 4.1M  | 32G   | 1%   | /dev/shm        |
| /dev/sdc1       | 5.5T | 1.3T  | 3.9T  | 25%  | /opt/data3      |
| /dev/sda1       | 3.6T | 3.4T  | 101G  | 98%  | /opt/work       |
| /dev/nvme0n1p2  | 457G | 361G  | 77G   | 83%  | /opt/vdt        |
| /dev/sdb1       | 1.9T | 1017G | 847G  | 55%  | /opt/data       |
| tmpfs           | 32G  | 0     | 32G   | 0%   | /proc/asound    |
| tmpfs           | 32G  | 0     | 32G   | 0%   | /proc/acpi      |
| tmpfs           | 32G  | 0     | 32G   | 0%   | /proc/scsi      |
| tmpfs           | 32G  | 0     | 32G   | 0%   | /sys/firmware   |

## Python Version
- **Python**: 3.9.4

## Python Package Requirements
To install all the packages, run:
`pip install -r requirements.txt`
