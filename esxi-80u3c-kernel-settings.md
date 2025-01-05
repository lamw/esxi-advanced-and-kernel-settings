# ESXi 8.0 Update 3c Build 24414501 Kernel Settings

Total: 316

| Name | Description | Default | Runtime | Configured |
|---|---|---|---|---|
| acpiDbgLevel | ACPI debug level | 0 | 0 | 0 |
| acpiEnableAmlDebugObject | enable output from the AML Debug Object | FALSE | FALSE | FALSE |
| allowCoreDumpOnUsb | Enable/Disable creation of core dump file on USB devices. | FALSE | FALSE | FALSE |
| allowDsmForNVDIMMHealth | For platforms that did not implement ACPI NVDIMM device health methods (_NCH and _NBS) allow to use vendor specific DSMs to get NVDIMM's health info | TRUE | TRUE | TRUE |
| allowPtrace | Whether to allow ptrace() debugging. TRUE=Allow ptrace(), FALSE=completely disable ptrace() | FALSE | FALSE | FALSE |
| amdIommuMmioEventHandler | Enable AMD IOMMU event handler using MMIO Access to MSI Capability Block Registers | TRUE | TRUE | TRUE |
| asanPanicOnBadRead | Panic/Report error on an illegal read access. Default Panic | TRUE | TRUE | TRUE |
| asyncSerialLogging | Make serial logging asynchronous | TRUE | TRUE | TRUE |
| atsSupport | Enable Support for PCIe ATS. | TRUE | TRUE | TRUE |
| auditMode | Audit mode boot. | FALSE | FALSE | FALSE |
| autoCreateDumpFile | If enabled and if no suitable dump partition or dump file exists, create a dump file. | TRUE | TRUE | TRUE |
| autoPartition | Enable/Disable auto-partitioning of empty local disks. | FALSE | FALSE | FALSE |
| autoPartitionCreateUSBCoreDumpPartition | Enable/Disable auto-partitioning of core dump partition for USB boot devices. Requires that autoPartition is set to TRUE as well. | FALSE | FALSE | FALSE |
| autoPartitionDiskDumpPartitionSize | Disk dump partition size in MB that gets configured during the auto-partition process. | 2560 | 2560 | 2560 |
| autoPartitionOnlyOnceAndSkipSsd | When using auto-partitioning, only create one set of VMFS/Diagnostic/Scratch partitions, and skip partitioning SSDs | FALSE | FALSE | FALSE |
| autoSetupLocalPMem | Auto setup PMem.0 - Do not do any auto setup1 (default) - Auto create PMem namespace, format a namespace if it              is empty. Don't touch Block namespaces2 (force) - Use with care. Remove all data and namespaces. Auto create PMem namespace and setup PMem | 1 | 1 | 1 |
| bootDeviceRescanTimeout | Boot device rescan timeout (in minutes). | 1 | 1 | 1 |
| BOOTIF | MAC address of the NIC used for booting. |  |  |  |
| BOOTUUID | Boot partition UUID. |  | a56b7ce670d046bebb870a1ff53db322 |  |
| buddyPhysicalMemoryDebugStruct | Buddy physical mem debug info switch. | FALSE | FALSE | FALSE |
| busSpeedMayVary | Allow different APIC timer speeds on different CPUs. | FALSE | FALSE | FALSE |
| cacheFlushImmOnAllHalt | Flush caches immediately if all cores sharing LLC halt (AMD only) | FALSE | FALSE | FALSE |
| checkCPUIDLimit | Refuse to run on CPUID limited cpus. | TRUE | TRUE | TRUE |
| checkPages | Check that free and free-lpage-pool pages are not corrupted. | FALSE | FALSE | FALSE |
| clockEnable2038 | If FALSE, allow the clock to be set to years only in the range 1970-2037. If TRUE, allow years in the range 1970-2105. | FALSE | FALSE | FALSE |
| com1_baud | Baud rate for COM1 (0 -> automatic) | 0 | 0 | 0 |
| com1_bitwidth | COM1 register width in bits | 0 | 0 | 0 |
| com1_hz | COM1 input frequency in Hz (0 -> automatic) | 0 | 0 | 0 |
| com1_irq | COM1 IRQ override (0 -> no override) | 0 | 0 | 0 |
| com1_mem | COM1 memory address (0 -> no override) | 0 | 0 | 0 |
| com1_port | COM1 I/O address override (0 -> no override) | 0 | 0 | 0 |
| com1_sbdf | PCI device to use for COM1 |  |  |  |
| com2_baud | Baud rate for COM2 (0 -> automatic) | 0 | 0 | 0 |
| com2_bitwidth | COM2 register width in bits | 0 | 0 | 0 |
| com2_hz | COM2 input frequency in Hz (0 -> automatic) | 0 | 0 | 0 |
| com2_irq | COM2 IRQ override (0 -> no override) | 0 | 0 | 0 |
| com2_mem | COM2 memory address (0 -> no override) | 0 | 0 | 0 |
| com2_port | COM2 I/O address (0 -> no override) | 0 | 0 | 0 |
| com2_sbdf | PCI device to use for COM2 |  |  |  |
| correctBSPMTRRMasks | Correct BSP Variable MTRR masks to match the processor physical address bit support | TRUE | TRUE | TRUE |
| cpuUniformityHardCheckPanic | Panic if CPU uniformity hard check fails | TRUE | TRUE | TRUE |
| createNoMemFakeNUMAnode | Create one extra NUMA node that does not have memory. | FALSE | FALSE | FALSE |
| createNoPCPUFakeNUMAnode | Create one extra NUMA node that does not have PCPUs. | FALSE | FALSE | FALSE |
| cryptoFIPS140 | Only enable FIPS-140-2 approved function usage. | TRUE | TRUE | TRUE |
| cryptoUseASM | Use ASM for crypto: Default enabled. | TRUE | TRUE | TRUE |
| dcfMaxAttrsPerDevComp | Maximum number of attributes per device component | 16 | 16 | 16 |
| dcfMaxDevCompsPerDevice | Maximum number of device components per DCF device | 512 | 512 | 512 |
| dcfMaxDevices | Maximum number of devices supported by DCF | 10 | 10 | 10 |
| debugBreak | Break into debugger during vmkernel initialization. | FALSE | FALSE | FALSE |
| debugHeapList | Semicolon separated list of <heapname>:<alignment> that should run as debug heaps |  |  |  |
| debugLogToSerial | 0=Serial debug logging off, 1=Serial debug logging on, 2=Defer to config option DebugLogToSerial. | 2 | 2 | 2 |
| delayCFOH | Time delay for Cache Flush On Halt (0: 5.12us, 1-127: n*10.24us) | 128 | 128 | 128 |
| deviceBindParallel | Enable parallel binding of devices across drivers in the device manager. | TRUE | TRUE | TRUE |
| devListStabilityCount | Dev/Path list stability max iterations | 3 | 3 | 3 |
| disableACSCheck | Bypass ACS capability checks on all PCIE devices | FALSE | FALSE | FALSE |
| disableC1E | Disable C1E | FALSE | FALSE | FALSE |
| disableCFOH | Disable Cache Flush on Halt | FALSE | FALSE | FALSE |
| disableHwrng | Disable hardware random number generator (RDRAND, RDSEED). Overrides entropySources. | FALSE | FALSE | FALSE |
| disableMSI | Disable use of MSI/MSI-X | FALSE | FALSE | FALSE |
| disablePciPassthrough | Disable PCI Passthrough | FALSE | FALSE | FALSE |
| disableQuerySvgaFeatures | Disable graphics QuerySvgaFeatures | FALSE | FALSE | FALSE |
| disableTopoEx | Ignore AMD CPU topology extensions | FALSE | FALSE | FALSE |
| disableTurbo | Disable Turbo Mode | FALSE | FALSE | FALSE |
| diskDumpSlotSize | Disk dump slot size in MB. 0 = automatically sized, otherwise requested size >= 100 MB. | 0 | 0 | 0 |
| dmaEngineExposeIdentityMapping | Whether to expose whether DMA engines do identity mapping. | TRUE | TRUE | TRUE |
| dmaMapperPolicy | DMA mapping policy to use. | disabled | disabled | disabled |
| dumpSize | Maximum core dump file size in MB. Used for automatic core dump file creation. 0 = automatically sized. | 0 | 0 | 0 |
| dynamicLatency | Enable NUMA dynamic latency | FALSE | FALSE | FALSE |
| earlyPoisonVerify | Check that all pages are poisoned before the first regular allocation is made | FALSE | FALSE | FALSE |
| efiInternalTests | Run some basic unit tests for EFI support | FALSE | FALSE | FALSE |
| EFISetupRTSExceptionHandler | Setup exception handler for EFI Run Time services | TRUE | TRUE | TRUE |
| EFIVars | Support UEFI Runtime Variable Services | TRUE | TRUE | TRUE |
| elcr | Override ELCR value (-1 = use actual ELCR value) | -1 | -1 | -1 |
| enableACPIPCIeHotplug | Enable ACPI Event based PCIe Hotplug support | FALSE | FALSE | FALSE |
| enableACSCheckForRP | Enable ACS capability checks for Root Port | FALSE | FALSE | FALSE |
| enableAllPCIESegments | Enable PCIE segment numbers > 0 (segment 0 is always enabled) | TRUE | TRUE | TRUE |
| enableCXL | Enable discovery of CXL devices | FALSE | FALSE | FALSE |
| enableEFI_SP | Enable detection of EFI_MEMORY_SP for specific purpose memory | TRUE | TRUE | TRUE |
| enableIPT | Enables Intel Processor Trace for debugging | FALSE | FALSE | FALSE |
| enableLPageEagerValidation | Enable eager validation of lpages with memory tiering | FALSE | FALSE | FALSE |
| enablePCIEDPCAllPorts | Enable PCIe Error Containment and Recovery drivers for all DPC capable downstream and root ports. Requires enablePCIEErrRecov to be set to 0x1 as well. | FALSE | FALSE | FALSE |
| enablePCIEErrRecov | Enable PCIe Error Containment and Recovery drivers (bitmap): Set bit[0]=Enables DPC | 0x1 | 0x1 | 0x1 |
| enablePCIEHotplug | Enable PCI-E Native Hotplug support | TRUE | TRUE | TRUE |
| enablePCIErrors | Enable PCI-E Error Reporting | FALSE | FALSE | FALSE |
| enablePMemTier | Enable memory tiering with PMem as a second tier | FALSE | FALSE | FALSE |
| enableSDPM | Enable discovery of Dell SDPM | TRUE | TRUE | TRUE |
| enableValidPCIDevices | Enable all PCI devices with valid BAR resources which were not enabled by BIOS | TRUE | TRUE | TRUE |
| enableVmBwMonitoring | Enable/Disable vm level bandwidth monitoring on App-Direct Systems | FALSE | FALSE | FALSE |
| ensMbufPoolMaxMBPerGB | Maximum MB of ENS mbuf pool to be allocated per GB of physical memory. Maximum value for this setting is 512. ENS mbuf pool maximum per system will be at least 656MB. | 200 | 200 | 200 |
| ensMbufPoolMaxMinMB | Upper limit of ENS mbuf pool minimum per system in MB. | 5000 | 5000 | 5000 |
| ensMbufPoolMinMBPerGB | Minimum MB of ENS mbuf pool to be allocated per GB of physical memory. | 10 | 10 | 10 |
| entropySources | Which entropy sources to enable. 0=defaults, otherwise bitmask values: 1=interrupts, 2=RDRAND, 4=RDSEED, 8=entropyd. If RDSEED is supported, the default is FIPS compliance. Otherwise the default is all entropy sources except entropyd. | 0 | 0 | 0 |
| esxioK2KUplinks | List of vmnics to use as if they are K2K NICs |  |  |  |
| execInstalledOnly | Execute only those files that have been installed via a vib package and have not been modified. | FALSE | FALSE | FALSE |
| fakeCXLMemPct | Amount of fake CXL memory (in pct of all volatile memory) | 0 | 0 | 0 |
| fakeNUMAnodes | Fake # NUMA nodes on UMA systems. | 0 | 0 | 0 |
| fakePMemPct | Amount of fake persistent memory (in pct of all volatile memory) | 0 | 0 | 0 |
| fakeReliableMemMPN | Mark all MPNs up to the specified value as reliable. MPNs already marked as reliable will not be affected by this option. | 0 | 0 | 0 |
| firmwareConsolePort | Select which serial port is associated with the firmware-described console (e.g. via ACPI SPCR). The selected port uses the firmware config (except for baud rate, which is always controlled via the com*_baud option) | com1 | com1 | com1 |
| forceCRS | Always use IRQ from _CRS | FALSE | FALSE | FALSE |
| forceHyperthreadingMitigation | Restrict the simultaneous use of logical processors from the same hyperthreaded core regardless of detected security vulnerabilities. | FALSE | FALSE | FALSE |
| forceOSCGrantPCIEHotplug | Force grant ACPI _OSC control of PCI-E Native Hotplug feature | FALSE | FALSE | FALSE |
| forceUseSafeZone | Enable the HTSched safe zone even if hyperthreading or hyperthreadingMigitation are disabled. | FALSE | FALSE | FALSE |
| fsCheck | Run filesystem checks on system partitions. | FALSE | FALSE | FALSE |
| FSSNumAIORequests | Number of requests that can be queued to the file system aio helper queue. | 0 | 0 | 0 |
| FSSNumBaseFileHandles | Maximum number of base file handles | 12288 | 12288 | 12288 |
| gdbPort | gdb port; com1 or com2 | default | default | default |
| hashedFakeMac | If a MAC address for use in UUIDs cannot be obtained from a NIC, generate a fake MAC by hashing the SMBIOS UUID, if present. | TRUE | TRUE | TRUE |
| healthCheckEnabled | Run entropy health checks: Default enabled. | TRUE | TRUE | TRUE |
| healthCheckPanic | Panic if entropy health check fails: Default enabled. | TRUE | TRUE | TRUE |
| heapCheckTimerInterval | Interval in seconds between heap timer checks | 10 | 10 | 10 |
| heapFreePoisonByte | Byte pattern used to poison freed memory | 0xFF | 0xFF | 0xFF |
| heapMetadataProtect | Use poisoned red zones to protect against under/overruns | FALSE | FALSE | FALSE |
| heapMetaPoisonByte | Byte pattern used to poison red zones for allocations | 0x5A | 0x5A | 0x5A |
| heapPoisonFreeMem | Poison free memory to catch use after free bugs | FALSE | FALSE | FALSE |
| heapPoisonTimerChecks | Check heap poisoned areas for corruption on regular intervals | FALSE | FALSE | FALSE |
| hijackSCIForNMI | Wire SCI to generate an NMI. | FALSE | FALSE | FALSE |
| hyperthreading | Enable hyperthreading if available. | TRUE | TRUE | TRUE |
| hyperthreadingMitigation | Restrict the simultaneous use of logical processors from the same hyperthreaded core as necessary to mitigate a security vulnerability. | FALSE | FALSE | FALSE |
| hyperthreadingMitigationIntraVM | Restrict the simultaneous use of logical processors from the same hyperthreaded core as necessary to mitigate a security vulnerability within a single VM. | TRUE | TRUE | TRUE |
| ignoreHeadless | Ignore Headless attribute from ACPI FADT. | FALSE | FALSE | FALSE |
| ignoreHwSMBIOSInfo | Ignore hardware provided SMBIOS information | FALSE | FALSE | FALSE |
| ignoreLowMem | Ignore memory below 4GB for special (e.g. I/O, DMA) allocations | FALSE | FALSE | FALSE |
| ignoreMsrFaults | Ignore general protection faults as a result of rdmsr and wrmsr instructions | FALSE | FALSE | FALSE |
| ignorePPTT | Ignore the PPTT table | FALSE | FALSE | FALSE |
| ignoreSigTarCheck | Ignore boot checks for unknown tardisks and unsigned vibs when UEFI secure boot is disabled | TRUE | TRUE | TRUE |
| injectNVDIMMState | Inject NVDIMM state flags to simulate various NVDIMM failure events. (default 0 = use actual NFIT provided NVDIMM state flags). | 0 | 0 | 0 |
| injectPMemSratEntries | Inject SRAT entries for PMem ranges. Use this in case the platform does not report PMem ranges in ACPI SRAT. | FALSE | FALSE | FALSE |
| inputPassthru | Pass HID input through to user worlds via character devices | FALSE | FALSE | FALSE |
| interleaveFakeNUMAnodes | Fake nodes will be created as interleaved nodes. | FALSE | FALSE | FALSE |
| interruptsDisabledPanicTimeUS | Panic timeout for how long an IRQs can be disabled via VMKAPI | 0 | 0 | 0 |
| intrBalancingEnabled | Indicates if interrupt balancing is enabled. | TRUE | TRUE | TRUE |
| intrFirstMsixVector | Start of x86 vector range reserved for MSI-X | 0x70 | 0x70 | 0x70 |
| intrSyncInFlightTimeoutMS | Interrupt sync in-flight timeout (in milliseconds) | 1 | 1 | 1 |
| intrSyncInHandlerTimeoutMS | Interrupt sync in-handler timeout (in milliseconds) | 100 | 100 | 100 |
| intrVectRetireTimeMS | Delay to retire an interrupt vector after migration, in ms | 4000 | 4000 | 4000 |
| ioAbilityChecks | Enforce checking of whether regions can be DMA mapped. | FALSE | FALSE | FALSE |
| iommuMapReservedMem | Controls mapping of reserved memory for identity-mapped IOMMU domains; 0 = Honor ACPI RMRR; 1 = Map all reserved memory; 2 = Don't map any reserved memory;3 = Auto, ESXi kernel makes the decision. | 3 | 3 | 3 |
| iovDisableIR | Disable Interrupt Remapping in the IOMMU. | FALSE | FALSE | FALSE |
| iovEnablePostedIntr | Enable support for posted interrupts in the IOMMU. | TRUE | TRUE | TRUE |
| iovNonUniformPasidMode | Enable non uniform PASID support in IOV | TRUE | TRUE | TRUE |
| iovPasidMode | Enable PASID support in IOV | TRUE | TRUE | TRUE |
| ipmiEnabled | Enable IPMI | TRUE | TRUE | TRUE |
| isPerFileSchedModelActive | Enable per file scheduling model on this host | TRUE | TRUE | TRUE |
| kbddev | Enable VMkernel char driver interface between host keyboard and Guest | FALSE | FALSE | FALSE |
| labelLessNamespace | Enable support for NVDIMM platforms that does not support Label Storage Area with Label-less Namespaces. | FALSE | FALSE | FALSE |
| leaveWakeGPEsDisabled | Disallow a wake GPE from also being a runtime GPE | TRUE | TRUE | TRUE |
| llcSchedEnable | Enable scheduler enhancement for architecture with multi last level caches per NUMA node | TRUE | TRUE | TRUE |
| logEFILevel | Log level for LogEFI. | 1 | 1 | 1 |
| logicalApicId | Use logical not physical APIC IDs. | FALSE | FALSE | FALSE |
| logOnScreen | Display vmkernel log on screen. | FALSE | FALSE | FALSE |
| logPort | Serial port to enable for logging; com1 or com2 | default | default | default |
| logTermChopFields | Simulate logTerm scrolling right by so many fields | 0 | 0 | 0 |
| maxCartelsPerContainer | Number of cartels per userworld container | 50 | 50 | 50 |
| maxHTPerCore | The maximum number of hyperthreads per core ESXi should use | 2 | 2 | 2 |
| maxIntrCookies | Maximum number of interrupts vmkernel should support. | 4096 | 4096 | 4096 |
| maxLogEntries | Size of the kernel log buffer in 256-byte lines. 0=Use default. Min is 1024. Max is 32768. | 0 | 0 | 0 |
| maxNumExtraSplitsPerNode | Maximum number of extra splits added to each memory node | 0 | 0 | 0 |
| maxPCPUS | Number of PCPUs vmkernel should use. | 1024 | 1024 | 1024 |
| maxPCPUsNUMAInterleaving | Enable NUMA-node interleaving of enabled PCPUs. | TRUE | TRUE | TRUE |
| maxVCPUsPerCore | Max number of VCPUs should run on a single core. 0 == determine at runtime | 0 | 0 | 0 |
| maxVMs | Max number of VMs VMKernel should support. 0 == determine at runtime | 0 | 0 | 0 |
| memCheckEveryWord | Check every single word when checking mem. | FALSE | FALSE | FALSE |
| memDistPolicyNumber | Memory distribution policy to use. | 0 | 0 | 0 |
| memLowReservedMB | Amount of low memory (< 4 GB) which gets reserved. 0 == determine at runtime | 0 | 0 | 0 |
| memmapMaxEarlyPoisonMemMB | Memory that should be poisoned during early initialization. | 65536 | 65536 | 65536 |
| memmapMaxPhysicalMemMB | Maximum physical memory (in MB) addressable by kernel, used to calculate the cut-off MPN, when added to the first valid memory MPN. | 0 | 0 | 0 |
| memmapMaxRAMMB | Maximum conventional memory (RAM) supported on the system. Additional RAM above this limit will not be used by the system. | 33585088 | 33585088 | 33585088 |
| memNodeLookupTableBranchFactor | How much is a cache line worth compared to a branch when determining if we should use a lookup table for the MPN->MemNode translation | 1 | 1 | 1 |
| memoryTiering | Enables Memory Tiering | FALSE | FALSE | FALSE |
| microcodeUpdate | Update microcode from boot module if available | TRUE | TRUE | TRUE |
| microcodeUpdateForce | Disable check that microcode update is newer than installed microcode and that both are released versions | FALSE | FALSE | FALSE |
| netCoalesceTimerHdlrPcpu | Pcpu that coalesce timeout handler runs on. | 0 | 0 | 0 |
| netDVSSyncEnabled | Enable/Disable DVSSync support. | TRUE | TRUE | TRUE |
| netGPHeapMaxMBPerGB | Maximum MB of the general purpose networking heap to be allocated per GB of physical memory. | 4 | 4 | 4 |
| netHeapsAdditionalMB | Additional heap memory for most networking heaps in MB | 0 | 0 | 0 |
| netMaxPCPUPktCacheSize | Maximum number of pkt buffers queued in each PCPU slab cache. | 128 | 128 | 128 |
| netMaxPktsToProcess | Maximum number of packets to process in each invocation packet processing routine | 64 | 64 | 64 |
| netMaxPktsToRelease | Maximum number of packets to release in each invocation packet releasing routine | 128 | 128 | 128 |
| netMinContainerPortsSystemWide | Minimum threshold for the number of active container ports systemwide. | 1024 | 1024 | 1024 |
| netMinPortsSystemWide | Minimum threshold for the number of active ports systemwide. | 512 | 512 | 512 |
| netNetqueueEnabled | Enable/Disable NetQueue support. | TRUE | TRUE | TRUE |
| netNetqueueEnblSwlroWithPnicHwlro | Enable/Disable SW LRO for PNIC with HWLRO. Requires REBOOT. | TRUE | TRUE | TRUE |
| netNetqueueMaxFiltersPerUplink | Maximum number of netqueue filters for Uplink. Maximum value for this setting is 32768. Requires REBOOT. | 4096 | 4096 | 4096 |
| netNetqueueMaxLearnedFilters | Maximum number of hostwide netqueue learned filters. Maximum value for this setting is 16384. Requires REBOOT. | 9216 | 9216 | 9216 |
| netNetqueueMaxStaticFilters | Maximum number of hostwide netqueue static filters. Maximum value for this setting is 16384. Requires REBOOT. | 10240 | 10240 | 10240 |
| netNetqueuePortFeatInheritance | Enable/Disable Inheritance of queue feature of port filter for learned mac filter's. Requires REBOOT. | TRUE | TRUE | TRUE |
| netNumPortsets | Maximum number of portsets, maximum value is 128. | 64 | 64 | 64 |
| netPagePoolLimitCap | Maximum number of pages period for the packet page pool. | 1048576 | 1048576 | 1048576 |
| netPagePoolLimitPerGB | Maximum number of pages for the packet page pool per gigabyte. | 5120 | 5120 | 5120 |
| netPagePoolResvCap | Maximum number of pages to reserve for the packet page pool. | 0 | 0 | 0 |
| netPagePoolResvPerGB | Number of pages to reserve for the packet page pool per gigabyte. | 0 | 0 | 0 |
| netPanicBadDevOpen | Panic if device has a bad open handler. | TRUE | TRUE | TRUE |
| netPktHeapMaxMBPerGB | Maximum MB of low-memory packet heap to be allocated per GB of physical memory. Maximum value for this setting is 512. | 6 | 6 | 6 |
| netPktHeapMinMBPerGB | Minimum MB of low-memory packet heap to be allocated per GB of physical memory. Maximum value for this setting is 512. | 0 | 0 | 0 |
| netPktJumboSlabMinSize | Minimum MB of jumbo frame packet slab | 0 | 0 | 0 |
| netPktPoolMaxMBPerGB | Maximum MB of networking packet buffer pool to be allocated per GB of physical memory. Maximum value for this setting is 512. Net packet pool maximum per system will be at least 656MB. | 75 | 75 | 75 |
| netPktPoolMinMBPerGB | Minimum MB of networking packet buffer pool to be allocated per GB of physical memory (multiple of 24) | 0 | 0 | 0 |
| netPreemptionEnabled | Enable/disable preemption support in overall networking area | TRUE | TRUE | TRUE |
| netPSBlockableLock | Control portset locks in networking areas be blockable | FALSE | FALSE | FALSE |
| netTcpipMcsLock | Control locks within Tcpip module be MCS | FALSE | FALSE | FALSE |
| netVSSUseEtherswitch | Use etherswitch instead of cswitch to back the virtual standard switch. | FALSE | FALSE | FALSE |
| nmiAction | Action on hardware generated NMI: 0=default (panic, unless changed by advanced config option), 1=enter debugger, 2=panic, 3=log and ignore (not recommended), 4=log and ignore if undiagnosed | 0 | 0 | 0 |
| noIOMMU | Disable IOMMU (and IOV) support forcibly | FALSE | FALSE | FALSE |
| numActiveSysSchedGroups | Number of non-userworld non-VM scheduler groups which have worlds attached. | 200 | 200 | 200 |
| numaLatencyRemoteThresholdPct | Maximum measured memory access latency difference (in percent units) between 2 pairs of NUMA nodes for the pairs to be considered equidistant | 10 | 10 | 10 |
| numNonVMXUWCartels | Maximum combined number of non-VMX userworld cartels in all user spaces. | 1024 | 1024 | 1024 |
| numOfPshareOverflowCounters | Number of pshare overflow counters | 0 | 0 | 0 |
| numReaperQueuesPct | Percentage of numPCPUs to use as number of reaper queues. Valid values are between 1 to 100. | 50 | 50 | 50 |
| numReapersPerQueue | Number of reaper worlds to create per reaper queue | 2 | 2 | 2 |
| numSpareCoresPerLLC | Number of spare cores reserved at boot time per last-level cache (LLC) | 0 | 0 | 0 |
| numSysSchedGroups | Number of non-userworld non-VM scheduler groups. | 1000 | 1000 | 1000 |
| numVmxReaperQueuesPct | Percentage of numPCPUs to use as number of reaper queues for VMX worlds. Valid values are between 0 to 100. | 50 | 50 | 50 |
| nvdArsBootWaitMaxTimeout | Maximum time to wait (in seconds) for ARS to complete during boot | 80 | 80 | 80 |
| nvdArsErrorInject | Generate NVDIMM ARS random error records.0 (default) - No random error generation.1 - Enable hardware error injection.2 - Generate and inject hardware random errors.3 - Generate software random errors.<Other value> - Use value as start address for software error record. | 0 | 0 | 0 |
| overrideDuplicateImageDetection | Override duplicate ESXi image detection | FALSE | FALSE | FALSE |
| overridePCIeHPCapableCheck | Override PCIe Hot-plug capable check to treat the PCIe ports as hot-plug capable | FALSE | FALSE | FALSE |
| panicOnInvalidRMRR | Panic the system if any RMRR is overlapping an usable memory range. | TRUE | TRUE | TRUE |
| panicOnRebootFailure | Panic the system if an error occurs in the reboot path. | FALSE | FALSE | FALSE |
| pciBarAllocPolicy | PCI BAR allocation policy; 0=first-fit, 1=smallest-fit, 2=BAR-fit | 2 | 2 | 2 |
| pciExperimentalFlags | Experimental PCI code options | 0 | 0 | 0 |
| pciForceDebugDmaMapperVidDid | Colon separated <vendorID>:<deviceID> in hex of the devicefor which DMA Mapper policy should be set to debug. |  |  |  |
| pciHonorAcpiRootBridgeRes | Honor ACPI PCI Root Bridge Resource info; if set to FALSE, the PCI root bridge(s) are assumed to have unlimited resources. | TRUE | TRUE | TRUE |
| pcipDisablePciErrReporting | Disable error reporting for PCI passthru devices. | TRUE | TRUE | TRUE |
| pcipSaveOPROM | Save PCI OPROM images on boot: 0=Disabled, 1=Enabled, 2=Enabled (VGA Only) | 0 | 0 | 0 |
| pciSetBusMaster | Set bus master bit on PCI devices discovered by vmkernel | TRUE | TRUE | TRUE |
| pmemGcDisable | Disable pmem garbage collection script | FALSE | FALSE | FALSE |
| poisonMarker | Value used to poison memmap pages | 0xaaaaaaaaaaaaaaaa | 0xaaaaaaaaaaaaaaaa | 0xaaaaaaaaaaaaaaaa |
| poisonPagePool | Poison memmap pages | FALSE | FALSE | FALSE |
| poisonPmem | Create new pmem volumes as poisoned volumes and load already poisoned volumes as such. If set to FALSE the poisoned property will be removed from a volume. Poisoning is never available on release builds. | TRUE | TRUE | TRUE |
| preReserveMemForAsan | Amount of memory in KB to prereseve to be used by Asan. | 0 | 0 | 0 |
| preventFreePageMapping | Prevent mapping of free pages | FALSE | FALSE | FALSE |
| processIntrHandlerInWorlds | Process interrupt handler in high priority worlds | FALSE | FALSE | FALSE |
| processorSpeedMayVary | Allow different CPU speeds on different CPUs. | FALSE | FALSE | FALSE |
| randomFakeMac | If a MAC address for use in UUIDs cannot be obtained from a NIC or by hashing the SMBIOS UUID, generate a random MAC. | TRUE | TRUE | TRUE |
| randomizeInit | Seed to use to randomize vmkernel initialization steps. 0 means disabled, 1 means use RDTSC, any other value seeds pseudo-random generator. Ignored on non-debug builds. | 0 | 0 | 0 |
| rdmaRoceIPBasedGidGeneration | Use the new IP-based GID generation for RoCE. | TRUE | TRUE | TRUE |
| rdmaUseTeamingPolicy | Use teaming policy for rdma connection. | TRUE | TRUE | TRUE |
| reliableMemPsodOnAllocFailure | PSOD the system on an allocation with an incorrect reliability | 0 | 0 | 0 |
| repostLevelTrigIntr | Repost skipped level triggered interrupts; not applicable when running ESX in a VM | TRUE | TRUE | TRUE |
| rollback | Indicate if the boot happened after a firmware rollback. | FALSE | FALSE | FALSE |
| rtcEnableEFI | Enable UEFI Runtime Services as real time clock | TRUE | TRUE | TRUE |
| rtcEnableLegacy | Enable legacy CMOS device as real time clock | TRUE | TRUE | TRUE |
| rtcEnableLegacyForce | Enable legacy CMOS device as real time clock even if FADT has the CMOS RTC Not Present flag set | FALSE | FALSE | FALSE |
| rtcEnableTAD | Enable ACPI 5.0 Time and Alarm Device as real time clock | TRUE | TRUE | TRUE |
| scanHonoringMemMap | Honor the BIOS memory map when scanning memory for firmware tables. | FALSE | FALSE | FALSE |
| scrubIgnoredPages | Check pages that were ignored due to vmbIgnoreStartMPN and vmbIgnoreNumMPNs boot options. | FALSE | FALSE | FALSE |
| scrubMemoryAfterModuleLoad | Check all memory after each module load. This causes booting to be very slow. | FALSE | FALSE | FALSE |
| serialIgnoreDefaultConfig | Ignore default configuration for serial ports | FALSE | FALSE | FALSE |
| serialIgnoreFirmwareConfig | Ignore firmware configuration for serial ports | FALSE | FALSE | FALSE |
| serialPolledIrq | Simulated periodic IRQ for serial devices with broken interrupt delivery | FALSE | FALSE | FALSE |
| serialPolledIrqMs | Polling period (in ms) for simulated periodic IRQ for serial devices | 10 | 10 | 10 |
| serialUntrusted | Disable serial port if UART misbehaves. | TRUE | TRUE | TRUE |
| sharePerNode | Share each page once per NUMA node. | TRUE | TRUE | TRUE |
| skipMicrocodeCompatCheck | Disable check for supported processor microcode revision at boot | FALSE | FALSE | FALSE |
| skipPartitioningSsds | If enabled, skip auto-partitioning of empty local SSDs. | FALSE | FALSE | FALSE |
| smallFontForTTY | Use 50-line font for tty. | FALSE | FALSE | FALSE |
| smpPermanentlySpin | Permanently spin instead of halt | FALSE | FALSE | FALSE |
| statelessBOOTIF | MAC address of the NIC that was used for booting stateless. |  |  |  |
| storAdptrMultCplWrldsPerNuma | Pcpu Based multiple adapter completion worlds per Numa | TRUE | TRUE | TRUE |
| storageEnablePrpAtPsa | Enable NVMe PRP handling in PSA | TRUE | TRUE | TRUE |
| storageHeapMaxSize | Maximum size in bytes of the main storage heap | 0 | 0 | 0 |
| storageHeapMinSize | Minimum size in bytes of the main storage heap | 0 | 0 | 0 |
| storageMaxDevices | Maximum number of supported SCSI devices | 1024 | 1024 | 1024 |
| storageMaxPaths | Maximum number of supported SCSI paths | 4096 | 4096 | 4096 |
| storageMaxVMsPerDevice | Maximum number of VMs expected to use a given device | 32 | 32 | 32 |
| SVGAScaling | Pixel scaling factor for SVGA console (default 1) | 1 | 1 | 1 |
| terminateVMOnPDL | Terminate virtual machine on permanent loss of storage | FALSE | FALSE | FALSE |
| testPanic | Trigger a kernel abort of a specified type at a specified point | 0 | 0 | 0 |
| timerEnableACPI | Obsolete option, do not use. | FALSE | FALSE | FALSE |
| timerEnableHPET | Obsolete option, do not use. | FALSE | FALSE | FALSE |
| timerEnableTSC | Obsolete option, do not use. | TRUE | TRUE | TRUE |
| timerForceTSC | Obsolete option, do not use. | TRUE | TRUE | TRUE |
| timerInitialCountHigh | Initial high 32-bits Timer_GetCycles(). | 0 | 0 | 0 |
| tracePages | Record a stack trace of the freer in freed pages. 0 = off, 1 = on, 2 = auto-select | 0 | 0 | 0 |
| tscSpeedMayVary | Allow different TSC speeds on different CPUs. | FALSE | FALSE | FALSE |
| tscSyncSkip | Do not check or resync TSCs during boot. | FALSE | FALSE | FALSE |
| tscSyncStress | Fraction of boots to force TSC resync (per thousand). | 0 | 0 | 0 |
| tty1Port | TTY1 port; com1, com2 ... to enable | default | default | default |
| tty2Port | TTY2 port; com1, com2 ... to enable | default | default | default |
| tty3Port | TTY3 port; com1, com2 ... to enable | default | default | default |
| undoUCEDowngrade | Treat downgraded patrol scrub errors as uncorrected when needed | TRUE | TRUE | TRUE |
| updateBusIRQ | Allow adding/removing busIRQ information | FALSE | FALSE | FALSE |
| useLMCE | Use Local MCE feature if supported by hardware and firmware | TRUE | TRUE | TRUE |
| useNHCC | Use non-halted core cycles instead of TSC for accounting in CPU scheduler | TRUE | TRUE | TRUE |
| useNUMAInfo | Enable/disable NUMA-ness | TRUE | TRUE | TRUE |
| useReliableMem | System is aware of reliable memory. | TRUE | TRUE | TRUE |
| userInitInteractive | TRUE if first UW needs an interactive console (init doesn't) | FALSE | FALSE | FALSE |
| userInitPath | First UW path override | /bin/init | /bin/init | /bin/init |
| useSLIT | Use NUMA latency information from the SLIT table if available | TRUE | TRUE | TRUE |
| useVmkperfTSXForceAbort | Recover PMC3 on some Intel processors that clobber it with RTM.This is done by forcing RTM aborts when ever PMC3 is in use. WhenPMC3 is not in use, RTM semantics return to normal. | FALSE | FALSE | FALSE |
| uwSimScale | Support the given number of hostd-simulators | 0 | 0 | 0 |
| vga | Enable/Disable VGA support. | TRUE | TRUE | TRUE |
| vga64 | Use 64K VGA aperture. | FALSE | FALSE | FALSE |
| vgpuMockDeviceCount | Number of mock vGPU devices to create when mock devices are in use. Valid values are 0 (equivalent to disabling mock devices) to 8. | 1 | 1 | 1 |
| visorfsCompressTardiskPages | Keep tardisk pages compressed | TRUE | TRUE | TRUE |
| visorfsEvictUserPages | Eagerly evict userworld pages | TRUE | TRUE | TRUE |
| visorfsPagerReservation | Tardisk pager reserved memory (mb) | 16 | 16 | 16 |
| visorfsShareRamdiskPages | Share VisorFS ramdisk pages | TRUE | TRUE | TRUE |
| visorfsSwap | Enable VisorFS swap if the system matches the required criteria (auto) | FALSE | FALSE | FALSE |
| vmkacEnable | 0=Disabled, 1=Enforcing, 2=Do not enforce, just warn | 1 | 1 | 1 |
| vmkacMaxObjects | Maximum number of security object types | 60 | 60 | 60 |
| vmkATKeyboard | Enable VMkernel AT keyboard driver. | FALSE | FALSE | FALSE |
| vmkLoadEntry | Static kernel entry point (offset) | 0 | 0 | 0 |
| vmkLoadSeed | Random seed for kernel entry point | 0 | 0 | 0 |
| vmmrEnable | Enable/Disable vmmr, monitoring of x86 host-wide and per-vm stats | TRUE | TRUE | TRUE |
| vtdDevIotlbFlushGranFactor | Tunable to control Device IOTLB Granularity factorif vtdDevIotlbFlushGranFactor > 0, we will save0 and 2*vtdDevIotlbFlushGranFactor flushes at the costof flushing between 0 and 2**(vtdDevIotlbFlushGranFactor+1) - 2pages needlessly. | 8 | 8 | 8 |
| vtdEnableIRValidation | Enable support for VT-d validation of interrupt source identifiers. | FALSE | FALSE | FALSE |
| vtdMaxDomains | Upper limit for number of VT-d domains supported. | 512 | 512 | 512 |
| vtdMaxUnits | Upper limit for number of VT-d units supported. | 128 | 128 | 128 |
| vtdRecordMapsForPciVidDid | Causes the IOMMU driver to record a history of IOMMU maps, unmaps, and iotlb flushes for the IOMMU domain(s) associated with all devices that match the given <vendorID>:<deviceID> (in hex); the recorded history is dumped to the vmkernel's log if an iommu fault is detected in order to help root cause the source of the fault. Only supported in debug/beta builds. |  |  |  |
| vtdRecordMapsLimit | Number of entries in the IOMMU domain's map history (see boot option vtdRecordMapsForPciVidDid). The map history contains the last X map, unmap, iotlb flush operations for the domain, where X is the number set by this boot option. Only supported in debug/beta builds | 512 | 512 | 512 |
| vtdSuperPages | Enable support for VT-d Super Pages (aka 2MB, 1GB large pages); super-page usage is dependent on this option as well as hardware support. | TRUE | TRUE | TRUE |
| x2ApicForce | Use x2APIC if it exists, even if firmware has set X2APIC_OPT_OUT. | FALSE | FALSE | FALSE |
| x2ApicPreferred | Use x2APIC if available, even with less than 256 cpus. | TRUE | TRUE | TRUE |
| xmapGB | Maximum XMap size in GiB. | 32 | 32 | 32 |

