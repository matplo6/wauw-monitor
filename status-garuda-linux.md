
### inxi ###
System:
  Kernel: 6.15.4-zen2-1-zen arch: x86_64 bits: 64 compiler: gcc v: 15.1.1 clocksource: tsc
    avail: acpi_pm parameters: BOOT_IMAGE=/@/boot/vmlinuz-linux-zen
    root=UUID=206eec02-6fca-4d04-910e-2bf9fddca883 rw rootflags=subvol=@ quiet loglevel=3 ibt=off
  Console: N/A DM: SDDM Distro: Garuda base: Arch Linux
Machine:
  Type: Desktop System: Gigabyte product: B760 DS3H v: -CF serial: N/A
  Mobo: Gigabyte model: B760 DS3H v: x.x serial: N/A uuid: 03560274-043c-05eb-0106-d10700080009
    UEFI: American Megatrends LLC. v: F11 date: 09/27/2024
CPU:
  Info: model: 13th Gen Intel Core i5-13400 socket: LGA1700 (U3E1) note: check bits: 64
    type: MST AMCP arch: Raptor Lake gen: core 13 level: v3 note: check built: 2022+
    process: Intel 7 (10nm) family: 6 model-id: 0xBF (191) stepping: 2 microcode: 0x3A
  Topology: cpus: 1x dies: 1 clusters: 7 cores: 10 threads: 16 mt: 6 tpc: 2 st: 4 smt: enabled
    cache: L1: 864 KiB desc: d-4x32 KiB, 6x48 KiB; i-6x32 KiB, 4x64 KiB L2: 9.5 MiB
    desc: 6x1.2 MiB, 1x2 MiB L3: 20 MiB desc: 1x20 MiB
  Speed (MHz): avg: 803 min/max: 800/4600:3300 base/boost: 2475/4600 scaling:
    driver: intel_pstate governor: powersave volts: 0.9 V ext-clock: 100 MHz cores: 1: 803 2: 803
    3: 803 4: 803 5: 803 6: 803 7: 803 8: 803 9: 803 10: 803 11: 803 12: 803 13: 803 14: 803
    15: 803 16: 803 bogomips: 79872
  Flags: avx avx2 ht lm nx pae sse sse2 sse3 sse4_1 sse4_2 ssse3 vmx
  Vulnerabilities: <filter>
Graphics:
  Device-1: Intel Alder Lake-S GT1 [UHD Graphics 730] vendor: Gigabyte driver: i915 v: kernel
    alternate: xe arch: Xe process: Intel 10nm built: 2020-21 ports: active: none
    empty: DP-1,HDMI-A-1,HDMI-A-2 bus-ID: 0000:00:02.0 chip-ID: 8086:4682 class-ID: 0380
  Device-2: Advanced Micro Devices [AMD/ATI] Navi 32 [Radeon RX 7700 XT / 7800 XT]
    vendor: Gigabyte driver: amdgpu v: kernel arch: RDNA-3 code: Navi-3x process: TSMC n5 (5nm)
    built: 2022+ ports: active: HDMI-A-3 empty: DP-2, DP-3, HDMI-A-4, Writeback-1
    bus-ID: 0000:03:00.0 chip-ID: 1002:747e class-ID: 0300
  Display: unspecified server: X.org v: 1.21.1.18 with: Xwayland v: 24.1.8
    compositor: kwin_wayland driver: X: loaded: amdgpu,modesetting unloaded: radeon
    alternate: fbdev,intel,vesa dri: radeonsi,iris gpu: amdgpu tty: 80x40
  Monitor-1: HDMI-A-3 model: HP S340c serial: <filter> built: 2017 res: 3440x1440 dpi: 110
    gamma: 1.2 size: 797x333mm (31.38x13.11") diag: 864mm (34") modes: max: 3440x1440 min: 720x400
  API: EGL v: 1.5 hw: drv: intel iris drv: amd radeonsi platforms: device: 0 drv: radeonsi
    device: 1 drv: iris device: 2 drv: swrast gbm: drv: radeonsi surfaceless: drv: radeonsi
    inactive: wayland,x11
  API: OpenGL v: 4.6 compat-v: 4.5 vendor: mesa v: 25.1.4-arch1.1 note: console (EGL sourced)
    renderer: AMD Radeon RX 7700 XT (radeonsi navi32 LLVM 20.1.6 DRM 3.63 6.15.4-zen2-1-zen), Mesa
    Intel UHD Graphics 730 (ADL-S GT1), llvmpipe (LLVM 20.1.6 256 bits)
  API: Vulkan v: 1.4.313 layers: 9 device: 0 type: discrete-gpu name: AMD Radeon RX 7700 XT
    (RADV NAVI32) driver: mesa radv v: 25.1.4-arch1.1 device-ID: 1002:747e surfaces: N/A device: 1
    type: integrated-gpu name: Intel UHD Graphics 730 (ADL-S GT1) driver: mesa intel
    v: 25.1.4-arch1.1 device-ID: 8086:4682 surfaces: N/A device: 2 type: cpu name: llvmpipe (LLVM
    20.1.6 256 bits) driver: mesa llvmpipe v: 25.1.4-arch1.1 (LLVM 20.1.6) device-ID: 10005:0000
    surfaces: N/A
  Info: Tools: api: clinfo, eglinfo, glxinfo, vulkaninfo de: kscreen-console,kscreen-doctor
    gpu: corectrl wl: wayland-info x11: xdpyinfo, xprop, xrandr
Audio:
  Device-1: Intel Raptor Lake High Definition Audio vendor: Gigabyte driver: snd_hda_intel
    v: kernel alternate: snd_soc_avs,snd_sof_pci_intel_tgl bus-ID: 0000:00:1f.3 chip-ID: 8086:7a50
    class-ID: 0403
  Device-2: Advanced Micro Devices [AMD/ATI] Navi 31 HDMI/DP Audio driver: snd_hda_intel
    v: kernel bus-ID: 0000:03:00.1 chip-ID: 1002:ab30 class-ID: 0403
  API: ALSA v: k6.15.4-zen2-1-zen status: kernel-api with: aoss type: oss-emulator tools: N/A
  Server-1: PipeWire v: 1.4.6 status: n/a (root, process) with: 1: pipewire-pulse status: active
    2: wireplumber status: active 3: pipewire-alsa type: plugin 4: pw-jack type: plugin
    tools: pactl,pw-cat,pw-cli,wpctl
Network:
  Device-1: Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet vendor: Gigabyte
    driver: r8169 v: kernel port: 4000 bus-ID: 0000:05:00.0 chip-ID: 10ec:8168 class-ID: 0200
  IF: enp5s0 state: down mac: <filter>
  Device-2: Intel 82572EI Gigabit Ethernet driver: e1000e v: kernel port: 3000
    bus-ID: 0000:06:00.0 chip-ID: 8086:107d class-ID: 0200
  IF: enp6s0 state: up speed: 1000 Mbps duplex: full mac: <filter>
  Info: services: NetworkManager, smbd, systemd-timesyncd
RAID:
  Hardware-1: Intel Volume Management Device NVMe RAID Controller driver: vmd v: 0.6 port: N/A
    bus-ID: 0000:00:0e.0 chip-ID: 8086:467f rev: class-ID: 0104
Drives:
  Local Storage: total: 3.17 TiB used: 356.78 GiB (11.0%)
  ID-1: /dev/nvme0n1 maj-min: 259:0 vendor: Samsung model: SSD 980 PRO 1TB size: 931.51 GiB
    block-size: physical: 512 B logical: 512 B speed: 63.2 Gb/s lanes: 4 tech: SSD serial: <filter>
    fw-rev: 5B2QGXA7 temp: 39.9 C scheme: GPT
  SMART: yes health: PASSED on: 19d 20h cycles: 564 read-units: 16,734,935 [8.56 TB]
    written-units: 20,700,096 [10.5 TB]
  ID-2: /dev/sda maj-min: 8:0 vendor: Samsung model: MZ7L3480HCHQ-00A07 family: based SSDs
    size: 447.13 GiB block-size: physical: 4096 B logical: 512 B sata: 3.2 speed: 6.0 Gb/s tech: SSD
    serial: <filter> fw-rev: 104Q temp: 41 C scheme: GPT
  SMART: yes state: enabled health: PASSED on: 1y 139d 11h cycles: 511 read: 39.15 TiB
    written: 19.57 TiB
  ID-3: /dev/sdb maj-min: 8:16 vendor: Seagate model: ST3500413AS family: Barracuda 7200.12
    size: 465.76 GiB block-size: physical: 512 B logical: 512 B sata: 3.0 speed: 6.0 Gb/s tech: HDD
    rpm: 7200 serial: <filter> fw-rev: HP61 temp: 32 C scheme: MBR
  SMART: yes state: enabled health: PASSED on: 259d 6h cycles: 4187 Pre-Fail:
    attribute: Spin_Retry_Count value: 100 worst: 100 threshold: 97
  ID-4: /dev/sdc maj-min: 8:32 vendor: Hitachi model: HDS721010CLA632 family: Deskstar 7K1000.C
    size: 931.51 GiB block-size: physical: 512 B logical: 512 B sata: 3.0 speed: 6.0 Gb/s tech: HDD
    rpm: 7200 serial: <filter> fw-rev: A41A temp: 35 C
  SMART: yes state: enabled health: PASSED on: 4y 316d 11h cycles: 2460
  ID-5: /dev/sdd maj-min: 8:48 vendor: Seagate model: ST3500413AS family: Barracuda 7200.12
    size: 465.76 GiB block-size: physical: 512 B logical: 512 B sata: 3.0 speed: 6.0 Gb/s tech: HDD
    rpm: 7200 serial: <filter> fw-rev: HP61 temp: 31 C scheme: GPT
  SMART: yes state: enabled health: PASSED on: 283d 15h cycles: 3816 Pre-Fail:
    reallocated sector: 94 threshold: 36 attribute: Spin_Retry_Count value: 100 worst: 100
    threshold: 97
  ID-6: /dev/sde maj-min: 8:64 vendor: Silicon Motion model: 1000 size: 1.88 GiB block-size:
    physical: 512 B logical: 512 B type: USB rev: 2.0 spd: 480 Mb/s lanes: 1 mode: 2.0 tech: N/A
    serial: <filter>
  SMART Message: Unknown USB bridge. Flash drive/Unsupported enclosure?
Partition:
  ID-1: / raw-size: 931.22 GiB size: 931.22 GiB (100.00%) used: 164.33 GiB (17.6%) fs: btrfs
    block-size: 4096 B dev: /dev/nvme0n1p2 maj-min: 259:2
  ID-2: /boot/efi raw-size: 300 MiB size: 299.4 MiB (99.80%) used: 616 KiB (0.2%) fs: vfat
    block-size: 512 B dev: /dev/nvme0n1p1 maj-min: 259:1
  ID-3: /home raw-size: 931.22 GiB size: 931.22 GiB (100.00%) used: 164.33 GiB (17.6%) fs: btrfs
    block-size: 4096 B dev: /dev/nvme0n1p2 maj-min: 259:2
  ID-4: /var/log raw-size: 931.22 GiB size: 931.22 GiB (100.00%) used: 164.33 GiB (17.6%)
    fs: btrfs block-size: 4096 B dev: /dev/nvme0n1p2 maj-min: 259:2
  ID-5: /var/tmp raw-size: 931.22 GiB size: 931.22 GiB (100.00%) used: 164.33 GiB (17.6%)
    fs: btrfs block-size: 4096 B dev: /dev/nvme0n1p2 maj-min: 259:2
Swap:
  Kernel: swappiness: 133 (default 60) cache-pressure: 100 (default) zswap: no
  ID-1: swap-1 type: zram size: 62.56 GiB used: 0 KiB (0.0%) priority: 100 comp: zstd
    avail: lzo-rle,lzo,lz4,lz4hc,deflate,842 dev: /dev/zram0
Sensors:
  System Temperatures: cpu: 46.8 C mobo: 43.0 C gpu: amdgpu temp: 51.0 C mem: 48.0 C
  Fan Speeds (rpm): N/A gpu: amdgpu fan: 0
Info:
  Memory: total: 64 GiB available: 62.56 GiB used: 3.99 GiB (6.4%)
  Processes: 445 Power: uptime: 9h 1m states: freeze,mem,disk suspend: deep avail: s2idle
    wakeups: 0 hibernate: platform avail: shutdown, reboot, suspend, test_resume image: 25 GiB
    services: org_kde_powerdevil, power-profiles-daemon, upowerd Init: systemd v: 257
    default: graphical tool: systemctl
  Packages: 2577 pm: pacman pkgs: 2516 libs: 607 tools: gnome-software,octopi,paru,yay
    pm: flatpak pkgs: 61 Compilers: clang: 20.1.6 gcc: 15.1.1 Client: shell wrapper v: 5.2.37-release
    inxi: 3.3.38
Garuda (2.7.2-1):
  System install date:     2025-06-28
  Last full system update: 2025-07-11
  Is partially upgraded:   No
  Relevant software:       snapper NetworkManager dracut
  Windows dual boot:       No/Undetected
  Failed units:            
### END garuda-inxi ###
5.752s NetworkManager-wait-online.service
4.827s plocate-updatedb.service
4.528s dev-ttyS2.device
4.528s sys-devices-platform-serial8250-serial8250:0-serial8250:0.2-tty-ttyS2.device
4.527s dev-ttyS3.device
4.527s sys-devices-platform-serial8250-serial8250:0-serial8250:0.3-tty-ttyS3.device
4.527s sys-devices-platform-serial8250-serial8250:0-serial8250:0.1-tty-ttyS1.device
4.527s dev-ttyS1.device
4.525s sys-devices-pnp0-00:01-00:01:0-00:01:0.0-tty-ttyS0.device
4.525s dev-ttyS0.device
4.525s sys-module-fuse.device
4.523s sys-module-configfs.device
4.485s sys-devices-pci0000:00-0000:00:1c.2-0000:05:00.0-net-enp5s0.device
4.485s sys-subsystem-net-devices-enp5s0.device
4.338s sys-devices-pci0000:00-0000:00:1c.6-0000:06:00.0-net-enp6s0.device
4.338s sys-subsystem-net-devices-enp6s0.device
4.093s sys-devices-pci0000:00-0000:00:0e.0-pci10000:e0-10000:e0:17.0-ata7-host6-target6:0:0-6:0:0:0-block-sdc.device
4.093s dev-disk-by\x2did-wwn\x2d0x5000cca396e31c7f.device
4.093s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d7.0.device
4.093s dev-sdc.device
4.093s dev-disk-by\x2ddiskseq-3.device
4.093s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d7.device
4.093s dev-disk-by\x2did-ata\x2dHitachi_HDS721010CLA632_JP2940J82H7ELV.device
3.961s dev-disk-by\x2dpartuuid-a4aa563c\x2df792\x2d42a0\x2d9880\x2d082f3500c7e0.device
3.961s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d5.0\x2dpart-by\x2dpartnum-1.device
3.961s sys-devices-pci0000:00-0000:00:0e.0-pci10000:e0-10000:e0:17.0-ata5-host4-target4:0:0-4:0:0:0-block-sda-sda1.device
3.961s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d5\x2dpart1.device
3.961s dev-disk-by\x2dlabel-Data.device
3.961s dev-disk-by\x2ddiskseq-1\x2dpart1.device
3.961s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d5.0\x2dpart-by\x2dlabel-Data.device
3.961s dev-disk-by\x2did-ata\x2dSAMSUNG_MZ7L3480HCHQ\x2d00A07_S664NE0RC26616\x2dpart1.device
3.961s dev-sda1.device
3.961s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d5.0\x2dpart-by\x2dpartuuid-a4aa563c\x2df792\x2d42a0\x2d9880\x2d082f3500c7e0.device
3.961s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d5.0\x2dpart-by\x2duuid-bf97dd75\x2d0621\x2d4d96\x2d8eca\x2dcd1433c9795c.device
3.961s dev-disk-by\x2duuid-bf97dd75\x2d0621\x2d4d96\x2d8eca\x2dcd1433c9795c.device
3.961s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d5.0\x2dpart1.device
3.961s dev-disk-by\x2did-wwn\x2d0x5002538f01c4919e\x2dpart1.device
3.960s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e1:00.0\x2dnvme\x2d1\x2dpart-by\x2dpartnum-1.device
3.960s dev-disk-by\x2ddiskseq-5\x2dpart1.device
3.960s sys-devices-pci0000:00-0000:00:0e.0-pci10000:e0-10000:e0:06.0-10000:e1:00.0-nvme-nvme0-nvme0n1-nvme0n1p1.device
3.960s dev-disk-by\x2did-nvme\x2deui.002538bc31a0859d\x2dpart1.device
3.960s dev-nvme0n1p1.device
3.960s dev-disk-by\x2did-nvme\x2dSamsung_SSD_980_PRO_1TB_S5GXNU0WC15399B_1\x2dpart1.device
3.960s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e1:00.0\x2dnvme\x2d1\x2dpart-by\x2duuid-BFB3\x2d965C.device
3.960s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e1:00.0\x2dnvme\x2d1\x2dpart1.device
3.960s dev-disk-by\x2dpartuuid-1c714600\x2d8444\x2d48d1\x2d85f5\x2d1bb6e1075940.device
3.960s dev-disk-by\x2duuid-BFB3\x2d965C.device
3.960s dev-disk-by\x2did-nvme\x2dSamsung_SSD_980_PRO_1TB_S5GXNU0WC15399B\x2dpart1.device
3.960s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e1:00.0\x2dnvme\x2d1\x2dpart-by\x2dpartuuid-1c714600\x2d8444\x2d48d1\x2d85f5\x2d1bb6e1075940.device
3.960s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e1:00.0\x2dnvme\x2d1\x2dpart2.device
3.960s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e1:00.0\x2dnvme\x2d1\x2dpart-by\x2dpartuuid-479de418\x2dd005\x2d4aff\x2db4c2\x2d129ec7d5f26d.device
3.960s dev-disk-by\x2did-nvme\x2dSamsung_SSD_980_PRO_1TB_S5GXNU0WC15399B\x2dpart2.device
3.960s dev-disk-by\x2dpartuuid-479de418\x2dd005\x2d4aff\x2db4c2\x2d129ec7d5f26d.device
3.960s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e1:00.0\x2dnvme\x2d1\x2dpart-by\x2dpartlabel-root.device
3.960s dev-disk-by\x2duuid-206eec02\x2d6fca\x2d4d04\x2d910e\x2d2bf9fddca883.device
3.960s dev-disk-by\x2dpartlabel-root.device
3.960s dev-disk-by\x2did-nvme\x2deui.002538bc31a0859d\x2dpart2.device
3.960s dev-nvme0n1p2.device
3.960s sys-devices-pci0000:00-0000:00:0e.0-pci10000:e0-10000:e0:06.0-10000:e1:00.0-nvme-nvme0-nvme0n1-nvme0n1p2.device
3.960s dev-disk-by\x2did-nvme\x2dSamsung_SSD_980_PRO_1TB_S5GXNU0WC15399B_1\x2dpart2.device
3.960s dev-disk-by\x2ddiskseq-5\x2dpart2.device
3.960s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e1:00.0\x2dnvme\x2d1\x2dpart-by\x2duuid-206eec02\x2d6fca\x2d4d04\x2d910e\x2d2bf9fddca883.device
3.960s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e1:00.0\x2dnvme\x2d1\x2dpart-by\x2dpartnum-2.device
3.958s dev-disk-by\x2did-ata\x2dSAMSUNG_MZ7L3480HCHQ\x2d00A07_S664NE0RC26616.device
3.958s dev-disk-by\x2did-wwn\x2d0x5002538f01c4919e.device
3.958s dev-disk-by\x2ddiskseq-1.device
3.958s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d5.0.device
3.958s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d5.device
3.958s dev-sda.device
3.958s sys-devices-pci0000:00-0000:00:0e.0-pci10000:e0-10000:e0:17.0-ata5-host4-target4:0:0-4:0:0:0-block-sda.device
3.944s dev-disk-by\x2did-nvme\x2deui.002538bc31a0859d.device
3.944s dev-disk-by\x2did-nvme\x2dSamsung_SSD_980_PRO_1TB_S5GXNU0WC15399B.device
3.944s dev-disk-by\x2ddiskseq-5.device
3.944s sys-devices-pci0000:00-0000:00:0e.0-pci10000:e0-10000:e0:06.0-10000:e1:00.0-nvme-nvme0-nvme0n1.device
3.944s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e1:00.0\x2dnvme\x2d1.device
3.944s dev-disk-by\x2did-nvme\x2dSamsung_SSD_980_PRO_1TB_S5GXNU0WC15399B_1.device
3.944s dev-nvme0n1.device
3.864s sys-devices-pci0000:00-0000:00:0e.0-pci10000:e0-10000:e0:17.0-ata8-host7-target7:0:0-7:0:0:0-block-sdd.device
3.864s dev-disk-by\x2ddiskseq-4.device
3.864s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d8.0.device
3.864s dev-disk-by\x2did-ata\x2dST3500413AS_Z2A6CBV3.device
3.864s dev-sdd.device
3.864s dev-disk-by\x2did-wwn\x2d0x5000c500354eb714.device
3.864s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d8.device
3.843s dev-disk-by\x2did-wwn\x2d0x5000c50035524a31.device
3.843s sys-devices-pci0000:00-0000:00:0e.0-pci10000:e0-10000:e0:17.0-ata6-host5-target5:0:0-5:0:0:0-block-sdb.device
3.843s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d6.device
3.843s dev-sdb.device
3.843s dev-disk-by\x2did-ata\x2dST3500413AS_Z2A6BAMD.device
3.843s dev-disk-by\x2ddiskseq-2.device
3.843s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d6.0.device
3.817s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d8\x2dpart1.device
3.817s dev-disk-by\x2ddiskseq-4\x2dpart1.device
3.817s dev-disk-by\x2duuid-51df8341\x2d0b68\x2d4455\x2d9101\x2dd673d923deb0.device
3.817s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d8.0\x2dpart-by\x2dpartnum-1.device
3.817s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d8.0\x2dpart-by\x2dpartuuid-b292e7b1\x2d2e38\x2d48b8\x2db98a\x2d5e4aec940586.device
3.817s dev-disk-by\x2dpartuuid-b292e7b1\x2d2e38\x2d48b8\x2db98a\x2d5e4aec940586.device
3.817s dev-disk-by\x2did-wwn\x2d0x5000c500354eb714\x2dpart1.device
3.817s dev-disk-by\x2did-ata\x2dST3500413AS_Z2A6CBV3\x2dpart1.device
3.817s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d8.0\x2dpart-by\x2duuid-51df8341\x2d0b68\x2d4455\x2d9101\x2dd673d923deb0.device
3.817s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d8.0\x2dpart1.device
3.817s sys-devices-pci0000:00-0000:00:0e.0-pci10000:e0-10000:e0:17.0-ata8-host7-target7:0:0-7:0:0:0-block-sdd-sdd1.device
3.817s dev-sdd1.device
3.690s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d6\x2dpart1.device
3.690s dev-disk-by\x2did-ata\x2dST3500413AS_Z2A6BAMD\x2dpart1.device
3.690s sys-devices-pci0000:00-0000:00:0e.0-pci10000:e0-10000:e0:17.0-ata6-host5-target5:0:0-5:0:0:0-block-sdb-sdb1.device
3.690s dev-disk-by\x2dlabel-VMs.device
3.690s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d6.0\x2dpart-by\x2duuid-C4CE9330CE9319AE.device
3.690s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d6.0\x2dpart1.device
3.690s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d6.0\x2dpart-by\x2dpartnum-1.device
3.690s dev-disk-by\x2did-wwn\x2d0x5000c50035524a31\x2dpart1.device
3.690s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d6.0\x2dpart-by\x2dlabel-VMs.device
3.690s dev-disk-by\x2dpartuuid-2d6b7785\x2d01.device
3.690s dev-sdb1.device
3.690s dev-disk-by\x2duuid-C4CE9330CE9319AE.device
3.690s dev-disk-by\x2ddiskseq-2\x2dpart1.device
3.690s dev-disk-by\x2dpath-pci\x2d0000:00:0e.0\x2dpci\x2d10000:e0:17.0\x2data\x2d6.0\x2dpart-by\x2dpartuuid-2d6b7785\x2d01.device
3.103s dracut-initqueue.service
1.818s sys-devices-pci0000:00-0000:00:14.0-usb1-1\x2d4-1\x2d4.4-1\x2d4.4:1.1-0003:046D:C22D.0006-leds-g15::kbd_backlight.device
1.223s boot-efi.mount
1.023s man-db.service
 915ms linux-modules-cleanup.service
 715ms initrd-switch-root.service
 531ms mnt-github.mount
 523ms NetworkManager.service
 402ms dev-zram0.swap
 319ms systemd-backlight@leds:g15::kbd_backlight.service
 259ms ldconfig.service
 191ms dracut-cmdline.service
 172ms dracut-pre-udev.service
 165ms systemd-oomd.service
 147ms systemd-tmpfiles-setup-dev-early.service
 126ms systemd-userdbd.service
 123ms systemd-remount-fs.service
 120ms user@1000.service
 112ms dracut-pre-trigger.service
 107ms systemd-journal-flush.service
  88ms systemd-tmpfiles-clean.service
  75ms systemd-udev-trigger.service
  73ms lvm2-monitor.service
  71ms dracut-pre-pivot.service
  60ms logrotate.service
  56ms systemd-timesyncd.service
  56ms accounts-daemon.service
  53ms systemd-tmpfiles-setup.service
  51ms systemd-journald.service
  50ms systemd-tmpfiles-setup-dev.service
  49ms systemd-zram-setup@zram0.service
  47ms initrd-cleanup.service
  46ms polkit.service
  45ms nmb.service
  45ms initrd-parse-etc.service
  43ms smb.service
  43ms dracut-pre-mount.service
  43ms systemd-fsck-root.service
  42ms upower.service
  41ms libvirtd.service
  40ms virtlogd.service
  40ms ModemManager.service
  39ms power-profiles-daemon.service
  39ms udisks2.service
  38ms systemd-logind.service
  34ms systemd-hostnamed.service
  34ms systemd-udevd.service
  32ms lm_sensors.service
  32ms systemd-sysusers.service
  31ms systemd-random-seed.service
  28ms dev-hugepages.mount
  28ms dev-mqueue.mount
  28ms systemd-vconsole-setup.service
  28ms sys-kernel-debug.mount
  27ms sys-kernel-tracing.mount
  27ms colord.service
  27ms kmod-static-nodes.service
  25ms systemd-fsck@dev-disk-by\x2duuid-BFB3\x2d965C.service
  25ms avahi-daemon.service
  23ms systemd-user-sessions.service
  23ms initrd-udevadm-cleanup-db.service
  21ms modprobe@dm_mod.service
  21ms modprobe@loop.service
  21ms modprobe@configfs.service
  18ms modprobe@fuse.service
  18ms rtkit-daemon.service
  15ms user-runtime-dir@1000.service
  14ms systemd-modules-load.service
  14ms modprobe@drm.service
  13ms systemd-update-done.service
  13ms mnt-data.mount
  12ms dbus-broker.service
  12ms systemd-udev-load-credentials.service
  11ms systemd-machined.service
  11ms systemd-sysctl.service
  10ms systemd-journal-catalog-update.service
   9ms systemd-binfmt.service
   9ms dracut-shutdown.service
   8ms home.mount
   8ms srv.mount
   8ms garuda-pacman-lock.service
   7ms root.mount
   7ms var-cache.mount
   6ms var-log.mount
   6ms sys-fs-fuse-connections.mount
   6ms var-tmp.mount
   5ms systemd-update-utmp.service
   3ms proc-sys-fs-binfmt_misc.mount
   3ms tmp.mount
The time when unit became active or started is printed after the "@" character.
The time the unit took to start is printed after the "+" character.

graphical.target @9.485s
`-multi-user.target @9.485s
  `-smb.service @9.441s +43ms
    `-nmb.service @9.394s +45ms
      `-network-online.target @9.393s
        `-NetworkManager-wait-online.service @3.640s +5.752s
          `-NetworkManager.service @3.116s +523ms
            `-basic.target @3.115s
              `-dbus-broker.service @3.101s +12ms
                `-dbus.socket @3.097s
                  `-sysinit.target @3.096s
                    `-systemd-update-done.service @3.082s +13ms
                      `-ldconfig.service @2.822s +259ms
                        `-systemd-tmpfiles-setup.service @2.768s +53ms
                          `-local-fs.target @2.756s
                            `-boot-efi.mount @1.533s +1.223s
                              `-systemd-fsck@dev-disk-by\x2duuid-BFB3\x2d965C.service @936ms +25ms
                                `-dev-disk-by\x2duuid-BFB3\x2d965C.device
### END systemd-analyze blame --no-pager && systemd-analyze critical-chain --no-pager ###
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="line"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="keyValues"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][webview:trace@tauri://localhost/main-BBVWX35Y.js:773:821] Updates: haskell-regex-tdfa 1.3.2.4-8 -> 1.3.2.4-9
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; response="null"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; mime_type="application/json"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle; uri="ipc://localhost/plugin%3Alog%7Clog"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][tracing::span] wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; kind="custom-protocol"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; request="{\"level\":1,\"location\":\"trace@tauri://localhost/main-BBVWX35Y.js:773:821\",\"message\":\"Updates: haskell-semialign 1.3-36 -> 1.3-37\"}"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::handle; cmd="plugin:log|log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::plugin] plugin::hooks::ipc; name="log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tauri_plugin_log] ipc::request::handler; cmd="log" kind="sync" loc.line=0 loc.col=0 is_internal=false
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tracing::span] ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="level"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="message"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="location"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="file"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="line"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="keyValues"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][webview:trace@tauri://localhost/main-BBVWX35Y.js:773:821] Updates: haskell-semialign 1.3-36 -> 1.3-37
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; response="null"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; mime_type="application/json"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle; uri="ipc://localhost/plugin%3Alog%7Clog"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][tracing::span] wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; kind="custom-protocol"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; request="{\"level\":1,\"location\":\"trace@tauri://localhost/main-BBVWX35Y.js:773:821\",\"message\":\"Updates: haskell-semigroupoids 6.0.1-19 -> 6.0.1-20\"}"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::handle; cmd="plugin:log|log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::plugin] plugin::hooks::ipc; name="log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tauri_plugin_log] ipc::request::handler; cmd="log" kind="sync" loc.line=0 loc.col=0 is_internal=false
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tracing::span] ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="level"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="message"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="location"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="file"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="line"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="keyValues"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][webview:trace@tauri://localhost/main-BBVWX35Y.js:773:821] Updates: haskell-semigroupoids 6.0.1-19 -> 6.0.1-20
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; response="null"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; mime_type="application/json"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle; uri="ipc://localhost/plugin%3Alog%7Clog"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][tracing::span] wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; kind="custom-protocol"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; request="{\"level\":1,\"location\":\"trace@tauri://localhost/main-BBVWX35Y.js:773:821\",\"message\":\"Updates: haskell-strict 0.5-66 -> 0.5-68\"}"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::handle; cmd="plugin:log|log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::plugin] plugin::hooks::ipc; name="log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tauri_plugin_log] ipc::request::handler; cmd="log" kind="sync" loc.line=0 loc.col=0 is_internal=false
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tracing::span] ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="level"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="message"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="location"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="file"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="line"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="keyValues"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][webview:trace@tauri://localhost/main-BBVWX35Y.js:773:821] Updates: haskell-strict 0.5-66 -> 0.5-68
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; response="null"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; mime_type="application/json"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle; uri="ipc://localhost/plugin%3Alog%7Clog"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][tracing::span] wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; kind="custom-protocol"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; request="{\"level\":1,\"location\":\"trace@tauri://localhost/main-BBVWX35Y.js:773:821\",\"message\":\"Updates: haskell-these 1.2.1-4 -> 1.2.1-6\"}"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::handle; cmd="plugin:log|log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::plugin] plugin::hooks::ipc; name="log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tauri_plugin_log] ipc::request::handler; cmd="log" kind="sync" loc.line=0 loc.col=0 is_internal=false
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tracing::span] ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="level"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="message"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="location"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="file"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="line"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="keyValues"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][webview:trace@tauri://localhost/main-BBVWX35Y.js:773:821] Updates: haskell-these 1.2.1-4 -> 1.2.1-6
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; response="null"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; mime_type="application/json"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle; uri="ipc://localhost/plugin%3Alog%7Clog"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][tracing::span] wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; kind="custom-protocol"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; request="{\"level\":1,\"location\":\"trace@tauri://localhost/main-BBVWX35Y.js:773:821\",\"message\":\"Updates: haskell-unordered-containers 0.2.20-56 -> 0.2.20-57\"}"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::handle; cmd="plugin:log|log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::plugin] plugin::hooks::ipc; name="log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tauri_plugin_log] ipc::request::handler; cmd="log" kind="sync" loc.line=0 loc.col=0 is_internal=false
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tracing::span] ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="level"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="message"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="location"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="file"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="line"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="keyValues"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][webview:trace@tauri://localhost/main-BBVWX35Y.js:773:821] Updates: haskell-unordered-containers 0.2.20-56 -> 0.2.20-57
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; response="null"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; mime_type="application/json"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle; uri="ipc://localhost/plugin%3Alog%7Clog"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][tracing::span] wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; kind="custom-protocol"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; request="{\"level\":1,\"location\":\"trace@tauri://localhost/main-BBVWX35Y.js:773:821\",\"message\":\"Updates: haskell-witherable 0.4.2-154 -> 0.4.2-155\"}"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::handle; cmd="plugin:log|log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::plugin] plugin::hooks::ipc; name="log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tauri_plugin_log] ipc::request::handler; cmd="log" kind="sync" loc.line=0 loc.col=0 is_internal=false
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tracing::span] ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="level"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="message"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="location"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="file"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="line"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="keyValues"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][webview:trace@tauri://localhost/main-BBVWX35Y.js:773:821] Updates: haskell-witherable 0.4.2-154 -> 0.4.2-155
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; response="null"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; mime_type="application/json"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle; uri="ipc://localhost/plugin%3Alog%7Clog"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][tracing::span] wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; kind="custom-protocol"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; request="{\"level\":1,\"location\":\"trace@tauri://localhost/main-BBVWX35Y.js:773:821\",\"message\":\"Updates: hwdata 0.396-1 -> 0.397-1\"}"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::handle; cmd="plugin:log|log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::plugin] plugin::hooks::ipc; name="log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tauri_plugin_log] ipc::request::handler; cmd="log" kind="sync" loc.line=0 loc.col=0 is_internal=false
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tracing::span] ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="level"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="message"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="location"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="file"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="line"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="keyValues"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][webview:trace@tauri://localhost/main-BBVWX35Y.js:773:821] Updates: hwdata 0.396-1 -> 0.397-1
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; response="null"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; mime_type="application/json"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle; uri="ipc://localhost/plugin%3Alog%7Clog"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][tracing::span] wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; kind="custom-protocol"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; request="{\"level\":1,\"location\":\"trace@tauri://localhost/main-BBVWX35Y.js:773:821\",\"message\":\"Updates: intellij-idea-community-edition 4:2025.1.2-1 -> 4:2025.1.3-1\"}"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::handle; cmd="plugin:log|log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::plugin] plugin::hooks::ipc; name="log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tauri_plugin_log] ipc::request::handler; cmd="log" kind="sync" loc.line=0 loc.col=0 is_internal=false
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tracing::span] ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="level"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="message"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="location"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="file"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="line"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="keyValues"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][webview:trace@tauri://localhost/main-BBVWX35Y.js:773:821] Updates: intellij-idea-community-edition 4:2025.1.2-1 -> 4:2025.1.3-1
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; response="null"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; mime_type="application/json"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle; uri="ipc://localhost/plugin%3Alog%7Clog"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][tracing::span] wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; kind="custom-protocol"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; request="{\"level\":1,\"location\":\"trace@tauri://localhost/main-BBVWX35Y.js:773:821\",\"message\":\"Updates: jq 1.8.0-1 -> 1.8.1-1\"}"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::handle; cmd="plugin:log|log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::plugin] plugin::hooks::ipc; name="log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tauri_plugin_log] ipc::request::handler; cmd="log" kind="sync" loc.line=0 loc.col=0 is_internal=false
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tracing::span] ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="level"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="message"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="location"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="file"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="line"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="keyValues"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][webview:trace@tauri://localhost/main-BBVWX35Y.js:773:821] Updates: jq 1.8.0-1 -> 1.8.1-1
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; response="null"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; mime_type="application/json"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle; uri="ipc://localhost/plugin%3Alog%7Clog"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][tracing::span] wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; kind="custom-protocol"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request; request="{\"level\":1,\"location\":\"trace@tauri://localhost/main-BBVWX35Y.js:773:821\",\"message\":\"Updates: kaccounts-integration 25.04.2-1 -> 25.04.3-1\"}"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::handle; cmd="plugin:log|log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::plugin] plugin::hooks::ipc; name="log"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tauri_plugin_log] ipc::request::handler; cmd="log" kind="sync" loc.line=0 loc.col=0 is_internal=false
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][DEBUG][tracing::span] ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="level"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="message"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="location"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="file"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="line"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="keyValues"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][webview:trace@tauri://localhost/main-BBVWX35Y.js:773:821] Updates: kaccounts-integration 25.04.2-1 -> 25.04.3-1
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; response="null"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tauri::ipc::protocol] ipc::request::response; mime_type="application/json"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::response;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::respond;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request::run;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- plugin::hooks::ipc;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- ipc::request;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] <- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span] -- wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::handle;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle; uri="ipc://localhost/plugin%3Alog%7Clog"
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][INFO][tracing::span] wry::custom_protocol::call_handler;
Jul 12 22:15:27 matthias garuda-rani[2254467]: [2025-07-12][22:15:27][TRACE][tracing::span::active] -> wry::custom_protocol::call_handler;
Jul 12 22:15:33 matthias systemd[1]: systemd-hostnamed.service: Deactivated successfully.
-- Subject: Unit succeeded
-- Defined-By: systemd
-- Support: https://lists.freedesktop.org/mailman/listinfo/systemd-devel
-- 
-- The unit systemd-hostnamed.service has successfully entered the 'dead' state.
Jul 12 22:15:36 matthias polkit-kde-authentication-agent-1[2252237]: Listener adapter polkit_qt_listener_initiate_authentication
Jul 12 22:15:36 matthias polkit-kde-authentication-agent-1[2252237]: GSimpleAsyncResult: 0x5556d31c6be0
Jul 12 22:15:36 matthias polkit-kde-authentication-agent-1[2252237]: polkit_qt_listener_initiate_authentication callback for  0x5556d31b8440
Jul 12 22:15:36 matthias polkit-kde-authentication-agent-1[2252237]: Initiating authentication
Jul 12 22:15:36 matthias polkit-kde-authentication-agent-1[2252237]: Action description has been found
Jul 12 22:15:36 matthias polkit-kde-authentication-agent-1[2252237]: User:  "unix-user:administrator"
Jul 12 22:15:36 matthias polkit-kde-authentication-agent-1[2252237]: Trying again
Jul 12 22:15:36 matthias polkit-kde-authentication-agent-1[2252237]: REQUEST
Jul 12 22:15:36 matthias polkit-kde-authentication-agent-1[2252237]: Request:  "Password: "  echo:  false
Jul 12 22:15:43 matthias systemd-journald[744]: Suppressed 25533 messages from user@1000.service
-- Subject: Messages from a service have been suppressed
-- Defined-By: systemd
-- Support: https://lists.freedesktop.org/mailman/listinfo/systemd-devel
-- Documentation: man:journald.conf(5)
-- 
-- A service has logged too many messages within a time period. Messages
-- from the service have been dropped.
-- 
-- Note that only messages from the service in question have been
-- dropped, other services' messages are unaffected.
-- 
-- The limits controlling when messages are dropped may be configured
-- with RateLimitIntervalSec= and RateLimitBurst= in
-- /etc/systemd/journald.conf or LogRateLimitIntervalSec= and LogRateLimitBurst=
-- in the unit file. See journald.conf(5) and systemd.exec(5) for details.
Jul 12 22:15:43 matthias pkexec[2256476]: pam_unix(polkit-1:session): session opened for user root(uid=0) by administrator(uid=1000)
Jul 12 22:15:43 matthias pkexec[2256476]: administrator: Executing command [USER=root] [TTY=unknown] [CWD=/home/administrator] [COMMAND=/usr/bin/snapper-tools find-old]
Jul 12 22:15:44 matthias systemd[1]: run-snapper\x2dtools\x2dxPDlHy.mount: Deactivated successfully.
-- Subject: Unit succeeded
-- Defined-By: systemd
-- Support: https://lists.freedesktop.org/mailman/listinfo/systemd-devel
-- 
-- The unit run-snapper\x2dtools\x2dxPDlHy.mount has successfully entered the 'dead' state.
Jul 12 22:15:54 matthias polkit-kde-authentication-agent-1[2252237]: Dialog accepted
Jul 12 22:15:54 matthias unix_chkpwd[2256496]: password check failed for user (administrator)
Jul 12 22:15:54 matthias polkit-agent-helper-1[2254834]: pam_unix(polkit-1:auth): authentication failure; logname=administrator uid=1000 euid=0 tty= ruser=administrator rhost=  user=administrator
Jul 12 22:15:56 matthias polkit-kde-authentication-agent-1[2254834]: polkit-agent-helper-1: pam_authenticate failed: Authentication failure
Jul 12 22:15:56 matthias polkit-kde-authentication-agent-1[2252237]: COMPLETED
Jul 12 22:15:56 matthias polkit-kde-authentication-agent-1[2252237]: Completed:  false
Jul 12 22:15:56 matthias polkit-kde-authentication-agent-1[2252237]: Finishing obtaining privileges
Jul 12 22:15:56 matthias polkit-kde-authentication-agent-1[2252237]: Trying again
Jul 12 22:15:56 matthias polkit-kde-authentication-agent-1[2252237]: REQUEST
Jul 12 22:15:56 matthias polkit-kde-authentication-agent-1[2252237]: Request:  "Password: "  echo:  false
Jul 12 22:16:00 matthias polkit-kde-authentication-agent-1[2252237]: Dialog accepted
Jul 12 22:16:00 matthias polkit-kde-authentication-agent-1[2252237]: COMPLETED
Jul 12 22:16:00 matthias polkit-kde-authentication-agent-1[2252237]: Completed:  true
Jul 12 22:16:00 matthias polkit-kde-authentication-agent-1[2252237]: Finishing obtaining privileges
Jul 12 22:16:00 matthias polkit-kde-authentication-agent-1[2252237]: Listener adapter polkit_qt_listener_initiate_authentication_finish
Jul 12 22:16:00 matthias polkit-kde-authentication-agent-1[2252237]: polkit_qt_listener_initiate_authentication_finish callback for  0x5556d31b8440
Jul 12 22:16:00 matthias polkit-kde-authentication-agent-1[2252237]: Finish obtain authorization: true
Jul 12 22:16:00 matthias polkit-kde-authentication-agent-1[2252237]: Dialog cancelled
Jul 12 22:16:00 matthias polkit-kde-authentication-agent-1[2252237]: Finishing obtaining privileges
Jul 12 22:16:00 matthias polkit-kde-authentication-agent-1[2252237]: Finish obtain authorization: true
Jul 12 22:16:00 matthias polkitd[1231]: Operator of unix-session:5 successfully authenticated as unix-user:administrator to gain ONE-SHOT authorization for action org.freedesktop.policykit.exec for unix-process:2254467:3245489 [/usr/bin/garuda-rani] (owned by unix-user:administrator)
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][INFO][tauri::manager] app::emit::filter; event=EventName("tauri://focus")
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> app::emit::filter;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][DEBUG][tracing::span] emit::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> emit::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][DEBUG][tracing::span] window::emit::serialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> window::emit::serialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- window::emit::serialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- window::emit::serialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- emit::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- emit::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- app::emit::filter;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- app::emit::filter;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][INFO][tauri::manager] app::emit::filter; event=EventName("tauri://move")
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> app::emit::filter;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][DEBUG][tracing::span] emit::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> emit::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][DEBUG][tracing::span] window::emit::serialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> window::emit::serialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- window::emit::serialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- window::emit::serialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- emit::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- emit::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- app::emit::filter;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- app::emit::filter;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][INFO][tauri::manager] app::emit::filter; event=EventName("tauri://resize")
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> app::emit::filter;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][DEBUG][tracing::span] emit::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> emit::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][DEBUG][tracing::span] window::emit::serialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> window::emit::serialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- window::emit::serialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- window::emit::serialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][DEBUG][tracing::span] wry::eval;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> wry::eval;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- emit::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- emit::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- app::emit::filter;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- app::emit::filter;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> wry::custom_protocol::handle;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle; uri="ipc://localhost/plugin%3Alog%7Clog"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][INFO][tracing::span] wry::custom_protocol::call_handler;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> wry::custom_protocol::call_handler;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tauri::ipc::protocol] ipc::request; kind="custom-protocol"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] ipc::request::deserialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request::deserialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request::deserialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request::deserialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tauri::ipc::protocol] ipc::request; request="{\"level\":1,\"location\":\"trace@tauri://localhost/main-BBVWX35Y.js:773:821\",\"message\":\"Resize window event\"}"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tauri::ipc::protocol] ipc::request::handle; cmd="plugin:log|log"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tauri::plugin] plugin::hooks::ipc; name="log"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> plugin::hooks::ipc;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][DEBUG][tauri_plugin_log] ipc::request::handler; cmd="log" kind="sync" loc.line=0 loc.col=0 is_internal=false
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request::handler;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request::handler;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request::handler;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][DEBUG][tracing::span] ipc::request::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="level"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="message"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="location"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="file"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="line"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="keyValues"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][webview:trace@tauri://localhost/main-BBVWX35Y.js:773:821] Resize window event
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] ipc::request::respond;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request::respond;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tauri::ipc::protocol] ipc::request::response; response="null"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request::response;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tauri::ipc::protocol] ipc::request::response; mime_type="application/json"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request::response;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request::response;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request::respond;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request::respond;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request::handle;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- plugin::hooks::ipc;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- plugin::hooks::ipc;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- wry::custom_protocol::call_handler;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- wry::custom_protocol::call_handler;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- wry::custom_protocol::handle;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- wry::custom_protocol::handle;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> wry::custom_protocol::handle;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][INFO][wry::webkitgtk::web_context] wry::custom_protocol::handle; uri="ipc://localhost/plugin%3Awindow%7Cis_maximized"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][INFO][tracing::span] wry::custom_protocol::call_handler;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> wry::custom_protocol::call_handler;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tauri::ipc::protocol] ipc::request; kind="custom-protocol"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] ipc::request::deserialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request::deserialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request::deserialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request::deserialize;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tauri::ipc::protocol] ipc::request; request="{\"label\":\"main\"}"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tauri::ipc::protocol] ipc::request::handle; cmd="plugin:window|is_maximized"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tauri::plugin] plugin::hooks::ipc; name="window"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> plugin::hooks::ipc;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][DEBUG][tauri::window::plugin] ipc::request::handler; cmd="is_maximized" kind="async" loc.line=0 loc.col=0 is_internal=false
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request::handler;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request::handler;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request::handler;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][DEBUG][tracing::span] ipc::request::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- plugin::hooks::ipc;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- plugin::hooks::ipc;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- wry::custom_protocol::call_handler;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- wry::custom_protocol::call_handler;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- wry::custom_protocol::handle;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- wry::custom_protocol::handle;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tauri::ipc::command] ipc::request::deserialize_arg; arg="label"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request::deserialize_arg;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- wry::eval;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- wry::eval;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request::run;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] ipc::request::respond;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request::respond;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tauri::ipc::protocol] ipc::request::response; response="false"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] -> ipc::request::response;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tauri::ipc::protocol] ipc::request::response; mime_type="application/json"
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request::response;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request::response;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span::active] <- ipc::request::respond;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request::respond;
Jul 12 22:16:00 matthias garuda-rani[2254467]: [2025-07-12][22:16:00][TRACE][tracing::span] -- ipc::request::handle;
Jul 12 22:16:00 matthias pkexec[2254825]: pam_unix(polkit-1:session): session opened for user root(uid=0) by administrator(uid=1000)
Jul 12 22:16:00 matthias pkexec[2254825]: administrator: Executing command [USER=root] [TTY=unknown] [CWD=/home/administrator] [COMMAND=/usr/bin/sh -c echo "### inxi ###"; garuda-inxi; echo "### END garuda-inxi ###"; echoecho "### systemd-analyze ###"; systemd-analyze blame --no-pager && systemd-analyze critical-chain --no-pager; echo "### END systemd-analyze blame --no-pager && systemd-analyze critical-chain --no-pager ###"; echoecho "### journalctl ###"; journalctl -xe --no-pager; echo "### END journalctl -xe --no-pager ###"; echoecho "### dmesg ###"; dmesg; echo "### END dmesg ###"; echo]
Jul 12 22:16:03 matthias kernel: SGI XFS with ACLs, security attributes, realtime, scrub, repair, quota, no debug enabled
Jul 12 22:16:03 matthias kernel: JFS: nTxBlock = 8192, nTxLock = 65536
Jul 12 22:16:04 matthias root[2258488]: os-prober: debug: running /usr/lib/os-probes/mounted/05efi on mounted /dev/nvme0n1p1
Jul 12 22:16:04 matthias root[2258488]: 05efi: debug: /dev/nvme0n1p1 is a FAT32 partition
Jul 12 22:16:04 matthias root[2258488]: 05efi: debug: /dev/nvme0n1p1 partition scheme is gpt
Jul 12 22:16:04 matthias root[2258488]: 05efi: debug: /dev/nvme0n1p1 partition type is c12a7328-f81f-11d2-ba4b-00a0c93ec93b
Jul 12 22:16:04 matthias root[2258488]: 05efi: debug: running subtest /usr/lib/os-probes/mounted/efi/10elilo
Jul 12 22:16:04 matthias root[2258488]: 05efi: debug: running subtest /usr/lib/os-probes/mounted/efi/20microsoft
Jul 12 22:16:04 matthias root[2258488]: os-prober: debug: running /usr/lib/os-probes/mounted/10freedos on mounted /dev/nvme0n1p1
Jul 12 22:16:04 matthias root[2258488]: 10freedos: debug: /dev/nvme0n1p1 is a FAT32 partition
Jul 12 22:16:04 matthias root[2258488]: os-prober: debug: running /usr/lib/os-probes/mounted/10qnx on mounted /dev/nvme0n1p1
Jul 12 22:16:04 matthias root[2258488]: 10qnx: debug: /dev/nvme0n1p1 is not a QNX4 partition: exiting
Jul 12 22:16:04 matthias root[2258488]: os-prober: debug: running /usr/lib/os-probes/mounted/20macosx on mounted /dev/nvme0n1p1
Jul 12 22:16:04 matthias macosx-prober[2258564]: debug: /dev/nvme0n1p1 is not an HFS+ partition: exiting
Jul 12 22:16:04 matthias root[2258488]: os-prober: debug: running /usr/lib/os-probes/mounted/20microsoft on mounted /dev/nvme0n1p1
Jul 12 22:16:04 matthias root[2258488]: 20microsoft: debug: Skipping legacy bootloaders on UEFI system
Jul 12 22:16:04 matthias root[2258488]: os-prober: debug: running /usr/lib/os-probes/mounted/30utility on mounted /dev/nvme0n1p1
Jul 12 22:16:04 matthias root[2258488]: 30utility: debug: /dev/nvme0n1p1 is a FAT32 partition
Jul 12 22:16:04 matthias root[2258488]: os-prober: debug: running /usr/lib/os-probes/mounted/40lsb on mounted /dev/nvme0n1p1
Jul 12 22:16:04 matthias root[2258488]: os-prober: debug: running /usr/lib/os-probes/mounted/70hurd on mounted /dev/nvme0n1p1
Jul 12 22:16:04 matthias root[2258488]: os-prober: debug: running /usr/lib/os-probes/mounted/80minix on mounted /dev/nvme0n1p1
Jul 12 22:16:04 matthias root[2258488]: os-prober: debug: running /usr/lib/os-probes/mounted/83haiku on mounted /dev/nvme0n1p1
Jul 12 22:16:04 matthias root[2258488]: 83haiku: debug: /dev/nvme0n1p1 is not a BeFS partition: exiting
Jul 12 22:16:04 matthias root[2258488]: os-prober: debug: running /usr/lib/os-probes/mounted/90linux-distro on mounted /dev/nvme0n1p1
Jul 12 22:16:04 matthias root[2258488]: os-prober: debug: running /usr/lib/os-probes/mounted/90linux-distro.orig on mounted /dev/nvme0n1p1
Jul 12 22:16:04 matthias root[2258488]: os-prober: debug: running /usr/lib/os-probes/mounted/90solaris on mounted /dev/nvme0n1p1
Jul 12 22:16:04 matthias root[2258488]: os-prober: debug: btrfs volume uuid=206eec02-6fca-4d04-910e-2bf9fddca883 partition=/dev/nvme0n1p2
Jul 12 22:16:04 matthias root[2258488]: os-prober: debug: running /usr/lib/os-probes/50mounted-tests on btrfs /dev/nvme0n1p2
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: btrfs volume 206eec02-6fca-4d04-910e-2bf9fddca883 mounted
Jul 12 22:16:04 matthias systemd[1]: var-lib-os\x2dprober-mount.mount: Deactivated successfully.
-- Subject: Unit succeeded
-- Defined-By: systemd
-- Support: https://lists.freedesktop.org/mailman/listinfo/systemd-devel
-- 
-- The unit var-lib-os\x2dprober-mount.mount has successfully entered the 'dead' state.
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883 subvol=@
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883 subvol=@home
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/90linux-distro
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883 subvol=@root
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/90linux-distro
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883 subvol=@srv
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/90linux-distro
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883 subvol=@cache
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/90linux-distro
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883 subvol=@log
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/90linux-distro
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883 subvol=@tmp
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/90linux-distro
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883 subvol=@/.snapshots
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/90linux-distro
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883 subvol=@/.snapshots/31/snapshot
Jul 12 22:16:04 matthias systemd[1]: var-lib-os\x2dprober-mount.mount: Deactivated successfully.
-- Subject: Unit succeeded
-- Defined-By: systemd
-- Support: https://lists.freedesktop.org/mailman/listinfo/systemd-devel
-- 
-- The unit var-lib-os\x2dprober-mount.mount has successfully entered the 'dead' state.
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883 subvol=@/.snapshots/62/snapshot
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883 subvol=@/.snapshots/63/snapshot
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883 subvol=@/.snapshots/64/snapshot
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883 subvol=@/.snapshots/65/snapshot
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883 subvol=@/.snapshots/66/snapshot
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883 subvol=@/.snapshots/67/snapshot
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883 subvol=@/.snapshots/68/snapshot
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883 subvol=@/.snapshots/69/snapshot
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883 subvol=@/.snapshots/70/snapshot
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 206eec02-6fca-4d04-910e-2bf9fddca883 subvol=@/.snapshots/71/snapshot
Jul 12 22:16:04 matthias root[2258488]: os-prober: debug: btrfs volume uuid=bf97dd75-0621-4d96-8eca-cd1433c9795c partition=/dev/sda1
Jul 12 22:16:04 matthias root[2258488]: os-prober: debug: running /usr/lib/os-probes/50mounted-tests on btrfs /dev/sda1
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for bf97dd75-0621-4d96-8eca-cd1433c9795c
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: btrfs volume bf97dd75-0621-4d96-8eca-cd1433c9795c mounted
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: no subvols found on btrfs volume bf97dd75-0621-4d96-8eca-cd1433c9795c
Jul 12 22:16:04 matthias root[2258488]: os-prober: debug: running /usr/lib/os-probes/50mounted-tests on /dev/sdb1
Jul 12 22:16:04 matthias systemd[1]: systemd-localed.service: Deactivated successfully.
-- Subject: Unit succeeded
-- Defined-By: systemd
-- Support: https://lists.freedesktop.org/mailman/listinfo/systemd-devel
-- 
-- The unit systemd-localed.service has successfully entered the 'dead' state.
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: mounted using GRUB ntfs filesystem driver
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/05efi
Jul 12 22:16:04 matthias root[2258488]: 05efi: debug: /dev/sdb1 is ntfs partition: exiting
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/10freedos
Jul 12 22:16:04 matthias root[2258488]: 10freedos: debug: /dev/sdb1 is not a FAT partition: exiting
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/10qnx
Jul 12 22:16:04 matthias root[2258488]: 10qnx: debug: /dev/sdb1 is not a QNX4 partition: exiting
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/20macosx
Jul 12 22:16:04 matthias macosx-prober[2258787]: debug: /dev/sdb1 is not an HFS+ partition: exiting
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/20microsoft
Jul 12 22:16:04 matthias root[2258488]: 20microsoft: debug: Skipping legacy bootloaders on UEFI system
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/30utility
Jul 12 22:16:04 matthias root[2258488]: 30utility: debug: /dev/sdb1 is not a FAT partition: exiting
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/40lsb
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/70hurd
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/80minix
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/83haiku
Jul 12 22:16:04 matthias root[2258488]: 83haiku: debug: /dev/sdb1 is not a BeFS partition: exiting
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/90linux-distro
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/90linux-distro.orig
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/90solaris
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests: debug: running subtest /usr/lib/os-probes/mounted/efi
Jul 12 22:16:04 matthias root[2258488]: os-prober: debug: running /usr/lib/os-probes/50mounted-tests.orig on /dev/sdb1
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests.orig: debug: mounted using GRUB ntfs filesystem driver
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests.orig: debug: running subtest /usr/lib/os-probes/mounted/05efi
Jul 12 22:16:04 matthias root[2258488]: 05efi: debug: /dev/sdb1 is ntfs partition: exiting
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests.orig: debug: running subtest /usr/lib/os-probes/mounted/10freedos
Jul 12 22:16:04 matthias root[2258488]: 10freedos: debug: /dev/sdb1 is not a FAT partition: exiting
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests.orig: debug: running subtest /usr/lib/os-probes/mounted/10qnx
Jul 12 22:16:04 matthias root[2258488]: 10qnx: debug: /dev/sdb1 is not a QNX4 partition: exiting
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests.orig: debug: running subtest /usr/lib/os-probes/mounted/20macosx
Jul 12 22:16:04 matthias macosx-prober[2258831]: debug: /dev/sdb1 is not an HFS+ partition: exiting
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests.orig: debug: running subtest /usr/lib/os-probes/mounted/20microsoft
Jul 12 22:16:04 matthias root[2258488]: 20microsoft: debug: Skipping legacy bootloaders on UEFI system
Jul 12 22:16:04 matthias root[2258488]: 50mounted-tests.orig: debug: running subtest /usr/lib/os-probes/mounted/30utility
Jul 12 22:16:05 matthias root[2258488]: 30utility: debug: /dev/sdb1 is not a FAT partition: exiting
Jul 12 22:16:05 matthias root[2258488]: 50mounted-tests.orig: debug: running subtest /usr/lib/os-probes/mounted/40lsb
Jul 12 22:16:05 matthias root[2258488]: 50mounted-tests.orig: debug: running subtest /usr/lib/os-probes/mounted/70hurd
Jul 12 22:16:05 matthias root[2258488]: 50mounted-tests.orig: debug: running subtest /usr/lib/os-probes/mounted/80minix
Jul 12 22:16:05 matthias root[2258488]: 50mounted-tests.orig: debug: running subtest /usr/lib/os-probes/mounted/83haiku
Jul 12 22:16:05 matthias root[2258488]: 83haiku: debug: /dev/sdb1 is not a BeFS partition: exiting
Jul 12 22:16:05 matthias root[2258488]: 50mounted-tests.orig: debug: running subtest /usr/lib/os-probes/mounted/90linux-distro
Jul 12 22:16:05 matthias root[2258488]: 50mounted-tests.orig: debug: running subtest /usr/lib/os-probes/mounted/90linux-distro.orig
Jul 12 22:16:05 matthias root[2258488]: 50mounted-tests.orig: debug: running subtest /usr/lib/os-probes/mounted/90solaris
Jul 12 22:16:05 matthias root[2258488]: 50mounted-tests.orig: debug: running subtest /usr/lib/os-probes/mounted/efi
Jul 12 22:16:05 matthias root[2258488]: os-prober: debug: btrfs volume uuid=51df8341-0b68-4455-9101-d673d923deb0 partition=/dev/sdd1
Jul 12 22:16:05 matthias root[2258488]: os-prober: debug: running /usr/lib/os-probes/50mounted-tests on btrfs /dev/sdd1
Jul 12 22:16:05 matthias root[2258488]: 50mounted-tests: debug: begin btrfs processing for 51df8341-0b68-4455-9101-d673d923deb0
Jul 12 22:16:05 matthias root[2258488]: 50mounted-tests: debug: btrfs volume 51df8341-0b68-4455-9101-d673d923deb0 mounted
Jul 12 22:16:05 matthias root[2258488]: 50mounted-tests: debug: no subvols found on btrfs volume 51df8341-0b68-4455-9101-d673d923deb0
Jul 12 22:16:05 matthias systemd[1]: var-lib-os\x2dprober-mount.mount: Deactivated successfully.
-- Subject: Unit succeeded
-- Defined-By: systemd
-- Support: https://lists.freedesktop.org/mailman/listinfo/systemd-devel
-- 
-- The unit var-lib-os\x2dprober-mount.mount has successfully entered the 'dead' state.
### END journalctl -xe --no-pager ###
[    0.000000] Linux version 6.15.4-zen2-1-zen (linux-zen@archlinux) (gcc (GCC) 15.1.1 20250425, GNU ld (GNU Binutils) 2.44.0) #1 ZEN SMP PREEMPT_DYNAMIC Fri, 27 Jun 2025 15:34:50 +0000
[    0.000000] Command line: BOOT_IMAGE=/@/boot/vmlinuz-linux-zen root=UUID=206eec02-6fca-4d04-910e-2bf9fddca883 rw rootflags=subvol=@ quiet loglevel=3 ibt=off
[    0.000000] x86/split lock detection: #AC: crashing the kernel on kernel split_locks and warning on user-space split_locks
[    0.000000] BIOS-provided physical RAM map:
[    0.000000] BIOS-e820: [mem 0x0000000000000000-0x000000000009dfff] usable
[    0.000000] BIOS-e820: [mem 0x000000000009e000-0x000000000009efff] reserved
[    0.000000] BIOS-e820: [mem 0x000000000009f000-0x000000000009ffff] usable
[    0.000000] BIOS-e820: [mem 0x00000000000a0000-0x00000000000fffff] reserved
[    0.000000] BIOS-e820: [mem 0x0000000000100000-0x0000000030f92fff] usable
[    0.000000] BIOS-e820: [mem 0x0000000030f93000-0x0000000030f93fff] reserved
[    0.000000] BIOS-e820: [mem 0x0000000030f94000-0x000000003186afff] usable
[    0.000000] BIOS-e820: [mem 0x000000003186b000-0x000000003496afff] reserved
[    0.000000] BIOS-e820: [mem 0x000000003496b000-0x0000000034bfcfff] ACPI data
[    0.000000] BIOS-e820: [mem 0x0000000034bfd000-0x00000000350cbfff] ACPI NVS
[    0.000000] BIOS-e820: [mem 0x00000000350cc000-0x0000000035ffefff] reserved
[    0.000000] BIOS-e820: [mem 0x0000000035fff000-0x0000000035ffffff] usable
[    0.000000] BIOS-e820: [mem 0x0000000036000000-0x0000000039ffffff] reserved
[    0.000000] BIOS-e820: [mem 0x000000003aa00000-0x000000003abfffff] reserved
[    0.000000] BIOS-e820: [mem 0x000000003b000000-0x00000000403fffff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000c0000000-0x00000000cfffffff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000fc000000-0x00000000fc00ffff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000fe000000-0x00000000fe010fff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000fec00000-0x00000000fec00fff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000fed00000-0x00000000fed00fff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000fed20000-0x00000000fed7ffff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000fee00000-0x00000000fee00fff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000ff000000-0x00000000ffffffff] reserved
[    0.000000] BIOS-e820: [mem 0x0000000100000000-0x00000010bfbfffff] usable
[    0.000000] NX (Execute Disable) protection: active
[    0.000000] APIC: Static calls initialized
[    0.000000] efi: EFI v2.8 by American Megatrends
[    0.000000] efi: ACPI=0x35049000 ACPI 2.0=0x35049014 SMBIOS=0x35a4a000 SMBIOS 3.0=0x35a49000 MEMATTR=0x2e33a018 ESRT=0x2f7b4398 INITRD=0x2af49118 RNG=0x349ef018 
[    0.000000] random: crng init done
[    0.000000] efi: Remove mem93: MMIO range=[0xc0000000-0xcfffffff] (256MB) from e820 map
[    0.000000] e820: remove [mem 0xc0000000-0xcfffffff] reserved
[    0.000000] efi: Not removing mem94: MMIO range=[0xfc000000-0xfc00ffff] (64KB) from e820 map
[    0.000000] efi: Not removing mem95: MMIO range=[0xfe000000-0xfe010fff] (68KB) from e820 map
[    0.000000] efi: Not removing mem96: MMIO range=[0xfec00000-0xfec00fff] (4KB) from e820 map
[    0.000000] efi: Not removing mem97: MMIO range=[0xfed00000-0xfed00fff] (4KB) from e820 map
[    0.000000] efi: Not removing mem99: MMIO range=[0xfee00000-0xfee00fff] (4KB) from e820 map
[    0.000000] efi: Remove mem100: MMIO range=[0xff000000-0xffffffff] (16MB) from e820 map
[    0.000000] e820: remove [mem 0xff000000-0xffffffff] reserved
[    0.000000] SMBIOS 3.6.0 present.
[    0.000000] DMI: Gigabyte Technology Co., Ltd. B760 DS3H/B760 DS3H, BIOS F11 09/27/2024
[    0.000000] DMI: Memory slots populated: 4/4
[    0.000000] tsc: Detected 2500.000 MHz processor
[    0.000000] tsc: Detected 2496.000 MHz TSC
[    0.001105] e820: update [mem 0x00000000-0x00000fff] usable ==> reserved
[    0.001125] e820: remove [mem 0x000a0000-0x000fffff] usable
[    0.001134] last_pfn = 0x10bfc00 max_arch_pfn = 0x400000000
[    0.001138] MTRR map: 5 entries (3 fixed + 2 variable; max 23), built from 10 variable MTRRs
[    0.001140] x86/PAT: Configuration [0-7]: WB  WC  UC- UC  WB  WP  UC- WT  
[    0.001647] last_pfn = 0x36000 max_arch_pfn = 0x400000000
[    0.019608] esrt: Reserving ESRT space from 0x000000002f7b4398 to 0x000000002f7b4448.
[    0.019614] e820: update [mem 0x2f7b4000-0x2f7b4fff] usable ==> reserved
[    0.019635] Using GB pages for direct mapping
[    0.020143] Secure boot disabled
[    0.020144] RAMDISK: [mem 0x238d1000-0x26892fff]
[    0.020149] ACPI: Early table checksum verification disabled
[    0.020152] ACPI: RSDP 0x0000000035049014 000024 (v02 ALASKA)
[    0.020157] ACPI: XSDT 0x0000000035048728 00012C (v01 ALASKA A M I    01072009 AMI  01000013)
[    0.020164] ACPI: FACP 0x0000000034BFA000 000114 (v06 ALASKA A M I    01072009 AMI  01000013)
[    0.020169] ACPI: DSDT 0x0000000034B71000 088540 (v02 ALASKA A M I    01072009 INTL 20200717)
[    0.020173] ACPI: FACS 0x00000000350CB000 000040
[    0.020176] ACPI: FIDT 0x0000000034B70000 00009C (v01 ALASKA A M I    01072009 AMI  00010013)
[    0.020179] ACPI: SSDT 0x0000000034B64000 00BC3E (v02 GBT    GSWApp   00000001 INTL 20200717)
[    0.020183] ACPI: HWIN 0x0000000034BFC000 0000D4 (v00 GBT    INTEL    00070000 AMI  01000013)
[    0.020186] ACPI: SSDT 0x0000000034B60000 0031C9 (v02 INTEL  DTbtSsdt 00001000 INTL 20200717)
[    0.020189] ACPI: SSDT 0x0000000034BFB000 00038C (v02 PmaxDv Pmax_Dev 00000001 INTL 20200717)
[    0.020192] ACPI: SSDT 0x0000000034B5A000 005D34 (v02 CpuRef CpuSsdt  00003000 INTL 20200717)
[    0.020195] ACPI: SSDT 0x0000000034B57000 002A81 (v02 SaSsdt SaSsdt   00003000 INTL 20200717)
[    0.020198] ACPI: SSDT 0x0000000034B53000 00334F (v02 INTEL  IgfxSsdt 00003000 INTL 20200717)
[    0.020201] ACPI: HPET 0x0000000034B52000 000038 (v01 ALASKA A M I    01072009 AMI  01000013)
[    0.020204] ACPI: APIC 0x0000000034B51000 0001DC (v05 ALASKA A M I    01072009 AMI  01000013)
[    0.020207] ACPI: MCFG 0x0000000034B50000 00003C (v01 ALASKA A M I    01072009 AMI  01000013)
[    0.020210] ACPI: SSDT 0x0000000034B47000 008595 (v02 ALASKA A M I    00001000 INTL 20200717)
[    0.020213] ACPI: SSDT 0x0000000034B45000 001F1A (v02 ALASKA A M I    00001000 INTL 20200717)
[    0.020216] ACPI: NHLT 0x0000000034B44000 00002D (v00 ALASKA A M I    01072009 AMI  01000013)
[    0.020219] ACPI: LPIT 0x0000000034B43000 0000CC (v01 ALASKA A M I    01072009 AMI  01000013)
[    0.020222] ACPI: SSDT 0x0000000034B3F000 002A83 (v02 ALASKA A M I    00001000 INTL 20200717)
[    0.020225] ACPI: SSDT 0x0000000034B35000 0092F4 (v02 ALASKA A M I    00000000 INTL 20200717)
[    0.020228] ACPI: DBGP 0x0000000034B34000 000034 (v01 ALASKA A M I    01072009 AMI  01000013)
[    0.020231] ACPI: DBG2 0x0000000034B33000 000054 (v00 ALASKA A M I    01072009 AMI  01000013)
[    0.020234] ACPI: SSDT 0x0000000034B31000 00190A (v02 ALASKA A M I    00001000 INTL 20200717)
[    0.020237] ACPI: DMAR 0x0000000034B30000 000088 (v01 INTEL  EDK2     00000002      01000013)
[    0.020240] ACPI: FPDT 0x0000000034B2F000 000044 (v01 ALASKA A M I    01072009 AMI  01000013)
[    0.020243] ACPI: SSDT 0x0000000034B2D000 0019FA (v02 INTEL  xh_rps14 00000000 INTL 20200717)
[    0.020246] ACPI: SSDT 0x0000000034B29000 0039DA (v02 SocGpe SocGpe   00003000 INTL 20200717)
[    0.020249] ACPI: SSDT 0x0000000034B25000 0039DA (v02 SocCmn SocCmn   00003000 INTL 20200717)
[    0.020252] ACPI: VFCT 0x0000000034B16000 00E284 (v01 ALASKA A M I    00000001 AMD  33504F47)
[    0.020255] ACPI: BGRT 0x0000000034B15000 000038 (v01 ALASKA A M I    01072009 AMI  00010013)
[    0.020259] ACPI: UEFI 0x0000000035024000 00063A (v01 INTEL  RstVmdE  00000000 INTL 00000000)
[    0.020261] ACPI: UEFI 0x0000000035023000 00005C (v01 INTEL  RstVmdV  00000000 INTL 00000000)
[    0.020264] ACPI: WPBT 0x00000000349F1000 000034 (v01 ALASKA A M I    00000001 GBT  20221021)
[    0.020266] ACPI: PHAT 0x00000000349F0000 0005F1 (v01 ALASKA A M I    00000005 MSFT 0100000D)
[    0.020269] ACPI: WSMT 0x0000000034B42000 000028 (v01 ALASKA A M I    01072009 AMI  00010013)
[    0.020271] ACPI: Reserving FACP table memory at [mem 0x34bfa000-0x34bfa113]
[    0.020272] ACPI: Reserving DSDT table memory at [mem 0x34b71000-0x34bf953f]
[    0.020273] ACPI: Reserving FACS table memory at [mem 0x350cb000-0x350cb03f]
[    0.020273] ACPI: Reserving FIDT table memory at [mem 0x34b70000-0x34b7009b]
[    0.020274] ACPI: Reserving SSDT table memory at [mem 0x34b64000-0x34b6fc3d]
[    0.020275] ACPI: Reserving HWIN table memory at [mem 0x34bfc000-0x34bfc0d3]
[    0.020275] ACPI: Reserving SSDT table memory at [mem 0x34b60000-0x34b631c8]
[    0.020276] ACPI: Reserving SSDT table memory at [mem 0x34bfb000-0x34bfb38b]
[    0.020277] ACPI: Reserving SSDT table memory at [mem 0x34b5a000-0x34b5fd33]
[    0.020277] ACPI: Reserving SSDT table memory at [mem 0x34b57000-0x34b59a80]
[    0.020278] ACPI: Reserving SSDT table memory at [mem 0x34b53000-0x34b5634e]
[    0.020279] ACPI: Reserving HPET table memory at [mem 0x34b52000-0x34b52037]
[    0.020279] ACPI: Reserving APIC table memory at [mem 0x34b51000-0x34b511db]
[    0.020280] ACPI: Reserving MCFG table memory at [mem 0x34b50000-0x34b5003b]
[    0.020280] ACPI: Reserving SSDT table memory at [mem 0x34b47000-0x34b4f594]
[    0.020281] ACPI: Reserving SSDT table memory at [mem 0x34b45000-0x34b46f19]
[    0.020282] ACPI: Reserving NHLT table memory at [mem 0x34b44000-0x34b4402c]
[    0.020282] ACPI: Reserving LPIT table memory at [mem 0x34b43000-0x34b430cb]
[    0.020283] ACPI: Reserving SSDT table memory at [mem 0x34b3f000-0x34b41a82]
[    0.020284] ACPI: Reserving SSDT table memory at [mem 0x34b35000-0x34b3e2f3]
[    0.020284] ACPI: Reserving DBGP table memory at [mem 0x34b34000-0x34b34033]
[    0.020285] ACPI: Reserving DBG2 table memory at [mem 0x34b33000-0x34b33053]
[    0.020285] ACPI: Reserving SSDT table memory at [mem 0x34b31000-0x34b32909]
[    0.020286] ACPI: Reserving DMAR table memory at [mem 0x34b30000-0x34b30087]
[    0.020287] ACPI: Reserving FPDT table memory at [mem 0x34b2f000-0x34b2f043]
[    0.020287] ACPI: Reserving SSDT table memory at [mem 0x34b2d000-0x34b2e9f9]
[    0.020288] ACPI: Reserving SSDT table memory at [mem 0x34b29000-0x34b2c9d9]
[    0.020288] ACPI: Reserving SSDT table memory at [mem 0x34b25000-0x34b289d9]
[    0.020289] ACPI: Reserving VFCT table memory at [mem 0x34b16000-0x34b24283]
[    0.020290] ACPI: Reserving BGRT table memory at [mem 0x34b15000-0x34b15037]
[    0.020290] ACPI: Reserving UEFI table memory at [mem 0x35024000-0x35024639]
[    0.020291] ACPI: Reserving UEFI table memory at [mem 0x35023000-0x3502305b]
[    0.020292] ACPI: Reserving WPBT table memory at [mem 0x349f1000-0x349f1033]
[    0.020292] ACPI: Reserving PHAT table memory at [mem 0x349f0000-0x349f05f0]
[    0.020293] ACPI: Reserving WSMT table memory at [mem 0x34b42000-0x34b42027]
[    0.020439] No NUMA configuration found
[    0.020440] Faking a node at [mem 0x0000000000000000-0x00000010bfbfffff]
[    0.020446] NODE_DATA(0) allocated [mem 0x10bfbd5280-0x10bfbfffff]
[    0.020646] Zone ranges:
[    0.020647]   DMA      [mem 0x0000000000001000-0x0000000000ffffff]
[    0.020649]   DMA32    [mem 0x0000000001000000-0x00000000ffffffff]
[    0.020650]   Normal   [mem 0x0000000100000000-0x00000010bfbfffff]
[    0.020651]   Device   empty
[    0.020652] Movable zone start for each node
[    0.020653] Early memory node ranges
[    0.020654]   node   0: [mem 0x0000000000001000-0x000000000009dfff]
[    0.020655]   node   0: [mem 0x000000000009f000-0x000000000009ffff]
[    0.020656]   node   0: [mem 0x0000000000100000-0x0000000030f92fff]
[    0.020657]   node   0: [mem 0x0000000030f94000-0x000000003186afff]
[    0.020657]   node   0: [mem 0x0000000035fff000-0x0000000035ffffff]
[    0.020658]   node   0: [mem 0x0000000100000000-0x00000010bfbfffff]
[    0.020663] Initmem setup node 0 [mem 0x0000000000001000-0x00000010bfbfffff]
[    0.020667] On node 0, zone DMA: 1 pages in unavailable ranges
[    0.020668] On node 0, zone DMA: 1 pages in unavailable ranges
[    0.020688] On node 0, zone DMA: 96 pages in unavailable ranges
[    0.021612] On node 0, zone DMA32: 1 pages in unavailable ranges
[    0.021737] On node 0, zone DMA32: 18324 pages in unavailable ranges
[    0.098812] On node 0, zone Normal: 8192 pages in unavailable ranges
[    0.098821] On node 0, zone Normal: 1024 pages in unavailable ranges
[    0.099175] ACPI: PM-Timer IO Port: 0x1808
[    0.099185] ACPI: LAPIC_NMI (acpi_id[0x01] high edge lint[0x1])
[    0.099187] ACPI: LAPIC_NMI (acpi_id[0x02] high edge lint[0x1])
[    0.099188] ACPI: LAPIC_NMI (acpi_id[0x03] high edge lint[0x1])
[    0.099188] ACPI: LAPIC_NMI (acpi_id[0x04] high edge lint[0x1])
[    0.099189] ACPI: LAPIC_NMI (acpi_id[0x05] high edge lint[0x1])
[    0.099190] ACPI: LAPIC_NMI (acpi_id[0x06] high edge lint[0x1])
[    0.099190] ACPI: LAPIC_NMI (acpi_id[0x07] high edge lint[0x1])
[    0.099191] ACPI: LAPIC_NMI (acpi_id[0x08] high edge lint[0x1])
[    0.099191] ACPI: LAPIC_NMI (acpi_id[0x09] high edge lint[0x1])
[    0.099192] ACPI: LAPIC_NMI (acpi_id[0x0a] high edge lint[0x1])
[    0.099192] ACPI: LAPIC_NMI (acpi_id[0x0b] high edge lint[0x1])
[    0.099193] ACPI: LAPIC_NMI (acpi_id[0x0c] high edge lint[0x1])
[    0.099193] ACPI: LAPIC_NMI (acpi_id[0x0d] high edge lint[0x1])
[    0.099194] ACPI: LAPIC_NMI (acpi_id[0x0e] high edge lint[0x1])
[    0.099194] ACPI: LAPIC_NMI (acpi_id[0x0f] high edge lint[0x1])
[    0.099195] ACPI: LAPIC_NMI (acpi_id[0x10] high edge lint[0x1])
[    0.099196] ACPI: LAPIC_NMI (acpi_id[0x11] high edge lint[0x1])
[    0.099196] ACPI: LAPIC_NMI (acpi_id[0x12] high edge lint[0x1])
[    0.099197] ACPI: LAPIC_NMI (acpi_id[0x13] high edge lint[0x1])
[    0.099197] ACPI: LAPIC_NMI (acpi_id[0x14] high edge lint[0x1])
[    0.099198] ACPI: LAPIC_NMI (acpi_id[0x15] high edge lint[0x1])
[    0.099199] ACPI: LAPIC_NMI (acpi_id[0x16] high edge lint[0x1])
[    0.099199] ACPI: LAPIC_NMI (acpi_id[0x17] high edge lint[0x1])
[    0.099200] ACPI: LAPIC_NMI (acpi_id[0x00] high edge lint[0x1])
[    0.099238] IOAPIC[0]: apic_id 2, version 32, address 0xfec00000, GSI 0-119
[    0.099241] ACPI: INT_SRC_OVR (bus 0 bus_irq 0 global_irq 2 dfl dfl)
[    0.099243] ACPI: INT_SRC_OVR (bus 0 bus_irq 9 global_irq 9 high level)
[    0.099247] ACPI: Using ACPI (MADT) for SMP configuration information
[    0.099248] ACPI: HPET id: 0x8086a201 base: 0xfed00000
[    0.099257] e820: update [mem 0x2dbd8000-0x2dc56fff] usable ==> reserved
[    0.099270] TSC deadline timer available
[    0.099273] CPU topo: Max. logical packages:   1
[    0.099274] CPU topo: Max. logical dies:       1
[    0.099274] CPU topo: Max. dies per package:   1
[    0.099277] CPU topo: Max. threads per core:   2
[    0.099278] CPU topo: Num. cores per package:    10
[    0.099279] CPU topo: Num. threads per package:  16
[    0.099279] CPU topo: Allowing 16 present CPUs plus 0 hotplug CPUs
[    0.099299] PM: hibernation: Registered nosave memory: [mem 0x00000000-0x00000fff]
[    0.099301] PM: hibernation: Registered nosave memory: [mem 0x0009e000-0x0009efff]
[    0.099302] PM: hibernation: Registered nosave memory: [mem 0x000a0000-0x000fffff]
[    0.099304] PM: hibernation: Registered nosave memory: [mem 0x2dbd8000-0x2dc56fff]
[    0.099305] PM: hibernation: Registered nosave memory: [mem 0x2f7b4000-0x2f7b4fff]
[    0.099306] PM: hibernation: Registered nosave memory: [mem 0x30f93000-0x30f93fff]
[    0.099308] PM: hibernation: Registered nosave memory: [mem 0x3186b000-0x35ffefff]
[    0.099309] PM: hibernation: Registered nosave memory: [mem 0x36000000-0xffffffff]
[    0.099311] [mem 0x40400000-0xfbffffff] available for PCI devices
[    0.099312] Booting paravirtualized kernel on bare hardware
[    0.099314] clocksource: refined-jiffies: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 1910969940391419 ns
[    0.108177] setup_percpu: NR_CPUS:8192 nr_cpumask_bits:16 nr_cpu_ids:16 nr_node_ids:1
[    0.108691] percpu: Embedded 62 pages/cpu s217088 r8192 d28672 u262144
[    0.108698] pcpu-alloc: s217088 r8192 d28672 u262144 alloc=1*2097152
[    0.108700] pcpu-alloc: [0] 00 01 02 03 04 05 06 07 [0] 08 09 10 11 12 13 14 15 
[    0.108720] Kernel command line: BOOT_IMAGE=/@/boot/vmlinuz-linux-zen root=UUID=206eec02-6fca-4d04-910e-2bf9fddca883 rw rootflags=subvol=@ quiet loglevel=3 ibt=off
[    0.108785] Unknown kernel command line parameters "BOOT_IMAGE=/@/boot/vmlinuz-linux-zen", will be passed to user space.
[    0.108795] printk: log buffer data + meta data: 131072 + 458752 = 589824 bytes
[    0.113658] Dentry cache hash table entries: 8388608 (order: 14, 67108864 bytes, linear)
[    0.116090] Inode-cache hash table entries: 4194304 (order: 13, 33554432 bytes, linear)
[    0.116282] software IO TLB: area num 16.
[    0.126057] Fallback order for Node 0: 0 
[    0.126061] Built 1 zonelists, mobility grouping on.  Total pages: 16716809
[    0.126062] Policy zone: Normal
[    0.126269] mem auto-init: stack:all(zero), heap alloc:on, heap free:off
[    0.227268] SLUB: HWalign=64, Order=0-3, MinObjects=0, CPUs=16, Nodes=1
[    0.235237] ftrace: allocating 52803 entries in 208 pages
[    0.235238] ftrace: allocated 208 pages with 3 groups
[    0.235325] Dynamic Preempt: full
[    0.235399] rcu: Preemptible hierarchical RCU implementation.
[    0.235400] rcu: 	RCU restricting CPUs from NR_CPUS=8192 to nr_cpu_ids=16.
[    0.235401] rcu: 	RCU priority boosting: priority 1 delay 500 ms.
[    0.235402] 	Trampoline variant of Tasks RCU enabled.
[    0.235403] 	Rude variant of Tasks RCU enabled.
[    0.235403] 	Tracing variant of Tasks RCU enabled.
[    0.235404] rcu: RCU calculated value of scheduler-enlistment delay is 100 jiffies.
[    0.235405] rcu: Adjusting geometry for rcu_fanout_leaf=16, nr_cpu_ids=16
[    0.235417] RCU Tasks: Setting shift to 4 and lim to 1 rcu_task_cb_adjust=1 rcu_task_cpu_ids=16.
[    0.235422] RCU Tasks Rude: Setting shift to 4 and lim to 1 rcu_task_cb_adjust=1 rcu_task_cpu_ids=16.
[    0.235425] RCU Tasks Trace: Setting shift to 4 and lim to 1 rcu_task_cb_adjust=1 rcu_task_cpu_ids=16.
[    0.240927] NR_IRQS: 524544, nr_irqs: 2184, preallocated irqs: 16
[    0.241243] rcu: srcu_init: Setting srcu_struct sizes based on contention.
[    0.241533] kfence: initialized - using 2097152 bytes for 255 objects at 0x(____ptrval____)-0x(____ptrval____)
[    0.241580] Console: colour dummy device 80x25
[    0.241583] printk: legacy console [tty0] enabled
[    0.241631] ACPI: Core revision 20240827
[    0.242088] hpet: HPET dysfunctional in PC10. Force disabled.
[    0.242164] APIC: Switch to symmetric I/O mode setup
[    0.242166] DMAR: Host address width 39
[    0.242167] DMAR: DRHD base: 0x000000fed90000 flags: 0x0
[    0.242172] DMAR: dmar0: reg_base_addr fed90000 ver 4:0 cap 1c0000c40660462 ecap 29a00f0505e
[    0.242174] DMAR: DRHD base: 0x000000fed91000 flags: 0x1
[    0.242179] DMAR: dmar1: reg_base_addr fed91000 ver 5:0 cap d2008c40660462 ecap f050da
[    0.242181] DMAR: RMRR base: 0x0000003c000000 end: 0x000000403fffff
[    0.242184] DMAR-IR: IOAPIC id 2 under DRHD base  0xfed91000 IOMMU 1
[    0.242185] DMAR-IR: HPET id 0 under DRHD base 0xfed91000
[    0.242186] DMAR-IR: Queued invalidation will be enabled to support x2apic and Intr-remapping.
[    0.244119] DMAR-IR: Enabled IRQ remapping in x2apic mode
[    0.244122] x2apic enabled
[    0.244187] APIC: Switched APIC routing to: cluster x2apic
[    0.249003] clocksource: tsc-early: mask: 0xffffffffffffffff max_cycles: 0x23fa772cf26, max_idle_ns: 440795269835 ns
[    0.249012] Calibrating delay loop (skipped), value calculated using timer frequency.. 4992.00 BogoMIPS (lpj=2496000)
[    0.249078] CPU0: Thermal monitoring enabled (TM1)
[    0.249080] x86/cpu: User Mode Instruction Prevention (UMIP) activated
[    0.249211] Last level iTLB entries: 4KB 0, 2MB 0, 4MB 0
[    0.249212] Last level dTLB entries: 4KB 0, 2MB 0, 4MB 0, 1GB 0
[    0.249216] process: using mwait in idle threads
[    0.249218] Spectre V1 : Mitigation: usercopy/swapgs barriers and __user pointer sanitization
[    0.249221] Spectre V2 : Mitigation: Enhanced / Automatic IBRS
[    0.249222] Spectre V2 : Spectre v2 / PBRSB-eIBRS: Retire a single CALL on VMEXIT
[    0.249224] Spectre V2 : mitigation: Enabling conditional Indirect Branch Prediction Barrier
[    0.249225] Speculative Store Bypass: Mitigation: Speculative Store Bypass disabled via prctl
[    0.249226] Register File Data Sampling: Mitigation: Clear Register File
[    0.249241] x86/fpu: Supporting XSAVE feature 0x001: 'x87 floating point registers'
[    0.249242] x86/fpu: Supporting XSAVE feature 0x002: 'SSE registers'
[    0.249243] x86/fpu: Supporting XSAVE feature 0x004: 'AVX registers'
[    0.249244] x86/fpu: Supporting XSAVE feature 0x200: 'Protection Keys User registers'
[    0.249245] x86/fpu: Supporting XSAVE feature 0x800: 'Control-flow User registers'
[    0.249246] x86/fpu: xstate_offset[2]:  576, xstate_sizes[2]:  256
[    0.249247] x86/fpu: xstate_offset[9]:  832, xstate_sizes[9]:    8
[    0.249248] x86/fpu: xstate_offset[11]:  840, xstate_sizes[11]:   16
[    0.249249] x86/fpu: Enabled xstate features 0xa07, context size is 856 bytes, using 'compacted' format.
[    0.250008] Freeing SMP alternatives memory: 64K
[    0.250008] pid_max: default: 32768 minimum: 301
[    0.250008] LSM: initializing lsm=capability,landlock,lockdown,yama,bpf
[    0.250008] landlock: Up and running.
[    0.250008] Yama: becoming mindful.
[    0.250008] LSM support for eBPF active
[    0.250008] Mount-cache hash table entries: 131072 (order: 8, 1048576 bytes, linear)
[    0.250008] Mountpoint-cache hash table entries: 131072 (order: 8, 1048576 bytes, linear)
[    0.250008] smpboot: CPU0: 13th Gen Intel(R) Core(TM) i5-13400 (family: 0x6, model: 0xbf, stepping: 0x2)
[    0.250008] Performance Events: XSAVE Architectural LBR, PEBS fmt4+-baseline,  AnyThread deprecated, Alderlake Hybrid events, 32-deep LBR, full-width counters, Intel PMU driver.
[    0.250008] core: cpu_core PMU driver: 
[    0.250008] ... version:                5
[    0.250008] ... bit width:              48
[    0.250008] ... generic registers:      8
[    0.250008] ... value mask:             0000ffffffffffff
[    0.250008] ... max period:             00007fffffffffff
[    0.250008] ... fixed-purpose events:   4
[    0.250008] ... event mask:             0001000f000000ff
[    0.250008] signal: max sigframe size: 3632
[    0.250008] Estimated ratio of average max frequency by base frequency (times 1024): 1843
[    0.250008] rcu: Hierarchical SRCU implementation.
[    0.250008] rcu: 	Max phase no-delay instances is 400.
[    0.250008] Timer migration: 2 hierarchy levels; 8 children per group; 2 crossnode level
[    0.250511] NMI watchdog: Enabled. Permanently consumes one hw-PMU counter.
[    0.250626] smp: Bringing up secondary CPUs ...
[    0.250709] smpboot: x86: Booting SMP configuration:
[    0.250710] .... node  #0, CPUs:        #2  #4  #6  #8 #10 #12 #13 #14 #15
[    0.008587] core: cpu_atom PMU driver: 
[    0.008587] ... version:                5
[    0.008587] ... bit width:              48
[    0.008587] ... generic registers:      6
[    0.008587] ... value mask:             0000ffffffffffff
[    0.008587] ... max period:             00007fffffffffff
[    0.008587] ... fixed-purpose events:   3
[    0.008587] ... event mask:             000000070000003f
[    0.257071]   #1  #3  #5  #7  #9 #11
[    0.262067] smp: Brought up 1 node, 16 CPUs
[    0.262067] smpboot: Total of 16 processors activated (79872.00 BogoMIPS)
[    0.263150] Memory: 65512708K/66867236K available (22464K kernel code, 2944K rwdata, 16252K rodata, 4784K init, 4744K bss, 1325416K reserved, 0K cma-reserved)
[    0.264631] devtmpfs: initialized
[    0.264631] x86/mm: Memory block size: 2048MB
[    0.265412] ACPI: PM: Registering ACPI NVS region [mem 0x34bfd000-0x350cbfff] (5042176 bytes)
[    0.265412] clocksource: jiffies: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 1911260446275000 ns
[    0.265412] posixtimers hash table entries: 8192 (order: 5, 131072 bytes, linear)
[    0.265412] futex hash table entries: 4096 (order: 6, 262144 bytes, linear)
[    0.265412] pinctrl core: initialized pinctrl subsystem
[    0.265412] PM: RTC time: 11:14:28, date: 2025-07-12
[    0.266369] NET: Registered PF_NETLINK/PF_ROUTE protocol family
[    0.266806] DMA: preallocated 4096 KiB GFP_KERNEL pool for atomic allocations
[    0.267122] DMA: preallocated 4096 KiB GFP_KERNEL|GFP_DMA pool for atomic allocations
[    0.267445] DMA: preallocated 4096 KiB GFP_KERNEL|GFP_DMA32 pool for atomic allocations
[    0.267451] audit: initializing netlink subsys (disabled)
[    0.267461] audit: type=2000 audit(1752318868.018:1): state=initialized audit_enabled=0 res=1
[    0.267461] thermal_sys: Registered thermal governor 'fair_share'
[    0.267461] thermal_sys: Registered thermal governor 'bang_bang'
[    0.267461] thermal_sys: Registered thermal governor 'step_wise'
[    0.267461] thermal_sys: Registered thermal governor 'user_space'
[    0.267461] thermal_sys: Registered thermal governor 'power_allocator'
[    0.267461] cpuidle: using governor ladder
[    0.267461] cpuidle: using governor menu
[    0.267461] ACPI FADT declares the system doesn't support PCIe ASPM, so disable it
[    0.267461] acpiphp: ACPI Hot Plug PCI Controller Driver version: 0.5
[    0.267461] PCI: ECAM [mem 0xc0000000-0xce0fffff] (base 0xc0000000) for domain 0000 [bus 00-e0]
[    0.267461] PCI: Using configuration type 1 for base access
[    0.268013] kprobes: kprobe jump-optimization is enabled. All kprobes are optimized if possible.
[    0.271080] HugeTLB: allocation took 0ms with hugepage_allocation_threads=4
[    0.271080] HugeTLB: registered 1.00 GiB page size, pre-allocated 0 pages
[    0.271080] HugeTLB: 16380 KiB vmemmap can be freed for a 1.00 GiB page
[    0.271080] HugeTLB: registered 2.00 MiB page size, pre-allocated 0 pages
[    0.271080] HugeTLB: 28 KiB vmemmap can be freed for a 2.00 MiB page
[    0.271629] raid6: skipped pq benchmark and selected avx2x4
[    0.271629] raid6: using avx2x2 recovery algorithm
[    0.271629] ACPI: Added _OSI(Module Device)
[    0.271629] ACPI: Added _OSI(Processor Device)
[    0.271629] ACPI: Added _OSI(Processor Aggregator Device)
[    0.419188] ACPI: 15 ACPI AML tables successfully acquired and loaded
[    0.440266] ACPI: Dynamic OEM Table Load:
[    0.440278] ACPI: SSDT 0xFFFF8E1941848C00 000394 (v02 PmRef  Cpu0Cst  00003001 INTL 20200717)
[    0.441874] ACPI: Dynamic OEM Table Load:
[    0.441882] ACPI: SSDT 0xFFFF8E1941845800 000560 (v02 PmRef  Cpu0Ist  00003000 INTL 20200717)
[    0.443470] ACPI: Dynamic OEM Table Load:
[    0.443476] ACPI: SSDT 0xFFFF8E1941FAD400 0001AB (v02 PmRef  Cpu0Psd  00003000 INTL 20200717)
[    0.444951] ACPI: Dynamic OEM Table Load:
[    0.444958] ACPI: SSDT 0xFFFF8E1941844800 0004B5 (v02 PmRef  Cpu0Hwp  00003000 INTL 20200717)
[    0.447037] ACPI: Dynamic OEM Table Load:
[    0.447047] ACPI: SSDT 0xFFFF8E1941836000 001BAF (v02 PmRef  ApIst    00003000 INTL 20200717)
[    0.449538] ACPI: Dynamic OEM Table Load:
[    0.449546] ACPI: SSDT 0xFFFF8E1941834000 001038 (v02 PmRef  ApHwp    00003000 INTL 20200717)
[    0.451767] ACPI: Dynamic OEM Table Load:
[    0.451775] ACPI: SSDT 0xFFFF8E19426B4000 001349 (v02 PmRef  ApPsd    00003000 INTL 20200717)
[    0.454052] ACPI: Dynamic OEM Table Load:
[    0.454060] ACPI: SSDT 0xFFFF8E1941853000 000FBB (v02 PmRef  ApCst    00003000 INTL 20200717)
[    0.465590] ACPI: Interpreter enabled
[    0.465667] ACPI: PM: (supports S0 S3 S4 S5)
[    0.465669] ACPI: Using IOAPIC for interrupt routing
[    0.467522] PCI: Using host bridge windows from ACPI; if necessary, use "pci=nocrs" and report a bug
[    0.467524] PCI: Ignoring E820 reservations for host bridge windows
[    0.469180] ACPI: Enabled 7 GPEs in block 00 to 7F
[    0.500746] ACPI: \_SB_.PC00.PAUD: New power resource
[    0.505091] ACPI: \_SB_.PC00.I2C1.PXTC: New power resource
[    0.509610] ACPI: \_SB_.PC00.CNVW.WRST: New power resource
[    0.520687] ACPI: \_SB_.PC00.VMD0.PEG0.NVPR: New power resource
[    0.521028] ACPI: \_SB_.PC00.VMD0.PRT0.NVPR: New power resource
[    0.521195] ACPI: \_SB_.PC00.VMD0.PRT1.NVPR: New power resource
[    0.521359] ACPI: \_SB_.PC00.VMD0.PRT2.NVPR: New power resource
[    0.521524] ACPI: \_SB_.PC00.VMD0.PRT3.NVPR: New power resource
[    0.521688] ACPI: \_SB_.PC00.VMD0.PRT4.NVPR: New power resource
[    0.521854] ACPI: \_SB_.PC00.VMD0.PRT5.NVPR: New power resource
[    0.522018] ACPI: \_SB_.PC00.VMD0.PRT6.NVPR: New power resource
[    0.522185] ACPI: \_SB_.PC00.VMD0.PRT7.NVPR: New power resource
[    0.522301] ACPI: \_SB_.PC00.VMD0.VOL0.V0PR: New power resource
[    0.522368] ACPI: \_SB_.PC00.VMD0.VOL1.V1PR: New power resource
[    0.522434] ACPI: \_SB_.PC00.VMD0.VOL2.V2PR: New power resource
[    0.522500] ACPI: \_SB_.PC00.VMD0.VOL3.V3PR: New power resource
[    0.530085] ACPI: \_TZ_.FN00: New power resource
[    0.530159] ACPI: \_TZ_.FN01: New power resource
[    0.530231] ACPI: \_TZ_.FN02: New power resource
[    0.530301] ACPI: \_TZ_.FN03: New power resource
[    0.530372] ACPI: \_TZ_.FN04: New power resource
[    0.531007] ACPI: \PIN_: New power resource
[    0.531275] ACPI: \SPR4: New power resource
[    0.531357] ACPI: \SPR5: New power resource
[    0.531437] ACPI: \SPR6: New power resource
[    0.531813] ACPI: PCI Root Bridge [PC00] (domain 0000 [bus 00-e0])
[    0.531820] acpi PNP0A08:00: _OSC: OS supports [ExtendedConfig ASPM ClockPM Segments MSI EDR HPX-Type3]
[    0.535693] acpi PNP0A08:00: _OSC: OS now controls [PCIeHotplug SHPCHotplug PME AER PCIeCapability LTR DPC]
[    0.535695] acpi PNP0A08:00: FADT indicates ASPM is unsupported, using BIOS configuration
[    0.537842] PCI host bridge to bus 0000:00
[    0.537846] pci_bus 0000:00: root bus resource [io  0x0000-0x0cf7 window]
[    0.537849] pci_bus 0000:00: root bus resource [io  0x0d00-0xffff window]
[    0.537850] pci_bus 0000:00: root bus resource [mem 0x000a0000-0x000bffff window]
[    0.537852] pci_bus 0000:00: root bus resource [mem 0x000e0000-0x000fffff window]
[    0.537854] pci_bus 0000:00: root bus resource [mem 0x40400000-0xbfffffff window]
[    0.537855] pci_bus 0000:00: root bus resource [mem 0x4000000000-0x7fffffffff window]
[    0.537857] pci_bus 0000:00: root bus resource [bus 00-e0]
[    0.537898] pci 0000:00:00.0: [8086:4648] type 00 class 0x060000 conventional PCI endpoint
[    0.538039] pci 0000:00:01.0: [8086:460d] type 01 class 0x060400 PCIe Root Port
[    0.538053] pci 0000:00:01.0: PCI bridge to [bus 01-03]
[    0.538056] pci 0000:00:01.0:   bridge window [io  0x6000-0x6fff]
[    0.538058] pci 0000:00:01.0:   bridge window [mem 0x44a00000-0x44dfffff]
[    0.538064] pci 0000:00:01.0:   bridge window [mem 0x6000000000-0x640fffffff 64bit pref]
[    0.538106] pci 0000:00:01.0: PME# supported from D0 D3hot D3cold
[    0.538126] pci 0000:00:01.0: PTM enabled (root), 4ns granularity
[    0.538980] pci 0000:00:02.0: [8086:4682] type 00 class 0x038000 PCIe Root Complex Integrated Endpoint
[    0.538997] pci 0000:00:02.0: BAR 0 [mem 0x6414000000-0x6414ffffff 64bit]
[    0.539000] pci 0000:00:02.0: BAR 2 [mem 0x4000000000-0x400fffffff 64bit pref]
[    0.539002] pci 0000:00:02.0: BAR 4 [io  0x7000-0x703f]
[    0.539014] pci 0000:00:02.0: DMAR: Skip IOMMU disabling for graphics
[    0.539040] pci 0000:00:02.0: VF BAR 0 [mem 0x00000000-0x00ffffff 64bit]
[    0.539042] pci 0000:00:02.0: VF BAR 0 [mem 0x00000000-0x06ffffff 64bit]: contains BAR 0 for 7 VFs
[    0.539044] pci 0000:00:02.0: VF BAR 2 [mem 0x00000000-0x1fffffff 64bit pref]
[    0.539046] pci 0000:00:02.0: VF BAR 2 [mem 0x00000000-0xdfffffff 64bit pref]: contains BAR 2 for 7 VFs
[    0.539246] pci 0000:00:06.0: [8086:09ab] type 00 class 0x088000 conventional PCI endpoint
[    0.540109] pci 0000:00:0e.0: [8086:467f] type 00 class 0x010400 PCIe Root Complex Integrated Endpoint
[    0.540141] pci 0000:00:0e.0: BAR 0 [mem 0x6412000000-0x6413ffffff 64bit]
[    0.540144] pci 0000:00:0e.0: BAR 2 [mem 0x42000000-0x43ffffff]
[    0.540148] pci 0000:00:0e.0: BAR 4 [mem 0x6415100000-0x64151fffff 64bit]
[    0.540620] pci 0000:00:14.0: [8086:7a60] type 00 class 0x0c0330 conventional PCI endpoint
[    0.540663] pci 0000:00:14.0: BAR 0 [mem 0x6415200000-0x641520ffff 64bit]
[    0.540710] pci 0000:00:14.0: PME# supported from D3hot D3cold
[    0.541727] pci 0000:00:14.2: [8086:7a27] type 00 class 0x050000 conventional PCI endpoint
[    0.541777] pci 0000:00:14.2: BAR 0 [mem 0x6415214000-0x6415217fff 64bit]
[    0.541782] pci 0000:00:14.2: BAR 2 [mem 0x6415220000-0x6415220fff 64bit]
[    0.541910] pci 0000:00:15.0: [8086:7a4c] type 00 class 0x0c8000 conventional PCI endpoint
[    0.541965] pci 0000:00:15.0: BAR 0 [mem 0xfe0f9000-0xfe0f9fff 64bit]
[    0.542382] pci 0000:00:15.1: [8086:7a4d] type 00 class 0x0c8000 conventional PCI endpoint
[    0.542441] pci 0000:00:15.1: BAR 0 [mem 0xfe0fa000-0xfe0fafff 64bit]
[    0.542840] pci 0000:00:15.2: [8086:7a4e] type 00 class 0x0c8000 conventional PCI endpoint
[    0.542902] pci 0000:00:15.2: BAR 0 [mem 0xfe0fb000-0xfe0fbfff 64bit]
[    0.543304] pci 0000:00:15.3: [8086:7a4f] type 00 class 0x0c8000 conventional PCI endpoint
[    0.543364] pci 0000:00:15.3: BAR 0 [mem 0xfe0fc000-0xfe0fcfff 64bit]
[    0.543777] pci 0000:00:16.0: [8086:7a68] type 00 class 0x078000 conventional PCI endpoint
[    0.543828] pci 0000:00:16.0: BAR 0 [mem 0x641521b000-0x641521bfff 64bit]
[    0.543881] pci 0000:00:16.0: PME# supported from D3hot
[    0.544705] pci 0000:00:17.0: [8086:09ab] type 00 class 0x088000 conventional PCI endpoint
[    0.545203] pci 0000:00:19.0: [8086:7a7c] type 00 class 0x0c8000 conventional PCI endpoint
[    0.545263] pci 0000:00:19.0: BAR 0 [mem 0x641521a000-0x641521afff 64bit]
[    0.545666] pci 0000:00:19.1: [8086:7a7d] type 00 class 0x0c8000 conventional PCI endpoint
[    0.545726] pci 0000:00:19.1: BAR 0 [mem 0x6415219000-0x6415219fff 64bit]
[    0.546162] pci 0000:00:1c.0: [8086:7a38] type 01 class 0x060400 PCIe Root Port
[    0.546187] pci 0000:00:1c.0: PCI bridge to [bus 04]
[    0.546192] pci 0000:00:1c.0:   bridge window [io  0x5000-0x5fff]
[    0.546195] pci 0000:00:1c.0:   bridge window [mem 0x44000000-0x449fffff]
[    0.546205] pci 0000:00:1c.0:   bridge window [mem 0x6410100000-0x6410afffff 64bit pref]
[    0.547088] pci 0000:00:1c.2: [8086:7a3a] type 01 class 0x060400 PCIe Root Port
[    0.547114] pci 0000:00:1c.2: PCI bridge to [bus 05]
[    0.547119] pci 0000:00:1c.2:   bridge window [io  0x4000-0x4fff]
[    0.547122] pci 0000:00:1c.2:   bridge window [mem 0x45000000-0x451fffff]
[    0.547210] pci 0000:00:1c.2: PME# supported from D0 D3hot D3cold
[    0.547247] pci 0000:00:1c.2: PTM enabled (root), 4ns granularity
[    0.548110] pci 0000:00:1c.6: [8086:7a3e] type 01 class 0x060400 PCIe Root Port
[    0.548137] pci 0000:00:1c.6: PCI bridge to [bus 06]
[    0.548141] pci 0000:00:1c.6:   bridge window [io  0x3000-0x3fff]
[    0.548144] pci 0000:00:1c.6:   bridge window [mem 0x44e00000-0x44ffffff]
[    0.548231] pci 0000:00:1c.6: PME# supported from D0 D3hot D3cold
[    0.548268] pci 0000:00:1c.6: PTM enabled (root), 4ns granularity
[    0.549124] pci 0000:00:1f.0: [8086:7a06] type 00 class 0x060100 conventional PCI endpoint
[    0.549593] pci 0000:00:1f.3: [8086:7a50] type 00 class 0x040300 conventional PCI endpoint
[    0.549695] pci 0000:00:1f.3: BAR 0 [mem 0x6415210000-0x6415213fff 64bit]
[    0.549707] pci 0000:00:1f.3: BAR 4 [mem 0x6415000000-0x64150fffff 64bit]
[    0.549800] pci 0000:00:1f.3: PME# supported from D3hot D3cold
[    0.549931] pci 0000:00:1f.4: [8086:7a23] type 00 class 0x0c0500 conventional PCI endpoint
[    0.549984] pci 0000:00:1f.4: BAR 0 [mem 0x6415218000-0x64152180ff 64bit]
[    0.549991] pci 0000:00:1f.4: BAR 4 [io  0xefa0-0xefbf]
[    0.550332] pci 0000:00:1f.5: [8086:7a24] type 00 class 0x0c8000 conventional PCI endpoint
[    0.550388] pci 0000:00:1f.5: BAR 0 [mem 0xfe010000-0xfe010fff]
[    0.550492] pci 0000:01:00.0: [1002:1478] type 01 class 0x060400 PCIe Switch Upstream Port
[    0.550512] pci 0000:01:00.0: BAR 0 [mem 0x44c00000-0x44c03fff]
[    0.550516] pci 0000:01:00.0: PCI bridge to [bus 02-03]
[    0.550522] pci 0000:01:00.0:   bridge window [io  0x6000-0x6fff]
[    0.550524] pci 0000:01:00.0:   bridge window [mem 0x44a00000-0x44bfffff]
[    0.550533] pci 0000:01:00.0:   bridge window [mem 0x6000000000-0x640fffffff 64bit pref]
[    0.550609] pci 0000:01:00.0: PME# supported from D0 D3hot D3cold
[    0.550757] pci 0000:00:01.0: PCI bridge to [bus 01-03]
[    0.550805] pci 0000:02:00.0: [1002:1479] type 01 class 0x060400 PCIe Switch Downstream Port
[    0.550826] pci 0000:02:00.0: PCI bridge to [bus 03]
[    0.550832] pci 0000:02:00.0:   bridge window [io  0x6000-0x6fff]
[    0.550834] pci 0000:02:00.0:   bridge window [mem 0x44a00000-0x44bfffff]
[    0.550843] pci 0000:02:00.0:   bridge window [mem 0x6000000000-0x640fffffff 64bit pref]
[    0.550918] pci 0000:02:00.0: PME# supported from D0 D3hot D3cold
[    0.551047] pci 0000:01:00.0: PCI bridge to [bus 02-03]
[    0.551098] pci 0000:03:00.0: [1002:747e] type 00 class 0x030000 PCIe Legacy Endpoint
[    0.551131] pci 0000:03:00.0: BAR 0 [mem 0x6000000000-0x63ffffffff 64bit pref]
[    0.551134] pci 0000:03:00.0: BAR 2 [mem 0x6400000000-0x640fffffff 64bit pref]
[    0.551136] pci 0000:03:00.0: BAR 4 [io  0x6000-0x60ff]
[    0.551138] pci 0000:03:00.0: BAR 5 [mem 0x44a00000-0x44afffff]
[    0.551140] pci 0000:03:00.0: ROM [mem 0x44b00000-0x44b1ffff pref]
[    0.551221] pci 0000:03:00.0: PME# supported from D1 D2 D3hot D3cold
[    0.551371] pci 0000:03:00.1: [1002:ab30] type 00 class 0x040300 PCIe Legacy Endpoint
[    0.551401] pci 0000:03:00.1: BAR 0 [mem 0x44b20000-0x44b23fff]
[    0.551462] pci 0000:03:00.1: PME# supported from D1 D2 D3hot D3cold
[    0.551570] pci 0000:02:00.0: PCI bridge to [bus 03]
[    0.551643] pci 0000:00:1c.0: PCI bridge to [bus 04]
[    0.551736] pci 0000:05:00.0: [10ec:8168] type 00 class 0x020000 PCIe Endpoint
[    0.551808] pci 0000:05:00.0: BAR 0 [io  0x4000-0x40ff]
[    0.551815] pci 0000:05:00.0: BAR 2 [mem 0x45004000-0x45004fff 64bit]
[    0.551820] pci 0000:05:00.0: BAR 4 [mem 0x45000000-0x45003fff 64bit]
[    0.551953] pci 0000:05:00.0: supports D1 D2
[    0.551954] pci 0000:05:00.0: PME# supported from D0 D1 D2 D3hot D3cold
[    0.552173] pci 0000:00:1c.2: PCI bridge to [bus 05]
[    0.552278] pci 0000:06:00.0: [8086:107d] type 00 class 0x020000 PCIe Endpoint
[    0.552373] pci 0000:06:00.0: BAR 0 [mem 0x44e40000-0x44e5ffff]
[    0.552377] pci 0000:06:00.0: BAR 1 [mem 0x44e20000-0x44e3ffff]
[    0.552381] pci 0000:06:00.0: BAR 2 [io  0x3000-0x301f]
[    0.552393] pci 0000:06:00.0: ROM [mem 0x44e00000-0x44e1ffff pref]
[    0.552517] pci 0000:06:00.0: PME# supported from D0 D3hot D3cold
[    0.552708] pci 0000:00:1c.6: PCI bridge to [bus 06]
[    0.555613] ACPI: PCI: Interrupt link LNKA configured for IRQ 0
[    0.555764] ACPI: PCI: Interrupt link LNKB configured for IRQ 1
[    0.555912] ACPI: PCI: Interrupt link LNKC configured for IRQ 0
[    0.556061] ACPI: PCI: Interrupt link LNKD configured for IRQ 0
[    0.556208] ACPI: PCI: Interrupt link LNKE configured for IRQ 0
[    0.556354] ACPI: PCI: Interrupt link LNKF configured for IRQ 0
[    0.556501] ACPI: PCI: Interrupt link LNKG configured for IRQ 0
[    0.556648] ACPI: PCI: Interrupt link LNKH configured for IRQ 0
[    0.567485] iommu: Default domain type: Translated
[    0.567485] iommu: DMA domain TLB invalidation policy: lazy mode
[    0.567485] SCSI subsystem initialized
[    0.567485] libata version 3.00 loaded.
[    0.567485] ACPI: bus type USB registered
[    0.567485] usbcore: registered new interface driver usbfs
[    0.567485] usbcore: registered new interface driver hub
[    0.567485] usbcore: registered new device driver usb
[    0.567485] EDAC MC: Ver: 3.0.0
[    0.568074] efivars: Registered efivars operations
[    0.568288] NetLabel: Initializing
[    0.568290] NetLabel:  domain hash size = 128
[    0.568291] NetLabel:  protocols = UNLABELED CIPSOv4 CALIPSO
[    0.568311] NetLabel:  unlabeled traffic allowed by default
[    0.568316] mctp: management component transport protocol core
[    0.568317] NET: Registered PF_MCTP protocol family
[    0.568328] PCI: Using ACPI for IRQ routing
[    0.587872] PCI: pci_cache_line_size set to 64 bytes
[    0.587899] pci 0000:00:15.0: BAR 0 [mem 0xfe0f9000-0xfe0f9fff 64bit]: can't claim; no compatible bridge window
[    0.587903] pci 0000:00:15.1: BAR 0 [mem 0xfe0fa000-0xfe0fafff 64bit]: can't claim; no compatible bridge window
[    0.587908] pci 0000:00:15.2: BAR 0 [mem 0xfe0fb000-0xfe0fbfff 64bit]: can't claim; no compatible bridge window
[    0.587911] pci 0000:00:15.3: BAR 0 [mem 0xfe0fc000-0xfe0fcfff 64bit]: can't claim; no compatible bridge window
[    0.587942] pci 0000:00:1f.5: BAR 0 [mem 0xfe010000-0xfe010fff]: can't claim; no compatible bridge window
[    0.587983] e820: reserve RAM buffer [mem 0x0009e000-0x0009ffff]
[    0.587985] e820: reserve RAM buffer [mem 0x2dbd8000-0x2fffffff]
[    0.587987] e820: reserve RAM buffer [mem 0x2f7b4000-0x2fffffff]
[    0.587988] e820: reserve RAM buffer [mem 0x30f93000-0x33ffffff]
[    0.587989] e820: reserve RAM buffer [mem 0x3186b000-0x33ffffff]
[    0.587990] e820: reserve RAM buffer [mem 0x36000000-0x37ffffff]
[    0.587990] e820: reserve RAM buffer [mem 0x10bfc00000-0x10bfffffff]
[    0.588035] pci 0000:03:00.0: vgaarb: setting as boot VGA device
[    0.588035] pci 0000:03:00.0: vgaarb: bridge control possible
[    0.588035] pci 0000:03:00.0: vgaarb: VGA device added: decodes=io+mem,owns=none,locks=none
[    0.588035] vgaarb: loaded
[    0.588103] clocksource: Switched to clocksource tsc-early
[    0.588578] VFS: Disk quotas dquot_6.6.0
[    0.588589] VFS: Dquot-cache hash table entries: 512 (order 0, 4096 bytes)
[    0.588613] pnp: PnP ACPI init
[    0.588957] system 00:00: [io  0x0a00-0x0a2f] has been reserved
[    0.588961] system 00:00: [io  0x0a30-0x0a3f] has been reserved
[    0.588963] system 00:00: [io  0x0a40-0x0a4f] has been reserved
[    0.589932] pnp 00:01: [dma 0 disabled]
[    0.590146] system 00:02: [io  0x0680-0x069f] has been reserved
[    0.590149] system 00:02: [io  0x164e-0x164f] has been reserved
[    0.590312] system 00:03: [io  0x1854-0x1857] has been reserved
[    0.590426] system 00:04: [mem 0xfc000000-0xfc00ffff] has been reserved
[    0.591778] pnp 00:05: disabling [mem 0xc0000000-0xcfffffff] because it overlaps 0000:00:02.0 BAR 9 [mem 0x00000000-0xdfffffff 64bit pref]
[    0.591808] system 00:05: [mem 0xfedc0000-0xfedc7fff] has been reserved
[    0.591811] system 00:05: [mem 0xfeda0000-0xfeda0fff] has been reserved
[    0.591812] system 00:05: [mem 0xfeda1000-0xfeda1fff] has been reserved
[    0.591814] system 00:05: [mem 0xfed20000-0xfed7ffff] has been reserved
[    0.591816] system 00:05: [mem 0xfed90000-0xfed93fff] could not be reserved
[    0.591817] system 00:05: [mem 0xfed45000-0xfed8ffff] could not be reserved
[    0.591819] system 00:05: [mem 0xfee00000-0xfeefffff] could not be reserved
[    0.592990] system 00:06: [io  0x2000-0x20fe] has been reserved
[    0.594177] pnp: PnP ACPI: found 8 devices
[    0.599981] clocksource: acpi_pm: mask: 0xffffff max_cycles: 0xffffff, max_idle_ns: 2085701024 ns
[    0.600037] NET: Registered PF_INET protocol family
[    0.600243] IP idents hash table entries: 262144 (order: 9, 2097152 bytes, linear)
[    0.616536] tcp_listen_portaddr_hash hash table entries: 32768 (order: 7, 524288 bytes, linear)
[    0.616603] Table-perturb hash table entries: 65536 (order: 6, 262144 bytes, linear)
[    0.616979] TCP established hash table entries: 524288 (order: 10, 4194304 bytes, linear)
[    0.617647] TCP bind hash table entries: 65536 (order: 9, 2097152 bytes, linear)
[    0.617768] TCP: Hash tables configured (established 524288 bind 65536)
[    0.618026] MPTCP token hash table entries: 65536 (order: 8, 1572864 bytes, linear)
[    0.618790] UDP hash table entries: 32768 (order: 9, 2097152 bytes, linear)
[    0.619145] UDP-Lite hash table entries: 32768 (order: 9, 2097152 bytes, linear)
[    0.619369] NET: Registered PF_UNIX/PF_LOCAL protocol family
[    0.619377] NET: Registered PF_XDP protocol family
[    0.619400] pci 0000:00:02.0: VF BAR 2 [mem 0x4020000000-0x40ffffffff 64bit pref]: assigned
[    0.619406] pci 0000:00:02.0: VF BAR 0 [mem 0x4010000000-0x4016ffffff 64bit]: assigned
[    0.619409] pci 0000:00:15.0: BAR 0 [mem 0x4017000000-0x4017000fff 64bit]: assigned
[    0.619424] pci 0000:00:15.1: BAR 0 [mem 0x4017001000-0x4017001fff 64bit]: assigned
[    0.619436] pci 0000:00:15.2: BAR 0 [mem 0x4017002000-0x4017002fff 64bit]: assigned
[    0.619448] pci 0000:00:15.3: BAR 0 [mem 0x4017003000-0x4017003fff 64bit]: assigned
[    0.619460] pci 0000:00:1f.5: BAR 0 [mem 0x40400000-0x40400fff]: assigned
[    0.619468] pci 0000:02:00.0: PCI bridge to [bus 03]
[    0.619475] pci 0000:02:00.0:   bridge window [io  0x6000-0x6fff]
[    0.619479] pci 0000:02:00.0:   bridge window [mem 0x44a00000-0x44bfffff]
[    0.619482] pci 0000:02:00.0:   bridge window [mem 0x6000000000-0x640fffffff 64bit pref]
[    0.619487] pci 0000:01:00.0: PCI bridge to [bus 02-03]
[    0.619490] pci 0000:01:00.0:   bridge window [io  0x6000-0x6fff]
[    0.619494] pci 0000:01:00.0:   bridge window [mem 0x44a00000-0x44bfffff]
[    0.619497] pci 0000:01:00.0:   bridge window [mem 0x6000000000-0x640fffffff 64bit pref]
[    0.619501] pci 0000:00:01.0: PCI bridge to [bus 01-03]
[    0.619503] pci 0000:00:01.0:   bridge window [io  0x6000-0x6fff]
[    0.619505] pci 0000:00:01.0:   bridge window [mem 0x44a00000-0x44dfffff]
[    0.619508] pci 0000:00:01.0:   bridge window [mem 0x6000000000-0x640fffffff 64bit pref]
[    0.619512] pci 0000:00:1c.0: PCI bridge to [bus 04]
[    0.619520] pci 0000:00:1c.0:   bridge window [io  0x5000-0x5fff]
[    0.619524] pci 0000:00:1c.0:   bridge window [mem 0x44000000-0x449fffff]
[    0.619527] pci 0000:00:1c.0:   bridge window [mem 0x6410100000-0x6410afffff 64bit pref]
[    0.619533] pci 0000:00:1c.2: PCI bridge to [bus 05]
[    0.619535] pci 0000:00:1c.2:   bridge window [io  0x4000-0x4fff]
[    0.619539] pci 0000:00:1c.2:   bridge window [mem 0x45000000-0x451fffff]
[    0.619546] pci 0000:00:1c.6: PCI bridge to [bus 06]
[    0.619548] pci 0000:00:1c.6:   bridge window [io  0x3000-0x3fff]
[    0.619552] pci 0000:00:1c.6:   bridge window [mem 0x44e00000-0x44ffffff]
[    0.619560] pci_bus 0000:00: resource 4 [io  0x0000-0x0cf7 window]
[    0.619562] pci_bus 0000:00: resource 5 [io  0x0d00-0xffff window]
[    0.619564] pci_bus 0000:00: resource 6 [mem 0x000a0000-0x000bffff window]
[    0.619565] pci_bus 0000:00: resource 7 [mem 0x000e0000-0x000fffff window]
[    0.619566] pci_bus 0000:00: resource 8 [mem 0x40400000-0xbfffffff window]
[    0.619568] pci_bus 0000:00: resource 9 [mem 0x4000000000-0x7fffffffff window]
[    0.619570] pci_bus 0000:01: resource 0 [io  0x6000-0x6fff]
[    0.619571] pci_bus 0000:01: resource 1 [mem 0x44a00000-0x44dfffff]
[    0.619572] pci_bus 0000:01: resource 2 [mem 0x6000000000-0x640fffffff 64bit pref]
[    0.619574] pci_bus 0000:02: resource 0 [io  0x6000-0x6fff]
[    0.619575] pci_bus 0000:02: resource 1 [mem 0x44a00000-0x44bfffff]
[    0.619576] pci_bus 0000:02: resource 2 [mem 0x6000000000-0x640fffffff 64bit pref]
[    0.619578] pci_bus 0000:03: resource 0 [io  0x6000-0x6fff]
[    0.619579] pci_bus 0000:03: resource 1 [mem 0x44a00000-0x44bfffff]
[    0.619580] pci_bus 0000:03: resource 2 [mem 0x6000000000-0x640fffffff 64bit pref]
[    0.619582] pci_bus 0000:04: resource 0 [io  0x5000-0x5fff]
[    0.619583] pci_bus 0000:04: resource 1 [mem 0x44000000-0x449fffff]
[    0.619584] pci_bus 0000:04: resource 2 [mem 0x6410100000-0x6410afffff 64bit pref]
[    0.619586] pci_bus 0000:05: resource 0 [io  0x4000-0x4fff]
[    0.619592] pci_bus 0000:05: resource 1 [mem 0x45000000-0x451fffff]
[    0.619593] pci_bus 0000:06: resource 0 [io  0x3000-0x3fff]
[    0.619595] pci_bus 0000:06: resource 1 [mem 0x44e00000-0x44ffffff]
[    0.620306] pci 0000:03:00.1: D0 power state depends on 0000:03:00.0
[    0.620369] PCI: CLS 64 bytes, default 64
[    0.620415] PCI-DMA: Using software bounce buffering for IO (SWIOTLB)
[    0.620416] software IO TLB: mapped [mem 0x00000000268e8000-0x000000002a8e8000] (64MB)
[    0.620443] Trying to unpack rootfs image as initramfs...
[    0.620464] clocksource: tsc: mask: 0xffffffffffffffff max_cycles: 0x23fa772cf26, max_idle_ns: 440795269835 ns
[    0.620491] clocksource: Switched to clocksource tsc
[    0.620514] platform rtc_cmos: registered platform RTC device (no PNP device found)
[    0.644309] Initialise system trusted keyrings
[    0.644321] Key type blacklist registered
[    0.644386] workingset: timestamp_bits=36 max_order=24 bucket_order=0
[    0.644648] fuse: init (API version 7.43)
[    0.644744] integrity: Platform Keyring initialized
[    0.644747] integrity: Machine keyring initialized
[    0.655724] xor: automatically using best checksumming function   avx       
[    0.655727] Key type asymmetric registered
[    0.655728] Asymmetric key parser 'x509' registered
[    0.655759] Block layer SCSI generic (bsg) driver version 0.4 loaded (major 246)
[    0.655814] io scheduler mq-deadline registered
[    0.655816] io scheduler kyber registered
[    0.655837] io scheduler bfq registered
[    0.656089] ledtrig-cpu: registered to indicate activity on CPUs
[    0.656423] pcieport 0000:00:01.0: PME: Signaling with IRQ 120
[    0.656486] pcieport 0000:00:01.0: AER: enabled with IRQ 120
[    0.656680] pcieport 0000:00:1c.0: PME: Signaling with IRQ 121
[    0.656725] pcieport 0000:00:1c.0: pciehp: Slot #0 AttnBtn- PwrCtrl- MRL- AttnInd- PwrInd- HotPlug+ Surprise+ Interlock- NoCompl+ IbPresDis- LLActRep+
[    0.657133] pcieport 0000:00:1c.2: PME: Signaling with IRQ 122
[    0.657207] pcieport 0000:00:1c.2: AER: enabled with IRQ 122
[    0.657564] pcieport 0000:00:1c.6: PME: Signaling with IRQ 123
[    0.657643] pcieport 0000:00:1c.6: AER: enabled with IRQ 123
[    0.658413] Monitor-Mwait will be used to enter C-1 state
[    0.658425] Monitor-Mwait will be used to enter C-2 state
[    0.658431] Monitor-Mwait will be used to enter C-3 state
[    0.659047] input: Sleep Button as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0C0E:00/input/input0
[    0.659075] ACPI: button: Sleep Button [SLPB]
[    0.659108] input: Power Button as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0C0C:00/input/input1
[    0.659125] ACPI: button: Power Button [PWRB]
[    0.659153] input: Power Button as /devices/LNXSYSTM:00/LNXPWRBN:00/input/input2
[    0.659623] ACPI: button: Power Button [PWRF]
[    0.895509] Freeing initrd memory: 48904K
[    2.696326] ACPI: \_TZ_.TZ10: _PSL evaluation failure
[    2.696672] thermal LNXTHERM:00: registered as thermal_zone0
[    2.696674] ACPI: thermal: Thermal Zone [TZ10] (17 C)
[    2.696914] thermal LNXTHERM:01: registered as thermal_zone1
[    2.696915] ACPI: thermal: Thermal Zone [TZ00] (28 C)
[    2.697227] Serial: 8250/16550 driver, 32 ports, IRQ sharing enabled
[    2.697925] 00:01: ttyS0 at I/O 0x3f8 (irq = 4, base_baud = 115200) is a 16550A
[    2.701765] hpet_acpi_add: no address or irqs in _CRS
[    2.701811] Non-volatile memory driver v1.3
[    2.701812] Linux agpgart interface v0.103
[    2.703193] ACPI: bus type drm_connector registered
[    2.704650] xhci_hcd 0000:00:14.0: xHCI Host Controller
[    2.704655] xhci_hcd 0000:00:14.0: new USB bus registered, assigned bus number 1
[    2.705756] xhci_hcd 0000:00:14.0: hcc params 0x20007fc1 hci version 0x120 quirks 0x0000000200009810
[    2.706066] xhci_hcd 0000:00:14.0: xHCI Host Controller
[    2.706068] xhci_hcd 0000:00:14.0: new USB bus registered, assigned bus number 2
[    2.706070] xhci_hcd 0000:00:14.0: Host supports USB 3.2 Enhanced SuperSpeed
[    2.706098] usb usb1: New USB device found, idVendor=1d6b, idProduct=0002, bcdDevice= 6.15
[    2.706101] usb usb1: New USB device strings: Mfr=3, Product=2, SerialNumber=1
[    2.706102] usb usb1: Product: xHCI Host Controller
[    2.706103] usb usb1: Manufacturer: Linux 6.15.4-zen2-1-zen xhci-hcd
[    2.706104] usb usb1: SerialNumber: 0000:00:14.0
[    2.706204] hub 1-0:1.0: USB hub found
[    2.706226] hub 1-0:1.0: 16 ports detected
[    2.709334] usb usb2: New USB device found, idVendor=1d6b, idProduct=0003, bcdDevice= 6.15
[    2.709336] usb usb2: New USB device strings: Mfr=3, Product=2, SerialNumber=1
[    2.709338] usb usb2: Product: xHCI Host Controller
[    2.709339] usb usb2: Manufacturer: Linux 6.15.4-zen2-1-zen xhci-hcd
[    2.709340] usb usb2: SerialNumber: 0000:00:14.0
[    2.709393] hub 2-0:1.0: USB hub found
[    2.709413] hub 2-0:1.0: 9 ports detected
[    2.711203] usbcore: registered new interface driver usbserial_generic
[    2.711207] usbserial: USB Serial support registered for generic
[    2.711229] i8042: PNP: No PS/2 controller found.
[    2.711294] rtc_cmos rtc_cmos: RTC can wake from S4
[    2.712183] rtc_cmos rtc_cmos: registered as rtc0
[    2.712366] rtc_cmos rtc_cmos: setting system clock to 2025-07-12T11:14:31 UTC (1752318871)
[    2.712396] rtc_cmos rtc_cmos: alarms up to one month, y3k, 114 bytes nvram
[    2.713046] intel_pstate: Intel P-state driver initializing
[    2.714064] intel_pstate: HWP enabled
[    2.714281] simple-framebuffer simple-framebuffer.0: [drm] Registered 1 planes with drm panic
[    2.714282] [drm] Initialized simpledrm 1.0.0 for simple-framebuffer.0 on minor 0
[    2.715354] fbcon: Deferring console take-over
[    2.715355] simple-framebuffer simple-framebuffer.0: [drm] fb0: simpledrmdrmfb frame buffer device
[    2.715380] hid: raw HID events driver (C) Jiri Kosina
[    2.715389] usbcore: registered new interface driver usbhid
[    2.715390] usbhid: USB HID core driver
[    2.715423] drop_monitor: Initializing network drop monitor service
[    2.715489] NET: Registered PF_INET6 protocol family
[    2.720433] Segment Routing with IPv6
[    2.720435] RPL Segment Routing with IPv6
[    2.720439] In-situ OAM (IOAM) with IPv6
[    2.720457] NET: Registered PF_PACKET protocol family
[    2.721228] microcode: Current revision: 0x0000003a
[    2.721228] microcode: Updated early from: 0x00000036
[    2.721326] IPI shorthand broadcast: enabled
[    2.722328] sched_clock: Marking stable (2714001174, 7587149)->(2782515226, -60926903)
[    2.722432] registered taskstats version 1
[    2.722652] Loading compiled-in X.509 certificates
[    2.726015] Loaded X.509 cert 'Build time autogenerated kernel key: c925277f41a018ad10e592e1e9ffe216e7688a9f'
[    2.728776] zswap: loaded using pool zstd/zsmalloc
[    2.728804] Demotion targets for Node 0: null
[    2.728878] Key type .fscrypt registered
[    2.728879] Key type fscrypt-provisioning registered
[    2.729336] Btrfs loaded, zoned=yes, fsverity=yes
[    2.729350] Key type big_key registered
[    2.729569] integrity: Loading X.509 certificate: UEFI:db
[    2.729584] integrity: Loaded X.509 cert 'Microsoft Corporation UEFI CA 2011: 13adbf4309bd82709c8cd54f316ed522988a1bd4'
[    2.729585] integrity: Loading X.509 certificate: UEFI:db
[    2.729605] integrity: Loaded X.509 cert 'Microsoft Windows Production PCA 2011: a92902398e16c49778cd90f99e4f9ae17c55af53'
[    2.729605] integrity: Loading X.509 certificate: UEFI:db
[    2.731226] integrity: Problem loading X.509 certificate -22
[    2.731228] integrity: Error adding keys to platform keyring UEFI:db
[    2.731228] integrity: Loading X.509 certificate: UEFI:db
[    2.731238] integrity: Problem loading X.509 certificate -22
[    2.731239] integrity: Error adding keys to platform keyring UEFI:db
[    2.731239] integrity: Loading X.509 certificate: UEFI:db
[    2.731249] integrity: Loaded X.509 cert 'Microsoft UEFI CA 2023: 81aa6b3244c935bce0d6628af39827421e32497d'
[    2.731249] integrity: Loading X.509 certificate: UEFI:db
[    2.731257] integrity: Loaded X.509 cert 'Microsoft Option ROM UEFI CA 2023: 514fbf937fa46fb57bf07af8bed84b3b864b1711'
[    2.732162] PM:   Magic number: 1:242:226
[    2.732163] PM:   hash matches drivers/base/power/main.c:1478
[    2.732214] acpi device:73: hash matches
[    2.732885] RAS: Correctable Errors collector initialized.
[    2.735336] clk: Disabling unused clocks
[    2.735337] PM: genpd: Disabling unused power domains
[    2.747465] Freeing unused decrypted memory: 2028K
[    2.748053] Freeing unused kernel image (initmem) memory: 4784K
[    2.748069] Write protecting the kernel read-only data: 38912k
[    2.748477] Freeing unused kernel image (text/rodata gap) memory: 60K
[    2.748512] Freeing unused kernel image (rodata/data gap) memory: 132K
[    2.753726] x86/mm: Checked W+X mappings: passed, no W+X pages found.
[    2.753729] rodata_test: all tests were successful
[    2.753732] Run /init as init process
[    2.753733]   with arguments:
[    2.753734]     /init
[    2.753735]   with environment:
[    2.753735]     HOME=/
[    2.753736]     TERM=linux
[    2.753736]     BOOT_IMAGE=/@/boot/vmlinuz-linux-zen
[    2.773518] systemd[1]: Successfully made /usr/ read-only.
[    2.773578] systemd[1]: systemd 257.7-1-arch running in system mode (+PAM +AUDIT -SELINUX -APPARMOR -IMA +IPE +SMACK +SECCOMP +GCRYPT +GNUTLS +OPENSSL +ACL +BLKID +CURL +ELFUTILS +FIDO2 +IDN2 -IDN +IPTC +KMOD +LIBCRYPTSETUP +LIBCRYPTSETUP_PLUGINS +LIBFDISK +PCRE2 +PWQUALITY +P11KIT +QRENCODE +TPM2 +BZIP2 +LZ4 +XZ +ZLIB +ZSTD +BPF_FRAMEWORK +BTF +XKBCOMMON +UTMP -SYSVINIT +LIBARCHIVE)
[    2.773581] systemd[1]: Detected architecture x86-64.
[    2.773582] systemd[1]: Running in initrd.
[    2.773655] systemd[1]: Hostname set to <matthias>.
[    2.943697] systemd[1]: bpf-restrict-fs: LSM BPF program attached
[    2.944600] usb 1-4: new high-speed USB device number 2 using xhci_hcd
[    3.004470] systemd[1]: Queued start job for default target Initrd Default Target.
[    3.016001] systemd[1]: Started Dispatch Password Requests to Console Directory Watch.
[    3.016025] systemd[1]: Expecting device /dev/disk/by-uuid/206eec02-6fca-4d04-910e-2bf9fddca883...
[    3.016042] systemd[1]: Reached target Initrd /usr File System.
[    3.016054] systemd[1]: Reached target Path Units.
[    3.016069] systemd[1]: Reached target Slice Units.
[    3.016079] systemd[1]: Reached target Swaps.
[    3.016088] systemd[1]: Reached target Timer Units.
[    3.016135] systemd[1]: Listening on D-Bus System Message Bus Socket.
[    3.016152] systemd[1]: Listening on Open-iSCSI iscsid Socket.
[    3.016172] systemd[1]: Listening on Open-iSCSI iscsiuio Socket.
[    3.016203] systemd[1]: Listening on Journal Socket (/dev/log).
[    3.016233] systemd[1]: Listening on Journal Sockets.
[    3.016261] systemd[1]: Listening on udev Control Socket.
[    3.016281] systemd[1]: Listening on udev Kernel Socket.
[    3.016289] systemd[1]: Reached target Socket Units.
[    3.016939] systemd[1]: Starting Create List of Static Device Nodes...
[    3.016985] systemd[1]: Check battery level during early boot was skipped because of an unmet condition check (ConditionDirectoryNotEmpty=/sys/class/power_supply).
[    3.017974] systemd[1]: Starting Journal Service...
[    3.018484] systemd[1]: Starting Load Kernel Modules...
[    3.018504] systemd[1]: TPM PCR Barrier (initrd) was skipped because of an unmet condition check (ConditionSecurity=measured-uki).
[    3.018516] systemd[1]: Reached target Local Encrypted Volumes.
[    3.018916] systemd[1]: Starting Virtual Console Setup...
[    3.020397] systemd[1]: Finished Create List of Static Device Nodes.
[    3.020872] systemd[1]: Starting Create Static Device Nodes in /dev gracefully...
[    3.025371] systemd[1]: Finished Virtual Console Setup.
[    3.025418] i2c_dev: i2c /dev entries driver
[    3.025836] systemd[1]: Starting dracut ask for additional cmdline parameters...
[    3.027755] systemd-journald[221]: Collecting audit messages is disabled.
[    3.028785] systemd[1]: Finished Create Static Device Nodes in /dev gracefully.
[    3.029200] systemd[1]: Starting Create Static Device Nodes in /dev...
[    3.031424] vboxdrv: loading out-of-tree module taints kernel.
[    3.031427] vboxdrv: module verification failed: signature and/or required key missing - tainting kernel
[    3.038271] vboxdrv: Found 16 processor cores/threads
[    3.038298] systemd[1]: Finished dracut ask for additional cmdline parameters.
[    3.038941] systemd[1]: Starting dracut cmdline hook...
[    3.040366] systemd[1]: Finished Create Static Device Nodes in /dev.
[    3.040415] systemd[1]: Reached target Preparation for Local File Systems.
[    3.040423] systemd[1]: Reached target Local File Systems.
[    3.053772] vboxdrv: TSC mode is Invariant, tentative frequency 2495991236 Hz
[    3.053773] vboxdrv: Successfully loaded version 7.1.10 r169112 (interface 0x00340001)
[    3.053821] systemd[1]: Started Journal Service.
[    3.058163] VBoxNetAdp: Successfully started.
[    3.062365] VBoxNetFlt: Successfully started.
[    3.071047] usb 1-4: New USB device found, idVendor=05e3, idProduct=0610, bcdDevice= 6.56
[    3.071051] usb 1-4: New USB device strings: Mfr=1, Product=2, SerialNumber=0
[    3.071052] usb 1-4: Product: USB2.1 Hub
[    3.071053] usb 1-4: Manufacturer: GenesysLogic
[    3.072101] hub 1-4:1.0: USB hub found
[    3.072339] hub 1-4:1.0: 4 ports detected
[    3.177614] Loading iSCSI transport class v2.0-870.
[    3.181703] usb 2-9: new SuperSpeed USB device number 2 using xhci_hcd
[    3.183354] iscsi: registered transport (tcp)
[    3.195985] usb 2-9: New USB device found, idVendor=05e3, idProduct=0626, bcdDevice= 6.56
[    3.195991] usb 2-9: New USB device strings: Mfr=1, Product=2, SerialNumber=0
[    3.195993] usb 2-9: Product: USB3.1 Hub
[    3.195995] usb 2-9: Manufacturer: GenesysLogic
[    3.197939] hub 2-9:1.0: USB hub found
[    3.198223] hub 2-9:1.0: 4 ports detected
[    3.304376] device-mapper: uevent: version 1.0.3
[    3.304444] device-mapper: ioctl: 4.49.0-ioctl (2025-01-17) initialised: dm-devel@lists.linux.dev
[    3.306598] usb 1-9: new high-speed USB device number 3 using xhci_hcd
[    3.342563] RPC: Registered named UNIX socket transport module.
[    3.342565] RPC: Registered udp transport module.
[    3.342565] RPC: Registered tcp transport module.
[    3.342566] RPC: Registered tcp-with-tls transport module.
[    3.342566] RPC: Registered tcp NFSv4.1 backchannel transport module.
[    3.432918] usb 1-9: New USB device found, idVendor=05e3, idProduct=0608, bcdDevice=60.70
[    3.432932] usb 1-9: New USB device strings: Mfr=0, Product=1, SerialNumber=0
[    3.432937] usb 1-9: Product: USB2.0 Hub
[    3.434609] hub 1-9:1.0: USB hub found
[    3.434901] hub 1-9:1.0: 4 ports detected
[    3.518783] usb 1-4.2: new high-speed USB device number 4 using xhci_hcd
[    3.619148] usb 1-4.2: New USB device found, idVendor=05e3, idProduct=0610, bcdDevice= 6.63
[    3.619158] usb 1-4.2: New USB device strings: Mfr=1, Product=2, SerialNumber=0
[    3.619162] usb 1-4.2: Product: USB2.1 Hub
[    3.619165] usb 1-4.2: Manufacturer: GenesysLogic
[    3.620890] hub 1-4.2:1.0: USB hub found
[    3.621134] hub 1-4.2:1.0: 4 ports detected
[    3.680676] ACPI: video: Video Device [GFX0] (multi-head: yes  rom: no  post: no)
[    3.681294] input: Video Bus as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0A08:00/LNXVIDEO:00/input/input3
[    3.681719] usb 2-9.2: new SuperSpeed USB device number 3 using xhci_hcd
[    3.685995] vmd 0000:00:0e.0: PCI host bridge to bus 10000:e0
[    3.685999] pci_bus 10000:e0: root bus resource [bus e0-ff]
[    3.686001] pci_bus 10000:e0: root bus resource [mem 0x42000000-0x43ffffff]
[    3.686002] pci_bus 10000:e0: root bus resource [mem 0x6415102000-0x64151fffff 64bit]
[    3.686026] pci 10000:e0:06.0: [8086:464d] type 01 class 0x060400 PCIe Root Port
[    3.686037] pci 10000:e0:06.0: PCI bridge to [bus e1]
[    3.686040] pci 10000:e0:06.0:   bridge window [io  0x0000-0x0fff]
[    3.686042] pci 10000:e0:06.0:   bridge window [mem 0x42100000-0x421fffff]
[    3.686076] pci 10000:e0:06.0: PME# supported from D0 D3hot D3cold
[    3.686094] pci 10000:e0:06.0: PTM enabled (root), 4ns granularity
[    3.686262] pci 10000:e0:17.0: [8086:7a62] type 00 class 0x010601 conventional PCI endpoint
[    3.686309] pci 10000:e0:17.0: BAR 0 [mem 0x00000000-0x00001fff]
[    3.686312] pci 10000:e0:17.0: BAR 1 [mem 0x00000000-0x000000ff]
[    3.686314] pci 10000:e0:17.0: BAR 2 [io  0x0000-0x0007]
[    3.686316] pci 10000:e0:17.0: BAR 3 [io  0x0000-0x0003]
[    3.686318] pci 10000:e0:17.0: BAR 4 [io  0x0000-0x001f]
[    3.686320] pci 10000:e0:17.0: BAR 5 [mem 0x42000000-0x420007ff]
[    3.686349] pci 10000:e0:17.0: PME# supported from D3hot
[    3.686387] pci 10000:e0:06.0: Primary bus is hard wired to 0
[    3.686419] pci 10000:e1:00.0: [144d:a80a] type 00 class 0x010802 PCIe Endpoint
[    3.686453] pci 10000:e1:00.0: BAR 0 [mem 0x42100000-0x42103fff 64bit]
[    3.686675] pci 10000:e0:06.0: PCI bridge to [bus e1]
[    3.686685] pci 10000:e0:06.0: Primary bus is hard wired to 0
[    3.686754] pps_core: LinuxPPS API ver. 1 registered
[    3.686755] pps_core: Software ver. 5.3.6 - Copyright 2005-2007 Rodolfo Giometti <giometti@linux.it>
[    3.687845] cryptd: max_cpu_qlen set to 1000
[    3.691155] PTP clock support registered
[    3.691828] idma64 idma64.0: Found Intel integrated DMA 64-bit
[    3.697783] e1000e: Intel(R) PRO/1000 Network Driver
[    3.697785] e1000e: Copyright(c) 1999 - 2015 Intel Corporation.
[    3.697816] e1000e 0000:06:00.0: enabling device (0000 -> 0002)
[    3.698054] e1000e 0000:06:00.0: Interrupt Throttling Rate (ints/sec) set to dynamic conservative mode
[    3.698192] idma64 idma64.1: Found Intel integrated DMA 64-bit
[    3.698948] r8169 0000:05:00.0: can't disable ASPM; OS doesn't have ASPM control
[    3.699716] usb 2-9.2: New USB device found, idVendor=05e3, idProduct=0626, bcdDevice= 6.63
[    3.699718] usb 2-9.2: New USB device strings: Mfr=1, Product=2, SerialNumber=0
[    3.699719] usb 2-9.2: Product: USB3.1 Hub
[    3.699720] usb 2-9.2: Manufacturer: GenesysLogic
[    3.702767] hub 2-9.2:1.0: USB hub found
[    3.703204] i2c i2c-1: Invalid 7-bit I2C address 0xffff
[    3.703555] hub 2-9.2:1.0: 4 ports detected
[    3.704010] idma64 idma64.2: Found Intel integrated DMA 64-bit
[    3.705180] r8169 0000:05:00.0 eth0: RTL8168h/8111h, 74:56:3c:eb:01:d1, XID 541, IRQ 153
[    3.705183] r8169 0000:05:00.0 eth0: jumbo features [frames: 9194 bytes, tx checksumming: ko]
[    3.709313] idma64 idma64.3: Found Intel integrated DMA 64-bit
[    3.714493] idma64 idma64.4: Found Intel integrated DMA 64-bit
[    3.719407] r8169 0000:05:00.0 enp5s0: renamed from eth0
[    3.719664] idma64 idma64.5: Found Intel integrated DMA 64-bit
[    3.807847] usb 1-10: new high-speed USB device number 5 using xhci_hcd
[    3.854231] e1000e 0000:06:00.0 eth0: (PCI Express:2.5GT/s:Width x1) 00:15:17:38:10:7e
[    3.854246] e1000e 0000:06:00.0 eth0: Intel(R) PRO/1000 Network Connection
[    3.854333] e1000e 0000:06:00.0 eth0: MAC: 1, PHY: 4, PBA No: D50861-003
[    3.858172] e1000e 0000:06:00.0 enp6s0: renamed from eth0
[    3.873711] pci 10000:e0:06.0: bridge window [mem 0x42000000-0x420fffff]: assigned
[    3.873725] pci 10000:e0:17.0: BAR 0 [mem 0x42100000-0x42101fff]: assigned
[    3.873737] pci 10000:e0:06.0: bridge window [io  size 0x1000]: can't assign; no space
[    3.873741] pci 10000:e0:06.0: bridge window [io  size 0x1000]: failed to assign
[    3.873745] pci 10000:e0:17.0: BAR 5 [mem 0x42102000-0x421027ff]: assigned
[    3.873765] pci 10000:e0:17.0: BAR 1 [mem 0x42102800-0x421028ff]: assigned
[    3.873772] pci 10000:e0:17.0: BAR 4 [io  size 0x0020]: can't assign; no space
[    3.873775] pci 10000:e0:17.0: BAR 4 [io  size 0x0020]: failed to assign
[    3.873778] pci 10000:e0:17.0: BAR 2 [io  size 0x0008]: can't assign; no space
[    3.873781] pci 10000:e0:17.0: BAR 2 [io  size 0x0008]: failed to assign
[    3.873784] pci 10000:e0:17.0: BAR 3 [io  size 0x0004]: can't assign; no space
[    3.873787] pci 10000:e0:17.0: BAR 3 [io  size 0x0004]: failed to assign
[    3.873792] pci 10000:e0:06.0: bridge window [io  size 0x1000]: can't assign; no space
[    3.873795] pci 10000:e0:06.0: bridge window [io  size 0x1000]: failed to assign
[    3.873798] pci 10000:e0:17.0: BAR 4 [io  size 0x0020]: can't assign; no space
[    3.873802] pci 10000:e0:17.0: BAR 4 [io  size 0x0020]: failed to assign
[    3.873804] pci 10000:e0:17.0: BAR 2 [io  size 0x0008]: can't assign; no space
[    3.873807] pci 10000:e0:17.0: BAR 2 [io  size 0x0008]: failed to assign
[    3.873810] pci 10000:e0:17.0: BAR 3 [io  size 0x0004]: can't assign; no space
[    3.873813] pci 10000:e0:17.0: BAR 3 [io  size 0x0004]: failed to assign
[    3.873819] pci 10000:e1:00.0: BAR 0 [mem 0x42000000-0x42003fff 64bit]: assigned
[    3.873832] pci 10000:e0:06.0: PCI bridge to [bus e1]
[    3.873838] pci 10000:e0:06.0:   bridge window [mem 0x42000000-0x420fffff]
[    3.873877] pci 10000:e1:00.0: can't override BIOS ASPM; OS doesn't have ASPM control
[    3.873933] pcieport 10000:e0:06.0: can't derive routing for PCI INT D
[    3.873937] pcieport 10000:e0:06.0: PCI INT D: no GSI
[    3.874083] pcieport 10000:e0:06.0: PME: Signaling with IRQ 154
[    3.874354] pcieport 10000:e0:06.0: AER: enabled with IRQ 154
[    3.874513] ahci 10000:e0:17.0: version 3.0
[    3.874524] ahci 10000:e0:17.0: can't derive routing for PCI INT A
[    3.874527] ahci 10000:e0:17.0: PCI INT A: no GSI
[    3.874800] ahci 10000:e0:17.0: AHCI vers 0001.0301, 32 command slots, 6 Gbps, SATA mode
[    3.874808] ahci 10000:e0:17.0: 4/4 ports implemented (port mask 0xf0)
[    3.874812] ahci 10000:e0:17.0: flags: 64bit ncq sntf pm led clo only pio slum part ems deso sadm sds 
[    3.881868] scsi host0: ahci
[    3.882196] scsi host1: ahci
[    3.882502] scsi host2: ahci
[    3.882823] scsi host3: ahci
[    3.883129] scsi host4: ahci
[    3.883476] scsi host5: ahci
[    3.883810] scsi host6: ahci
[    3.884125] scsi host7: ahci
[    3.884274] ata1: DUMMY
[    3.884280] ata2: DUMMY
[    3.884283] ata3: DUMMY
[    3.884286] ata4: DUMMY
[    3.884294] ata5: SATA max UDMA/133 abar m2048@0x42102000 port 0x42102300 irq 155 lpm-pol 3
[    3.884302] ata6: SATA max UDMA/133 abar m2048@0x42102000 port 0x42102380 irq 155 lpm-pol 3
[    3.884308] ata7: SATA max UDMA/133 abar m2048@0x42102000 port 0x42102400 irq 155 lpm-pol 3
[    3.884314] ata8: SATA max UDMA/133 abar m2048@0x42102000 port 0x42102480 irq 155 lpm-pol 3
[    3.884397] vmd 0000:00:0e.0: Bound to PCI domain 10000
[    4.040719] usb 1-4.3: new full-speed USB device number 6 using xhci_hcd
[    4.150869] usb 1-4.3: New USB device found, idVendor=1038, idProduct=1836, bcdDevice= 1.00
[    4.150884] usb 1-4.3: New USB device strings: Mfr=1, Product=2, SerialNumber=0
[    4.150889] usb 1-4.3: Product: SteelSeries Aerox 3
[    4.150893] usb 1-4.3: Manufacturer: SteelSeries
[    4.161714] input: SteelSeries SteelSeries Aerox 3 as /devices/pci0000:00/0000:00:14.0/usb1/1-4/1-4.3/1-4.3:1.0/0003:1038:1836.0001/input/input4
[    4.162046] hid-generic 0003:1038:1836.0001: input,hidraw0: USB HID v1.11 Mouse [SteelSeries SteelSeries Aerox 3] on usb-0000:00:14.0-4.3/input0
[    4.163750] input: SteelSeries SteelSeries Aerox 3 Keyboard as /devices/pci0000:00/0000:00:14.0/usb1/1-4/1-4.3/1-4.3:1.1/0003:1038:1836.0002/input/input5
[    4.191912] ata5: SATA link up 6.0 Gbps (SStatus 133 SControl 300)
[    4.192266] ata7: SATA link up 6.0 Gbps (SStatus 133 SControl 300)
[    4.192319] ata8: SATA link up 6.0 Gbps (SStatus 133 SControl 300)
[    4.192372] ata6: SATA link up 6.0 Gbps (SStatus 133 SControl 300)
[    4.192537] ata5.00: supports DRM functions and may not be fully accessible
[    4.192548] ata5.00: ATA-11: SAMSUNG MZ7L3480HCHQ-00A07, JXTC104Q, max UDMA/133
[    4.193398] ata7.00: ATA-8: Hitachi HDS721010CLA632, JP4OA41A, max UDMA/133
[    4.193426] ata8.00: ATA-8: ST3500413AS, HP61, max UDMA/100
[    4.193439] ata8.00: 976773168 sectors, multi 0: LBA48 NCQ (depth 32)
[    4.193468] ata6.00: ATA-8: ST3500413AS, HP61, max UDMA/100
[    4.193480] ata6.00: 976773168 sectors, multi 0: LBA48 NCQ (depth 32)
[    4.193550] ata7.00: 1953525168 sectors, multi 0: LBA48 NCQ (depth 32), AA
[    4.193696] ata5.00: 937703088 sectors, multi 16: LBA48 NCQ (depth 32), AA
[    4.194750] ata6.00: configured for UDMA/100
[    4.194795] ata8.00: configured for UDMA/100
[    4.195082] ata7.00: configured for UDMA/133
[    4.197001] ata5.00: Features: Trust NCQ-sndrcv
[    4.197318] ata5.00: supports DRM functions and may not be fully accessible
[    4.201558] ata5.00: configured for UDMA/133
[    4.211936] scsi 4:0:0:0: Direct-Access     ATA      SAMSUNG MZ7L3480 104Q PQ: 0 ANSI: 5
[    4.212549] sd 4:0:0:0: [sda] 937703088 512-byte logical blocks: (480 GB/447 GiB)
[    4.212557] sd 4:0:0:0: [sda] 4096-byte physical blocks
[    4.212570] sd 4:0:0:0: [sda] Write Protect is off
[    4.212574] sd 4:0:0:0: [sda] Mode Sense: 00 3a 00 00
[    4.212606] sd 4:0:0:0: [sda] Write cache: enabled, read cache: enabled, doesn't support DPO or FUA
[    4.212664] sd 4:0:0:0: [sda] Preferred minimum I/O size 4096 bytes
[    4.214551] scsi 5:0:0:0: Direct-Access     ATA      ST3500413AS      HP61 PQ: 0 ANSI: 5
[    4.215189] sd 5:0:0:0: [sdb] 976773168 512-byte logical blocks: (500 GB/466 GiB)
[    4.215205] sd 5:0:0:0: [sdb] Write Protect is off
[    4.215209] sd 5:0:0:0: [sdb] Mode Sense: 00 3a 00 00
[    4.215229] sd 5:0:0:0: [sdb] Write cache: enabled, read cache: enabled, doesn't support DPO or FUA
[    4.215264] sd 5:0:0:0: [sdb] Preferred minimum I/O size 512 bytes
[    4.215338] scsi 6:0:0:0: Direct-Access     ATA      Hitachi HDS72101 A41A PQ: 0 ANSI: 5
[    4.216443] sd 6:0:0:0: [sdc] 1953525168 512-byte logical blocks: (1.00 TB/932 GiB)
[    4.216468] scsi 7:0:0:0: Direct-Access     ATA      ST3500413AS      HP61 PQ: 0 ANSI: 5
[    4.216500] sd 6:0:0:0: [sdc] Write Protect is off
[    4.216511] sd 6:0:0:0: [sdc] Mode Sense: 00 3a 00 00
[    4.216560] sd 6:0:0:0: [sdc] Write cache: enabled, read cache: enabled, doesn't support DPO or FUA
[    4.216620] sd 6:0:0:0: [sdc] Preferred minimum I/O size 512 bytes
[    4.217460] sd 7:0:0:0: [sdd] 976773168 512-byte logical blocks: (500 GB/466 GiB)
[    4.217481] sd 7:0:0:0: [sdd] Write Protect is off
[    4.217486] sd 7:0:0:0: [sdd] Mode Sense: 00 3a 00 00
[    4.217509] sd 7:0:0:0: [sdd] Write cache: enabled, read cache: enabled, doesn't support DPO or FUA
[    4.217545] sd 7:0:0:0: [sdd] Preferred minimum I/O size 512 bytes
[    4.224668]  sda: sda1
[    4.225822] sd 4:0:0:0: [sda] supports TCG Opal
[    4.225827] sd 4:0:0:0: [sda] Attached SCSI disk
[    4.230961]  sdb: sdb1
[    4.231085] sd 5:0:0:0: [sdb] Attached SCSI disk
[    4.232361] sd 6:0:0:0: [sdc] Attached SCSI disk
[    4.240746] hid-generic 0003:1038:1836.0002: input,hidraw1: USB HID v1.11 Keyboard [SteelSeries SteelSeries Aerox 3] on usb-0000:00:14.0-4.3/input1
[    4.241555] hid-generic 0003:1038:1836.0003: hiddev96,hidraw2: USB HID v1.11 Device [SteelSeries SteelSeries Aerox 3] on usb-0000:00:14.0-4.3/input2
[    4.242280] hid-generic 0003:1038:1836.0004: hiddev97,hidraw3: USB HID v1.11 Device [SteelSeries SteelSeries Aerox 3] on usb-0000:00:14.0-4.3/input3
[    4.258701]  sdd: sdd1
[    4.258845] sd 7:0:0:0: [sdd] Attached SCSI disk
[    4.278616] Key type psk registered
[    4.289181] nvme nvme0: pci function 10000:e1:00.0
[    4.289191] pcieport 10000:e0:06.0: can't derive routing for PCI INT A
[    4.289192] nvme 10000:e1:00.0: PCI INT A: not connected
[    4.291015] nvme nvme0: D3 entry latency set to 10 seconds
[    4.297929] nvme nvme0: 16/0/0 default/read/poll queues
[    4.300951]  nvme0n1: p1 p2
[    4.329595] usb 1-4.4: new full-speed USB device number 7 using xhci_hcd
[    4.439967] usb 1-4.4: New USB device found, idVendor=046d, idProduct=c22d, bcdDevice= 1.65
[    4.439970] usb 1-4.4: New USB device strings: Mfr=1, Product=2, SerialNumber=0
[    4.439971] usb 1-4.4: Product: G510 Gaming Keyboard
[    4.439972] usb 1-4.4: Manufacturer: Logitech
[    4.451847] input: Logitech G510 Gaming Keyboard as /devices/pci0000:00/0000:00:14.0/usb1/1-4/1-4.4/1-4.4:1.0/0003:046D:C22D.0005/input/input6
[    4.562901] hid-generic 0003:046D:C22D.0005: input,hidraw4: USB HID v1.11 Keyboard [Logitech G510 Gaming Keyboard] on usb-0000:00:14.0-4.4/input0
[    4.564824] input: Logitech G510 Gaming Keyboard Consumer Control as /devices/pci0000:00/0000:00:14.0/usb1/1-4/1-4.4/1-4.4:1.1/0003:046D:C22D.0006/input/input7
[    4.615942] hid-generic 0003:046D:C22D.0006: input,hiddev98,hidraw5: USB HID v1.11 Device [Logitech G510 Gaming Keyboard] on usb-0000:00:14.0-4.4/input1
[    6.187291] usb 1-10: New USB device found, idVendor=090c, idProduct=1000, bcdDevice=10.00
[    6.187306] usb 1-10: New USB device strings: Mfr=1, Product=2, SerialNumber=3
[    6.187311] usb 1-10: SerialNumber: 10102386002101
[    6.301776] usb 1-11: new full-speed USB device number 8 using xhci_hcd
[    6.434722] usb 1-11: New USB device found, idVendor=048d, idProduct=5702, bcdDevice= 0.01
[    6.434739] usb 1-11: New USB device strings: Mfr=1, Product=2, SerialNumber=0
[    6.434744] usb 1-11: Product: ITE Device
[    6.434748] usb 1-11: Manufacturer: ITE Tech. Inc.
[    6.442992] hid-generic 0003:048D:5702.0007: hiddev99,hidraw6: USB HID v1.12 Device [ITE Tech. Inc. ITE Device] on usb-0000:00:14.0-11/input0
[    6.453707] usb-storage 1-10:1.0: USB Mass Storage device detected
[    6.453825] scsi host8: usb-storage 1-10:1.0
[    6.453864] usbcore: registered new interface driver usb-storage
[    6.458526] usbcore: registered new interface driver uas
[    6.552331] input: Logitech G510 Gaming Keyboard as /devices/pci0000:00/0000:00:14.0/usb1/1-4/1-4.4/1-4.4:1.0/0003:046D:C22D.0005/input/input9
[    6.641974] lg-g15 0003:046D:C22D.0005: input,hidraw4: USB HID v1.11 Keyboard [Logitech G510 Gaming Keyboard] on usb-0000:00:14.0-4.4/input0
[    6.662419] input: Logitech G510 Gaming Keyboard Consumer Control as /devices/pci0000:00/0000:00:14.0/usb1/1-4/1-4.4/1-4.4:1.1/0003:046D:C22D.0006/input/input11
[    6.713358] lg-g15 0003:046D:C22D.0006: input,hidraw5: USB HID v1.11 Device [Logitech G510 Gaming Keyboard] on usb-0000:00:14.0-4.4/input1
[    6.717720] input: Logitech Gaming Keyboard Gaming Keys as /devices/pci0000:00/0000:00:14.0/usb1/1-4/1-4.4/1-4.4:1.1/0003:046D:C22D.0006/input/input10
[    6.905786] BTRFS: device fsid 206eec02-6fca-4d04-910e-2bf9fddca883 devid 1 transid 8533 /dev/nvme0n1p2 (259:2) scanned by mount (640)
[    6.906332] BTRFS info (device nvme0n1p2): first mount of filesystem 206eec02-6fca-4d04-910e-2bf9fddca883
[    6.906361] BTRFS info (device nvme0n1p2): using crc32c (crc32c-x86) checksum algorithm
[    6.906372] BTRFS info (device nvme0n1p2): using free-space-tree
[    7.241740] systemd-journald[221]: Received SIGTERM from PID 1 (systemd).
[    7.373814] systemd[1]: systemd 257.7-1-arch running in system mode (+PAM +AUDIT -SELINUX -APPARMOR -IMA +IPE +SMACK +SECCOMP +GCRYPT +GNUTLS +OPENSSL +ACL +BLKID +CURL +ELFUTILS +FIDO2 +IDN2 -IDN +IPTC +KMOD +LIBCRYPTSETUP +LIBCRYPTSETUP_PLUGINS +LIBFDISK +PCRE2 +PWQUALITY +P11KIT +QRENCODE +TPM2 +BZIP2 +LZ4 +XZ +ZLIB +ZSTD +BPF_FRAMEWORK +BTF +XKBCOMMON +UTMP -SYSVINIT +LIBARCHIVE)
[    7.373819] systemd[1]: Detected architecture x86-64.
[    7.598926] systemd[1]: bpf-restrict-fs: LSM BPF program attached
[    7.763363] scsi 8:0:0:0: Direct-Access                                    PQ: 0 ANSI: 0 CCS
[    7.765057] sd 8:0:0:0: [sde] 3948544 512-byte logical blocks: (2.02 GB/1.88 GiB)
[    7.765845] sd 8:0:0:0: [sde] Write Protect is off
[    7.765859] sd 8:0:0:0: [sde] Mode Sense: 43 00 00 00
[    7.768054] sd 8:0:0:0: [sde] No Caching mode page found
[    7.768065] sd 8:0:0:0: [sde] Assuming drive cache: write through
[    7.770881] systemd-sslh-generator: Configuration directory '/etc/sslh/' does not exist! No units generated.
[    7.771038] systemd-fstab-generator[707]: Mount point Partition is not a valid path, ignoring.
[    7.773718] (sd-exec-[698]: /usr/lib/systemd/system-generators/systemd-sslh-generator terminated by signal ABRT.
[    7.787907]  sde:
[    7.787943] sd 8:0:0:0: [sde] Attached SCSI removable disk
[    7.805059] zram: Added device: zram0
[    7.873457] systemd[1]: initrd-switch-root.service: Deactivated successfully.
[    7.873521] systemd[1]: Stopped Switch Root.
[    7.874058] systemd[1]: systemd-journald.service: Scheduled restart job, restart counter is at 1.
[    7.874215] systemd[1]: Created slice Virtual Machine and Container Slice.
[    7.874386] systemd[1]: Created slice Slice /system/dirmngr.
[    7.874530] systemd[1]: Created slice Slice /system/getty.
[    7.874711] systemd[1]: Created slice Slice /system/gpg-agent.
[    7.874855] systemd[1]: Created slice Slice /system/gpg-agent-browser.
[    7.874990] systemd[1]: Created slice Slice /system/gpg-agent-extra.
[    7.875126] systemd[1]: Created slice Slice /system/gpg-agent-ssh.
[    7.875256] systemd[1]: Created slice Slice /system/keyboxd.
[    7.875391] systemd[1]: Created slice Slice /system/systemd-fsck.
[    7.875524] systemd[1]: Created slice Slice /system/systemd-zram-setup.
[    7.875662] systemd[1]: Created slice User and Session Slice.
[    7.875691] systemd[1]: Started Dispatch Password Requests to Console Directory Watch.
[    7.875705] systemd[1]: Started Forward Password Requests to Wall Directory Watch.
[    7.875783] systemd[1]: Set up automount Arbitrary Executable File Formats File System Automount Point.
[    7.875790] systemd[1]: Expecting device /dev/disk/by-uuid/206eec02-6fca-4d04-910e-2bf9fddca883...
[    7.875793] systemd[1]: Expecting device /dev/disk/by-uuid/BFB3-965C...
[    7.875796] systemd[1]: Expecting device /dev/disk/by-uuid/bf97dd75-0621-4d96-8eca-cd1433c9795c...
[    7.875799] systemd[1]: Expecting device /dev/sdd1...
[    7.875803] systemd[1]: Expecting device /dev/zram0...
[    7.875810] systemd[1]: Reached target Local Encrypted Volumes.
[    7.875817] systemd[1]: Reached target Login Prompts.
[    7.875827] systemd[1]: Stopped target Switch Root.
[    7.875834] systemd[1]: Stopped target Initrd File Systems.
[    7.875839] systemd[1]: Stopped target Initrd Root File System.
[    7.875846] systemd[1]: Reached target Local Integrity Protected Volumes.
[    7.875856] systemd[1]: Reached target Remote File Systems.
[    7.875862] systemd[1]: Reached target Slice Units.
[    7.875878] systemd[1]: Reached target Local Verity Protected Volumes.
[    7.875913] systemd[1]: Listening on Device-mapper event daemon FIFOs.
[    7.875955] systemd[1]: Listening on LVM2 poll daemon socket.
[    7.876464] systemd[1]: Listening on Process Core Dump Socket.
[    7.876754] systemd[1]: Listening on Credential Encryption/Decryption.
[    7.876801] systemd[1]: Listening on Userspace Out-Of-Memory (OOM) Killer Socket.
[    7.876816] systemd[1]: TPM PCR Measurements was skipped because of an unmet condition check (ConditionSecurity=measured-uki).
[    7.876824] systemd[1]: Make TPM PCR Policy was skipped because of an unmet condition check (ConditionSecurity=measured-uki).
[    7.876847] systemd[1]: Listening on udev Control Socket.
[    7.876865] systemd[1]: Listening on udev Kernel Socket.
[    7.876892] systemd[1]: Listening on User Database Manager Socket.
[    7.877628] systemd[1]: Mounting Huge Pages File System...
[    7.878022] systemd[1]: Mounting POSIX Message Queue File System...
[    7.878381] systemd[1]: Mounting Kernel Debug File System...
[    7.878770] systemd[1]: Mounting Kernel Trace File System...
[    7.879276] systemd[1]: Starting Create List of Static Device Nodes...
[    7.879752] systemd[1]: Starting Monitoring of LVM2 mirrors, snapshots etc. using dmeventd or progress polling...
[    7.893004] systemd[1]: Starting Load Kernel Module configfs...
[    7.893545] systemd[1]: Starting Load Kernel Module dm_mod...
[    7.894478] systemd[1]: Starting Load Kernel Module drm...
[    7.895807] systemd[1]: Starting Load Kernel Module fuse...
[    7.896674] systemd[1]: Starting Load Kernel Module loop...
[    7.896725] systemd[1]: systemd-fsck-root.service: Deactivated successfully.
[    7.896755] systemd[1]: Stopped File System Check on Root Device.
[    7.896815] systemd[1]: Clear Stale Hibernate Storage Info was skipped because of an unmet condition check (ConditionPathExists=/sys/firmware/efi/efivars/HibernateLocation-8cf2644b-4b0b-428f-9387-6d876050dc67).
[    7.898360] systemd[1]: Starting Journal Service...
[    7.899770] systemd[1]: Starting Load Kernel Modules...
[    7.901498] systemd[1]: Starting Userspace Out-Of-Memory (OOM) Killer...
[    7.901530] systemd[1]: TPM PCR Machine ID Measurement was skipped because of an unmet condition check (ConditionSecurity=measured-uki).
[    7.902766] systemd[1]: Starting Remount Root and Kernel File Systems...
[    7.902880] systemd[1]: Early TPM SRK Setup was skipped because of an unmet condition check (ConditionSecurity=measured-uki).
[    7.903827] systemd[1]: Starting Load udev Rules from Credentials...
[    7.904744] systemd[1]: Starting Coldplug All udev Devices...
[    7.906507] systemd[1]: Mounted Huge Pages File System.
[    7.906612] systemd[1]: Mounted POSIX Message Queue File System.
[    7.906681] systemd[1]: Mounted Kernel Debug File System.
[    7.906740] systemd[1]: Mounted Kernel Trace File System.
[    7.906971] systemd[1]: Finished Create List of Static Device Nodes.
[    7.907216] systemd[1]: modprobe@configfs.service: Deactivated successfully.
[    7.907386] systemd[1]: Finished Load Kernel Module configfs.
[    7.907653] systemd[1]: modprobe@dm_mod.service: Deactivated successfully.
[    7.907853] systemd[1]: Finished Load Kernel Module dm_mod.
[    7.907870] loop: module loaded
[    7.908533] systemd[1]: modprobe@drm.service: Deactivated successfully.
[    7.908705] systemd[1]: Finished Load Kernel Module drm.
[    7.908909] systemd[1]: modprobe@fuse.service: Deactivated successfully.
[    7.909055] systemd[1]: Finished Load Kernel Module fuse.
[    7.909239] systemd[1]: modprobe@loop.service: Deactivated successfully.
[    7.909371] systemd[1]: Finished Load Kernel Module loop.
[    7.910995] systemd[1]: Mounting FUSE Control File System...
[    7.911016] systemd[1]: Repartition Root Disk was skipped because no trigger condition checks were met.
[    7.911594] systemd[1]: Starting Create Static Device Nodes in /dev gracefully...
[    7.913517] systemd[1]: Starting User Database Manager...
[    7.914061] systemd[1]: Finished Load Kernel Modules.
[    7.915279] systemd[1]: Starting Apply Kernel Variables...
[    7.915988] systemd[1]: Finished Load udev Rules from Credentials.
[    7.917278] systemd[1]: Mounted FUSE Control File System.
[    7.921093] systemd-journald[744]: Collecting audit messages is disabled.
[    7.924577] systemd[1]: Started Journal Service.
[    8.025892] BTRFS info (device nvme0n1p2 state M): use zstd compression, level 3
[    8.248702] zram0: detected capacity change from 0 to 131194880
[    8.271370] input: Intel HID events as /devices/platform/INTC1078:00/input/input13
[    8.272864] intel-hid INTC1078:00: failed to enable HID power button
[    8.274623] intel_pmc_core INT33A1:00:  initialized
[    8.281017] i801_smbus 0000:00:1f.4: SPD Write Disable is set
[    8.281045] i801_smbus 0000:00:1f.4: SMBus using PCI interrupt
[    8.283939] i2c i2c-6: Successfully instantiated SPD at 0x50
[    8.284326] i2c i2c-6: Successfully instantiated SPD at 0x51
[    8.284729] i2c i2c-6: Successfully instantiated SPD at 0x52
[    8.285087] i2c i2c-6: Successfully instantiated SPD at 0x53
[    8.338307] iTCO_vendor_support: vendor-support=0
[    8.342618] spd5118 6-0050: DDR5 temperature sensor: vendor 0x06:0x32 revision 1.6
[    8.343615] spi-nor spi0.0: supply vcc not found, using dummy regulator
[    8.343625] RAPL PMU: API unit is 2^-32 Joules, 3 fixed counters, 655360 ms ovfl timer
[    8.343627] RAPL PMU: hw unit of domain pp0-core 2^-14 Joules
[    8.343628] RAPL PMU: hw unit of domain package 2^-14 Joules
[    8.343629] RAPL PMU: hw unit of domain pp1-gpu 2^-14 Joules
[    8.344792] iTCO_wdt iTCO_wdt: Found a Intel PCH TCO device (Version=6, TCOBASE=0x0400)
[    8.344879] iTCO_wdt iTCO_wdt: initialized. heartbeat=30 sec (nowayout=0)
[    8.346720] spd5118 6-0051: DDR5 temperature sensor: vendor 0x00:0xb3 revision 2.2
[    8.346824] Creating 1 MTD partitions on "0000:00:1f.5":
[    8.346826] 0x000000000000-0x000001000000 : "BIOS"
[    8.350706] spd5118 6-0052: DDR5 temperature sensor: vendor 0x06:0x32 revision 1.6
[    8.351775] snd_hda_intel 0000:00:1f.3: enabling device (0000 -> 0002)
[    8.352091] snd_hda_intel 0000:03:00.1: enabling device (0000 -> 0002)
[    8.352195] snd_hda_intel 0000:03:00.1: Force to non-snoop mode
[    8.354631] spd5118 6-0053: DDR5 temperature sensor: vendor 0x00:0xb3 revision 2.2
[    8.548339] i915 0000:00:02.0: enabling device (0006 -> 0007)
[    8.548476] i915 0000:00:02.0: [drm] Found alderlake_s (device ID 4682) integrated display version 12.00 stepping C0
[    8.549228] i915 0000:00:02.0: [drm] Using Transparent Hugepages
[    8.559959] i915 0000:00:02.0: [drm] Finished loading DMC firmware i915/adls_dmc_ver2_01.bin (v2.1)
[    8.561367] input: HDA ATI HDMI HDMI/DP,pcm=3 as /devices/pci0000:00/0000:00:01.0/0000:01:00.0/0000:02:00.0/0000:03:00.1/sound/card0/input14
[    8.561424] input: HDA ATI HDMI HDMI/DP,pcm=7 as /devices/pci0000:00/0000:00:01.0/0000:01:00.0/0000:02:00.0/0000:03:00.1/sound/card0/input15
[    8.561699] input: HDA ATI HDMI HDMI/DP,pcm=8 as /devices/pci0000:00/0000:00:01.0/0000:01:00.0/0000:02:00.0/0000:03:00.1/sound/card0/input16
[    8.561823] input: HDA ATI HDMI HDMI/DP,pcm=9 as /devices/pci0000:00/0000:00:01.0/0000:01:00.0/0000:02:00.0/0000:03:00.1/sound/card0/input17
[    8.566411] i915 0000:00:02.0: [drm] GT0: GuC firmware i915/tgl_guc_70.bin version 70.44.1
[    8.566417] i915 0000:00:02.0: [drm] GT0: HuC firmware i915/tgl_huc.bin version 7.9.3
[    8.578594] i915 0000:00:02.0: [drm] GT0: HuC: authenticated for all workloads
[    8.578599] i915 0000:00:02.0: [drm] GT0: GUC: submission disabled
[    8.578601] i915 0000:00:02.0: [drm] GT0: GUC: SLPC disabled
[    8.579420] i915 0000:00:02.0: [drm] Protected Xe Path (PXP) protected content support initialized
[    8.579895] [drm] Initialized i915 1.6.0 for 0000:00:02.0 on minor 1
[    8.609646] i915 0000:00:02.0: [drm] Cannot find any crtc or sizes
[    8.624631] i915 0000:00:02.0: [drm] Cannot find any crtc or sizes
[    8.624635] snd_hda_intel 0000:00:1f.3: bound 0000:00:02.0 (ops intel_audio_component_bind_ops [i915])
[    8.662437] Adding 65597436k swap on /dev/zram0.  Priority:100 extents:1 across:65597436k SSDsc
[    8.889385] BTRFS: device fsid 51df8341-0b68-4455-9101-d673d923deb0 devid 1 transid 1843 /dev/sdd1 (8:49) scanned by mount (1095)
[    8.889935] BTRFS: device label Data devid 1 transid 61 /dev/sda1 (8:1) scanned by mount (1094)
[    8.890823] BTRFS info (device sdd1): first mount of filesystem 51df8341-0b68-4455-9101-d673d923deb0
[    8.890833] BTRFS info (device sdd1): using crc32c (crc32c-x86) checksum algorithm
[    8.890837] BTRFS info (device sdd1): using free-space-tree
[    8.890958] BTRFS info (device sda1): first mount of filesystem bf97dd75-0621-4d96-8eca-cd1433c9795c
[    8.890964] BTRFS info (device sda1): using crc32c (crc32c-x86) checksum algorithm
[    8.890967] BTRFS info (device sda1): using free-space-tree
[    8.897108] systemd-journald[744]: Received client request to flush runtime journal.
[   10.094241] [drm] amdgpu kernel modesetting enabled.
[   10.094382] amdgpu: Virtual CRAT table created for CPU
[   10.094401] amdgpu: Topology: Add CPU node
[   10.094435] amdgpu: Overdrive is enabled, please disable it before reporting any bugs unrelated to overdrive.
[   10.094438] fbcon: Taking over console
[   10.094697] mousedev: PS/2 mouse device common for all mice
[   10.094707] amdgpu 0000:03:00.0: enabling device (0006 -> 0007)
[   10.094844] [drm] initializing kernel modesetting (IP DISCOVERY 0x1002:0x747E 0x1458:0x2414 0xFF).
[   10.094867] [drm] register mmio base: 0x44A00000
[   10.094868] [drm] register mmio size: 1048576
[   10.095485] Console: switching to colour frame buffer device 240x67
[   10.101106] amdgpu 0000:03:00.0: amdgpu: detected ip block number 0 <soc21_common>
[   10.101109] amdgpu 0000:03:00.0: amdgpu: detected ip block number 1 <gmc_v11_0>
[   10.101111] amdgpu 0000:03:00.0: amdgpu: detected ip block number 2 <ih_v6_0>
[   10.101112] amdgpu 0000:03:00.0: amdgpu: detected ip block number 3 <psp>
[   10.101112] amdgpu 0000:03:00.0: amdgpu: detected ip block number 4 <smu>
[   10.101113] amdgpu 0000:03:00.0: amdgpu: detected ip block number 5 <dm>
[   10.101114] amdgpu 0000:03:00.0: amdgpu: detected ip block number 6 <gfx_v11_0>
[   10.101115] amdgpu 0000:03:00.0: amdgpu: detected ip block number 7 <sdma_v6_0>
[   10.101117] amdgpu 0000:03:00.0: amdgpu: detected ip block number 8 <vcn_v4_0>
[   10.101118] amdgpu 0000:03:00.0: amdgpu: detected ip block number 9 <jpeg_v4_0>
[   10.101119] amdgpu 0000:03:00.0: amdgpu: detected ip block number 10 <mes_v11_0>
[   10.101142] amdgpu 0000:03:00.0: amdgpu: Fetched VBIOS from VFCT
[   10.101144] amdgpu: ATOM BIOS: 113-APM6770-58A1
[   10.105993] amdgpu 0000:03:00.0: amdgpu: CP RS64 enable
[   10.110358] snd_hda_codec_realtek hdaudioC1D0: autoconfig for ALC897: line_outs=1 (0x14/0x0/0x0/0x0/0x0) type:line
[   10.110362] snd_hda_codec_realtek hdaudioC1D0:    speaker_outs=0 (0x0/0x0/0x0/0x0/0x0)
[   10.110363] snd_hda_codec_realtek hdaudioC1D0:    hp_outs=1 (0x1b/0x0/0x0/0x0/0x0)
[   10.110364] snd_hda_codec_realtek hdaudioC1D0:    mono: mono_out=0x0
[   10.110364] snd_hda_codec_realtek hdaudioC1D0:    dig-out=0x11/0x0
[   10.110365] snd_hda_codec_realtek hdaudioC1D0:    inputs:
[   10.110366] snd_hda_codec_realtek hdaudioC1D0:      Rear Mic=0x18
[   10.110366] snd_hda_codec_realtek hdaudioC1D0:      Front Mic=0x19
[   10.110367] snd_hda_codec_realtek hdaudioC1D0:      Line=0x1a
[   10.130232] intel_tcc_cooling: TCC Offset locked
[   10.133713] Console: switching to colour dummy device 80x25
[   10.147493] input: HDA Intel PCH Rear Mic as /devices/pci0000:00/0000:00:1f.3/sound/card1/input18
[   10.147515] input: HDA Intel PCH Front Mic as /devices/pci0000:00/0000:00:1f.3/sound/card1/input19
[   10.147531] input: HDA Intel PCH Line as /devices/pci0000:00/0000:00:1f.3/sound/card1/input20
[   10.147545] input: HDA Intel PCH Line Out as /devices/pci0000:00/0000:00:1f.3/sound/card1/input21
[   10.147559] input: HDA Intel PCH Front Headphone as /devices/pci0000:00/0000:00:1f.3/sound/card1/input22
[   10.147575] input: HDA Intel PCH HDMI/DP,pcm=3 as /devices/pci0000:00/0000:00:1f.3/sound/card1/input23
[   10.147593] input: HDA Intel PCH HDMI/DP,pcm=7 as /devices/pci0000:00/0000:00:1f.3/sound/card1/input24
[   10.147607] input: HDA Intel PCH HDMI/DP,pcm=8 as /devices/pci0000:00/0000:00:1f.3/sound/card1/input25
[   10.147623] input: HDA Intel PCH HDMI/DP,pcm=9 as /devices/pci0000:00/0000:00:1f.3/sound/card1/input26
[   10.251967] amdgpu 0000:03:00.0: vgaarb: deactivate vga console
[   10.251971] amdgpu 0000:03:00.0: amdgpu: Trusted Memory Zone (TMZ) feature not supported
[   10.251998] amdgpu 0000:03:00.0: amdgpu: MEM ECC is not presented.
[   10.251999] amdgpu 0000:03:00.0: amdgpu: SRAM ECC is not presented.
[   10.252004] amdgpu 0000:03:00.0: amdgpu: DF poison setting is inconsistent(1:0:0:0)!
[   10.252005] amdgpu 0000:03:00.0: amdgpu: Poison setting is inconsistent in DF/UMC(0:1)!
[   10.252011] [drm] vm size is 262144 GB, 4 levels, block size is 9-bit, fragment size is 9-bit
[   10.252016] amdgpu 0000:03:00.0: amdgpu: VRAM: 12272M 0x0000008000000000 - 0x00000082FEFFFFFF (12272M used)
[   10.252018] amdgpu 0000:03:00.0: amdgpu: GART: 512M 0x00007FFF00000000 - 0x00007FFF1FFFFFFF
[   10.252028] [drm] Detected VRAM RAM=12272M, BAR=16384M
[   10.252029] [drm] RAM width 192bits GDDR6
[   10.252095] [drm] amdgpu: 12272M of VRAM memory ready
[   10.252096] [drm] amdgpu: 32030M of GTT memory ready.
[   10.252109] [drm] GART: num cpu pages 131072, num gpu pages 131072
[   10.252152] [drm] PCIE GART of 512M enabled (table at 0x00000082FEB00000).
[   10.252755] [drm] Loading DMUB firmware via PSP: version=0x07002F00
[   10.252908] amdgpu 0000:03:00.0: amdgpu: Found VCN firmware Version ENC: 1.24 DEC: 9 VEP: 0 Revision: 11
[   10.252991] amdgpu 0000:03:00.0: amdgpu: Found VCN firmware Version ENC: 1.24 DEC: 9 VEP: 0 Revision: 11
[   10.289018] intel_rapl_common: Found RAPL domain package
[   10.289021] intel_rapl_common: Found RAPL domain core
[   10.289022] intel_rapl_common: Found RAPL domain uncore
[   10.330450] amdgpu 0000:03:00.0: amdgpu: reserve 0xa700000 from 0x82e0000000 for PSP TMR
[   10.569397] NET: Registered PF_QIPCRTR protocol family
[   10.570600] Generic FE-GE Realtek PHY r8169-0-500:00: attached PHY driver (mii_bus:phy_addr=r8169-0-500:00, irq=MAC)
[   10.576824] amdgpu 0000:03:00.0: amdgpu: RAP: optional rap ta ucode is not available
[   10.576828] amdgpu 0000:03:00.0: amdgpu: SECUREDISPLAY: securedisplay ta ucode is not available
[   10.576857] amdgpu 0000:03:00.0: amdgpu: smu driver if version = 0x0000003d, smu fw if version = 0x00000040, smu fw program = 0, smu fw version = 0x00505400 (80.84.0)
[   10.576860] amdgpu 0000:03:00.0: amdgpu: SMU driver if version not matched
[   10.656806] amdgpu 0000:03:00.0: amdgpu: SMU is initialized successfully!
[   10.657354] [drm] Display Core v3.2.325 initialized on DCN 3.2
[   10.657356] [drm] DP-HDMI FRL PCON supported
[   10.659414] [drm] DMUB hardware initialized: version=0x07002F00
[   10.727398] snd_hda_intel 0000:03:00.1: bound 0000:03:00.0 (ops amdgpu_dm_audio_component_bind_ops [amdgpu])
[   10.738743] r8169 0000:05:00.0 enp5s0: Link is Down
[   10.820509] amdgpu: HMM registered 12272MB device memory
[   10.821541] kfd kfd: amdgpu: Allocated 3969056 bytes on gart
[   10.821557] kfd kfd: amdgpu: Total number of KFD nodes to be created: 1
[   10.821618] amdgpu: Virtual CRAT table created for GPU
[   10.821725] amdgpu: Topology: Add dGPU node [0x747e:0x1002]
[   10.821726] kfd kfd: amdgpu: added device 1002:747e
[   10.821737] amdgpu 0000:03:00.0: amdgpu: SE 3, SH per SE 2, CU per SH 10, active_cu_number 54
[   10.821741] amdgpu 0000:03:00.0: amdgpu: ring gfx_0.0.0 uses VM inv eng 0 on hub 0
[   10.821742] amdgpu 0000:03:00.0: amdgpu: ring comp_1.0.0 uses VM inv eng 1 on hub 0
[   10.821742] amdgpu 0000:03:00.0: amdgpu: ring comp_1.1.0 uses VM inv eng 4 on hub 0
[   10.821743] amdgpu 0000:03:00.0: amdgpu: ring comp_1.2.0 uses VM inv eng 6 on hub 0
[   10.821744] amdgpu 0000:03:00.0: amdgpu: ring comp_1.3.0 uses VM inv eng 7 on hub 0
[   10.821744] amdgpu 0000:03:00.0: amdgpu: ring comp_1.0.1 uses VM inv eng 8 on hub 0
[   10.821745] amdgpu 0000:03:00.0: amdgpu: ring comp_1.1.1 uses VM inv eng 9 on hub 0
[   10.821745] amdgpu 0000:03:00.0: amdgpu: ring comp_1.2.1 uses VM inv eng 10 on hub 0
[   10.821746] amdgpu 0000:03:00.0: amdgpu: ring comp_1.3.1 uses VM inv eng 11 on hub 0
[   10.821746] amdgpu 0000:03:00.0: amdgpu: ring sdma0 uses VM inv eng 12 on hub 0
[   10.821747] amdgpu 0000:03:00.0: amdgpu: ring sdma1 uses VM inv eng 13 on hub 0
[   10.821748] amdgpu 0000:03:00.0: amdgpu: ring vcn_unified_0 uses VM inv eng 0 on hub 8
[   10.821748] amdgpu 0000:03:00.0: amdgpu: ring vcn_unified_1 uses VM inv eng 1 on hub 8
[   10.821749] amdgpu 0000:03:00.0: amdgpu: ring jpeg_dec uses VM inv eng 4 on hub 8
[   10.821749] amdgpu 0000:03:00.0: amdgpu: ring mes_kiq_3.1.0 uses VM inv eng 14 on hub 0
[   10.822819] amdgpu 0000:03:00.0: amdgpu: Using BACO for runtime pm
[   10.823153] amdgpu 0000:03:00.0: [drm] Registered 4 planes with drm panic
[   10.823154] [drm] Initialized amdgpu 3.63.0 for 0000:03:00.0 on minor 2
[   10.830375] fbcon: amdgpudrmfb (fb0) is primary device
[   10.830691] [drm] pre_validate_dsc:1627 MST_DSC dsc precompute is not needed
[   10.908164] Console: switching to colour frame buffer device 215x45
[   10.927888] amdgpu 0000:03:00.0: [drm] fb0: amdgpudrmfb frame buffer device
[   13.364754] e1000e 0000:06:00.0 enp6s0: NIC Link is Up 1000 Mbps Full Duplex, Flow Control: Rx/Tx
[   18.717384] nvme nvme0: using unchecked data buffer
[   25.492002] /proc/cgroups lists only v1 controllers, use cgroup.controllers of root cgroup for v2 info
[32493.021161] SGI XFS with ACLs, security attributes, realtime, scrub, repair, quota, no debug enabled
[32493.038928] JFS: nTxBlock = 8192, nTxLock = 65536
### END dmesg ###

