SmartMinerPRO (SMP) - GUI multi crypto mining panel for GPU/CPU/ASIC/FPGA.
=======================================================================

SmartMinerPRO (SMP) is a software product that finds the available hardware itself and selects the optimal settings. developed by SmartMiner.PRO with a simple and user-friendly graphical interface. This version of SMP was created to work with every cryptocurrency based on these algorithms, including bitcoin. Ethereum, Ethereum Classic, Sumocoin, Grin, Monero, Ravencoin and many more. This version of SmartMinerPRO works on Windows with AMD or Nvidia processors and GPUs and ASIC / FPGA. SMP allows you to connect / disconnect / stop / start one or more farms with one click. During the initial startup, in the Quick Start phase, you can select a separate algorithm for each farm.

 + WebSite SmartMinerPRO: http://smartminer.pro/
 + Official github developer: https://github.com/MiningSoftware/SmartMinerPRO
 + Bitcointalk: https://bitcointalk.org/index.php?topic=5401073.0

DOWNLOAD LINKS: https://github.com/MiningSoftware/SmartMinerPRO/releases
---------------------------------------------------------------------------

<img src="SMP + v1.0.PNG" /> <img src="SMP+ miners.PNG" />

Key Features SmartMinerPRO:
===========================

The miner is focused on CPUs, NVIDIA and AMD GPUs, it supports the most popular algorithms such as: Ethash, ProgPoW, KAWPOW, Equihash, CuckooCycle.
SmartminerPRO has shown high efficiency in mining such coins as Bitcoin, Ethereum, Beam, Grin, Cortex, Bitcoin Gold, Ravencoin, Monero.

      • 💎 Built-in miners: XMR-STAK & XMRIG, GMINER. T-REX, TeamRedMiner, CGMiner, T-Rex, NBMiner, Nanominer, PhoenixMiner, CCMiner, miniz, cpu miner, cpuminer-opt, Kadena Miner, Kawpowminer and many others.
      • 🖥 Works on all versions of Windows
      • 📊 Over 50 of the best mining puols
      • ℹ️ Complete information about each currency with links   
      • 📈 CoinGecko price and coin statistics
      • 📊 Coin mining statistics from Cryptunit
      • ♻️ CPU & GPU Mining
      • 🔸 Easy to use
      • 🔸 Easy installation of other miners and .bat configuration files.
      • 🔸 To start mining using SMP +, just enter your wallet in the .bat file of the selected miner
      • 🔸 SMP + has demonstrated high performance when working with Bitcoin, Ethereum, Ethereum Classic, Monero, Raven and other currencies, stands out for its high stability and easy setup.
      • 🔸 Easy one-click CPU mining for CPUs that support at least SSE2 (only works on Windows x64).
      • 🔸 Easy one-click GPU mining for NVIDIA GPUs using microarchitecture (compute capability) SM 3.0+.
      • 🔸 Easy one-click GPU mining for AMD GPUs using any AMD GPU devices that supports OpenCL.
      • 🔸 Integrated support for Simple Multi-Algorithm. Always mine most profitable algorithm.
      • 🔸 Integrated benchmarking tool. Run it only once before you start mining and after every hardware/driver/software upgrade.
      • 🔸 Watch-feature - automatically restart miner if crashed or hanged.
      • 🔸 Much more..

System requirements:
=====================

+ WINDOWS XP,7,8,10 or later (x64) / LINUX / MAC OS
+ CPU (x64/x86/ARM) For CPU mining a modern CPU with SSE2 support
+ OpenCL for AMD GPUs. For AMD mining any AMD GPU with OpenCL support
+ CUDA for NVIDIA GPUs. For NVIDIA mining any NVIDIA GPU with Compute capability (SM) 3.0 or newer
+ up-to-date patches for OS
+ up-to-date drivers for all GPUs
+ Reliable internet connectivity

Note: .NET Framework 4.8 or higher and Microsoft Visual C++ Redistributable 2015 are required. No additional installations should be needed if you use Windows 7 or later. However, if you encounter any issues when starting application (application would fail to start or errors/warnings about missing DLL files are displayed) you should download and install Microsoft .NET Framework 4.8 and Microsoft Visual C++ Redistributable 2015 (vcredist_x64.exe) (after installation a reboot might be required).

+ Microsoft .NET Framework 4.8: https://dotnet.microsoft.com/download/dotnet-framework/thank-you/net48-web-installer
+ Microsoft Visual C++ Redistributable 2015: https://www.microsoft.com/en-us/download/details.aspx?id=48145

Full list Support miners:
==========================

+ bminer
+ bzminer
+ ccminer
+ cgminer
+ Nanominer
+ Claymore
+ cpuminer-opt
+ CPU Miner-GR
+ CryptoDredge
+ ethminer 
+ EWB
+ Gminer
+ kawpowminer
+ lolMiner
+ miniZ_cuda
+ NBMiner
+ NiceHashMiner
+ PhoenixMiner
+ Progpowminer
+ SRBMiner
+ SRBMiner-Multi
+ TeamRedMiner
+ TeamBlackMiner
+ T-Rex miner
+ TT-Miner
+ xmrig
+ xmr-stak
+ z-enemy
+ zm
+ wildrig-multi

! Please note that the list of supported miners will be expanded with subsequent versions of the SMP.

How to start:
=============

1. Download SmartMinerPRO
2. Unpack the archive .zip/.rar
3. Run SmartMinerPRO.exe

IMPORTANT! For your mining equipment, you must install the necessary dependencies. Since each miner program has its own requirements for work. For reference, you can refer to the root directory in the miner’s folder. version of SmartMinerPRO Lite, there are no built-in miners and config files for coins. You need to add them manually to the "Miners" folder.

How to use:
===========

1. At the first launch of SMP, select the coin to be mined
    • Optionally, you can choose what equipment will be used, according to the standard, all available CPU / GPUs are used.
2. Click "Start mining", in the mining parameters window, select the miner and the finished .bat file (coins \ pool)
    • By default, safe recommended settings for increased profitability of mining are used.
3. You can edit the .bat file to replace the wallet and pool values with your own by pressing the "EDIT" button.
    • If desired, you can replace the parameters of the request, for this we recommend that you refer to the practical guide in the root folders of the miners.
4. After replacing the values of the wallet and pool with yours, click "RUN"
5. Then begins the extraction of coins

DevFee & Donations:
===================

SmartMinerPRO (SMP/) is completely free software. This does not apply to built-in programs for mining (miners).


Command line options:
=====================

Network:
--------
    
    --no-cpu                  disable CPU mining backend
    -o, --url=URL                 URL of mining server
    -a, --algo=ALGO               mining algorithm 
      --coin=COIN               specify coin instead of algorithm
      -u, --user=USERNAME           username for mining server
      -p, --pass=PASSWORD           password for mining server
      -O, --userpass=U:P            username:password pair for mining server
      -x, --proxy=HOST:PORT         connect through a SOCKS5 proxy
      -k, --keepalive               send keepalive packet for prevent timeout (needs pool support)
      --nicehash                enable nicehash.com support
      --rig-id=ID               rig identifier for pool-side statistics (needs pool support)
      --tls                     enable SSL/TLS support (needs pool support)
      --tls-fingerprint=HEX     pool TLS certificate fingerprint for strict certificate pinning
      --daemon                  use daemon RPC instead of pool for solo mining
      --daemon-poll-interval=N  daemon poll interval in milliseconds (default: 1000)
      -r, --retries=N               number of times to retry before switch to backup server (default: 5)
      -R, --retry-pause=N           time to pause between retries (default: 5)
      --user-agent              set custom user-agent string for pool
      --donate-level=N          donate level, default %% (5 minutes in 100 minutes)
      --donate-over-proxy=N     control donate over xmrig-proxy feature
      
CPU backend:
------------

      --no-cpu                  disable CPU mining backend
      -t, --threads=N               number of CPU threads
      -v, --av=N                    algorithm variation, 0 auto select
      --cpu-affinity            set process affinity to CPU core(s), mask 0x3 for cores 0 and 1
      --cpu-priority            set process priority (0 idle, 2 normal to 5 highest)
      --cpu-max-threads-hint=N  maximum CPU threads count (in percentage) hint for autoconfig
      --cpu-memory-pool=N       number of 2 MB pages for persistent memory pool, -1 (auto), 0 (disable)
      --cpu-no-yield            prefer maximum hashrate rather than system response/stability
      --no-huge-pages           disable huge pages support
      --asm=ASM                 ASM optimizations, possible values: auto, none, intel, ryzen, bulldozer
      --randomx-init=N          thread count to initialize RandomX dataset
      --randomx-no-numa         disable NUMA support for RandomX
      --randomx-mode=MODE       RandomX mode: auto, fast, light
      --randomx-1gb-pages       use 1GB hugepages for dataset (Linux only)
      --randomx-wrmsr=N         write custom value (0-15) to Intel MSR register 0x1a4 or disable MSR mod (-1)
      --randomx-no-rdmsr        disable reverting initial MSR values on exit
      --astrobwt-max-size=N     skip hashes with large stage 2 size, default: 550, min: 400, max: 1200
      --astrobwt-avx2           enable AVX2 optimizations for AstroBWT algorithm

API:
------------

      --api-worker-id=ID        custom worker-id for API
      --api-id=ID               custom instance ID for API
      --http-host=HOST          bind host for HTTP API (default: 127.0.0.1)
      --http-port=N             bind port for HTTP API
      --http-access-token=T     access token for HTTP API
      --http-no-restricted      enable full remote access to HTTP API (only if access token set)

OpenCL backend:
---------------

      --opencl                  enable OpenCL mining backend
      --opencl-devices=N        comma separated list of OpenCL devices to use
      --opencl-platform=N       OpenCL platform index or name
      --opencl-loader=PATH      path to OpenCL-ICD-Loader (OpenCL.dll or libOpenCL.so)
      --opencl-no-cache         disable OpenCL cache
      --print-platforms         print available OpenCL platforms and exit

CUDA backend:
-------------

      --cuda                    enable CUDA mining backend
      --cuda-loader=PATH        path to CUDA plugin (xmrig-cuda.dll or libxmrig-cuda.so)
      --cuda-devices=N          comma separated list of CUDA devices to use
      --cuda-bfactor-hint=N     bfactor hint for autoconfig (0-12)
      --cuda-bsleep-hint=N      bsleep hint for autoconfig
      --no-nvml                 disable NVML (NVIDIA Management Library) support

TLS:
-----

      --tls-gen=HOSTNAME        generate TLS certificate for specific hostname
      --tls-cert=FILE           load TLS certificate chain from a file in the PEM format
      --tls-cert-key=FILE       load TLS certificate private key from a file in the PEM format
      --tls-dhparam=FILE        load DH parameters for DHE ciphers from a file in the PEM format
      --tls-protocols=N         enable specified TLS protocols, example: "TLSv1 TLSv1.1 TLSv1.2 TLSv1.3"
      --tls-ciphers=S           set list of available ciphers (TLSv1.2 and below)
      --tls-ciphersuites=S      set list of available TLSv1.3 ciphersuites

Logging:
---------

    -S, --syslog                  use system log for output messages
    -l, --log-file=FILE           log all output to a file
      --print-time=N            print hashrate report every N seconds
      --health-print-time=N     print health report every N seconds
      --no-color                disable colored output
      --verbose                 verbose output

Misc:
--------

    -c, --config=FILE             load a JSON-format configuration file
    -B, --background              run the miner in the background
    -V, --version                 output version information and exit
    -h, --help                    display this help and exit
      --dry-run                 test configuration and exit
      --export-topology         export hwloc topology to a XML file and exit
      --title                   set custom console window title
      --no-title                disable setting console window title      

DONATE:
=======

- BTC: bc1qmpdug4lkkz4kvw2gnrfx9hjgclcge9ytq0z0wl
- ETH: 0xd5533d796302DA0Ec67a34eBB0Ba432B164a1CA5
- XMR: 8BFHZwHteLf46VhuXdw9t8h3oEm1ajFxPeNdLLKsnLZjS5EJQL1dJpSCdYFAzty2S2UYd8G86YvioXLb3yXfPLVvN71u1XK
- RVN: RV8Tz58pZ6Q6fFn5LGGN8hQsUoPzJC1vMi
- LTC: ltc1q2c68a8spxap6j3nhjk09rem6zf75rahgu7s0gh
