# Gentoo PPC32 confs

server
    description: Computer
    product: Mac mini
    vendor: Copyright 1983-2004 Apple Computer, Inc. All Rights Reserved
    serial: RHR
    width: 32 bits
  *-core
       description: Motherboard
       physical id: 0
       clock: 166MHz
     *-firmware
          product: OpenFirmware 3
          physical id: 0
          logical name: /proc/device-tree
          capabilities: bootinfo
     *-cpu
          description: CPU
          product: 7447A, altivec supported
          physical id: 1
          bus info: cpu@0
          version: 1.2 (pvr 8003 0102)
          size: 1249MHz
          clock: 166MHz
          capabilities: altivec performance-monitor
        *-cache:0
             description: L1 Cache
             physical id: 0
             size: 32KiB
        *-cache:1
             description: L2 Cache (unified)
             physical id: 1
             size: 512KiB
             clock: 1249MHz (0.8ns)
     *-memory
          description: System memory
          physical id: 2
          size: 1GiB
        *-bank
             description: DDR SDRAM
             product: PC3200U-30330
             physical id: 0
             version: 4141,05 18,01
             serial: 0xffff3192
             slot: DIMM0/J11
             size: 1GiB
             capabilities: spd-0.0
             configuration: errordetection=none
