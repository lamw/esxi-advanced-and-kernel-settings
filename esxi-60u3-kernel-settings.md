# ESXi 6.0 Update 3 Build 5050593 Kernel Settings

Total: 197

| Name | Description | Default | Runtime | Configured |
|---|---|---|---|---|
| acpiDbgLevel | ACPI debug level | 0 | 0 | 0 |
| allowNonNX | Allow booting with NX feature disabled or non present. | FALSE | FALSE | FALSE |
| asyncSerialLogging | Make serial logging asynchronous | TRUE | TRUE | TRUE |
| auditMode | Audit mode boot. | FALSE | FALSE | FALSE |
| autoCreateDumpFile | If enabled and if no suitable dump partition or dump file exists, create a dump file. | TRUE | TRUE | TRUE |
| autoPartition | Enable/Disable auto-partitioning of empty local disks. | FALSE | FALSE | FALSE |
| autoPartitionCreateUSBCoreDumpPartition | Enable/Disable auto-partitioning of core dump partition for USB boot devices. Requires that autoPartition is set to TRUE as well. | FALSE | FALSE | FALSE |
| autoPartitionDiskDumpPartitionSize | Disk dump partition size in MB that gets configured during the auto-partition process. | 2560 | 2560 | 2560 |
| autoPartitionOnlyOnceAndSkipSsd | When using auto-partitioning, only create one set of VMFS/Diagnostic/Scratch partitions, and skip partitioning SSDs | FALSE | FALSE | FALSE |
| bcCatchBufOverRun | Catch uncached, non-zero-copy buffer overruns. | FALSE | FALSE | FALSE |
| bcNumPools | Number of buffer cache pools. Set to zero for auto-scale. | 0 | 0 | 0 |
| bootDeviceRescanTimeout | Boot device rescan timeout (in minutes). | 1 | 1 | 1 |
| BOOTIF | MAC address of the NIC used for booting. |  |  |  |
| BOOTUUID | Boot partition UUID. |  | 7941bfe2a6be0d20fe0d8c67a5b617bd |  |
| buddyPhysicalMemoryDebugStruct | Buddy physical mem debug info switch. | FALSE | FALSE | FALSE |
| busSpeedMayVary | Allow different APIC timer speeds on different CPUs. | FALSE | FALSE | FALSE |
| cacheFlushImmOnAllHalt | Flush caches immediately if all cores sharing LLC halt (AMD only) | FALSE | FALSE | FALSE |
| checkCPUIDLimit | Refuse to run on CPUID limited cpus. | TRUE | TRUE | TRUE |
| checkPages | Check that free and free-lpage-pool pages are not corrupted. | FALSE | FALSE | FALSE |
| com1_baud | Baud rate for COM1. | 115200 | 115200 | 115200 |
| com1_irq | COM1 IRQ (default 4) | 4 | 4 | 4 |
| com1_port | COM1 I/O address (0 -> disabled, default 0x3f8) | 0x3f8 | 0x3f8 | 0x3f8 |
| com2_baud | Baud rate for COM2. | 115200 | 115200 | 115200 |
| com2_irq | COM2 IRQ (default 3) | 3 | 3 | 3 |
| com2_port | COM2 I/O address (0 -> disabled, default 0x2f8) | 0x2f8 | 0x2f8 | 0x2f8 |
| coresPerPkg | Number of cores per package that vmkernel should use | 0 | 0 | 0 |
| correctBSPMTRRMasks | Correct BSP Variable MTRR masks to match the processor physical address bit support | TRUE | TRUE | TRUE |
| createNoMemFakeNUMAnode | Create one extra NUMA node that does not have memory. | FALSE | FALSE | FALSE |
| createNoPCPUFakeNUMAnode | Create one extra NUMA node that does not have PCPUs. | FALSE | FALSE | FALSE |
| debugBreak | Break into debugger during vmkernel initialization. | FALSE | FALSE | FALSE |
| debugHeapList | Semicolon separated list of <heapname>:<alignment> that should run as debug heaps |  |  |  |
| debugLogToSerial | 0=Serial debug logging off, 1=Serial debug logging on, 2=Defer to config option DebugLogToSerial. | 2 | 2 | 2 |
| delayCFOH | Time delay for Cache Flush On Halt (0: 5.12us, 1-127: n*10.24us) | 128 | 128 | 128 |
| devListStabilityCount | Dev/Path list stability max iterations | 3 | 3 | 3 |
| disableACSCheck | Bypass ACS capability checks on all PCIE devices | FALSE | FALSE | FALSE |
| disableC1E | Disable C1E | FALSE | FALSE | FALSE |
| disableCFOH | Disable Cache Flush on Halt | FALSE | FALSE | FALSE |
| disableTopoEx | Ignore AMD CPU topology extensions | FALSE | FALSE | FALSE |
| disableTurbo | Disable Turbo Mode | FALSE | FALSE | FALSE |
| diskDumpSlotSize | Disk dump slot size in MB. 0 = automatically sized, otherwise requsted size >= 100 MB. | 0 | 0 | 0 |
| diskPartitionType | Allow toggling scratch partition type0 - vfat (Scratch) only1 - ufs (Scratch) only2 - vfat (Scratch) + ufs3 - ufs (Scratch) + vfat | 0 | 0 | 0 |
| dmaEngineExposeIdentityMapping | Whether to expose whether DMA engines do identity mapping. | TRUE | TRUE | TRUE |
| dmaMapperPolicy | DMA mapping policy to use. | disabled | disabled | disabled |
| driverVMAllowDevicesWithDrivers | Allow the DriverVM to claim devices for which vmkernel already has drivers | FALSE | FALSE | FALSE |
| driverVMAutoclaim | Autoclaim unclaimed network devices and assign them to DriverVM (useful for installer and PXE booting) | FALSE | FALSE | FALSE |
| driverVMEnabled | Enable DriverVM functionality if required files are present | FALSE | FALSE | FALSE |
| dumpDiag | Dump diagnostics information. | FALSE | FALSE | FALSE |
| earlyPoisonVerify | Check that all pages are poisoned before the first regular allocation is made | FALSE | FALSE | FALSE |
| enableACSCheckForRP | Enable ACS capability checks for Root Port | FALSE | FALSE | FALSE |
| enableAdaptableLockSupport | Enable adaptable lock support. | TRUE | TRUE | TRUE |
| enablePCIEHotplug | Enable PCI-E Native Hotplug support | TRUE | TRUE | TRUE |
| enablePCIErrors | Enable PCI-E Error Reporting | FALSE | FALSE | FALSE |
| enableValidPCIDevices | Enable all PCI devices with valid resources, but are disabled by BIOS | TRUE | TRUE | TRUE |
| execInstalledOnly | Execute only those files that have been installed via a vib package and have not been modified. | FALSE | FALSE | FALSE |
| executePOST | Run POST tests. | FALSE | FALSE | FALSE |
| fakeNUMAnodes | Fake # NUMA nodes on UMA systems. | 0 | 0 | 0 |
| fakeReliableMemMPN | Mark all MPNs up to the specified value as reliable. MPNs already marked as reliable will not be affected by this option. | 0 | 0 | 0 |
| firewireEnabled | Enable FireWire support; Firewire will be enabled implicitly by the *Port settings below | FALSE | FALSE | FALSE |
| forceCRS | Always use IRQ from _CRS | FALSE | FALSE | FALSE |
| fsCheck | Run filesystem checks on system partitions. | FALSE | FALSE | FALSE |
| FSSNumAIORequests | Number of requests that can be queued to the file system aio helper queue. | 0 | 0 | 0 |
| FSSNumBaseFileHandles | Maximum number of base file handles | 4096 | 4096 | 4096 |
| gdbPort | gdb port; com1 or com2 | default | default | default |
| generalCriticalMemory | Pages to reserve as general critical memory | 0 | 0 | 0 |
| heapCheckTimerInterval | Interval in seconds between heap timer checks | 10 | 10 | 10 |
| heapFreeOwnerCheck | Check heap ownership on free operations | FALSE | FALSE | FALSE |
| heapFreePoisonByte | Byte pattern used to poison freed memory | 0xFF | 0xFF | 0xFF |
| heapMetadataProtect | Use poisoned red zones to protect against under/overruns | FALSE | FALSE | FALSE |
| heapMetaPoisonByte | Byte pattern used to poison red zones for allocations | 0x5A | 0x5A | 0x5A |
| heapMgrTotalVASpaceGB | VA space in GB allocated by heap manager for all heaps | 512 | 512 | 512 |
| heapPoisonFreeMem | Poison free memory to catch use after free bugs | FALSE | FALSE | FALSE |
| heapPoisonTimerChecks | Check heap poisoned areas for corruption on regular intervals | FALSE | FALSE | FALSE |
| hijackSCIForNMI | Wire SCI to generate an NMI. | FALSE | FALSE | FALSE |
| hyperthreading | Enable hyperthreading if available. | TRUE | TRUE | TRUE |
| ignoreHeadless | Ignore Headless attribute from ACPI FADT. | FALSE | FALSE | FALSE |
| intelTXTErrorCode | Intel TXT boot failed on previous attempt | 0 | 0 | 0 |
| interleaveFakeNUMAnodes | Fake nodes will be created as interleaved nodes. | FALSE | FALSE | FALSE |
| interruptsDisabledPanicTimeUS | Panic timeout for how long an IRQs can be disabled via VMKAPI | 0 | 0 | 0 |
| intrBalancingEnabled | Indicates if interrupt balancing is enabled | TRUE | TRUE | TRUE |
| intrVectRetireTimeMS | Delay to retire an interrupt vector after steering, in ms | 4000 | 4000 | 4000 |
| ioAbilityChecks | Enforce checking of whether regions can be DMA mapped. | FALSE | FALSE | FALSE |
| iovDisableIR | Disable Interrrupt Remapping in the IOMMU. Not applicable for platforms pre-configured by firmware to use x2APIC (e.g., platformswith > 256 logical processors); for these interrupt remapping is always enabled. | TRUE | TRUE | TRUE |
| ipmiEnabled | Enable IPMI | TRUE | TRUE | TRUE |
| isPerFileSchedModelActive | Enable per file scheduling model on this host | TRUE | TRUE | TRUE |
| leaveWakeGPEsDisabled | Disallow a wake GPE from also being a runtime GPE | TRUE | TRUE | TRUE |
| logicalApicId | Use logical not physical APIC IDs. | FALSE | FALSE | FALSE |
| logOnScreen | Display vmkernel log on screen. | FALSE | FALSE | FALSE |
| logPort | Serial port to enable for logging; com1 or com2 | default | default | default |
| maxCartelsPerContainer | Number of cartels per userworld container | 50 | 50 | 50 |
| maxIntrCookies | Maximum number of interrupts vmkernel should support. | 1024 | 1024 | 1024 |
| maxLogEntries | Size of the kernel log buffer in 256-byte lines. 0=Use default. Min is 1024. Max is 32768. | 0 | 0 | 0 |
| maxNumExtraSplitsPerNode | Maximum number of extra splits added to each memory node | 0 | 0 | 0 |
| maxPCPUS | Number of PCPUs vmkernel should use. | 480 | 480 | 480 |
| maxPCPUsNUMAInterleaving | Enable NUMA-node interleaving of enabled PCPUs. | TRUE | TRUE | TRUE |
| maxVCPUsPerCore | Max number of VCPUs should run on a single core. 0 == determine at runtime | 0 | 0 | 0 |
| maxVMs | Max number of VMs VMKernel should support. 0 == determine at runtime | 0 | 0 | 0 |
| mcaDisableUcAsCMCI | Disable special handling of uncorrected errors | FALSE | FALSE | FALSE |
| mcaFindDIMMFromAddr | Find DIMM from Addr in MCA banks | FALSE | FALSE | FALSE |
| memCheckEveryWord | Check every single word when checking mem. | FALSE | FALSE | FALSE |
| memDistPolicyNumber | Memory distribution policy to use. | 0 | 0 | 0 |
| memLowReservedMB | Amount of low memory (< 4 GB) which gets reserved. 0 == determine at runtime | 0 | 0 | 0 |
| memmapMaxEarlyPoisonMemMB | Memory that should be poisoned during early initialization. | 65536 | 65536 | 65536 |
| memmapMaxPhysicalMemMB | Maximum physical memory (in MB) addressable by kernel. | 16777216 | 16777216 | 16777216 |
| memmapMaxRAMMB | Maximum conventional memory (RAM) supported on the system. Additional RAM above this limit will not be used by the system. | 12582912 | 12582912 | 12582912 |
| memmapStressHighBitMPNs | Test > 64GB physical RAM support by ignoring 4GB - 64GB range | FALSE | FALSE | FALSE |
| memNodeLookupTableBranchFactor | How much is a cache line worth compared to a branch when determining if we should use a lookup table for the MPN->MemNode translation | 1 | 1 | 1 |
| microcodeUpdate | Update microcode from boot module if available | TRUE | TRUE | TRUE |
| microcodeUpdateForce | Disable check that microcode update is newer than installed microcode and that both are released versions | FALSE | FALSE | FALSE |
| minMemoryCheck | Enable check for minimum required system memory at boot | TRUE | TRUE | TRUE |
| netCoalesceTimerHdlrPcpu | Pcpu that coalesce timeout handler runs on. | 0 | 0 | 0 |
| netDVSSyncEnabled | Enable/Disable DVSSync support. | TRUE | TRUE | TRUE |
| netGPHeapMaxMBPerGB | Maximum MB of the general purpose networking heap to be allocated per GB of physical memory. | 4 | 4 | 4 |
| netHeapsAdditionalMB | Additional heap memory for most networking heaps in MB | 0 | 0 | 0 |
| netMaxPCPUPktCacheSize | Maximum number of pkt buffers queued in each PCPU slab cache. | 128 | 128 | 128 |
| netMaxPktsToProcess | Maximum number of packets to process in each invocation packet processing routine | 64 | 64 | 64 |
| netMinPortsSystemWide | Minimum threshold for the number of active ports systemwide. | 1536 | 1536 | 1536 |
| netNetqueueEnabled | Enable/Disable NetQueue support. | TRUE | TRUE | TRUE |
| netNumPortsets | Maximum number of portsets. | 256 | 256 | 256 |
| netPagePoolLimitCap | Maximum number of pages period for the packet page pool. | 98304 | 98304 | 98304 |
| netPagePoolLimitPerGB | Maximum number of pages for the packet page pool per gigabyte. | 5120 | 5120 | 5120 |
| netPagePoolResvCap | Maximum number of pages to reserve for the packet page pool. | 0 | 0 | 0 |
| netPagePoolResvPerGB | Number of pages to reserve for the packet page pool per gigabyte. | 0 | 0 | 0 |
| netPanicBadDevOpen | Panic if device has a bad open handler. | TRUE | TRUE | TRUE |
| netPktHeapMaxMBPerGB | Maximum MB of low-memory packet heap to be allocated per GB of physical memory. Maximum value for this setting is 512. | 6 | 6 | 6 |
| netPktHeapMinMBPerGB | Minimum MB of low-memory packet heap to be allocated per GB of physical memory. Maximum value for this setting is 200. | 0 | 0 | 0 |
| netPktPoolMaxMBPerGB | Maximum MB of networking packet buffer pool to be allocated per GB of physical memory. Maximum value for this setting is 200. Net packet pool maximum per system will be at least 656MB. | 75 | 75 | 75 |
| netPktPoolMinMBPerGB | Minimum MB of networking packet buffer pool to be allocated per GB of physical memory (multiple of 24) | 0 | 0 | 0 |
| netPollContext | The context to run netpoll (0 for worldlet and 1 for system world). | 1 | 1 | 1 |
| nmiAction | Action on hardware generated NMI: 0=default (panic, unless changed by advanced config option), 1=enter debugger, 2=panic, 3=log and ignore (not recommended) | 0 | 0 | 0 |
| noIOMMU | Disable IOMMU support forcibly | FALSE | FALSE | FALSE |
| nonScratchPartitionSize | Addtitional disk slot size in MB. | 2048 | 2048 | 2048 |
| NUMACodeRepStress | NUMA code replication stress mode | FALSE | FALSE | FALSE |
| numaLatencyLoops | Number of NUMA latency probing loops. 0 to disable latency measurement | 20 | 20 | 20 |
| numaLatencyPages | Number of pages to be probed per-node for NUMA latency measurements | 20 | 20 | 20 |
| numaLatencyRemoteThresholdPct | Maximum measured memory access latency difference (in percent units) between 2 pairs of NUMA nodes for the pairs to be considered equidistant | 10 | 10 | 10 |
| numCacheColors | Enforce a certain number of cache colors | 0 | 0 | 0 |
| numNonVMXUWCartels | Maximum combined number of non-VMX userworld cartels in all user spaces. | 200 | 200 | 200 |
| numOfPshareOverflowCounters | Number of pshare overflow counters | 0 | 0 | 0 |
| numSysSchedGroups | Number of non-userworld non-VM scheduler groups. | 500 | 500 | 500 |
| overrideDuplicateImageDetection | Override duplicate ESXi image detection | FALSE | FALSE | FALSE |
| pcipDisablePciErrReporting | Disable error reporting for PCI passthru devices. | TRUE | TRUE | TRUE |
| pcipSaveOPROM | Save PCI OPROM images on boot: 0=Disabled, 1=Enabled, 2=Enabled (VGA Only) | 0 | 0 | 0 |
| pciSetBusMaster | Set bus master bit on PCI devices which were enabled by vmkernel | TRUE | TRUE | TRUE |
| poisonMarker | Value used to poison memmap pages | 0xaaaaaaaaaaaaaaaa | 0xaaaaaaaaaaaaaaaa | 0xaaaaaaaaaaaaaaaa |
| poisonPagePool | Poison memmap pages | FALSE | FALSE | FALSE |
| preemptibleVmkapiTimers | Enable preemption of VMKAPI timer callbacks. | FALSE | FALSE | FALSE |
| preferVmklinux | Boost priority of vmklinux drivers to trump native drivers. | FALSE | FALSE | FALSE |
| preventFreePageMapping | Prevent mapping of free pages | FALSE | FALSE | FALSE |
| processInterruptsInWorlds | Process interrupts in high priority worlds | FALSE | FALSE | FALSE |
| rdmaRoceIPBasedGidGeneration | Use the new IP-based GID generation for RoCE. | FALSE | FALSE | FALSE |
| realNMI | Use real NMI for LINT1. | TRUE | TRUE | TRUE |
| reliableMemPsodOnAllocFailure | PSOD the system on an allocation with an incorrect reliability | 0 | 0 | 0 |
| repostLevelTrigIntr | repost skipped level triggered interrupts; not applicable when running ESX in a VM | TRUE | TRUE | TRUE |
| rollback | Indicate if the boot happened after a firmware rollback. | FALSE | FALSE | FALSE |
| rtcEnableLegacy | Enable legacy CMOS device as real time clock (preferred) | TRUE | TRUE | TRUE |
| rtcEnableTAD | Enable ACPI 5.0 Time and Alarm Device as real time clock | TRUE | TRUE | TRUE |
| scanHonoringMemMap | Honor the BIOS memory map when scanning memory for firmware tables. | FALSE | FALSE | FALSE |
| scrubIgnoredPages | Check pages that were ignored due to vmbIgnoreStartMPN and vmbIgnoreNumMPNs boot options. | FALSE | FALSE | FALSE |
| scrubMemoryAfterModuleLoad | Check all memory after each module load. This causes booting to be very slow. | FALSE | FALSE | FALSE |
| serialUntrusted | Disable serial port if UART misbehaves. | TRUE | TRUE | TRUE |
| sharePerNode | Share each page once per NUMA node. | TRUE | TRUE | TRUE |
| skipMicrocodeCompatCheck | Disable check for supported processor microcode revision at boot | FALSE | FALSE | FALSE |
| skipPartitioningSsds | If enabled, skip auto-partitioning of empty local SSDs. | FALSE | FALSE | FALSE |
| smallFontForTTY | Use 50-line font for tty. | FALSE | FALSE | FALSE |
| statelessBOOTIF | MAC address of the NIC that was used for booting stateless. |  |  |  |
| storageHeapMaxSize | Maximum size in bytes of the main storage heap | 0 | 0 | 0 |
| storageHeapMinSize | Minimum size in bytes of the main storage heap | 0 | 0 | 0 |
| storageMaxDevices | Maximum number of supported SCSI devices | 256 | 256 | 256 |
| storageMaxPaths | Maximum number of supported SCSI paths | 1024 | 1024 | 1024 |
| storageMaxVMsPerDevice | Maximum number of VMs expected to use a given device | 32 | 32 | 32 |
| terminateVMOnPDL | Terminate virtual machine on permanent loss of storage | FALSE | FALSE | FALSE |
| testEarlyPanic | Trigger a (fake) early kernel abort. | FALSE | FALSE | FALSE |
| timerEnableACPI | Enable ACPI PM timer as system reference timer. | TRUE | TRUE | TRUE |
| timerEnableHPET | Enable HPET as system reference timer. | TRUE | TRUE | TRUE |
| timerEnableTSC | Enable TSC as system reference timer. | TRUE | TRUE | TRUE |
| timerForceTSC | Always use TSC as system reference timer. | FALSE | FALSE | FALSE |
| timerInitialCountHigh | Initial high 32-bits Timer_GetCycles(). | 0 | 0 | 0 |
| tracePages | Record a stack trace of the freer in freed pages. 0 = off, 1 = on, 2 = auto-select | 0 | 0 | 0 |
| tscSpeedMayVary | Allow different TSC speeds on different CPUs. | FALSE | FALSE | FALSE |
| tscSyncStress | Fraction of boots to force TSC resync (per thousand). | 0 | 0 | 0 |
| tty1Port | TTY1 port; com1, com2 ... to enable | default | default | default |
| tty2Port | TTY2 port; com1, com2 ... to enable | default | default | default |
| updateBusIRQ | Allow adding/removing busIRQ information | FALSE | FALSE | FALSE |
| useNHCC | Use non-halted core cycles instead of TSC for accounting in CPU scheduler | TRUE | TRUE | TRUE |
| useNUMAInfo | Enable/disable NUMA-ness | TRUE | TRUE | TRUE |
| useReliableMem | System is aware of reliable memory. | TRUE | TRUE | TRUE |
| useSLIT | Use NUMA latency information from the SLIT table if available | TRUE | TRUE | TRUE |
| uwSimScale | Support the given number of hostd-simulators | 0 | 0 | 0 |
| vga | Enable/Disable S/VGA support. | TRUE | TRUE | TRUE |
| vga64 | Use 64K VGA aperture. | FALSE | FALSE | FALSE |
| vmkacEnable | 0=Disabled, 1=Enforcing, 2=Do not enforce, just warn | 1 | 1 | 1 |
| vmkacMaxDomains | Maximum number of security domains | 65 | 65 | 65 |
| vmkacMaxObjects | Maximum number of security object types | 60 | 60 | 60 |
| vmkATKeyboard | Enable VMkernel AT keyboard driver. | FALSE | FALSE | FALSE |
| vmkLoadEntry | Static kernel entry point (offset) | 0 | 0 | 0 |
| vmkLoadSeed | Random seed for kernel entry point | 0 | 0 | 0 |
| vmwirePort | Vmwire port to enable; com1 or com2 |  |  |  |

