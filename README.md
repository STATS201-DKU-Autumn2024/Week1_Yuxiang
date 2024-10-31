# Week2_Yuxiang

### System Configuration Report

**CPU Information:**
- **Architecture:** x86_64
- **CPU op-mode(s):** 32-bit, 64-bit
- **Byte Order:** Little Endian
- **Address sizes:** 42 bits physical, 48 bits virtual
- **CPU(s):** 76
- **On-line CPU(s) list:** 0-75
- **Thread(s) per core:** 1
- **Core(s) per socket:** 1
- **Socket(s):** 76
- **NUMA node(s):** 1
- **Vendor ID:** GenuineIntel
- **CPU family:** 6
- **Model:** 85
- **Model name:** Intel(R) Xeon(R) Gold 6252 CPU @ 2.10GHz
- **Stepping:** 7
- **CPU MHz:** 2099.999
- **BogoMIPS:** 4199.99
- **Hypervisor vendor:** VMware
- **Virtualization type:** Full
- **L1d cache:** 2.4 MiB
- **L1i cache:** 2.4 MiB
- **L2 cache:** 76 MiB
- **L3 cache:** 2.7 GiB
- **NUMA node0 CPU(s):** 0-75
- **Vulnerabilities:**
  - **Gather data sampling:** Unknown (Dependent on hypervisor status)
  - **Itlb multihit:** KVM: Mitigation (VMX unsupported)
  - **L1tf:** Not affected
  - **Mds:** Not affected
  - **Meltdown:** Not affected
  - **Mmio stale data:** Vulnerable (Clear CPU buffers attempted, no microcode; SMT Host state unknown)
  - **Reg file data sampling:** Not affected
  - **Retbleed:** Mitigation; Enhanced IBRS
  - **Spec rstack overflow:** Not affected
  - **Spec store bypass:** Mitigation; Speculative Store Bypass disabled via prctl and seccomp
  - **Spectre v1:** Mitigation; usercopy/swapgs barriers and __user pointer sanitization
  - **Spectre v2:** Mitigation; Enhanced / Automatic IBRS; IBPB conditional; RSB filling; PBRSB-eIBRS SW sequence; BHI SW loop, KVM SW loop
  - **Srbds:** Not affected
  - **Tsx async abort:** Not affected
- **Flags:** (e.g., `fpu`, `vme`, `de`, `pse`, `tsc`, `msr`, etc.)

**GPU Information:**
- **Timestamp:** Thu Oct 31 02:33:16 2024  
- **NVIDIA-SMI Version:** 495.29.05
- **Driver Version:** 470.129.06
- **CUDA Version:** 11.4
- **GPU:** NVIDIA TITAN Xp
  - **Persistence-M:** On
  - **Bus-Id:** 00000000:04:00.0
  - **Temperature:** 18C
  - **Performance State:** P8
  - **Power Usage:** 8W / 250W
  - **Memory Usage:** 0MiB / 12196MiB
  - **GPU Utilization:** 0%
  - **Display Active:** Off
- **Processes:** None running

**Memory Information:**
- **Total Memory:** 275Gi
- **Used:** 6.1Gi
- **Free:** 220Gi
- **Shared:** 2.0Mi
- **Buffer/Cache:** 48Gi
- **Available:** 266Gi
- **Swap:** 2.0Gi (Used: 0B, Free: 2.0Gi)

**Disk Space:**
| Filesystem                  | Size | Used | Avail | Use% | Mounted on       |
|-----------------------------|------|------|-------|------|------------------|
| overlay                     | 7.3T | 1.3T | 6.0T  | 18%  | /               |
| tmpfs                       | 64M  | 0B   | 64M   | 0%   | /dev            |
| shm                         | 5.0G | 0B   | 5.0G  | 0%   | /dev/shm        |
| /dev/mapper/srv_vg-srv_lv   | 7.3T | 1.3T | 6.0T  | 18%  | /shared_data    |
| tmpfs (acpi, scsi, firmware)| 138G | 0B   | 138G  | 0%   | various         |

**Python Version:**
- Python 3.9.7

**Installed Packages:**

| Package                       | Version    |
|-------------------------------|------------|
| absl-py                       | 0.15.0     |
| aiohttp                       | 3.8.1      |
| aiosignal                     | 1.2.0      |
| alembic                       | 1.7.5      |
| anyio                         | 3.4.0      |
| argon2-cffi                   | 21.1.0     |
| astunparse                    | 1.6.3      |
| async-generator               | 1.10       |
| async-timeout                 | 4.0.2      |
| attrs                         | 21.2.0     |
| Babel                         | 2.9.1      |
| backcall                      | 0.2.0      |
| backports.functools-lru-cache | 1.6.4      |
| beautifulsoup4                | 4.10.0     |
| bleach                        | 4.1.0      |
| blinker                       | 1.4        |
| bokeh                         | 2.3.3      |
| brotlipy                      | 0.7.0      |
| cached-property               | 1.5.2      |
| cachetools                    | 4.2.4      |
| certifi                       | 2021.10.8  |
| certipy                       | 0.1.3      |
| cffi                          | 1.15.0     |
| charset-normalizer            | 2.0.9      |
| click                         | 8.0.3      |
| cloudpickle                   | 2.0.0      |
| colorama                      | 0.4.4      |
| conda                         | 4.11.0     |
| conda-package-handling        | 1.7.3      |
| cryptography                  | 36.0.1     |
| cycler                        | 0.11.0     |
| Cython                        | 0.29.26    |
| cytoolz                       | 0.11.2     |
| dask                          | 2021.12.0  |
| dataclasses                   | 0.8        |
| debugpy                       | 1.5.1      |
| decorator                     | 5.1.0      |
| defusedxml                    | 0.7.1      |
| dill                          | 0.3.4      |
| entrypoints                   | 0.3        |
| flatbuffers                   | 1.12       |
| fonttools                     | 4.28.5     |
| frozenlist                    | 1.2.0      |
| fsspec                        | 2021.11.1  |
| gast                          | 0.4.0      |
| gmpy2                         | 2.1.0rc1   |
| google-auth                   | 1.35.0     |
| google-auth-oauthlib          | 0.4.6      |
| google-pasta                  | 0.2.0      |
| greenlet                      | 1.1.2      |
| grpcio                        | 1.39.0     |
| h5py                          | 3.1.0      |
| html5lib                      | 1.1        |
| idna                          | 3.1        |
| imagecodecs                   | 2021.11.20 |
| imageio                       | 2.13.4     |
| importlib-metadata            | 4.10.0     |
| importlib-resources           | 5.4.0      |
| ipykernel                     | 6.6.0      |
| ipympl                        | 0.8.4      |
| ipyparallel                   | 8.1.0      |
| ipython                       | 7.30.1     |
| ipython-genutils              | 0.2.0      |
| ipywidgets                    | 7.6.5      |
| jedi                          | 0.18.1     |
| Jinja2                        | 3.0.3      |
| joblib                        | 1.1.0      |
| json5                         | 0.9.5      |
| jsonschema                    | 4.3.1      |
| jupyter-client                | 7.1.0      |
| jupyter-core                  | 4.9.1      |
| jupyter-server                | 1.13.1     |
| jupyter-server-proxy          | 3.2.0      |
| jupyter-telemetry             | 0.1.0      |
| jupyterhub                    | 2.0.0      |
| jupyterlab                    | 3.2.5      |
| jupyterlab-nvdashboard        | 0.6.0      |
| jupyterlab-pygments           | 0.1.2      |
| jupyterlab-server             | 2.9.0      |
| jupyterlab-widgets            | 1.0.2      |
| keras                         | 2.6.0      |
| Keras-Preprocessing           | 1.1.2      |
| kiwisolver                    | 1.3.2      |
| libmambapy                    | 0.19.1     |
| llvmlite                      | 0.37.0     |
| locket                        | 0.2.0      |
| lxml                          | 4.7.1      |
| Mako                          | 1.1.6      |
| mamba                         | 0.19.1     |
| Markdown                      | 3.3.6      |
| MarkupSafe                    | 2.0.1      |
| matplotlib                    | 3.5.1      |
| matplotlib-inline             | 0.1.3      |
| mistune                       | 0.8.4      |
| mock                          | 4.0.3      |
| mpmath                        | 1.2.1      |
| multidict                     | 5.2.0      |
| munkres                       | 1.1.4      |
| nbclassic                     | 0.3.4      |
| nbclient                      | 0.5.9      |
| nbconvert                     | 6.3.0      |
| nbformat                      | 5.1.3      |
| nest-asyncio                  | 1.5.4      |
| networkx                      | 2.6.3      |
| notebook                      | 6.4.6      |
| numba                         | 0.54.1     |
| numexpr                       | 2.8.0      |
| numpy                         | 1.21.5     |
| oauthlib                      | 3.1.1      |
| olefile                       | 0.46       |
| opt-einsum                    | 3.3.0      |
| packaging                     | 21.3       |
| pamela                        | 1.0.0      |
| pandas                        | 1.3.5      |
| pandas-datareader             | 0.10.0     |
| pandocfilters                 | 1.5.0      |
| parso                         | 0.8.3      |
| partd                         | 1.2.0      |
| patsy                         | 0.5.2      |
| pexpect                       | 4.8.0      |
| pickleshare                   | 0.7.5      |
| Pillow                        | 8.4.0      |
| pip                           | 21.3.1     |
| prometheus-client             | 0.12.0     |
| prompt-toolkit                | 3.0.24     |
| protobuf                      | 3.16.0     |
| psutil                        | 5.8.0      |
| ptyprocess                    | 0.7.0      |
| pyasn1                        | 0.4.8      |
| pyasn1-modules                | 0.2.7      |
| pybind11                      | 2.8.1      |
| pybind11-global               | 2.8.1      |
| pycosat                       | 0.6.3      |
| pycparser                     | 2.21       |
| pycurl                        | 7.44.1     |
| Pygments                      | 2.10.0     |
| PyJWT                         | 2.3.0      |
| pynvml                        | 11.4.1     |
| pyOpenSSL                     | 21.0.0     |
| pyparsing                     | 3.0.6      |
| PyQt5                         | 5.12.3     |
| PyQt5_sip                     | 4.19.18    |
| PyQtChart                     | 5.12       |
| PyQtWebEngine                 | 5.12.1     |
| pyrsistent                    | 0.18.0     |
| PySocks                       | 1.7.1      |
| python-dateutil               | 2.8.2      |
| python-json-logger            | 2.0.1      |
| pytz                          | 2021.3     |
| pyu2f                         | 0.1.5      |
| PyWavelets                    | 1.2.0      |
| PyYAML                        | 6.0        |
| pyzmq                         | 22.3.0     |
| requests                      | 2.26.0     |
| requests-oauthlib             | 1.3.0      |
| rsa                           | 4.8        |
| ruamel.yaml                   | 0.17.17    |
| ruamel.yaml.clib              | 0.2.6      |
| ruamel-yaml-conda             | 0.15.80    |
| scikit-image                  | 0.19.1     |
| scikit-learn                  | 1.0.1      |
| scipy                         | 1.7.3      |
| seaborn                       | 0.11.2     |
| selenium                      | 3.141.0    |
| Send2Trash                    | 1.8.0      |
| setuptools                    | 59.6.0     |
| simpervisor                   | 0.4        |
| six                           | 1.15.0     |
| sniffio                       | 1.2.0      |
| soupsieve                     | 2.3.1      |
| SQLAlchemy                    | 1.4.28     |
| statsmodels                   | 0.13.1     |
| sympy                         | 1.9        |
| tables                        | 3.6.1      |
| tensorboard                   | 2.6.0      |
| tensorboard-data-server       | 0.6.0      |
| tensorboard-plugin-wit        | 1.8.0      |
| tensorflow                    | 2.6.0      |
| tensorflow-estimator          | 2.6.0      |
| termcolor                     | 1.1.0      |
| terminado                     | 0.12.1     |
| testpath                      | 0.5.0      |
| threadpoolctl                 | 3.0.0      |
| tifffile                      | 2021.11.2  |
| toolz                         | 0.11.2     |
| torch                         | 1.10.1     |
| torchaudio                    | 0.10.1     |
| torchvision                   | 0.11.2     |
| tornado                       | 6.1        |
| tqdm                          | 4.62.3     |
| traitlets                     | 5.1.1      |
| typing_extensions             | 4.0.1      |
| urllib3                       | 1.26.7     |
| vincent                       | 0.4.4      |
| wcwidth                       | 0.2.5      |
| webencodings                  | 0.5.1      |
| websocket-client              | 1.2.3      |
| Werkzeug                      | 2.0.1      |
| wheel                         | 0.37.0     |
| widgetsnbextension            | 3.5.2      |
| wrapt                         | 1.12.1     |
| xlrd                          | 2.0.1      |
| yarl                          | 1.7.2      |
| zipp                          | 3.6.0      |
