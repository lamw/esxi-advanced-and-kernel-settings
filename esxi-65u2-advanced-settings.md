# ESXi 6.5 Update 2 Build 8294253 Advanced Settings

Total: 1075

| Name | Description | Default | Current | Min | Max | ESXCLI |
|---|---|---|---|---|---|---|
| BufferCache.FlushInterval | Flush at this interval (milliseconds) | 30000 | 30000 | 100 | 3600000 | True |
| BufferCache.HardMaxDirty | Block writers if this many buffers are dirty (percent) | 95 | 95 | 0 | 100 | True |
| BufferCache.PerFileHardMaxDirty | Block writers if this many buffers of a given file are dirtied (percent) | 50 | 50 | 0 | 100 | True |
| BufferCache.SoftMaxDirty | Flush immediately if this many buffers are dirty (percent) | 15 | 15 | 0 | 100 | True |
| CBRC.DCacheMemReserved | Memory consumed by CBRC Data Cache (in MB) | 400 | 400 | 100 | 32768 | True |
| CBRC.DCacheSize | Size of CBRC Data Cache in MB. This cannot be changed if CBRC.Enable is set to 1. | 32768 | 32768 | 32768 | 32768 | True |
| CBRC.DigestJournalBootInterval | Interval (in minutes) for which Digest Journal is temporarily disabled to avoid interfering with the boot process | 10 | 10 | 0 | 10000 | True |
| CBRC.Enable | Enable Content Based Read Cache | False | False | N/A | N/A | False |
| COW.COWMaxHeapSizeMB | Maximum size (in MB) to which the COW heap is allowed to grow | 192 | 192 | 192 | 256 | True |
| COW.COWMaxREPageCacheszMB | Maximum size (in MB) of VMFSSparse metadata cache size before cache eviction kicks in | 256 | 256 | 32 | 512 | True |
| COW.COWMinREPageCacheszMB | Minimum size (in MB) of VMFSSparse metadata cache size. Valid when cache eviction is enabled. | 0 | 0 | 0 | 512 | True |
| COW.COWREPageCacheEviction | VMFSSparse metadata cache eviction: 0 - disabled, 1 enabled | 1 | 1 | 0 | 1 | True |
| Config.Defaults.cpuidMask.mode.0.eax | Controls the use of Config.Defaults.cpuidMask.val.0.eax; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.0.ebx | Controls the use of Config.Defaults.cpuidMask.val.0.ebx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.0.ecx | Controls the use of Config.Defaults.cpuidMask.val.0.ecx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.0.edx | Controls the use of Config.Defaults.cpuidMask.val.0.edx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.1.eax | Controls the use of Config.Defaults.cpuidMask.val.1.eax; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.1.ebx | Controls the use of Config.Defaults.cpuidMask.val.1.ebx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.1.ecx | Controls the use of Config.Defaults.cpuidMask.val.1.ecx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.1.edx | Controls the use of Config.Defaults.cpuidMask.val.1.edx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.80000000.eax | Controls the use of Config.Defaults.cpuidMask.val.80000000.eax; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.80000000.ebx | Controls the use of Config.Defaults.cpuidMask.val.80000000.ebx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.80000000.ecx | Controls the use of Config.Defaults.cpuidMask.val.80000000.ecx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.80000000.edx | Controls the use of Config.Defaults.cpuidMask.val.80000000.edx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.80000001.eax | Controls the use of Config.Defaults.cpuidMask.val.80000001.eax; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.80000001.ebx | Controls the use of Config.Defaults.cpuidMask.val.80000001.ebx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.80000001.ecx | Controls the use of Config.Defaults.cpuidMask.val.80000001.ecx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.80000001.edx | Controls the use of Config.Defaults.cpuidMask.val.80000001.edx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.80000008.eax | Controls the use of Config.Defaults.cpuidMask.val.80000008.eax; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.80000008.ebx | Controls the use of Config.Defaults.cpuidMask.val.80000008.ebx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.80000008.ecx | Controls the use of Config.Defaults.cpuidMask.val.80000008.ecx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.80000008.edx | Controls the use of Config.Defaults.cpuidMask.val.80000008.edx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.8000000A.eax | Controls the use of Config.Defaults.cpuidMask.val.8000000A.eax; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.8000000A.ebx | Controls the use of Config.Defaults.cpuidMask.val.8000000A.ebx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.8000000A.ecx | Controls the use of Config.Defaults.cpuidMask.val.8000000A.ecx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.8000000A.edx | Controls the use of Config.Defaults.cpuidMask.val.8000000A.edx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.d.eax | Controls the use of Config.Defaults.cpuidMask.val.d.eax; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.d.ebx | Controls the use of Config.Defaults.cpuidMask.val.d.ebx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.d.ecx | Controls the use of Config.Defaults.cpuidMask.val.d.ecx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.mode.d.edx | Controls the use of Config.Defaults.cpuidMask.val.d.edx; legal values "mask", "clobber", or "disable". | disable | disable | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.0.eax | CPUID override that may be applied to level 0 register eax; controlled by Config.Defaults.cpuidMask.mode.0.eax. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.0.ebx | CPUID override that may be applied to level 0 register ebx; controlled by Config.Defaults.cpuidMask.mode.0.ebx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.0.ecx | CPUID override that may be applied to level 0 register ecx; controlled by Config.Defaults.cpuidMask.mode.0.ecx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.0.edx | CPUID override that may be applied to level 0 register edx; controlled by Config.Defaults.cpuidMask.mode.0.edx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.1.eax | CPUID override that may be applied to level 1 register eax; controlled by Config.Defaults.cpuidMask.mode.1.eax. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.1.ebx | CPUID override that may be applied to level 1 register ebx; controlled by Config.Defaults.cpuidMask.mode.1.ebx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.1.ecx | CPUID override that may be applied to level 1 register ecx; controlled by Config.Defaults.cpuidMask.mode.1.ecx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.1.edx | CPUID override that may be applied to level 1 register edx; controlled by Config.Defaults.cpuidMask.mode.1.edx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.80000000.eax | CPUID override that may be applied to level 80000000 register eax; controlled by Config.Defaults.cpuidMask.mode.80000000.eax. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.80000000.ebx | CPUID override that may be applied to level 80000000 register ebx; controlled by Config.Defaults.cpuidMask.mode.80000000.ebx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.80000000.ecx | CPUID override that may be applied to level 80000000 register ecx; controlled by Config.Defaults.cpuidMask.mode.80000000.ecx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.80000000.edx | CPUID override that may be applied to level 80000000 register edx; controlled by Config.Defaults.cpuidMask.mode.80000000.edx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.80000001.eax | CPUID override that may be applied to level 80000001 register eax; controlled by Config.Defaults.cpuidMask.mode.80000001.eax. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.80000001.ebx | CPUID override that may be applied to level 80000001 register ebx; controlled by Config.Defaults.cpuidMask.mode.80000001.ebx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.80000001.ecx | CPUID override that may be applied to level 80000001 register ecx; controlled by Config.Defaults.cpuidMask.mode.80000001.ecx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.80000001.edx | CPUID override that may be applied to level 80000001 register edx; controlled by Config.Defaults.cpuidMask.mode.80000001.edx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.80000008.eax | CPUID override that may be applied to level 80000008 register eax; controlled by Config.Defaults.cpuidMask.mode.80000008.eax. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.80000008.ebx | CPUID override that may be applied to level 80000008 register ebx; controlled by Config.Defaults.cpuidMask.mode.80000008.ebx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.80000008.ecx | CPUID override that may be applied to level 80000008 register ecx; controlled by Config.Defaults.cpuidMask.mode.80000008.ecx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.80000008.edx | CPUID override that may be applied to level 80000008 register edx; controlled by Config.Defaults.cpuidMask.mode.80000008.edx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.8000000A.eax | CPUID override that may be applied to level 8000000A register eax; controlled by Config.Defaults.cpuidMask.mode.8000000A.eax. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.8000000A.ebx | CPUID override that may be applied to level 8000000A register ebx; controlled by Config.Defaults.cpuidMask.mode.8000000A.ebx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.8000000A.ecx | CPUID override that may be applied to level 8000000A register ecx; controlled by Config.Defaults.cpuidMask.mode.8000000A.ecx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.8000000A.edx | CPUID override that may be applied to level 8000000A register edx; controlled by Config.Defaults.cpuidMask.mode.8000000A.edx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.d.eax | CPUID override that may be applied to level d register eax; controlled by Config.Defaults.cpuidMask.mode.d.eax. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.d.ebx | CPUID override that may be applied to level d register ebx; controlled by Config.Defaults.cpuidMask.mode.d.ebx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.d.ecx | CPUID override that may be applied to level d register ecx; controlled by Config.Defaults.cpuidMask.mode.d.ecx. |  |  | N/A | N/A | False |
| Config.Defaults.cpuidMask.val.d.edx | CPUID override that may be applied to level d register edx; controlled by Config.Defaults.cpuidMask.mode.d.edx. |  |  | N/A | N/A | False |
| Config.Defaults.security.host.ruissl | Require SSL to be used when communicating with the host over port 902. | True | True | N/A | N/A | False |
| Config.Defaults.vGPU.consolidation | Assignment policy to place shared passthru graphics VMs on same physical GPU until full. | False | False | N/A | N/A | False |
| Config.Etc.issue | Contents of /etc/issue |  |  | N/A | N/A | False |
| Config.Etc.motd | Contents of /etc/motd |  | TOO LONG TO PRINT | N/A | N/A | False |
| Config.GlobalSettings.guest.commands.sharedPolicyRefCount | Reference count to enable guest operations. | 0 | 0 | N/A | N/A | False |
| Config.HostAgent.level[Hbrsvc].logLevel | Logging level for the loggers related to HBR services. |  |  | N/A | N/A | False |
| Config.HostAgent.level[Hostsvc].logLevel | Logging level for the loggers related to Host services. |  |  | N/A | N/A | False |
| Config.HostAgent.level[Proxysvc].logLevel | Logging level for the loggers related to proxy services. |  |  | N/A | N/A | False |
| Config.HostAgent.level[Snmpsvc].logLevel | Logging level for the loggers related to SNMP services. |  |  | N/A | N/A | False |
| Config.HostAgent.level[Statssvc].logLevel | Logging level for the loggers related to Stats services. |  |  | N/A | N/A | False |
| Config.HostAgent.level[Vcsvc].logLevel | Logging level for the loggres related to VC services. |  |  | N/A | N/A | False |
| Config.HostAgent.level[Vimsvc].logLevel | Logging level for the loggers related to Virtual infrastructure management services. |  |  | N/A | N/A | False |
| Config.HostAgent.level[Vmsvc].logLevel | Logging level for the loggers related to VM services. |  |  | N/A | N/A | False |
| Config.HostAgent.log.level | Controls the global log level. |  | info | N/A | N/A | False |
| Config.HostAgent.plugins.hostsvc.esxAdminsGroup | Active Directory group name that is automatically granted administrator privileges on the ESX. | ESX Admins | ESX Admins | N/A | N/A | False |
| Config.HostAgent.plugins.hostsvc.esxAdminsGroupAutoAdd | Controls whether the group specified by 'esxAdminsGroup' is automatically granted administrator permission. | True | True | N/A | N/A | False |
| Config.HostAgent.plugins.hostsvc.esxAdminsGroupUpdateInterval | Interval between checks for whether the group specified by 'esxAdminsGroup' has appeared in Active Directory, in minutes. | 1 | 1 | N/A | N/A | False |
| Config.HostAgent.plugins.solo.enableMob | Enables or disables the Debug Managed Object Browser for the ESXi host. | False | False | N/A | N/A | False |
| Config.HostAgent.plugins.solo.webServer.enableWebscriptLauncher | Controls the availability of webscript launcher page. | True | True | N/A | N/A | False |
| Config.HostAgent.plugins.vimsvc.authValidateInterval | Number of minutes between each validation of all known users and groups - set to zero to disable validation. | 1440 | 1440 | N/A | N/A | False |
| Config.HostAgent.plugins.vimsvc.userSearch.maxResults | Maximum number of users and groups to display in the Add Permissions dialog - set to zero to disable the limit. | 100 | 100 | N/A | N/A | False |
| Config.HostAgent.plugins.vimsvc.userSearch.maxTimeSeconds | Number of seconds to wait for a search for users and groups to return results - set to zero to disable the timeout. | 20 | 20 | N/A | N/A | False |
| Config.HostAgent.plugins.vmsvc.enforceMaxRegisteredVms | Enables enforcing the limitation on the number of registered virtual machines in the inventory. | True | True | N/A | N/A | False |
| Config.HostAgent.plugins.vmsvc.productLockerWatchInterval | Interval between checks for whether the product locker files are changed, in seconds. Set to -1 to disable checks. | 300 | 300 | N/A | N/A | False |
| Cpu.ActionLoadThreshold | load threshold below which vcpu affinity migration is performed, 0 to disable | 10 | 10 | 0 | 100 | True |
| Cpu.AllowWideVsmp | Allow VMs with more VCPUs than host PCPUs, 0 to disable | 0 | 0 | 0 | 1 | True |
| Cpu.BoundLagQuanta | Number of global quanta before bound lag | 8 | 8 | 1 | 100 | True |
| Cpu.CommRateThreshold | threshold for inter-sched-context rate above which the contexts are considered to be related (in num/sec) | 500 | 500 | 0 | 50000 | True |
| Cpu.CoschedCostartThreshold | costart threshold in usec, costart threshold should be less than costopThreshold | 2000 | 2000 | 0 | 100000 | True |
| Cpu.CoschedCostopThreshold | maximum skew between vcpus in usec, 0 to disable | 3000 | 3000 | 0 | 100000 | True |
| Cpu.CoschedCrossCall | 0: disable cosched on crosscall; 1: enable cosched on crosscall | 1 | 1 | 0 | 1 | True |
| Cpu.CoschedExclusiveAffinity | 1 to enable coscheduling for vcpus with exclusive affinity, 0 to disable | 0 | 0 | 0 | 1 | True |
| Cpu.CoschedHandoffLLC | 0: handoff by switching pcpu; 1: handoff to LLC if possible | 1 | 1 | 0 | 1 | True |
| Cpu.CoschedHandoffSkip | only skip handoff if ready time is smaller than this threshold, in usec, 0 to allow skip always | 10 | 10 | 0 | 1000 | True |
| Cpu.CoschedPollUsec | interval between coscheduling skew checks, in usec | 1000 | 1000 | 1000 | 5000 | True |
| Cpu.CreditAgePeriod | Period in milliseconds | 3000 | 3000 | 1000 | 10000 | True |
| Cpu.DefaultImpact | the default expected efficiency loss when the related contexts are not running on the same LLC (in percentage) | 30 | 30 | 0 | 100 | True |
| Cpu.FairnessRebalancePcpus | max number of PCPUs to be considered when doing fairness rebalance, 0 to disable | 4 | 4 | 0 | 32 | True |
| Cpu.HTRebalancePeriod | average milliseconds between opportunities for a pcpu to migrate vcpus from within a core | 5 | 5 | 0 | 5000 | True |
| Cpu.HTStolenAgeThreshold | the amount of htStolen time a vcpu can keep without being aged (in seconds) | 8 | 8 | 0 | 500 | True |
| Cpu.HTWholeCoreThreshold | a vcpu with vtime falling behind by this threshold (in ms) is eligible to use the whole core (HT only), 0 to disable (may violate resource settings) | 800 | 800 | 0 | 5000 | True |
| Cpu.HostRebalancePeriod | average milliseconds between opportunities for a pcpu to migrate vcpus from within the whole system, 0 to disable | 100 | 100 | 0 | 5000 | True |
| Cpu.L2RebalancePeriod | average milliseconds between opportunities for a pcpu to migrate vcpus from within the shared L2 cache, 0 to disable | 10 | 10 | 0 | 5000 | True |
| Cpu.L3RebalancePeriod | average milliseconds between opportunities for a pcpu to migrate vcpus from within the shared L3 cache, 0 to disable | 20 | 20 | 0 | 5000 | True |
| Cpu.LimitEnforcementThreshold | Only allows low-vtime children ro run when a group/VM's vtimeLimit is smaller than the global virtual time by less than this threshold (in ms), 0 to disable | 200 | 200 | 0 | 10000 | True |
| Cpu.MaxSampleRateLg | Sampling system services at most (2^MaxSampleRateLg) times a second | 7 | 7 | 1 | 15 | True |
| Cpu.MoveCurrentRunnerPcpus | max number of PCPUs to be considered when searching for runner move opportunity, 0 to disable | 4 | 4 | 0 | 32 | True |
| Cpu.NonTimerWakeupRate | Disable P state if the running vcpu's non-timer wakeup rate is higher than this threshold, 0 to disable | 500 | 500 | 0 | 5000 | True |
| Cpu.PackageRebalancePeriod | average milliseconds between opportunities for a pcpu to migrate vcpus from within a package, 0 to disable | 20 | 20 | 0 | 5000 | True |
| Cpu.PcpuMigrateIdlePcpus | max number of PCPUs to be considered when doing pcpu idle rebalance, 0 to disable | 4 | 4 | 0 | 32 | True |
| Cpu.Quantum | Quantum in milliseconds | 200 | 200 | 1 | 1000 | True |
| Cpu.UseMwait | use MWAIT vs. HLT in the idle loop; 0: use HLT, 1: use MWAIT if possible, 2: choose by cpu type | 2 | 2 | 0 | 3 | True |
| Cpu.VMAdmitCheckPerVcpuMin | Perform additional admission control check that per virtual CPU virtual machine minimum does not exceed the speed of a single physical CPU | 1 | 1 | 0 | 1 | True |
| Cpu.WakeupMigrateIdlePcpus | max number of PCPUs to be considered when doing wakeup idle rebalance, 0 to disable | 4 | 4 | 0 | 32 | True |
| DCUI.Access | One or more comma-separated local users which are granted unconditional access to DCUI, even if they don't have administrator role on the host. | root | root | N/A | N/A | False |
| DataMover.HardwareAcceleratedInit | Enable hardware accelerated VMFS data initialization (requires compliant hardware) | 1 | 1 | 0 | 1 | True |
| DataMover.HardwareAcceleratedMove | Enable hardware accelerated VMFS data movement (requires compliant hardware) | 1 | 1 | 0 | 1 | True |
| DataMover.MaxHeapSize | Maximum size of the heap in MB used for data movement | 64 | 64 | 16 | 256 | True |
| Digest.AlgoType | Digest Crypto Hash Type (1=SHA-1, 2=SHA-256). | 1 | 1 | 1 | 2 | True |
| Digest.BlockSize | Blocksize in the original VMDK to compute crypto hash codes. In pages of 4K size. Value needs to be power of 2. | 1 | 1 | 1 | 2 | True |
| Digest.CollisionEnabled | Enable collision detection (0=disabled, 1=enabled) | 0 | 0 | 0 | 1 | True |
| Digest.JournalCoverage | Journal coverage in MB. Value needs to be power of 2. | 8 | 8 | 0 | 32 | True |
| Digest.UpdateOnClose | Enable crypto-hash updates on DiskLib_Close (0=disabled, 1=enabled). | 0 | 0 | 0 | 1 | True |
| DirentryCache.MaxDentryPerObj | Maximum directory entries cached per directory | 15000 | 15000 | 60 | 30000 | True |
| Disk.AllowUsbClaimedAsSSD | Permit claim rules to mark USB disks as SSD | 0 | 0 | 0 | 1 | True |
| Disk.ApdTokenRetryCount | APD Token Retry Count | 25 | 25 | 10 | 99999 | True |
| Disk.AutoremoveOnPDL | Autoremove paths to a disk that is in PDL (Permanent Device Loss) | 1 | 1 | 0 | 1 | True |
| Disk.BandwidthCap | cap on disk bandwidth (KB/s) usage | 4294967294 | 4294967294 | 10 | 4294967294 | True |
| Disk.DelayOnBusy | Delay in milliseconds for completion of commands with a BUSY status | 400 | 400 | 0 | 5000 | True |
| Disk.DeviceReclaimTime | The number of seconds between device re-claim attempts | 300 | 300 | 0 | 31536000 | True |
| Disk.DisableVSCSIPollInBH | Disable VSCSI_Poll in bottom half. Set to 1 to disable. | 1 | 1 | 0 | 1 | True |
| Disk.DiskDelayPDLHelper | Delay PDL helper in secs | 10 | 10 | 0 | 300 | True |
| Disk.DiskMaxIOSize | Max Disk READ/WRITE I/O size before splitting (in KB) | 32767 | 32767 | 32 | 32767 | True |
| Disk.DiskReservationThreshold | Time window within which refcounted reservations on a device are permitted (in msec) | 45 | 45 | 0 | 3000 | True |
| Disk.DiskRetryPeriod | Retry period in milliseconds for a command with retry status | 2000 | 2000 | 500 | 50000 | True |
| Disk.DumpMaxRetries | Max number of I/O retries during disk dump | 10 | 10 | 0 | 1000 | True |
| Disk.DumpPollDelay | Number of microseconds to wait between polls during a disk dump. | 1000 | 1000 | 1 | 100000 | True |
| Disk.DumpPollMaxRetries | Max number of device poll retries during disk dump | 10000 | 10000 | 1 | 100000 | True |
| Disk.EnableNaviReg | Enable automatic NaviAgent registration with EMC CLARiiON and Invista | 1 | 1 | 0 | 1 | True |
| Disk.FailDiskRegistration | Fail device registration if disk has only standby paths and supports only implicit asymmetric logical unit access. | 0 | 0 | 0 | 1 | True |
| Disk.FastPathRestoreInterval | Time interval (in msec) to monitor the IO latency to evaluate eligibility for fast-path in PSA. | 100 | 100 | 10 | 1000 | True |
| Disk.IdleCredit | Amount of idle credit that a virtual machine can gain for I/O requests | 32 | 32 | 1 | 512 | True |
| Disk.MaxLUN | Only LUNs with LUN ID values below this value will be scanned | 1024 | 1024 | 1 | 16384 | True |
| Disk.MaxResetLatency | Delay in milliseconds before logging warnings and spawning new reset worlds if a reset is overdue or taking too long | 2000 | 2000 | 500 | 600000 | True |
| Disk.NmpMaxCmdExtension | Increase the maximum number of commands to be processed at once in NMP | 0 | 0 | 0 | 1000000000 | True |
| Disk.PathEvalTime | The number of seconds between FC path evaluations | 300 | 300 | 0 | 31536000 | True |
| Disk.PreventVMFSOverwrite | Prevent overwriting VMFS partitions | 1 | 1 | 0 | 1 | True |
| Disk.QFullSampleSize | I/O samples to monitor for detecting non-transient queue full condition. Should be nonzero to enable queue depth throttling. | 0 | 0 | 0 | 64 | True |
| Disk.QFullThreshold | BUSY or QFULL threshold, upon which LUN queue depth will be throttled. Should be <= QFullSampleSize if throttling is enabled. | 8 | 8 | 1 | 16 | True |
| Disk.ReqCallThreshold | Threshold in number of pending requests before calling into vmkernel to process the requests | 8 | 8 | 1 | 129 | True |
| Disk.ResetLatency | Delay in milliseconds between reset thread wakeups | 1000 | 1000 | 100 | 600000 | True |
| Disk.ResetMaxRetries | Maximum number of bus reset retries. Set to 0 for no limit. | 0 | 0 | 0 | 10000 | True |
| Disk.ResetOverdueLogPeriod | Delay in seconds between logs of overdue reset | 60 | 60 | 10 | 86400 | True |
| Disk.ResetPeriod | Delay in seconds between bus resets retries | 30 | 30 | 1 | 3600 | True |
| Disk.ResetThreadExpires | Life in seconds of an inactive reset handle thread | 1800 | 1800 | 0 | 86400 | True |
| Disk.ResetThreadMax | Maximum number of reset handler threads | 16 | 16 | 1 | 16 | True |
| Disk.ResetThreadMin | Minimum number of reset handler threads | 1 | 1 | 1 | 16 | True |
| Disk.RetryUnitAttention | Retry all SCSI commands that return a unit attention error | 1 | 1 | 0 | 1 | True |
| Disk.ReturnCCForNoSpace | Return CC 0x7/0x27/0x7 in the event where a backing datastore has run out of space as opposed to posting a monitor event to halt the VM | 0 | 0 | 0 | 1 | True |
| Disk.SchedCostUnit | IO Scheduler block size for accounting | 32768 | 32768 | 4096 | 262144 | True |
| Disk.SchedQCleanupInterval | Time interval (in secs) to cleanup per device unused schedQ list (default = 5 minutes). | 300 | 300 | 0 | 31536000 | True |
| Disk.SchedQControlSeqReqs | Number of consecutive requests from a virtual machine required to raise the outstanding commands to maximum | 128 | 128 | 0 | 2048 | True |
| Disk.SchedQControlVMSwitches | Number of switches between commands issued by different virtual machines required to reduce outstanding commands to CONFIG_DISK_CIF | 6 | 6 | 0 | 2048 | True |
| Disk.SchedQPriorityPercentage | Percentage of priority commands to serve from priority queue | 80 | 80 | 10 | 100 | True |
| Disk.SchedQuantum | Number of consecutive requests from one world | 8 | 8 | 1 | 64 | True |
| Disk.SchedReservationBurst | Permit I/O bursts in mclock scheduler with reservations. | 1 | 1 | 0 | 1 | True |
| Disk.SchedulerWithReservation | Disk I/O scheudler (0:default 1:mclock) | 1 | 1 | 0 | 1 | True |
| Disk.SectorMaxDiff | Distance in sectors at which the disk BW schedules affinity stops | 2000 | 2000 | 0 | 2000000 | True |
| Disk.SharesHigh | Shares for high disk priority | 2000 | 2000 | 100 | 10000 | True |
| Disk.SharesLow | Shares for low disk priority | 500 | 500 | 100 | 10000 | True |
| Disk.SharesNormal | Shares for normal disk priority | 1000 | 1000 | 100 | 10000 | True |
| Disk.SupportSparseLUN | Support for sparse LUNs if set to one | 1 | 1 | 0 | 1 | True |
| Disk.ThroughputCap | cap on disk throughput (IO/s) usage | 4294967294 | 4294967294 | 10 | 4294967294 | True |
| Disk.UseDeviceReset | Use device reset (instead of bus reset) to reset a SCSI device | 1 | 1 | 0 | 1 | True |
| Disk.UseIOWorlds | Use worlds instead of worldlets for async IO. | 1 | 1 | 0 | 1 | True |
| Disk.UseIoPool | Enable deferred work execution for the SCSI items. 8 worlds worker pool assignment with: 0x0000xxFF mask is for the issue path. 0x0000FFxx for the completion path. | 0 | 0 | 0 | 7 | True |
| Disk.UseLunReset | Use LUN reset (instead of device.bus reset) to reset a SCSI device | 1 | 1 | 0 | 1 | True |
| Disk.UseReportLUN | Use the REPORT LUN command to increase scanning speed for devices | 1 | 1 | 0 | 1 | True |
| Disk.VSCSICoalesceCount | Frequency with which the coalesce callback is called. | 1000 | 1000 | 0 | 100000 | True |
| Disk.VSCSIPollPeriod | Time in microseconds between VSCSI polls. | 1000 | 1000 | 1 | 99999999 | True |
| Disk.VSCSIResvCmdRetryInSecs | Time (in secs) to retry on transient errors for Reservation  commands for MSCS CAB configs. | 1 | 1 | 1 | 60 | True |
| Disk.VSCSIWriteSameBurstSize | Max number of split IOs per write same request. | 4 | 4 | 1 | 4 | True |
| FSS.FSSLightWeightProbe | Enable light-weight efficient probe of ESX supported datastores | 1 | 1 | 0 | 1 | True |
| FT.AckIntervalMax | Maximum time in microseconds between acks | 1000000 | 1000000 | 1000000 | 4000000 | True |
| FT.AckIntervalMin | Minimum time in microseconds between acks | 0 | 0 | 0 | 100000 | True |
| FT.BackupConnectTimeout | Time in milliseconds to wait for the backup to connect | 8000 | 8000 | 100 | 30000 | True |
| FT.BackupExtraTimeout | Extra milliseconds before backup declares primary dead | 100 | 100 | 0 | 30000 | True |
| FT.BadExecLatency | Latency considered bad execution latency(ms) | 800 | 800 | 0 | 10000 | True |
| FT.BindToVmknic | Bind the FT socket to a specific vmknic | 0 | 0 | 0 | 1 | True |
| FT.ChargeVMXForFlush | Charge the VMX world for log flushing instead of the global flush world | 1 | 1 | 0 | 1 | True |
| FT.CheckFCPathState | Check storage path state | 1 | 1 | 0 | 1 | True |
| FT.CheckForProgress | Check for progress on the backup and/or primary | 0 | 0 | 0 | 1 | True |
| FT.CoreDumpNoProgressMS | Milliseconds before live coredump vmm and vmx if progress isn't made | 0 | 0 | 0 | 10000 | True |
| FT.ExecLatencyKill | Time to wait for good latency before killing a slow backup(ms) | 0 | 0 | 0 | 100000 | True |
| FT.ExtraLogTimeout | Time in milliseconds for temporary increase in timeout | 10000 | 10000 | 500 | 300000 | True |
| FT.FTCptConcurrentSend | Send non-diff pages in parallel with diffing rather than after | 1 | 1 | 0 | 1 | True |
| FT.FTCptDelayCheckpoint | Delay checkpoint if no network packet waiting | 2 | 2 | 0 | 2 | True |
| FT.FTCptDiffCap | Max percent pages via diffs (EXPERIMENTAL, failover will not work if not 100) | 100 | 100 | 0 | 100 | True |
| FT.FTCptDiffThreads | Number of threads for diffing pages | 6 | 6 | 1 | 16 | True |
| FT.FTCptDisableFailover | Disable failovers (testing only) | 0 | 0 | 0 | 6 | True |
| FT.FTCptDiskWriteTimeout | Time in milliseconds for backup site to wait for a disk I/O to complete | 3000 | 3000 | 10 | 60000 | True |
| FT.FTCptDontDelayPkts | Do not delay network packets - for testing only | 0 | 0 | 0 | 1 | True |
| FT.FTCptDontSendPages | Do not send over modified pages - for testing only | 0 | 0 | 0 | 1 | True |
| FT.FTCptEpochList | List of potential epochs to try in order of increasing value | 5,10,20,100 | 5,10,20,100 | N/A | N/A | True |
| FT.FTCptEpochSample | Single epoch sampling time in ms | 1000 | 1000 | 1 | 60000 | True |
| FT.FTCptEpochWait | Wait in ms after epoch sampling | 8000 | 8000 | 1 | 4294967295 | True |
| FT.FTCptIORetryExtraInterval | Extra sleep interval (in ms) between retries on disk I/O error | 200 | 200 | 10 | 2000 | True |
| FT.FTCptIORetryInterval | Sleep interval (in ms) between retries on disk I/O error | 10 | 10 | 10 | 2000 | True |
| FT.FTCptIORetryTimes | Maximum retries on disk I/O error | 15 | 15 | 5 | 50 | True |
| FT.FTCptLogTimeout | Time in milliseconds to wait for FT log entries (read or write) | 8000 | 8000 | 500 | 30000 | True |
| FT.FTCptMaxPktsDelay | Max number of packets in the delayed queue before forcing a checkpoint | 0 | 0 | 0 | 10000 | True |
| FT.FTCptMinInterval | Time in milliseconds to wait between two forced checkpoints | 4 | 4 | 2 | 1000 | True |
| FT.FTCptNetDelayNoCpt | Delay to impose on virtual machine network output in ms | 0 | 0 | 0 | 5000 | True |
| FT.FTCptNumConnections | # of data connections to use for page sending | 2 | 2 | 1 | 4 | True |
| FT.FTCptNumaIndex | Index dirty pages by NUMA node.  Workers will use the index to prefer local work. | 0 | 0 | 0 | 1 | True |
| FT.FTCptPagePolicy | Page placement policy for side data.  < 2^16: Use a specific node mask, 0x10000: Put pages anywhere, 0x10001: Match nodes with virtual machine, 0x10002: Avoid matching nodes with virtual machine | 65538 | 65538 | 1 | 65538 | True |
| FT.FTCptPoweroff | Power off the Primary VM after the next checkpoint | 0 | 0 | 0 | 3 | True |
| FT.FTCptRcvBufSize | TCP receive buffer size for the backup | 562140 | 562140 | 16384 | 16777216 | True |
| FT.FTCptSndBufSize | TCP send buffer size for the Primary VM | 562140 | 562140 | 16384 | 16777216 | True |
| FT.FTCptStartTimeout | Time in milliseconds for backup site to wait for data for the next checkpoint | 90000 | 90000 | 1000 | 90000 | True |
| FT.FTCptStatsInterval | Time in milliseconds between stat printing | 30 | 30 | 0 | 600 | True |
| FT.FTCptThreadPolicy | Policy for placing helper threads.  < 2^16: Use a fixed NUMA node mask, 0x10000: Put threads anywhere, 0x10001: Match threads to a dynamic node index | 65536 | 65536 | 1 | 65537 | True |
| FT.FTCptVcpuMinUsage | VCPU usage in percentage below which the VM will be considered for forced checkpoint | 40 | 40 | 0 | 100 | True |
| FT.FTCptWaitOnSocket | Wait when socket is empty | 1 | 1 | 0 | 1 | True |
| FT.FillAffinity | Set the fill world/worldlet affinity to the tcp worldlet | 1 | 1 | 0 | 1 | True |
| FT.FillWorldlet | Fill the buffer from a worldlet | 1 | 1 | 0 | 1 | True |
| FT.FlushReservationMax | The maximum amount of CPU to reserve for the async flush world | 25 | 25 | 0 | 100 | True |
| FT.FlushReservationMin | The minimum amount of CPU to reserve for the async flush world | 5 | 5 | 0 | 100 | True |
| FT.FlushSleep | Sleep time in milliseconds when nothing to flush | 0 | 0 | 0 | 10000 | True |
| FT.FlushWorldlet | Flush the buffer from a worldlet | 1 | 1 | 0 | 1 | True |
| FT.GlobalFlushWorld | Use a global async flush world | 0 | 0 | 0 | 1 | True |
| FT.GoodExecLatency | Latency considered good execution latency(ms) | 200 | 200 | 0 | 10000 | True |
| FT.HeartbeatCount | Number of failed heartbeats before declare dead. | 10 | 10 | 5 | 20 | True |
| FT.HostTimeout | Time in milliseconds before declare FT host dead | 2000 | 2000 | 100 | 30000 | True |
| FT.IORetryExtraInterval | Sleep extra interval (msec) between I/O reissuing on I/O error | 200 | 200 | 10 | 2000 | True |
| FT.IORetryInterval | Sleep interval (msec) between I/O reissuing on I/O error | 10 | 10 | 10 | 2000 | True |
| FT.IORetryTimes | Maximum disk I/O reissuing times on I/O error | 15 | 15 | 5 | 50 | True |
| FT.LogBufferStallSleep | Sleep time in milliseconds when log buffer is full on the primary | 1 | 1 | 0 | 100000 | True |
| FT.LogTimeout | Time in milliseconds to wait on log socket | 8000 | 8000 | 500 | 30000 | True |
| FT.LongFlushDebugMS | Long millisecond interval for debugging flushing delays | 500 | 500 | 100 | 5000 | True |
| FT.MaxFlushInterval | Maximum amount of microseconds to wait before writing to flush socket | 0 | 0 | 0 | 10000 | True |
| FT.MinWriteSize | Minimum amount of data to write to flush socket | 0 | 0 | 0 | 65536 | True |
| FT.NoWaitOnSocket | Don't wait on socket | 0 | 0 | 0 | 1 | True |
| FT.PanicNoProgressMS | Milliseconds before panic if progress isn't made | 0 | 0 | 0 | 10000 | True |
| FT.PrimaryConnectTimeout | Time in milliseconds to wait when connecting to the primary | 8000 | 8000 | 100 | 30000 | True |
| FT.ShortFlushDebugMS | Short millisecond interval for debugging flushing delays | 100 | 100 | 10 | 5000 | True |
| FT.TCPNoDelayBackup | Set TCP_NODELAY on the socket on the backup | 1 | 1 | 0 | 1 | True |
| FT.TCPNoDelayPrimary | Set TCP_NODELAY on the socket on the primary | 1 | 1 | 0 | 1 | True |
| FT.TCPPersistTimer | TCP persist timer time in milliseconds | 500 | 500 | 500 | 5000 | True |
| FT.TCPRcvBufSize | TCP receive buffer size for the backup | 131072 | 131072 | 16384 | 1000000 | True |
| FT.TCPSndBufSize | TCP send buffer size for the primary | 131072 | 131072 | 16384 | 1000000 | True |
| FT.UseHostMonitor | Use the host monitor to ping the other host | 0 | 0 | 0 | 1 | True |
| FT.Vmknic | Vmknic for FT vmkernel VNIC |  |  | N/A | N/A | True |
| FT.XmitSyncQueueLen | Length of the Tx synchronization queue | 64 | 64 | 1 | 32768 | True |
| FT.adjDownInt | CPU adjust down interval in seconds | 10 | 10 | 3 | 30 | True |
| FT.adjDownPct | CPU slowdown adjustment pct parameter  | 10 | 10 | 1 | 30 | True |
| FT.adjUpInt | CPU adjust up interval in seconds | 200 | 200 | 5 | 12000 | True |
| FT.adjUpPct | CPU speedup adjustment pct parameter  | 10 | 10 | 1 | 30 | True |
| FT.execLatExtra | Extra execution latency allowed in msec | 500 | 500 | 0 | 3000 | True |
| FT.maxLowerBound | CPU minimum alloc.max allowed in pct  | 20 | 20 | 5 | 50 | True |
| FT.slowdownPctMax | Maximum primary vm CPU slowdown pct | 60 | 60 | 0 | 90 | True |
| FT.slowdownTimeMax | Maximum primary vm CPU slowdown duration in seconds | 600 | 600 | 0 | 9000 | True |
| HBR.ChecksumIoSize | Size in blocks of a checksum read I/O | 8 | 8 | 1 | 1024 | True |
| HBR.ChecksumMaxIo | Maximum number of I/O chunks read in parallel for checksum | 8 | 8 | 1 | 256 | True |
| HBR.ChecksumPerSlice | Maximum number of I/O chunks we read in each slice for checksum | 2 | 2 | 1 | 64 | True |
| HBR.ChecksumRegionSize | Size in blocks of one checksum region, corresponding to one network request | 256 | 256 | 1 | 4096 | True |
| HBR.ChecksumUseAllocInfo | Use disk allocation info to help speed up the checksum process | 1 | 1 | 0 | 1 | True |
| HBR.ChecksumUseChecksumInfo | Use disk checksum info to help speed up transfering valid blocks of data. | 1 | 1 | 0 | 1 | True |
| HBR.ChecksumZoneSize | Size in regions of one checksum zone for which allocation information will be cached | 32768 | 32768 | 32 | 1048576 | True |
| HBR.CopySnapDiskMaxExtentCount | Number of extents for a single snapshot disk that can be copied in parallel | 16 | 16 | 1 | 128 | True |
| HBR.CopySnapFidHashBuckets | Number of hash buckets to use to track the snapshot disks open to copy to demand log. | 256 | 256 | 1 | 1024 | True |
| HBR.DemandlogExtentHashBuckets | Number of hash buckets to use to track extents that haven't been read. | 512 | 512 | 1 | 65536 | True |
| HBR.DemandlogIoTimeoutSecs | Timeout for IOs for demand log operations. | 120 | 120 | 0 | 1000 | True |
| HBR.DemandlogReadRetries | Number of times to retry an internal read (for the demand log) before aborting the delta. | 20 | 20 | 0 | 1000 | True |
| HBR.DemandlogRetryDelayMs | Delay in milliseconds for retrying a demand log write. | 10 | 10 | 0 | 100000 | True |
| HBR.DemandlogSendHashBuckets | Number of hash buckets to use to track extents that have been sent. | 8 | 8 | 1 | 32 | True |
| HBR.DemandlogTransferIoSize | Size in blocks of a demandlog transfer read I/O | 8 | 8 | 1 | 16 | True |
| HBR.DemandlogTransferMaxIo | Maximum number of demandlog transfer I/O chunks issued in parallel | 4 | 4 | 1 | 16 | True |
| HBR.DemandlogTransferMaxNetwork | Maximum number of demandlog chunks transferred in parallel | 8 | 8 | 1 | 32 | True |
| HBR.DemandlogTransferPerSlice | Maximum number of demandlog chunks issued per slice | 2 | 2 | 1 | 16 | True |
| HBR.DemandlogWriteRetries | Number of times to retry a demand log write before aborting the delta. | 20 | 20 | 0 | 1000 | True |
| HBR.DisableChecksumOffload | Disable the use of SSE CRC32 instruction | 0 | 0 | 0 | 1 | True |
| HBR.DisconnectedEventDelayMs | Time to wait (while attempting reconnection) before posting a 'no connection to VR server' event | 60000 | 60000 | 100 | 600000 | True |
| HBR.ErrThrottleChecksumIO | Throttle Checksum I/O errors. | 1 | 1 | 0 | 1 | True |
| HBR.ErrThrottleDceRead | Throttle DCE Read errors. | 1 | 1 | 0 | 1 | True |
| HBR.HbrBitmapAllocTimeoutMS | A timeout in MS for how long we will wait to allocate a bitmap | 3000 | 3000 | 0 | 10000 | True |
| HBR.HbrBitmapVMMaxStorageGB | An estimation of the maximum storage allocated per VM in gigabytes | 65536 | 65536 | 100 | 131072 | True |
| HBR.HbrBitmapVMMinStorageGB | An estimation of the minimum storage allocated per VM in gigabytes | 500 | 500 | 100 | 131072 | True |
| HBR.HbrDemandLogIOPerVM | Number of concurrent demand log copies per VM | 64 | 64 | 1 | 128 | True |
| HBR.HbrDisableNetCompression | Disable end-to-end network compression. | 1 | 1 | 0 | 1 | True |
| HBR.HbrLowerExtentBreakGB | Disks with capacity between the min extent break and this number of gigabytes will have the lower extent size. | 8192 | 8192 | 1 | 65536 | True |
| HBR.HbrLowerExtentSizeKB | Lower extent size used for disks in kilobytes. | 16 | 16 | 1 | 128 | True |
| HBR.HbrMaxExtentSizeKB | Maximum extent size in kilobytes. Used for disks with capacity over the upper extent break. | 64 | 64 | 1 | 128 | True |
| HBR.HbrMaxGuestXferWhileDeltaMB | Maximum single SCSI command transfer size (in megabytes) that will be tolerated while a delta is taking place. | 1024 | 1024 | 256 | 3072 | True |
| HBR.HbrMaxUnmapExtents | Maximum expected number of extents for SCSI UNMAP commands. | 10 | 10 | 0 | 100000 | True |
| HBR.HbrMaxUnmapsInFlight | Maximum expected number of SCSI UNMAP commands in flight on a single disk. | 128 | 128 | 0 | 1048576 | True |
| HBR.HbrMinExtentBreakGB | Disks with capacity under this number of gigabytes will have the min extent size. | 2048 | 2048 | 1 | 65536 | True |
| HBR.HbrMinExtentSizeKB | Minimum extent size used for disks in kilobytes. | 8 | 8 | 1 | 128 | True |
| HBR.HbrOptimizeFullSync | Skip transfer of changed blocks during full sync to avoid sending them twice between the full sync and the subsequent delta. | 1 | 1 | 0 | 1 | True |
| HBR.HbrResourceHeapPerVMSizeKB | The additional amount of memory in KB per VM to add to the resource heap size | 128 | 128 | 0 | 4096 | True |
| HBR.HbrResourceHeapSizeMB | A base value in MB for the size of the resource heap | 2 | 2 | 2 | 256 | True |
| HBR.HbrResourceHeapUtilization | Expected usable percentage of the resource heap (minus overheads, fragmentation) | 95 | 95 | 1 | 200 | True |
| HBR.HbrResourceMaxDiskContexts | The maximum number of resource contexts allowed in disk phase for all VMs. | 512 | 512 | 16 | 8192 | True |
| HBR.HbrRuntimeHeapMaxBaseMB | A base value in MB for the maximum size of the runtime heap | 1 | 1 | 1 | 128 | True |
| HBR.HbrRuntimeHeapMinBaseMB | A base value in MB for the minimum size of the runtime heap | 1 | 1 | 1 | 128 | True |
| HBR.HbrStaticHeapMaxBaseMB | A base value in MB for the maximum size of the static heap | 1 | 1 | 1 | 128 | True |
| HBR.HbrStaticHeapMinBaseMB | A base value in MB for the minimum size of the static heap | 1 | 1 | 1 | 128 | True |
| HBR.HbrUpperExtentBreakGB | Disks with capacity between the lower extent break and this number of gigabytes will have the upper extent size. | 32768 | 32768 | 1 | 65536 | True |
| HBR.HbrUpperExtentSizeKB | Upper extent size used for disks in kilobytes. | 32 | 32 | 1 | 128 | True |
| HBR.HelperQueueMaxRequests | Maximum number of helper requests the helper queue can support | 8192 | 8192 | 128 | 16384 | True |
| HBR.HelperQueueMaxWorlds | Maximum number of world processing helper queue requests | 8 | 8 | 1 | 16 | True |
| HBR.LocalReadIoTimeoutSecs | Timeout for IOs for dce local reads. | 120 | 120 | 0 | 1000 | True |
| HBR.MigrateFlushTimerSecs | Time between attempts to flush the state to the persistent file during migration. | 3 | 3 | 1 | 600 | True |
| HBR.NetworkUseCubic | Use the cubic TCP congestion algorithm for HBR sockets | 1 | 1 | 0 | 1 | True |
| HBR.NetworkerRecvHashBuckets | Number of hash buckets to use to track commands waiting to receive a response. | 64 | 64 | 1 | 65536 | True |
| HBR.OpportunisticBlockListSize | Number of blocks to keep around in a LRU list for opportunistic replication | 4000 | 4000 | 500 | 10000 | True |
| HBR.ProgressReportIntervalMs | Interval between per-disk progress updates to hostd | 5000 | 5000 | 1000 | 600000 | True |
| HBR.PsfIoTimeoutSecs | Timeout for IOs for persistent state file/demand log metadata. | 300 | 300 | 0 | 1000 | True |
| HBR.ReconnectFailureDelaySecs | Additional delay in seconds added per reconnection failure for a session | 10 | 10 | 10 | 300 | True |
| HBR.ReconnectMaxDelaySecs | Maximum delay in seconds between reconnection attempts for a session | 90 | 90 | 30 | 300 | True |
| HBR.ResourceServerHashBuckets | Number of hash buckets to use to track remote HBR servers. | 8 | 8 | 1 | 65536 | True |
| HBR.RetryMaxDelaySecs | Maximum server request retry delay in seconds (for non-fatal errors) | 60 | 60 | 1 | 120 | True |
| HBR.RetryMinDelaySecs | Minimum server request retry delay in seconds (for non-fatal errors) | 1 | 1 | 1 | 60 | True |
| HBR.SyncTransferRetrySleepSecs | Time in seconds to wait after a failure before retrying a sync operation. | 5 | 5 | 1 | 600 | True |
| HBR.TransferDiskMaxIo | Maximum number of blocks that will be read in parallel | 32 | 32 | 1 | 128 | True |
| HBR.TransferDiskMaxNetwork | Maximum number of blocks that will be transferred in parallel | 64 | 64 | 1 | 256 | True |
| HBR.TransferDiskPerSlice | Maximum number of blocks that will be read in each slice | 16 | 16 | 1 | 128 | True |
| HBR.TransferFileExtentSize | Chunk size for config file transfers | 8192 | 8192 | 512 | 1048576 | True |
| HBR.TransferMaxContExtents | Maximum number of contiguous extents that will be coalesced into a single update | 8 | 8 | 1 | 128 | True |
| HBR.WireChecksum | Use wire checksums | 1 | 1 | 0 | 1 | True |
| HBR.XferBitmapCheckIntervalSecs | Time in seconds to wait before checking the transfer bitmap for availability of dirty blocks. | 10 | 10 | 1 | 600 | True |
| ISCSI.MaxIoSizeKB | The maximum I/O size of Software iSCSI in KB. Requires rebooting the host. | 128 | 128 | 128 | 512 | True |
| Irq.BestVcpuRouting | IRQ best virtual CPU routing | 0 | 0 | 0 | 1 | True |
| Irq.IRQActionAffinityWeight | relative weight for action-vcpu affinity | 5 | 5 | 0 | 10 | True |
| Irq.IRQAvoidExclusive | Avoid placing interrupts on physical CPUs with exclusive affinity set. | 1 | 1 | 0 | 1 | True |
| Irq.IRQBHConflictWeight | relative weight for irq/BH conflict | 5 | 5 | 0 | 10 | True |
| Irq.IRQRebalancePeriod | Time in milliseconds between attempts to rebalance interrupts | 50 | 50 | 10 | 20000 | True |
| Irq.IRQVcpuConflictWeight | relative weight for irq/vcpu conflict | 3 | 3 | 1 | 10 | True |
| LPage.LPageAlwaysTryForNPT | Enable always try to alloc large page for NPT | 1 | 1 | 0 | 1 | True |
| LPage.LPageDefragEnable | Enable large page defragmentation | 1 | 1 | 0 | 1 | True |
| LPage.LPageMarkLowNodes | Enable marking of nodes with low large pages free | 1 | 1 | 0 | 1 | True |
| LPage.MaxSharedPages | Maximum number of shared pages in a 2MB region that may be broken to back the region with a large page | 512 | 512 | 0 | 512 | True |
| LPage.MaxSwappedPagesInitVal | Initial value for maximum number of swapped pages in a 2MB region that may be read to back the region with a large page | 10 | 10 | 0 | 512 | True |
| LPage.freePagesThresholdForRemote | Maximum number of free small pages on local nodes to allow remote lpages | 2048 | 2048 | 0 | 4294967295 | True |
| LSOM.blkAttrCacheSizePercent | BlkAttr cache size percent growth rate with peak value (100%) caching almost all blkattrs for the diskgroup. | 0 | 0 | 0 | 100 | True |
| Mem.AllocGuestLargePage | Enable large page backing of guest memory | 1 | 1 | 0 | 1 | True |
| Mem.CtlMaxPercent | Vmmemctl limit as percentage of virtual machine maximum size | 65 | 65 | 0 | 99 | True |
| Mem.IdleTax | Idle memory tax rate | 75 | 75 | 0 | 99 | True |
| Mem.IdleTaxType | idle tax type. 0=flat, 1=variable | 1 | 1 | 0 | 1 | True |
| Mem.MemDefragClientsPerDir | Clients that are allowed to defrags per directory. | 2 | 2 | 0 | 512 | True |
| Mem.MemMinFreePct | Percentage of host memory to reserve for accelerating memory allocations when free memory is low, 0 for automatic | 0 | 0 | 0 | 50 | True |
| Mem.MemZipEnable | Enable the memory compression cache | 1 | 1 | 0 | 1 | True |
| Mem.MemZipMaxAllocPct | Sets the maximum size for the compression cache as a percentage of allocated VM memory size | 50 | 50 | 5 | 100 | True |
| Mem.MemZipMaxPct | Sets the maximum target size for the compression cache as a percentage of VM size | 10 | 10 | 5 | 100 | True |
| Mem.SampleActivePctMin | lower bound for sampled active memory | 1 | 1 | 0 | 10 | True |
| Mem.SampleDirtiedPctMin | lower bound for sampled active dirtied memory | 0 | 0 | 0 | 10 | True |
| Mem.ShareForceSalting | PShare salting lest you limit the transparent page sharing only between a set of VMs. PShare salting is controlled by the VMX sched.mem.pshare.salt option. The PShare salting option has three states: 0 - no salting or isolation between VMs; 1 - VMs that have the sched.mem.pshare.salt option set are able to share memory with VMs with the same salt; 2 - VMs that do not have the sched.mem.pshare.salt option set cannot share memory with any other VM, page sharing is possible only inside the VM. If the  sched.mem.pshare.salt is present but empty, the VM gest its own unique salt. | 2 | 2 | 0 | 2 | True |
| Mem.ShareRateMax | per-VM upper limit on pshare scan rate in pages/sec. (0 to disable) | 1024 | 1024 | 0 | 32768 | True |
| Mem.ShareScanGHz | max page scan rate in MB/sec per GHz of host CPU, 0 to disable | 4 | 4 | 0 | 32 | True |
| Mem.ShareScanTime | desired time in minutes to scan entire VM | 60 | 60 | 10 | 600 | True |
| Mem.VMOverheadGrowthLimit | Default limit (in MB) on VM overhead memory growth. Valid values are 0 to maximum memory supported and (uint32)-1 which means "unlimited". | 4294967295 | 4294967295 | 0 | 4294967295 | True |
| Migrate.AutoBindVmknic | Autobind vMotion socket to the vmknic where data comes from. Used only for the vMotion server side, which is the vMotion listening and receiving side | 1 | 1 | 0 | 1 | True |
| Migrate.BindToVmknic | Bind the vMotion socket to a specific vmknic.  0 for never, 1 to bind only with FT, 2 to bind with FT or for multi-vmknic support, 3 to always bind | 3 | 3 | 0 | 3 | True |
| Migrate.CptCacheMaxSizeMB | Maximum checkpoint cache size in MB | 544 | 544 | 8 | 1024 | True |
| Migrate.DebugChecksumMismatch | Debug checksum mismatch. | 0 | 0 | 0 | 1 | True |
| Migrate.DetectZeroPages | Whether vMotion should detect zero pages during page transmission | 1 | 1 | 0 | 1 | True |
| Migrate.DisableResumeDuringPageIn | Disable observation of resume during page-in flag, always completing page-in before VM resume | 0 | 0 | 0 | 1 | True |
| Migrate.DiskOpsChunkSize | Size of each stream chunk in bytes (will be rounded up to multiple of block size) | 131072 | 131072 | 8096 | 1000000 | True |
| Migrate.DiskOpsEnabled | Enables VMotion disk-backed operation | 0 | 0 | 0 | 1 | True |
| Migrate.DiskOpsMaxRetries | Maximum number of times to retry a diskOp IO upon encountering a reservation conflict | 20 | 20 | 0 | 1000 | True |
| Migrate.DiskOpsStreamChunks | Stream Chunks to allocate on disk | 40 | 40 | 1 | 1024 | True |
| Migrate.Enabled | Enable hot migration support | 1 | 1 | 0 | 1 | True |
| Migrate.GetPageSysAlertThresholdMS | Threshold in milliseconds for the source host to prepare a page for transmission above which a SysAlert is triggered | 10000 | 10000 | 1000 | 100000 | True |
| Migrate.LowBandwidthSysAlertThreshold | Threshold in KB/s for VMotion bandwidth below which a SysAlert is triggered | 0 | 0 | 0 | 100000 | True |
| Migrate.LowMemWaitSysAlertThresholdMS | Threshold in milliseconds for the dest host to leave the low-memory state above which a SysAlert is triggered | 10000 | 10000 | 1000 | 100000 | True |
| Migrate.MigrateCpuMinPctDefault | Desired default shared CPU reservation (in %) for VMotions | 30 | 30 | 0 | 400 | True |
| Migrate.MigrateCpuPctPerGb | Desired per Gbit shared CPU reservation (in %) for VMotions | 10 | 10 | 0 | 100 | True |
| Migrate.MigrateCpuSharesHighPriority | CPU shares for a high priority VMotion | 60000 | 60000 | 1 | 100000 | True |
| Migrate.MigrateCpuSharesRegular | CPU shares for a regular VMotion | 30000 | 30000 | 1 | 100000 | True |
| Migrate.MonActionWaitSysAlertThresholdMS | Threshold in milliseconds for the monitor to process a pre-copy action after which a SysAlert is triggered | 2000 | 2000 | 1 | 100000 | True |
| Migrate.NetExpectedLineRateMBps | Expected network throughput, in MBps, for bandwidth-delay calculation | 133 | 133 | 1 | 2000 | True |
| Migrate.NetLatencyModeThreshold | Lowest possible round-trip time, in ms, before vMotion must operate in latency-aware mode. | 4 | 4 | 1 | 1000 | True |
| Migrate.NetTimeout | Time-out for migration network operations | 20 | 20 | 1 | 3600 | True |
| Migrate.OutstandingReadKBMax | Maximum socket-backed mbuf bytes vMotion will allow to be outstanding while drained concurrently with reads, 0 for unlimited | 128 | 128 | 0 | 2048 | True |
| Migrate.PanicOnChecksumMismatch | 1 for world panic, 2 for vmkernel panic | 0 | 0 | 0 | 2 | True |
| Migrate.PreCopyCountDelay | Delay preCopy next action every n action posts | 10 | 10 | 0 | 1000 | True |
| Migrate.PreCopyMinProgressPerc | Minimum allowed transmit to dirty page ratio per pre-copy iteration | 130 | 130 | 1 | 1000 | True |
| Migrate.PreCopyPagesPerSend | Maximum number of pages to send per precopy transmit | 32 | 32 | 1 | 1024 | True |
| Migrate.PreCopySwitchoverTimeGoal | Goal time in milliseconds to send changed pages after pre-copy completes | 500 | 500 | 100 | 100000 | True |
| Migrate.PreallocLPages | Attempt to prealloc destination pages via large page allocation | 1 | 1 | 0 | 1 | True |
| Migrate.ProhibitFork | Prohibit forking from a VM | 0 | 0 | 0 | 1 | True |
| Migrate.RcvBufSize | TCP receive buffer size for the destination | 562540 | 562540 | 65536 | 1000000 | True |
| Migrate.RdpiTransitionTimeMs | Milliseconds to wait for page-in completion before resuming, if rdpi is enabled | 1 | 1 | 1 | 300000 | True |
| Migrate.SdpsDynamicDelaySec | Delay, in seconds, between polling when considering enabling SDPS in the first preCopy iteration. | 30 | 30 | 0 | 10000 | True |
| Migrate.SdpsEnabled | Stuns VMotion source in small increments during precopy, 0=disabled, 1=always enabled, 2=dynamic | 2 | 2 | 0 | 2 | True |
| Migrate.SdpsTargetRate | Percent by which transmit should be made to exceed dirty | 500 | 500 | 1 | 10000 | True |
| Migrate.SndBufSize | TCP send buffer size for the source | 562540 | 562540 | 65536 | 1000000 | True |
| Migrate.TSMaster | Pseudo-synchronize clocks for migration to and from this machine | 0 | 0 | 0 | 1 | True |
| Migrate.TcpTsoDeferTx | Use TCP tso defer optimization for transmit | 0 | 0 | 0 | 1 | True |
| Migrate.TryToUseDefaultHeap | Attempt use the default migration heap when beginning new migrations | 1 | 1 | 0 | 1 | True |
| Migrate.VASpaceReserveCount | Number of migrations to reserve virtual address space for at module load time | 128 | 128 | 2 | 128 | True |
| Migrate.VASpaceReserveSize | Megabytes of virtual address space to reserve per migration at module load time | 768 | 768 | 64 | 1024 | True |
| Migrate.VMotionLatencySensitivity | Make vMotion helper worlds latency sensitive, avoid transmit delays. | 1 | 1 | 0 | 1 | True |
| Migrate.VMotionResolveSwapType | Attempt to resolve swap type during VMotion initialization | 1 | 1 | 0 | 1 | True |
| Migrate.VMotionStreamDisable | Pretend to not support streams | 0 | 0 | 0 | 1 | True |
| Migrate.VMotionStreamHelpers | Number of helpers to allocate for VMotion streams | 0 | 0 | 0 | 32 | True |
| Migrate.Vmknic | vmknic for vMotion vmkernel VNIC |  |  | N/A | N/A | True |
| Misc.APDHandlingEnable | Enable Storage APD Handling. | 1 | 1 | 0 | 1 | True |
| Misc.APDTimeout | Number of seconds a device can be in APD before failing User World I/O. | 140 | 140 | 20 | 999999 | True |
| Misc.BHTimeout | Time-out for bottom-half handlers in milliseconds | 0 | 0 | 0 | 5000 | True |
| Misc.BhTimeBound | Time bound on BH checking in us (microseconds). | 2000 | 2000 | 0 | 500000 | True |
| Misc.BlueScreenTimeout | Time-out in seconds. Set to 0 for no time-out. | 0 | 0 | 0 | 65535 | True |
| Misc.ConsolePort | Name of serial port to use for visor console (COM1, COM2, firewire) | none | none | N/A | N/A | True |
| Misc.DebugBuddyEnable | Enable buddy debugging. Set to 0 to disable. | 0 | 0 | 0 | 1 | True |
| Misc.DebugLogToSerial | Send vmkernel LOG messages to the serial port | 0 | 0 | 0 | 1 | True |
| Misc.DefaultHardwareVersion | Default virtual machine compatibility |  |  | N/A | N/A | True |
| Misc.EnableHighDMA | Enable DMA above 4GB | 1 | 1 | 0 | 1 | True |
| Misc.GDBPort | Name of serial port to use for GDB debugging (COM1, COM2, firewire) | none | none | N/A | N/A | True |
| Misc.GuestLibAllowHostInfo | Allow guest to read host-level metrics | 0 | 0 | 0 | 1 | True |
| Misc.HeapMgrGuardPages | Number of guard pages to insert between heap VA regions | 1 | 1 | 0 | 512 | True |
| Misc.HeapPanicDestroyNonEmpty | Panic when a non-empty heap gets destroyed | 0 | 0 | 0 | 1 | True |
| Misc.HeartbeatInterval | Interval to check CPU lockups | 1000 | 1000 | 100 | 86400000 | True |
| Misc.HeartbeatPanicTimeout | Interval in seconds after which to panic if no heartbeats received | 14 | 900 | 1 | 86400 | True |
| Misc.HeartbeatTimeout | Time-out for sending NMI to the locked CPU | 7 | 90 | 1 | 86400 | True |
| Misc.HordeEnabled | Enables horde mode | 0 | 0 | 0 | 1 | True |
| Misc.IntTimeout | Time-out for interrupt handlers in milliseconds | 0 | 0 | 0 | 5000 | True |
| Misc.IoFilterWatchdogTimeout | Timeout for the I/O filter watchdog in seconds. 0 means the watchdog is disabled. 120 seconds is the minimum timeout value. | 120 | 120 | 0 | 3600 | True |
| Misc.LogPort | Name of serial port to use for logging (COM1, COM2, firewire) | none | none | N/A | N/A | True |
| Misc.LogTimestampUptime | Use uptime rather than UTC for vmkernel log | 0 | 0 | 0 | 1 | True |
| Misc.LogToFile | Send VMkernel log messages to /var/log/vmkernel | 1 | 1 | 0 | 1 | True |
| Misc.LogToSerial | Send VMkernel log messages to the serial port | 1 | 1 | 0 | 1 | True |
| Misc.LogWldPrefix | Include running world on every log statement | 1 | 1 | 0 | 1 | True |
| Misc.MCEMonitorInterval | Interval[0 - 0x7fffffff ms] to check Machine Check Errors(0=never) | 250 | 250 | 0 | 2147483647 | True |
| Misc.MinimalPanic | Do not attempt core dump after purple screen | 0 | 0 | 0 | 1 | True |
| Misc.NMILint1IntAction | Change how a hardware generated NMI should be handled (1=enter debugger, 2=panic) | 0 | 0 | 0 | 3 | True |
| Misc.PowerButton | Action to take on a momentary press of the soft power button (0=ignore, 1=request graceful system shutdown and power-off) | 1 | 1 | 0 | 1 | True |
| Misc.PowerOffEnable | Action to take on system power-off request (0=halt only, 1=power off) | 1 | 1 | 0 | 1 | True |
| Misc.PreferredHostName | Preferred Host name |  |  | N/A | N/A | True |
| Misc.ProcVerbose | Option unused |  |  | N/A | N/A | True |
| Misc.SIOControlFlag1 | Storage I/O Control Internal Flag | 0 | 0 | 0 | 2147483647 | True |
| Misc.SIOControlFlag2 | Storage I/O Control Internal Flag | 0 | 0 | 0 | 2147483647 | True |
| Misc.SIOControlLoglevel | Storage I/O Control Log Level | 0 | 0 | 0 | 7 | True |
| Misc.SIOControlOptions | Storage I/O Control Options |  |  | N/A | N/A | True |
| Misc.ScreenSaverDelay | Delay in minutes before screensaver kicks in | 0 | 0 | 0 | 60 | True |
| Misc.ShaperStatsEnabled | Enable stats in shaper module | 1 | 1 | 0 | 1 | True |
| Misc.ShellPort | Name of serial port to use for visor shell (COM1, COM2, firewire) | none | none | N/A | N/A | True |
| Misc.TimerMaxHardPeriod | Maximum hard timer interrupt period in microseconds | 500000 | 500000 | 100 | 10000000 | True |
| Misc.TimerTolerance | Default timer lateness tolerance in microseconds | 2000 | 2000 | 100 | 1000000 | True |
| Misc.UsbArbitratorAutoStartDisabled | Disable automatic start of USB Arbitrator.  If set USB passthrough will not be available until USB arbitrator is started at the command line. | 0 | 0 | 0 | 1 | True |
| Misc.UserDuctDynBufferSize | Max buffer size for UW duct (bytes) | 16384 | 16384 | 0 | 32768 | True |
| Misc.UserSocketUnixMaxBufferSize | Max buffer size for UW unix domain sockets (bytes) | 65536 | 65536 | 0 | 131072 | True |
| Misc.WatchdogBacktrace | Backtrace on every Nth watchdog | 0 | 0 | 0 | 10 | True |
| Misc.WorldletActivationUS | Number of microseconds a worldlet may execute prior to being asked to yield. | 500 | 500 | 1 | 10000 | True |
| Misc.WorldletActivationsLimit | Number of worldlet activations permissible in each interruption (0==unlimited). | 8 | 8 | 0 | 1000 | True |
| Misc.WorldletGreedySampleMCycles | million cycles between greedy samples, controls greedy sampling rate | 10 | 10 | 1 | 1000 | True |
| Misc.WorldletGreedySampleRun | number of runs between greedy samples, controls greedy sampling rate | 256 | 256 | 16 | 4096 | True |
| Misc.WorldletIRQPenalty | constant load penalty for worldlets driven by interrupts | 10 | 10 | 0 | 200 | True |
| Misc.WorldletLoadThreshold | Worldlet load/score level below which a placement is deemed desirable | 90 | 90 | 0 | 200 | True |
| Misc.WorldletLoadType | Worldlet load type | medium | medium | N/A | N/A | True |
| Misc.WorldletLocalityBonus | load score bonus for keeping a worldlet on it's last PCPU/LLC | 10 | 10 | 0 | 200 | True |
| Misc.WorldletLoosePenalty | load penalty for leaving LOOSE affinity topology level | 30 | 30 | 0 | 200 | True |
| Misc.WorldletMigOverheadLLC | intra-cache worldlet migration overhead, default = 4/1024=0.39% | 4 | 4 | 0 | 1024 | True |
| Misc.WorldletMigOverheadRemote | inter-cache worldlet migration overhead, default = 16/1024=1.56% | 16 | 16 | 0 | 1024 | True |
| Misc.WorldletPreemptOverhead | overhead if worldlet preempts a running no-idle world, in percentage | 30 | 30 | 0 | 100 | True |
| Misc.WorldletRemoteActivateOverhead | remote activate overhead, in cycles | 0 | 0 | 0 | 50000 | True |
| Misc.WorldletWorldOverheadLLC | overhead if worldlet is on the same cache as its affinity world, in cycles | 0 | 0 | 0 | 50000 | True |
| Misc.WorldletWorldOverheadRemote | overhead if worldlet is on different cache as its affinity world, in percentage | 10 | 10 | 0 | 100 | True |
| Misc.vsanWitnessVirtualAppliance | Indicates a VSAN witness host running in a Virtual Appliance. VM services (create/register/power on) are blocked | 0 | 0 | 0 | 1 | True |
| Misc.DsNsMgrTimeout | Timeout for DatastoreNamespaceManager operations in milliseconds | 1200000 | 1200000 | 10000 | 1800000 | False |
| Misc.HostAgentUpdateLevel | The update level of Host Agent. |  | 2 | N/A | N/A | False |
| Misc.MetadataUpdateTimeoutMsec | Timeout for VM MetadataManager operations in milliseconds | 30000 | 30000 | 0 | 600000 | False |
| NFS.ApdStartCount | Number of sequential heartbeat failures after which APD start event is triggered | 3 | 3 | 1 | 5 | True |
| NFS.DiskFileLockUpdateFreq | Time (in seconds) between updates to a disk lock file | 10 | 10 | 8 | 3600 | True |
| NFS.HeartbeatDelta | Time in seconds since the last successful update before a heartbeat is sent | 5 | 5 | 3 | 30 | True |
| NFS.HeartbeatFrequency | Time in seconds between heartbeats | 12 | 12 | 5 | 86400 | True |
| NFS.HeartbeatMaxFailures | Number of sequential failures before a volume is marked down | 10 | 10 | 6 | 10 | True |
| NFS.HeartbeatTimeout | Time in seconds before an outstanding heartbeat is stopped | 5 | 5 | 3 | 30 | True |
| NFS.LockRenewMaxFailureNumber | Number of update failures before a disk file lock is declared stale | 3 | 3 | 1 | 100 | True |
| NFS.LockUpdateTimeout | Time (in seconds) before we abort an outstanding lock update | 5 | 5 | 1 | 8 | True |
| NFS.LogNfsStat3 | Log nfsstat3 code | 0 | 0 | 0 | 1 | True |
| NFS.MaxQueueDepth | Maximum per-Volume queue depth | 4294967295 | 4294967295 | 1 | 4294967295 | True |
| NFS.MaxVolumes | Maximum number of mounted NFS v3 volumes | 8 | 8 | 8 | 256 | True |
| NFS.ReceiveBufferSize | Default size of socket receive buffer (KB) | 256 | 256 | 64 | 512 | True |
| NFS.SendBufferSize | Default size of socket send buffer (KB) | 264 | 264 | 32 | 512 | True |
| NFS.SyncRetries | Number of retries before synchronous IO fails (10 seconds per retry) | 25 | 25 | 3 | 360 | True |
| NFS.VolumeRemountFrequency | Time in seconds before attempting to remount a volume | 30 | 30 | 30 | 3600 | True |
| NFS41.EOSDelay | Request EOS safety delay in seconds | 30 | 30 | 0 | 90 | True |
| NFS41.IOTaskRetry | Synchronous I/O task number of retries | 25 | 25 | 1 | 100 | True |
| NFS41.MaxRead | Maximum read transfer size in bytes (use the smaller of this value and the server advertised value) | 4294967295 | 4294967295 | 256 | 4294967295 | True |
| NFS41.MaxVolumes | Maximum number of mounted NFS v4.1 volumes | 8 | 8 | 8 | 256 | True |
| NFS41.MaxWrite | Maximum write transfer size in bytes (use the smaller of this value and the server advertised value) | 4294967295 | 4294967295 | 256 | 4294967295 | True |
| NFS41.MountTimeout | Mount timeout in seconds | 30 | 30 | 1 | 60 | True |
| NFS41.RecvBufSize | Socket receive buffer size in kilobytes (using default if set to zero) | 1024 | 1024 | 0 | 2048 | True |
| NFS41.SendBufSize | Socket send buffer size in kilobytes (using default if set to zero) | 1024 | 1024 | 0 | 2048 | True |
| Net.AdvertisementDuration | duration of RARP advertisements | 60 | 60 | 0 | 255 | True |
| Net.AllowPT | Whether to enable UPT/NPA | 1 | 1 | 0 | 1 | True |
| Net.BlockGuestBPDU | Block guest sourced BPDU frames | 0 | 0 | 0 | 1 | True |
| Net.CoalesceDefaultOn | Dynamic coalescing on by default | 1 | 1 | 0 | 1 | True |
| Net.CoalesceFavorNoVmmVmkTx | Favor disabling all vmm->vmk tx transitions; boost its score by factor of this/64. | 1 | 1 | 0 | 64 | True |
| Net.CoalesceFineTimeoutCPU | Set which CPU the fine timer will run on | 2 | 2 | 0 | 512 | True |
| Net.CoalesceFineTxTimeout | set the fine coalesce timeout in microseconds | 1000 | 1000 | 1 | 4294967295 | True |
| Net.CoalesceFlexMrq | Whether to dynamically switch on/off multiRxQCalib. | 1 | 1 | 0 | 1 | True |
| Net.CoalesceLowRxRate | No Rx coalescing calibration when the number of pkts Rx per timeout is lower than this number. | 4 | 4 | 0 | 256 | True |
| Net.CoalesceLowTxRate | No tx coalescing calibration when the number of pkts tx per timeout is lower than this number. | 4 | 4 | 0 | 256 | True |
| Net.CoalesceMatchedQs | Whether to use matched TxRxQ-pairs mode when applicable. | 1 | 1 | 0 | 1 | True |
| Net.CoalesceMrqLt | Whether to set a RxQ's coalesce to zero based on per-RxQ Low Traffic. | 1 | 1 | 0 | 1 | True |
| Net.CoalesceMrqMetricAllowTxOnly | Whether to allow's individual RxQ's perf metric to be tx pkt cnt only; if not, it will be tx + rx, or rx only. | 1 | 1 | 0 | 1 | True |
| Net.CoalesceMrqMetricRxOnly | Whether to force individual RxQ's perf metric to be rx pkt cnt only. | 0 | 0 | 0 | 1 | True |
| Net.CoalesceMrqOverallStop | Whether to use overall performance to stop RxQ Calib. | 0 | 0 | 0 | 1 | True |
| Net.CoalesceMrqRatioMetric | Whether Tx perf score is attributed to RxQ according to rxPktCnt ratio. | 1 | 1 | 0 | 1 | True |
| Net.CoalesceMrqTriggerReCalib | Whether to let individual RxQ's perf change trigger re-calib. | 1 | 1 | 0 | 1 | True |
| Net.CoalesceMultiRxQCalib | When not in matched TxRxQ-pairs mode, whether to uses separate RxQ Calib. | 1 | 1 | 0 | 1 | True |
| Net.CoalesceNoVmmVmkTx | Whether to try disable all vmm->vmk tx transitions. | 1 | 1 | 0 | 1 | True |
| Net.CoalesceParams | Set parameters for the default virtual NIC coalescing scheme. |  |  | N/A | N/A | True |
| Net.CoalesceRBCRate | Target event rate for RateBasedCoalescing | 4000 | 4000 | 100 | 100000 | True |
| Net.CoalesceRxLtStopCalib | Whether Rx Low Traffic stops Rx calibration. | 0 | 0 | 0 | 1 | True |
| Net.CoalesceRxQDepthCap | Cap of Rx coalescing size. | 40 | 40 | 0 | 80 | True |
| Net.CoalesceScheme | Set the default virtual NIC coalescing scheme. | rbc | rbc | N/A | N/A | True |
| Net.CoalesceTimeoutType | set the coalesce timeout type: fine(1 ms by default) or coarse (4 ms by default) | 2 | 2 | 1 | 2 | True |
| Net.CoalesceTxAlwaysPoll | Whether always poll Tx at coalesce timeout handler. | 1 | 1 | 0 | 1 | True |
| Net.CoalesceTxQDepthCap | Cap of Tx coalescing size. | 40 | 40 | 0 | 80 | True |
| Net.CoalesceTxTimeout | Set the coalesce time-out in microseconds | 4000 | 4000 | 1 | 4294967295 | True |
| Net.DCBEnable | Enable DCB for FCoE | 1 | 1 | 0 | 1 | True |
| Net.DVFilterBindIpAddress | DVFilter internal communication endpoint |  |  | N/A | N/A | True |
| Net.DVFilterPriorityRdLockEnable | Use priority locking in dvfilter to read lock portsets | 1 | 1 | 0 | 1 | True |
| Net.DVSLargeHeapMaxSize | Max size for the dvsLargeHeap | 80 | 80 | 64 | 256 | True |
| Net.DontOffloadInnerIPv6 | Don't offload inner IPv6 CSO/TSO packets to physical NICs | 0 | 0 | 0 | 1 | True |
| Net.E1000IntrCoalesce | Whether to enable interrupt coalescing for e1000 vNIC. | 1 | 1 | 0 | 1 | True |
| Net.E1000TxCopySize | e1000 tx less than or equal to this will be fully copied with no need for completion. | 2048 | 2048 | 0 | 4294967295 | True |
| Net.E1000TxZeroCopy | Use tx zero copy for non-tso packets for e1000. | 1 | 1 | 0 | 1 | True |
| Net.EnableDMASgCons | When non-zero, enable the DMA SG constraints support in uplink layer | 1 | 1 | 0 | 1 | True |
| Net.EnableOuterCsum | Enable uplink layer outer checksumming | 1 | 1 | 0 | 1 | True |
| Net.EtherswitchAllowFastPath | Allow Etherswitch fast path | 0 | 0 | 0 | 1 | True |
| Net.EtherswitchHashSize | Number of ports on the etherswitch x 2^N is the size of the hash table for looking up MACs | 1 | 1 | 0 | 4 | True |
| Net.EtherswitchHeapMax | The maximum size (in Megabytes) to which the etherswitch heap can grow. (REQUIRES REBOOT!) | 512 | 512 | 86 | 2047 | True |
| Net.EtherswitchNumPerPCPUDispatchData | The dispatch data number in the etherswitch per-pCPU dispatch data cache. (REQUIRES REBOOT!) | 3 | 3 | 3 | 63 | True |
| Net.FollowHardwareMac | If set to 1, the management interface MAC address will update whenever the hardware MAC address changes. | 0 | 1 | 0 | 1 | True |
| Net.GuestIPHack | Enable guest arp inspection IOChain to get IP | 0 | 0 | 0 | 1 | True |
| Net.GuestTxCopyBreak | Transmits smaller than this will be copied rather than mapped | 64 | 64 | 60 | 4294967295 | True |
| Net.IGMPQueries | Number of IGMP Queries to send during after VMotion/Teaming failover | 2 | 2 | 0 | 2 | True |
| Net.IGMPQueryInterval | Interval(in seconds) for IGMP/MLD general query in multicast snooping | 125 | 125 | 32 | 3600 | True |
| Net.IGMPRouterIP | Router IP Address for IGMP (generally not necessary to set this) | 0.0.0.0 | 0.0.0.0 | N/A | N/A | True |
| Net.IGMPV3MaxSrcIPNum | Max per-group srouce IP number for IGMP V3 | 10 | 10 | 1 | 32 | True |
| Net.IGMPVersion | IGMP Version (2 or 3) | 3 | 3 | 2 | 3 | True |
| Net.LRODefBackoffPeriod | After adaptive LRO decided not to do LRO, how many intervals to wait before trying again. | 8 | 8 | 0 | 65535 | True |
| Net.LRODefMaxLength | LRO default max length | 65535 | 65535 | 1 | 65535 | True |
| Net.LRODefThreshold | After this # packets, evaluate whether to continue SW LRO | 4000 | 4000 | 0 | 65535 | True |
| Net.LRODefUseRatioDenom | If SW LRO reduce pkt count to be smaller than ratio, continue to do LRO. Denominator of ratio. | 3 | 3 | 0 | 255 | True |
| Net.LRODefUseRatioNumer | If SW LRO reduce pkt count to be smaller than ratio, continue to do LRO. Numerator of ratio. | 1 | 1 | 0 | 255 | True |
| Net.LinkFlappingThreshold | Max number of link down events per minute before considering a link unstable (0 to deactivate) | 60 | 60 | 0 | 65535 | True |
| Net.LinkStatePollTimeout | Link State poll timer period in milliseconds. | 500 | 500 | 100 | 90000 | True |
| Net.MLDRouterIP | Router IPv6 Address for MLD (generally not necessary to set this) | FE80::FFFF:FFFF:FFFF:FFFF | FE80::FFFF:FFFF:FFFF:FFFF | N/A | N/A | True |
| Net.MLDV2MaxSrcIPNum | Max per-group srouce IP number for MLD V2 | 10 | 10 | 1 | 32 | True |
| Net.MLDVersion | MLD Version (1 or 2) | 2 | 2 | 1 | 2 | True |
| Net.MaxBeaconVlans | maximum number of VLANs to probe with beacons. | 100 | 100 | 0 | 4096 | True |
| Net.MaxBeaconsAtOnce | Maximum number of beacons to send in one beacon cycle | 100 | 100 | 0 | 4096 | True |
| Net.MaxGlobalRxQueueCount | Global max length of rx queues for all virtual ports on a ESX host that support queueing | 100000 | 100000 | 0 | 4294967295 | True |
| Net.MaxNetifTxQueueLen | Maximum length of the Tx queue for the physical NICs | 2000 | 2000 | 1 | 10000 | True |
| Net.MaxPageInQueueLen | Maximum number of paging requests to queue for guest DMA | 75 | 75 | 0 | 500 | True |
| Net.MaxPktRxListQueue | Maximum packet we can queue in rxList | 3500 | 3500 | 0 | 200000 | True |
| Net.MaxPortRxQueueLen | Maximum length of the rx queue for virtual ports whose clients support queuing | 80 | 80 | 1 | 500 | True |
| Net.MinEtherLen | Minimum size ethernet frame to transmit | 60 | 60 | 60 | 1518 | True |
| Net.NcpLlcSap | beacon/color NCP messages created with this SAP (DSAP/SSAP) | 0 | 0 | 0 | 255 | True |
| Net.NetBHRxStormThreshold | Declare Rx Storm after this number of consecutive rx pkt drops during queuing in NetBH rxList. | 320 | 320 | 0 | 200000 | True |
| Net.NetDebugRARPTimerInter | RARP timer will be triggered at this interval. | 30000 | 30000 | 0 | 16777215 | True |
| Net.NetDeferTxCompletion | Whether to defer tx completion to tx worldlet/world. | 1 | 1 | 0 | 1 | True |
| Net.NetDiscUpdateIntrvl | Set interval (in milliseconds) of networking discovery to update the VLAN information | 300 | 300 | 1 | 4294967295 | True |
| Net.NetEnableSwCsumForLro | Whether enable software checksum for LRO | 1 | 1 | 0 | 1 | True |
| Net.NetEsxfwPassOutboundGRE | Whether outbound GRE traffic is passed by ESXi firewall | 1 | 1 | 0 | 1 | True |
| Net.NetInStressTest | If set to 1, suppress certain logs to avoid log spew. | 0 | 0 | 0 | 1 | True |
| Net.NetLatencyAwareness | Whether to check virtual machine's latency settings or not for vmxnet2/3 | 1 | 1 | 0 | 1 | True |
| Net.NetMaxRarpsPerInterval | Max number of RARPs dispatched per timer callback. | 128 | 128 | 1 | 4294967295 | True |
| Net.NetNetqMaxDefQueueFilters | Maximum number of filters for default queue (REQUIRES REBOOT!) | 4096 | 4096 | 4096 | 32678 | True |
| Net.NetNetqNumaIOCpuPinThreshold | CPU threshold for pinning device queues in NUMA I/O | 0 | 0 | 0 | 200 | True |
| Net.NetNetqRxRebalRSSLoadThresholdPerc | Threshold percentage to rebalance RSS(Receive Side Scaling) queue | 10 | 10 | 0 | 100 | True |
| Net.NetNetqTxPackKpps | Max TX queue load (in thousand packet per second) to allow packing on the corresponding RX queue | 300 | 300 | 1 | 10000 | True |
| Net.NetNetqTxUnpackKpps | Threshold (in thousand packet per second) for TX queue load to trigger unpacking of the corresponding RX queue | 600 | 600 | 1 | 10000 | True |
| Net.NetNiocAllowOverCommit | Whether allow NIOC overcommit when a vNIC is in connected state for DVS | 1 | 1 | 0 | 1 | True |
| Net.NetPTMgrWakeupInterval | How often the PTMgr will wakeup and trigger the UPT mode switch in second. | 6 | 6 | 5 | 10 | True |
| Net.NetPktAllocTries | Number of attempts for allocating packet within the page | 5 | 5 | 1 | 10 | True |
| Net.NetPktSlabFreePercentThreshold | Percent of free network memory pool, below which an event is reported. | 2 | 2 | 2 | 50 | True |
| Net.NetPortFlushIterLimit | when input is serialized, this bounds the number of times a thread flushes the deferred list. | 2 | 2 | 0 | 127 | True |
| Net.NetPortFlushPktLimit | when input is serialized, this bounds the number of pkts a thread flushes from the deferred list. | 64 | 64 | 0 | 255 | True |
| Net.NetPortTrackTxRace | if enabled(1), collect statistics on potential tx race between concurrent threads. | 0 | 0 | 0 | 1 | True |
| Net.NetRmDistMacFilter | Activate/Deactivate the MAC filter on distributed NetRM | 1 | 1 | 0 | 1 | True |
| Net.NetRmDistSamplingRate | Sampling rate on distributed NetRM | 0 | 0 | 0 | 10000 | True |
| Net.NetRxCopyInTx | Whether to enable rx copy in tx worldlet/world. | 0 | 0 | 0 | 1 | True |
| Net.NetSchedCoalesceTxUsecs | Maximum number of microseconds the device can delay tx completions | 33 | 33 | 1 | 125 | True |
| Net.NetSchedDefaultResPoolSharesPct | Percent share given to unclassified traffic | 5 | 5 | 1 | 99 | True |
| Net.NetSchedDefaultSchedName | Default networking packet scheduler | fifo | fifo | N/A | N/A | True |
| Net.NetSchedECNEnabled | Enable net scheduler to send congestion notification to switch ports. | 1 | 1 | 0 | 1 | True |
| Net.NetSchedECNThreshold | Percentage queue utilization at which net scheduler will start sending congestion notifications to switch ports. | 70 | 70 | 0 | 100 | True |
| Net.NetSchedHClkLeafQueueDepthPkt | Maximum number of packets each HClk leaf node can hold | 500 | 500 | 1 | 10000 | True |
| Net.NetSchedHClkMQ | Enable multiple hardware queue for hclk netsched | 0 | 0 | 0 | 1 | True |
| Net.NetSchedHClkMaxHwQueue | Maximum number hardware queue that HClock can use | 2 | 2 | 1 | 128 | True |
| Net.NetSchedHeapMaxSizeMB | Size of the netsched subsystem heap in MB | 64 | 64 | 0 | 96 | True |
| Net.NetSchedInFlightMaxBytesDefault | Number of bytes fed to the nic for nics with a normal (1Gbps) linkspeed | 20000 | 20000 | 1500 | 1500000 | True |
| Net.NetSchedInFlightMaxBytesInsane | Number of bytes fed to the nic for nics that don't support tx completion coalescing | 1500000 | 1500000 | 1500 | 1500000 | True |
| Net.NetSchedMaxPktSend | Maximum number of packets that we can send to the driver at a time | 256 | 256 | 100 | 4096 | True |
| Net.NetSchedQoSSchedName | Default networking packet scheduler for QoS | hclk | hclk | N/A | N/A | True |
| Net.NetSchedSpareBasedShares | Enable shares scheduling only on spare bandwidth. Don't bill while doing reservation scheduling | 1 | 1 | 0 | 1 | True |
| Net.NetSendRARPOnPortEnablement | Ensure one RARP is sent immediately when a port is enabled | 1 | 1 | 0 | 1 | True |
| Net.NetShaperQueuePerL3L4Flow | Enable queuing per L3/L4 flow hashing | 1 | 1 | 0 | 1 | True |
| Net.NetSplitRxMode | Whether to enable automatic splitRxMode | 1 | 1 | 0 | 1 | True |
| Net.NetTraceEnable | Enable virtual network tracing | 0 | 0 | 0 | 1 | True |
| Net.NetTuneHostMode | Tuning mode for networking | default | default | N/A | N/A | True |
| Net.NetTuneInterval | Tuning interval in seconds | 60 | 60 | 1 | 3600 | True |
| Net.NetTuneThreshold | Threshold for activating a tuned mode | 1n 2n 50 | 1n 2n 50 | N/A | N/A | True |
| Net.NetTxDontClusterSize | Transmits smaller than this will not be subject to clustering.coalescing | 0 | 0 | 0 | 8192 | True |
| Net.NetVMTxType | Worldlet/world for asynchronous Tx for net devices. 1 for one tx context per vNIC. 2 for one tx context per VM | 2 | 2 | 1 | 3 | True |
| Net.NetVmxnet3TxHangTimeout | Detect tx hang in vmxnet3. | 0 | 0 | 0 | 1 | True |
| Net.NetpollSwLRO | Whether to perform SW LRO on pkts in netPoll | 1 | 1 | 0 | 1 | True |
| Net.NoLocalCSum | Do not checksum local tx.rx frames | 0 | 0 | 0 | 1 | True |
| Net.NotifySwitch | Broadcasts an arp request on net handle enable | 1 | 1 | 0 | 1 | True |
| Net.PTSwitchingTimeout | Timeout (in ms) when asking the VMX/guest to switch in/out of passthru | 20000 | 20000 | 0 | 60000 | True |
| Net.PVRDMAVmknic | Vmknic for PVRDMA |  |  | N/A | N/A | True |
| Net.PortDisableTimeout | Maximum time to wait for ports to complete I/O before disabling | 5000 | 5000 | 0 | 2147483647 | True |
| Net.ReversePathFwdCheck | Block the multicast/broadcast packets that come back from physical switches in a teamed environment | 1 | 1 | 0 | 1 | True |
| Net.ReversePathFwdCheckPromisc | Block duplicate packet in a teamed environment when the virtual switch is set to Promiscuous mode. | 0 | 0 | 0 | 1 | True |
| Net.TcpipCopySmallTx | Copy and tx complete small packets for tcp tx | 1 | 1 | 0 | 1 | True |
| Net.TcpipDefLROEnabled | LRO enabled for TCP/IP | 1 | 1 | 0 | 1 | True |
| Net.TcpipDefLROMaxLength | LRO default max length for TCP/IP | 32768 | 32768 | 1 | 65535 | True |
| Net.TcpipDgramRateLimiting | Enable Tx rate limiting for UDP sockets | 1 | 1 | 0 | 1 | True |
| Net.TcpipEnableABC | Enable Appropriate Byte Counting for TCP (RFC 3465) | 1 | 1 | 0 | 1 | True |
| Net.TcpipEnableFlowtable | Enable route caching through the use of flowtable | 1 | 1 | 0 | 1 | True |
| Net.TcpipEnableSendScaling | Enable Send-Side Scaling (requires RSS) | 1 | 1 | 0 | 1 | True |
| Net.TcpipHWLRONoDelayAck | Delayed ack timer not armed for Hardware LRO (socket option needs to be set in addition). | 1 | 1 | 0 | 1 | True |
| Net.TcpipHeapMax | Max megabytes the tcpip module heap can grow to. (REQUIRES REBOOT!) | 512 | 512 | 32 | 1536 | True |
| Net.TcpipHeapSize | Size of the TCP/IP module heap in megabytes (requires reboot) | 0 | 0 | 0 | 32 | True |
| Net.TcpipIGMPDefaultVersion | Default version of IGMP, in the absence of a querier | 3 | 3 | 1 | 3 | True |
| Net.TcpipIGMPRejoinInterval | Delay in seconds between automatic IGMP rejoins when no querier is present | 60 | 60 | 10 | 3600 | True |
| Net.TcpipLODispatchQueueMaxLen | Max # of pkts queued into the per-protocol queue used for dispatching loopback traffic (REQUIRES REBOOT!) | 128 | 128 | 50 | 512 | True |
| Net.TcpipLRONoDelayAck | Delayed ack timer not armed for LRO | 1 | 1 | 0 | 1 | True |
| Net.TcpipLogPackets | Turns on packet logging for a vmknic on debug builds, in a circular & in-memory buffer (Takes effect during vmknic creation time) | 0 | 0 | 0 | 1 | True |
| Net.TcpipLogPacketsCount | Number of packets to log in the in-memory logger. 24570 packets take up about 1.2 MB, and Tx & Rx use separate buffers. (Takes effect during vmknic creation time) | 24570 | 24570 | 1024 | 49140 | True |
| Net.TcpipMaxNetstackInstances | The maximum number of TCP/IP stack instances that can exist concurrently. If  you increase this number, you must also increase the TcpipHeapSize by about 2.5 MB per instance. Requires rebooting the host. | 48 | 48 | 48 | 513 | True |
| Net.TcpipNoBcopyRx | Avoid bcopy in tcp rx | 1 | 1 | 0 | 1 | True |
| Net.TcpipPendPktSocketFreeTimeout | Time Delay in seconds, for freeing UDP sockets that have pending packets for Tx completion | 300 | 300 | 1 | 300 | True |
| Net.TcpipRxDispatchQueueMaxLen | Max # of pkts queued into a tcpip vmknic by an execution context (applied when vmknic is created) | 2000 | 2000 | 1 | 20000 | True |
| Net.TcpipRxDispatchQueues | Max # of dispatch queues used for RX. For low memory systems, this should be minimum value(REQUIRES REBOOT!) | 1 | 1 | 1 | 8 | True |
| Net.TcpipRxDispatchQuota | Max # of pkts dispatched into the tcpip stack by an execution context | 200 | 200 | 1 | 1000 | True |
| Net.TcpipRxVmknicWorldletAffinityType | Use exact affinity for tcpip input worldlet (Takes hold at port creation time) | 0 | 0 | 0 | 1 | True |
| Net.TcpipTxDispatchQuota | Max # of pkts dispatched from the tcpip stack by an execution context | 100 | 100 | 1 | 1000 | True |
| Net.TcpipTxqBackoffTimeoutMs | Duration (in milli seconds) for which backoff is effective when the tx queue has reached the NET_TCPIP_TXQ_MAX_USAGE_THRESHOLD | 70 | 70 | 20 | 1000 | True |
| Net.TcpipTxqMaxUsageThreshold | Tx queue usage threshold in percent at which to start throttling | 80 | 80 | 50 | 100 | True |
| Net.TeamPolicyUpDelay | Delay (ms) before considering an `uplink up' event relevant | 100 | 100 | 0 | 600000 | True |
| Net.TrafficFilterIpAddress | Alternate DVFilter internal communication endpoint |  |  | N/A | N/A | True |
| Net.TsoDumpPkt | detailed dump of every <n> pkts | 0 | 0 | 0 | 2147483647 | True |
| Net.UplinkAbortDisconnectTimeout | Timeout (ms) waiting for pending calls to finish when disconnecting. | 5000 | 5000 | 1 | 6000000 | True |
| Net.UplinkKillAsyncTimeout | Timeout (ms) waiting for async when world is killed. | 10000 | 10000 | 1 | 6000000 | True |
| Net.UplinkTxQueuesDispEnabled | Enables dispatching of port traffic on multiple tx queues | 1 | 1 | 0 | 1 | True |
| Net.UseHwCsumForIPv6Csum | When non-zero, use pNIC HW_CSUM, if available, as IPv6 csum offload | 1 | 1 | 0 | 1 | True |
| Net.UseHwIPv6Csum | When non-zero, use pNIC HW IPv6 csum offload if available | 1 | 1 | 0 | 1 | True |
| Net.UseHwTSO | When non-zero, use pNIC HW TSO offload if available | 1 | 1 | 0 | 1 | True |
| Net.UseHwTSO6 | When non-zero, use pNIC HW IPv6 TSO offload if available | 1 | 1 | 0 | 1 | True |
| Net.UseLegacyProc | Enable or disable populating legacy entries in /proc/vmware/net | 0 | 0 | 0 | 1 | True |
| Net.UseProc | Populate /proc/vmware/net | 0 | 0 | 0 | 1 | True |
| Net.VLANMTUCheckMode | Set the unicast/broadcast checking mode in VLAN MTU check | 1 | 1 | 0 | 1 | True |
| Net.VmklnxLROEnabled | LRO enabled in vmklinux | 0 | 0 | 0 | 1 | True |
| Net.VmklnxLROMaxAggr | LRO max aggr in vmklinux | 6 | 6 | 0 | 24 | True |
| Net.VmknicDoLroSplit | whether for vmknic LRO avoids aggregating all pkts into a single (> 2 ms) large pkt. | 0 | 0 | 0 | 1 | True |
| Net.VmknicLroSplitBnd | when VmknicDoLroSplit is non-zero, while pktList is larger than this number, lroSplit is not done. | 12 | 12 | 2 | 255 | True |
| Net.Vmxnet2HwLRO | Whether to perform HW LRO on pkts going to a LPD capable vmxnet2 | 1 | 1 | 0 | 1 | True |
| Net.Vmxnet2PinRxBuf | Pin RX buffers for vmxnet2 clients (windows guest only) | 0 | 0 | 0 | 1 | True |
| Net.Vmxnet2SwLRO | Whether to perform SW LRO on pkts going to a LPD capable vmxnet2 | 1 | 1 | 0 | 1 | True |
| Net.Vmxnet3HwLRO | Whether to enable HW LRO on pkts going to a LPD capable vmxnet3 | 1 | 1 | 0 | 1 | True |
| Net.Vmxnet3PageInBound | max # pageIn requests to handle per helper call for vmxnet3. | 32 | 32 | 1 | 1024 | True |
| Net.Vmxnet3RSSHashCache | Enable RSS hash cache. | 1 | 1 | 0 | 1 | True |
| Net.Vmxnet3RxPollBound | max # pkts to receive per timeout for vmxnet3. | 256 | 256 | 0 | 4096 | True |
| Net.Vmxnet3SwLRO | Whether to perform SW LRO on pkts going to a LPD capable vmxnet3 | 1 | 1 | 0 | 1 | True |
| Net.Vmxnet3WinIntrHints | whether intr hints are used for Windows vmxnet3. | 1 | 1 | 0 | 1 | True |
| Net.Vmxnet3usePNICHash | Reuse pnic computed RSS hash. | 0 | 0 | 0 | 1 | True |
| Net.VmxnetBiDirNeedsTsoTx | Need to see Tso Tx to qualify for tsoSplit bidirectional traffic condition. | 1 | 1 | 0 | 1 | True |
| Net.VmxnetBiDirNoTsoSplit | For bidirectional traffic, don't do tsoSplit. | 1 | 1 | 0 | 1 | True |
| Net.VmxnetCopyTxRunLimit | non-Win vmxnet2/3 tx will have at most so many fully copied tx's in a row (65536 and larger means never). | 16 | 16 | 0 | 4294967295 | True |
| Net.VmxnetDoLroSplit | whether for vmxnet LRO avoids aggregating all pkts into a single (> 2 mss) large pkt. | 1 | 1 | 0 | 1 | True |
| Net.VmxnetDoTsoSplit | whether to split TSO pkts before LPD; 1: halved; 3: VmxnetTsoSplitSize; 2: hybrid. | 1 | 1 | 0 | 3 | True |
| Net.VmxnetLROBackoffPeriod | After adaptive LRO decided not to do LRO, how many intervals to wait before trying again. | 8 | 8 | 0 | 65535 | True |
| Net.VmxnetLROMaxLength | LRO default max length for TCP/IP | 32000 | 32000 | 1 | 65535 | True |
| Net.VmxnetLROThreshold | After this # packets, evaluate whether to continue SW LRO | 4000 | 4000 | 0 | 65535 | True |
| Net.VmxnetLROUseRatioDenom | If SW LRO reduce pkt count to be smaller than ratio, continue to do LRO. Denominator of ratio. | 3 | 3 | 0 | 255 | True |
| Net.VmxnetLROUseRatioNumer | If SW LRO reduce pkt count to be smaller than ratio, continue to do LRO. Numerator of ratio. | 2 | 2 | 0 | 255 | True |
| Net.VmxnetLroSplitBnd | when VmxnetDoLroSplit is non-zero, while pktList is larger than this number, lroSplit is not done. | 64 | 64 | 2 | 255 | True |
| Net.VmxnetPromDisableLro | Whether to disable SW LRO when vNIC goes into promiscuous mode. | 1 | 1 | 0 | 1 | True |
| Net.VmxnetSwLROSL | Whether to use ShortLived for vmxnet SW LRO | 1 | 1 | 0 | 1 | True |
| Net.VmxnetTsoSplitBnd | when VmxnetDoTsoSplit is 1 or 2, use targetSize as the tsoSplit threshold if the overall pkt list already has this number of pkts. | 12 | 12 | 2 | 255 | True |
| Net.VmxnetTsoSplitSize | split (byte) size; only used if DoTsoSplit >= 2. | 17500 | 17500 | 1500 | 65535 | True |
| Net.VmxnetTxCopySize | vmxnet tx <= than this will be fully copied with no need for completion. | 256 | 256 | 0 | 4294967295 | True |
| Net.VmxnetWinCopyTxRunLimit | Win vmxnet2/3 tx will have at most so many fully copied tx's in a row (65536 and larger means never). | 65535 | 65535 | 0 | 4294967295 | True |
| Net.VmxnetWinUDPTxFullCopy | whether Windows vmxnet UDP tx is fullCopy. | 1 | 1 | 0 | 2 | True |
| Net.vNicNumDeferredReset | max # normalPkts per poll. | 12 | 12 | 0 | 4096 | True |
| Net.vNicTxPollBound | max # normalPkts per poll. | 192 | 192 | 0 | 4096 | True |
| Net.vmxnetThroughputWeight | How far to favor throughput in vmxnet behavior. | 0 | 0 | 0 | 255 | True |
| Net.IOControlPnicOptOut | List of physical NICs to opt out of network I/O control |  |  | N/A | N/A | False |
| Nmp.NmpPReservationCmdRetryTime | Time (in secs) to retry on transient errors for Persistent reservation commands for MSCS CAB configs | 1 | 1 | 1 | 300 | True |
| Nmp.NmpSatpAluaCmdRetryTime | Time (in secs) to retry on transient errors | 10 | 10 | 0 | 50 | True |
| Numa.CoreCapRatioPct | The capacity of a core in percent. When exceeded, locality migration is rejected. Set to 0 to disable this check | 90 | 90 | 0 | 100 | True |
| Numa.CostopSkewAdjust | way to handle costop skew, 0:do nothing, 1:interleave vcpus among clients, 2:allow vcpus on all nodes | 1 | 1 | 0 | 2 | True |
| Numa.FollowCoresPerSocket | 1: if the vNUMA topology should strickly follow core-per-socket config, 0: to remove the restriction | 0 | 0 | 0 | 1 | True |
| Numa.LTermFairnessInterval | duration of long term fairness interval in terms of NUMA rebalance period, 0 indicates that long term fairness is disabled | 5 | 5 | 0 | 1000 | True |
| Numa.LTermMigImbalThreshold | imbalance in long term owed, in percentage, required to trigger migration for long term fairness | 10 | 10 | 0 | 100 | True |
| Numa.LargeInterleave | Always use large page interleaving; 0 to disable. | 1 | 1 | 0 | 1 | True |
| Numa.LocalityWeightActionAffinity | Benefit of improving action affinity by 1. | 130 | 130 | 0 | 200 | True |
| Numa.LocalityWeightMem | Benefit of improving memory locality by 1 pct. | 1 | 1 | 0 | 100 | True |
| Numa.MigImbalanceThreshold | Minimum percent load imbalance between nodes to trigger migration | 10 | 10 | 1 | 200 | True |
| Numa.MigPreventLTermThresh | long term owed for a VM, in percentage, above which NUMA migration and swaps are disabled for that VM | 0 | 0 | 0 | 100 | True |
| Numa.MigThrashThreshold | Maximum post-migration load imbalance as a percentage of pre-migration imbalance to prevent thrashing | 50 | 50 | 0 | 100 | True |
| Numa.MigThreshold | Minimum percent load balance improvement to allow single migration.swap | 2 | 2 | 0 | 100 | True |
| Numa.MonMigEnable | Allow NUMASched monitor migrations. Set to 1 to enable; set to 0 to disable. | 1 | 1 | 0 | 1 | True |
| Numa.PageMigEnable | Permit NUMASched to manipulate page migration. Set to 1 to enable; set to 0 to disable. | 1 | 1 | 0 | 1 | True |
| Numa.PageMigLinearRun | page migration candidates for linear scan, 0 to disable | 95 | 95 | 0 | 10000 | True |
| Numa.PageMigRandomRun | page migration candidates for random scan, 0 to disable | 5 | 5 | 0 | 10000 | True |
| Numa.PageMigRateMax | max page migration rate | 8000 | 8000 | 0 | 250000 | True |
| Numa.PreferHT | Prefer using HyperThreads on the same NUMA node over full cores on multiple nodes; 0 to disable. | 0 | 0 | 0 | 1 | True |
| Numa.RebalanceCoresNode | Minimum number of cores per node required to enable NUMA rebalancer | 2 | 2 | 1 | 8 | True |
| Numa.RebalanceCoresTotal | Minimum number of total host cores required to enable NUMA rebalancer | 4 | 4 | 1 | 32 | True |
| Numa.RebalanceEnable | Enable or disable NUMA scheduler rebalancer | 1 | 1 | 0 | 1 | True |
| Numa.RebalancePeriod | Frequency of NUMA node rebalancing in milliseconds | 2000 | 2000 | 100 | 60000 | True |
| Numa.SwapConsiderPeriod | time between reconsidering a client for swap, in units of NUMA rebalance period | 15 | 15 | 0 | 10000 | True |
| Numa.SwapInterval | frequency of NUMA node swap rebalancing, in units of NUMA rebalance period | 3 | 3 | 1 | 10000 | True |
| Numa.SwapLoadEnable | Enable or disable virtual machine swaps across nodes to balance CPU load | 1 | 1 | 0 | 1 | True |
| Numa.SwapLocalityEnable | Enable or disable virtual machine swaps across nodes to improve memory locality | 1 | 1 | 0 | 1 | True |
| Numa.SwapMigrateOnly | frequency of NUMA VM migration only considerations, in units of NUMA rebalance period, 0 to disable pure migrations | 2 | 2 | 0 | 100 | True |
| Power.CStateMaxLatency | In Custom policy, avoid a C-state whose latency is larger than this value (us) | 500 | 500 | 0 | 1000000 | True |
| Power.CStatePredictionCoef | In Custom policy, predict non-timer wakeup with error probability p, where CStatePredictionCoef = -ln(1 - p) * (1 << 20) | 110479 | 110479 | 0 | 2000000 | True |
| Power.CStateResidencyCoef | In Custom policy, avoid a C-state whose latency * CStateResidencyCoef > predicted residence time | 5 | 5 | 0 | 1000000 | True |
| Power.ChargeMemoryPct | Percentage of idle power consumed by memory | 20 | 20 | 0 | 100 | True |
| Power.MaxCpuLoad | In Custom policy, CPU utilization threshold below which CPU frequency can be dynamically adjusted | 60 | 60 | 0 | 100 | True |
| Power.MaxFreqPct | In Custom policy, do not use P-states faster than the given percentage of full CPU speed, rounded up to the next available P-state | 100 | 100 | 0 | 100 | True |
| Power.MinFreqPct | In Custom policy, do not use P-states slower than the given percentage of full CPU speed | 0 | 0 | 0 | 100 | True |
| Power.PerfBias | In Custom policy, Performance Energy Bias Hint (Intel-only), where 0-15 specify the exact value, while 16-18 choose an automatically determined value from a preset policy: 16=Low Power, 17=Balanced, 18=High Performance | 17 | 17 | 0 | 18 | True |
| Power.PerfBiasEnable | Use Performance Energy Bias Hint | 1 | 1 | 0 | 1 | True |
| Power.TimerHz | In Custom policy, dynamic power management timer sampling rate | 100 | 100 | 1 | 1000 | True |
| Power.UseCStates | In Custom policy, use ACPI C-states when processor is idle | 1 | 1 | 0 | 1 | True |
| Power.UsePStates | In Custom policy, use ACPI P-states to save power when processor is busy | 1 | 1 | 0 | 1 | True |
| RdmFilter.HbaIsShared | Allow local disks to be RDM candidates for Virtual Machines | False | True | N/A | N/A | False |
| ScratchConfig.ConfiguredScratchLocation | The directory configured to be used for scratch space. Changes will take effect on next reboot. |  |  | N/A | N/A | False |
| ScratchConfig.CurrentScratchLocation | The directory currently being used for scratch space. |  | /tmp/scratch | N/A | N/A | False |
| Scsi.ChangeQErrSetting | Change the QErr value of devices to 0x0. | 1 | 1 | 0 | 1 | True |
| Scsi.CompareLUNNumber | Consider LUN number when determining LUN identity. | 1 | 1 | 0 | 1 | True |
| Scsi.FailVMIOonAPD | Fast fail virtual machine I/Os on APD Timeout. | 0 | 0 | 0 | 1 | True |
| Scsi.LogCmdErrors | Log SCSI Device command errors. | 1 | 1 | 0 | 1 | True |
| Scsi.LogCmdRCErrorsFreq | Number of consecutive RC errors to be seen before logging SCSI Device command. | 0 | 0 | 0 | 4294967295 | True |
| Scsi.LogMPCmdErrors | Log SCSI Multi-path plugin command errors. | 1 | 1 | 0 | 1 | True |
| Scsi.LogScsiAborts | Log SCSI abort errors and success. | 0 | 0 | 0 | 1 | True |
| Scsi.LunCleanupInterval | Timeout for purging stale LUNs. Any LUN which was seen more than the configured number of days ago, will be deleted by the daily cleanup operation | 7 | 7 | 1 | 100 | True |
| Scsi.MaxReserveBacktrace | Log a backtrace if caller exceeds SCSI_MAX_RESERVE_TIME or SCSI_MAX_RESERVE_TOTALTIME (debug only) | 0 | 0 | 0 | 1 | True |
| Scsi.MaxReserveTime | Maximum time (in milliseconds) a system-initiated reservation is normally held | 200 | 200 | 50 | 500 | True |
| Scsi.MaxReserveTotalTime | Maximum time (in msecs) a system-initiated reservation normally takes from issue to release (debug only) | 250 | 250 | 50 | 500 | True |
| Scsi.PassthroughLocking | SCSI passthrough locking | 1 | 1 | 0 | 1 | True |
| Scsi.ReserveBacktrace | Log a backtrace for all Reserve/Release pairs (debug only) | 0 | 0 | 0 | 1 | True |
| Scsi.SCSIEnableDescToFixedConv | Enable or disable conversion of descriptor format sense to fixed for older plugins | 1 | 1 | 0 | 1 | True |
| Scsi.SCSIEnableIOLatencyMsgs | Enable or disable storage latency-related error messages from PSA | 1 | 1 | 0 | 1 | True |
| Scsi.SCSIStrictSPCVersionChecksForPEs | Only LUNs with version >= SCSI_ANSI_SCSI3_SPC4 can be PEs | 0 | 0 | 0 | 1 | True |
| Scsi.SCSITimeout_ReabortTime | Delay (in milliseconds) after a stop due to time-out before the stop is re-issued | 5000 | 5000 | 1 | 99999999 | True |
| Scsi.SCSITimeout_ScanTime | Time (in milliseconds) to sleep between checking for timed-out asynchronous I/O | 1000 | 1000 | 1 | 99999999 | True |
| Scsi.ScanOnDriverLoad | Scan new SCSI buses on device driver load | 1 | 1 | 0 | 1 | True |
| Scsi.ScanSync | Force LU scanning operations to be synchronous if set. | 0 | 0 | 0 | 1 | True |
| Scsi.ScsiRestartStalledQueueLatency | Delay in ms before restarting a stalled queue  | 500 | 500 | 1 | 60000 | True |
| Scsi.ScsiVVolPESNRO | Default schedNumReqOutstanding value for a PE LUN. | 128 | 128 | 32 | 4096 | True |
| Scsi.TimeoutTMThreadExpires | Life in seconds of timeout task mgmt handler thread | 1800 | 1800 | 1 | 86400 | True |
| Scsi.TimeoutTMThreadLatency | Delay in ms before waking up new task mgmt thread  | 2000 | 2000 | 1 | 600000 | True |
| Scsi.TimeoutTMThreadMax | Max number of timeout task-mgmt handler threads | 16 | 16 | 1 | 16 | True |
| Scsi.TimeoutTMThreadMin | Min number of timeout task-mgmt handler threads | 1 | 1 | 1 | 16 | True |
| Scsi.TimeoutTMThreadRetry | Delay in milliseconds before retrying taskmgmt which failed or for which the I/O did not complete | 2000 | 2000 | 1000 | 10000 | True |
| Scsi.TransFailLogPct | Percent of Transient failures seen on Scsi Device that will be logged. | 20 | 20 | 0 | 100 | True |
| Scsi.UseAdaptiveRetries | Use adaptive retries for transient errors. | 1 | 1 | 0 | 1 | True |
| Security.AccountLockFailures | Maximum allowed failed login attempts before locking out a user's account. Zero disables account locking. | 5 | 5 | N/A | N/A | False |
| Security.AccountUnlockTime | Duration in seconds to lock out a user's account after exceeding the maximum allowed failed login attempts. | 900 | 900 | N/A | N/A | False |
| Security.PasswordQualityControl | Raw options for pam_passwdqc PAM module. This value is used as is in PAM's configuration file, so use with caution. | retry=3 min=disabled,disabled,disabled,7,7 | retry=3 min=disabled,disabled,disabled,7,7 | N/A | N/A | False |
| SunRPC.MaxConnPerIP | Max number of TCP/IP connection per IP | 4 | 4 | 1 | 128 | True |
| SunRPC.SendLowat | Send buffer lowat (%) | 25 | 25 | 1 | 100 | True |
| SunRPC.WorldletAffinity | TX Affinity: 0 - Disabled, 1 - Issuing world, 2 - Exact RX worldlet, 3 - Loose RX worldlet | 2 | 2 | 0 | 2 | True |
| SvMotion.SvMotionAvgDisksPerVM | Initial Storage vMotion Heap Size is proportional to this setting | 8 | 8 | 4 | 1024 | True |
| Syslog.global.defaultRotate | Default number of rotated logs to keep. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.global.defaultSize | Default size of logs before rotation, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.global.logDir | Datastore path of directory to output logs to. Reset to default on null. Example: [datastoreName]/logdir |  | [] /scratch/log | N/A | N/A | False |
| Syslog.global.logDirUnique | Place logs in a unique subdirectory of logdir, based on hostname. | False | False | N/A | N/A | False |
| Syslog.global.logHost | The remote host to output logs to. Reset to default on null. Multiple hosts are supported and must be separated with comma (,). Example: udp://hostName1:514, hostName2, ssl://hostName3:1514 |  | 192.168.1.200 | N/A | N/A | False |
| Syslog.loggers.Xorg.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.Xorg.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.auth.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.auth.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.clomd.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.clomd.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.cmmdsTimeMachine.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.cmmdsTimeMachine.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.cmmdsTimeMachineDump.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 20 | N/A | N/A | False |
| Syslog.loggers.cmmdsTimeMachineDump.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 10240 | N/A | N/A | False |
| Syslog.loggers.ddecomd.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.ddecomd.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.dhclient.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.dhclient.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.epd.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.epd.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.esxupdate.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.esxupdate.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.fdm.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.fdm.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.hbrca.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.hbrca.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.hostd-probe.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.hostd-probe.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.hostd.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.hostd.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.hostdCgiServer.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.hostdCgiServer.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.hostprofiletrace.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.hostprofiletrace.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.iofiltervpd.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.iofiltervpd.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.lacp.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.lacp.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.nfcd.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.nfcd.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.osfsd.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.osfsd.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.rabbitmqproxy.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.rabbitmqproxy.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.rhttpproxy.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.rhttpproxy.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.sdrsInjector.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.sdrsInjector.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.shell.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.shell.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.storageRM.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.storageRM.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.swapobjd.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.swapobjd.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.syslog.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.syslog.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.upitd.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.upitd.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.usb.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.usb.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.vitd.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.vitd.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 10240 | N/A | N/A | False |
| Syslog.loggers.vmauthd.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.vmauthd.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.vmkdevmgr.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.vmkdevmgr.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.vmkernel.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.vmkernel.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.vmkeventd.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.vmkeventd.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.vmksummary.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.vmksummary.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.vmkwarning.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.vmkwarning.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.vobd.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.vobd.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.vprobe.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.vprobe.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.vpxa.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.vpxa.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.vsanSoapServer.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.vsanSoapServer.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 5120 | N/A | N/A | False |
| Syslog.loggers.vsanmgmt.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.vsanmgmt.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 10240 | N/A | N/A | False |
| Syslog.loggers.vsansystem.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 10 | N/A | N/A | False |
| Syslog.loggers.vsansystem.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 10240 | N/A | N/A | False |
| Syslog.loggers.vsantraceUrgent.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 8 | N/A | N/A | False |
| Syslog.loggers.vsantraceUrgent.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 1024 | N/A | N/A | False |
| Syslog.loggers.vvold.rotate | Number of rotated logs to keep for this logger. Reset to default on zero. | 0 | 16 | N/A | N/A | False |
| Syslog.loggers.vvold.size | Set size of logs before rotation for this logger, in KiB. Reset to default on zero. | 0 | 8192 | N/A | N/A | False |
| User.PTEDisableNX | Disables the use of NX bit in user pagetable entries | 0 | 0 | 0 | 1 | True |
| User.ReaddirRetries | Maximum number of retries when reading entries from directories | 10 | 10 | 1 | 20 | True |
| UserVars.ActiveDirectoryPreferredDomainControllers | Preferred Domain Controllers for Active Directory |  |  | N/A | N/A | True |
| UserVars.ActiveDirectoryVerifyCAMCertificate | Enable or disable verification of SSL certificate for vSphere Authentication Proxy server | 1 | 1 | 0 | 1 | True |
| UserVars.DcuiTimeOut | An idle time in seconds before DCUI is automatically logged out. Setting 0 disables the timeout. | 600 | 600 | 0 | 86400 | True |
| UserVars.ESXiShellInteractiveTimeOut | Idle time before an interactive shell is automatically logged out (in seconds, 0 disables).  Takes effect only for newly logged in sessions. | 0 | 0 | 0 | 86400 | True |
| UserVars.ESXiShellTimeOut | Time before automatically disabling local and remote shell access (in seconds, 0 disables).  Takes effect after the services are restarted. | 0 | 0 | 0 | 86400 | True |
| UserVars.ESXiVPsAllowedCiphers | ESXi VPs allowed ciphers. List of allowed ciphers to be used by the VPs. Must be in the form accepted by the SSL_CTX_set_cipher_list API. | !aNULL:kECDH+AESGCM:ECDH+AESGCM:RSA+AESGCM:kECDH+AES:ECDH+AES:RSA+AES | !aNULL:kECDH+AESGCM:ECDH+AESGCM:RSA+AESGCM:kECDH+AES:ECDH+AES:RSA+AES | N/A | N/A | True |
| UserVars.ESXiVPsDisabledProtocols | ESXi VPs disabled protocols. Choices are sslv3, tlsv1, tlsv1.1, tlsv1.2. By default sslv3 is disabled. If no protocol is specified, all protocols are enabled. | sslv3 | sslv3 | N/A | N/A | True |
| UserVars.EsximageNetRateLimit | Set the maximum rate, in bytes/sec, for downloading VIBs (0=no limit) | 0 | 0 | 0 | 2147483647 | True |
| UserVars.EsximageNetRetries | Set the number of times to retry in case of failure while downloading VIBs | 10 | 10 | 0 | 1024 | True |
| UserVars.EsximageNetTimeout | Set the timeout in seconds for downloading VIBs (0=no timeout) | 60 | 60 | 0 | 1024 | True |
| UserVars.HostClientCEIPOptIn | Whether or not to opt-in for the Customer Experience Improvement Program in Host Client, 0 for ask, 1 for yes, 2 for no | 0 | 0 | 0 | 2 | True |
| UserVars.HostClientDefaultConsole | The default console to use when clicking on a VM screen shot in Host Client, webmks or vmrc | webmks | webmks | N/A | N/A | True |
| UserVars.HostClientEnableMOTDNotification | Whether or not to enable MOTD notification on login for Host Client | 1 | 1 | 0 | 1 | True |
| UserVars.HostClientEnableVisualEffects | Whether or not to enable visual effects for Host Client | 1 | 1 | 0 | 1 | True |
| UserVars.HostClientSessionTimeout | Default timeout for Host Client sessions in seconds | 900 | 900 | 0 | 7200 | True |
| UserVars.HostClientShowOnlyRecentObjects | Whether or not to show only recent objects in Host Client | 1 | 1 | 0 | 1 | True |
| UserVars.HostClientWelcomeMessage | The welcome message that is displayed when a user logs into the Host Client | Welcome to {{hostname}} | Welcome to {{hostname}} | N/A | N/A | True |
| UserVars.HostdStatsstoreRamdiskSize | Explicitly specify size for the ramdisk hostd uses to store stats (in megabytes, 0 default). Takes effect after hostd service is restarted. | 0 | 0 | 0 | 1024 | True |
| UserVars.ProductLockerLocation | Path to VMware Tools and vSphere Client repository | /locker/packages/6.5.0/ | /locker/packages/6.5.0/ | N/A | N/A | True |
| UserVars.SuppressCoredumpWarning | Do not show warning for disabled or unconfigured coredump target | 0 | 0 | 0 | 1 | True |
| UserVars.SuppressShellWarning | Do not show warning for enabled local and remote shell access | 0 | 1 | 0 | 1 | True |
| UserVars.ToolsRamdisk | Use VMware Tools repository from /tools ramdisk. | 0 | 0 | 0 | 1 | True |
| UserVars.vGhettoSetup | Run vGhetto Guest Customization on Nested ESXi Appliance | 0 | 1 | 0 | 1 | True |
| VFLASH.CacheStatsEnable | Vitual Flash Read Cache statistics enable ? | 1 | 1 | 0 | 1 | True |
| VFLASH.CacheStatsFromVFC | Use cache statistics from virtual Flash Read Cache module ? | 1 | 1 | 0 | 1 | True |
| VFLASH.MaxCacheFileSizeMB | Maximum file size (in MB) of virtual Flash Read supported | 409600 | 409600 | 4 | 409600 | True |
| VFLASH.MaxDiskFileSizeGB | Maximum supported disk size (in GB) with virtual Flash Read Cache configuration | 16384 | 16384 | 0 | 16384 | True |
| VFLASH.MaxHeapSizeMB | Maximum size (in MB) to which the virtual flash heap is allowed to grow | 32 | 32 | 16 | 128 | True |
| VFLASH.MaxResourceGBForVmCache | Maximum supported virtual flash resource (in GB) to be allocated for VM caches | 2048 | 2048 | N/A | N/A | False |
| VFLASH.ResourceUsageThreshold | Threshold (in percentage) of virtual flash resource usage | 80 | 80 | N/A | N/A | False |
| VMFS.UnresolvedVolumeLiveCheck | Enable/disable liveliness check during unresolved volume query. | True | True | N/A | N/A | False |
| VMFS3.EnableBlockDelete | Enable VMFS block delete when UNMAP is issued from guest OS | 0 | 0 | 0 | 1 | True |
| VMFS3.FailVolumeOpenIfAPD | Fail VMFS volume open operation if the underlying device is deemed to be under an all-paths-down condition | 0 | 0 | 0 | 1 | True |
| VMFS3.HardwareAcceleratedLocking | Enable hardware accelerated VMFS locking (requires compliant hardware). Please see http://kb.vmware.com/kb/2094604 before disabling this option | 1 | 1 | 0 | 1 | True |
| VMFS3.LFBCSlabSizeMaxMB | Maximum size (in MB) to which the VMFS affinity manager cluster cache is allowed to grow. | 8 | 8 | 1 | 32 | True |
| VMFS3.MaxAddressableSpaceTB | Maximum size of all open files that VMFS cache will support before eviction mechanisms kick in | 32 | 32 | 32 | 128 | True |
| VMFS3.MaxHeapSizeMB | Maximum size (in MB) to which the VMFS heap is allowed to grow | 256 | 256 | 16 | 256 | True |
| VMFS3.MaxextendedTxnsUsingfs3Heap | Maximum number of extended transactions for which log space can be allocated from VMFS3 heap when the extendedTxnRegion is full | 20 | 20 | 20 | 40 | True |
| VMFS3.MinAddressableSpaceTB | Minimum size of all open files that VMFS cache will support (guaranteed) | 0 | 0 | 0 | 10 | True |
| VMFS3.OpenWithoutJournal | Open file system when out of space for journal allocation, allowing reads and no meta-data updates | 1 | 1 | 0 | 1 | True |
| VMFS3.PBCapMissRatioIntervalSec | Frequency (in seconds) that the Capacity Miss Ratio is computed for the VMFS Pointer Block cache. | 60 | 60 | 1 | 1800 | True |
| VMFS3.StAtExclLockEnd |  Generate Back Trace in FS3_EndIOExclusive | 0 | 0 | 0 | 1 | True |
| VMFS3.UseATSForHBOnVMFS5 | Use ATS for Heartbeat on ATS supported VMFS5 volumes | 1 | 1 | 0 | 1 | True |
| VMkernel.Boot.allowNonNX | Allow booting with NX feature disabled or non present. | False | False | N/A | N/A | False |
| VMkernel.Boot.autoCreateDumpFile | If enabled and if no suitable dump partition or dump file exists, create a dump file. | True | True | N/A | N/A | False |
| VMkernel.Boot.autoPartition | Enable/Disable auto-partitioning of empty local disks. | False | False | N/A | N/A | False |
| VMkernel.Boot.autoPartitionCreateUSBCoreDumpPartition | Enable/Disable auto-partitioning of core dump partition for USB boot devices. Requires that autoPartition is set to TRUE as well. | False | False | N/A | N/A | False |
| VMkernel.Boot.autoPartitionDiskDumpPartitionSize | Disk dump partition size in MB that gets configured during the auto-partition process. | 2560 | 2560 | 0 | 4294967295 | False |
| VMkernel.Boot.bootDeviceRescanTimeout | Boot device rescan timeout (in minutes). | 1 | 1 | N/A | N/A | False |
| VMkernel.Boot.busSpeedMayVary | Allow different APIC timer speeds on different CPUs. | False | False | N/A | N/A | False |
| VMkernel.Boot.cacheFlushImmOnAllHalt | Flush caches immediately if all cores sharing LLC halt (AMD only) | False | False | N/A | N/A | False |
| VMkernel.Boot.checkCPUIDLimit | Refuse to run on CPUID limited cpus. | True | True | N/A | N/A | False |
| VMkernel.Boot.checkPages | Check that free and free-lpage-pool pages are not corrupted. | False | False | N/A | N/A | False |
| VMkernel.Boot.com1_baud | Baud rate for COM1. | 115200 | 115200 | 0 | 4294967295 | False |
| VMkernel.Boot.com2_baud | Baud rate for COM2. | 115200 | 115200 | 0 | 4294967295 | False |
| VMkernel.Boot.coresPerPkg | Number of cores per package that vmkernel should use | 0 | 0 | N/A | N/A | False |
| VMkernel.Boot.debugBreak | Break into debugger during vmkernel initialization. | False | False | N/A | N/A | False |
| VMkernel.Boot.debugLogToSerial | 0=Serial debug logging off, 1=Serial debug logging on, 2=Defer to config option DebugLogToSerial. | 2 | 2 | 0 | 4294967295 | False |
| VMkernel.Boot.disableACSCheck | Bypass ACS capability checks on all PCIE devices | False | False | N/A | N/A | False |
| VMkernel.Boot.disableCFOH | Disable Cache Flush on Halt | False | False | N/A | N/A | False |
| VMkernel.Boot.disableHwrng | Disable hardware random number generator (RDRAND, RDSEED) | False | False | N/A | N/A | False |
| VMkernel.Boot.diskDumpSlotSize | Disk dump slot size in MB. 0 = automatically sized, otherwise requsted size >= 100 MB. | 0 | 0 | 0 | 4294967295 | False |
| VMkernel.Boot.dmaEngineExposeIdentityMapping | Whether to expose whether DMA engines do identity mapping. | True | True | N/A | N/A | False |
| VMkernel.Boot.dmaMapperPolicy | DMA mapping policy to use. | disabled | disabled | N/A | N/A | False |
| VMkernel.Boot.enableACSCheckForRP | Enable ACS capability checks for Root Port | False | False | N/A | N/A | False |
| VMkernel.Boot.execInstalledOnly | Execute only those files that have been installed via a vib package and have not been modified. | False | False | N/A | N/A | False |
| VMkernel.Boot.fsCheck | Run filesystem checks on system partitions. | False | False | N/A | N/A | False |
| VMkernel.Boot.gdbPort | gdb port; com1 or com2 | default | default | N/A | N/A | False |
| VMkernel.Boot.generalCriticalMemory | Pages to reserve as general critical memory | 0 | 0 | 0 | 4294967295 | False |
| VMkernel.Boot.heapCheckTimerInterval | Interval in seconds between heap timer checks | 10 | 10 | 0 | 4294967295 | False |
| VMkernel.Boot.heapFreeOwnerCheck | Check heap ownership on free operations | False | False | N/A | N/A | False |
| VMkernel.Boot.heapFreePoisonByte | Byte pattern used to poison freed memory | 255 | 255 | N/A | N/A | False |
| VMkernel.Boot.heapMetaPoisonByte | Byte pattern used to poison red zones for allocations | 90 | 90 | N/A | N/A | False |
| VMkernel.Boot.heapMetadataProtect | Use poisoned red zones to protect against under/overruns | False | False | N/A | N/A | False |
| VMkernel.Boot.heapMgrTotalVASpaceGB | VA space (in GB) that is allocated by heap manager for all heaps | 512 | 512 | 0 | 4294967295 | False |
| VMkernel.Boot.heapPoisonFreeMem | Poison free memory to catch use after free bugs | False | False | N/A | N/A | False |
| VMkernel.Boot.heapPoisonTimerChecks | Check heap poisoned areas for corruption on regular intervals | False | False | N/A | N/A | False |
| VMkernel.Boot.hyperthreading | Enable hyperthreading if available. | True | True | N/A | N/A | False |
| VMkernel.Boot.ignoreMsrFaults | Ignore general protection faults as a result of rdmsr and wrmsr instructions | False | False | N/A | N/A | False |
| VMkernel.Boot.intrBalancingEnabled | Indicates if interrupt balancing is enabled. | True | True | N/A | N/A | False |
| VMkernel.Boot.ioAbilityChecks | Enforce checking of whether regions can be DMA mapped. | False | False | N/A | N/A | False |
| VMkernel.Boot.iovDisableIR | Disable Interrrupt Remapping in the IOMMU. Not applicable for platforms pre-configured by firmware to use x2APIC (e.g., platforms with > 256 logical processors); for these interrupt remapping is always enabled. | False | False | N/A | N/A | False |
| VMkernel.Boot.ipmiEnabled | Enable IPMI | True | True | N/A | N/A | False |
| VMkernel.Boot.isPerFileSchedModelActive | Enable per file scheduling model on this host | True | True | N/A | N/A | False |
| VMkernel.Boot.leaveWakeGPEsDisabled | Disallow a wake GPE from also being a runtime GPE | True | True | N/A | N/A | False |
| VMkernel.Boot.logPort | Serial port to enable for logging; com1 or com2 | default | default | N/A | N/A | False |
| VMkernel.Boot.maxLogEntries | Size of the kernel log buffer in 256-byte lines. 0=Use default. Min is 1024. Max is 32768. | 0 | 0 | 0 | 4294967295 | False |
| VMkernel.Boot.maxPCPUS | Number of PCPUs vmkernel should use. | 576 | 576 | 0 | 4294967295 | False |
| VMkernel.Boot.maxPCPUsNUMAInterleaving | Enable NUMA-node interleaving of enabled PCPUs. | True | True | N/A | N/A | False |
| VMkernel.Boot.maxVMs | Max number of VMs VMKernel should support. 0 == determine at runtime | 0 | 0 | 0 | 4294967295 | False |
| VMkernel.Boot.memCheckEveryWord | Check every single word when checking mem. | False | False | N/A | N/A | False |
| VMkernel.Boot.memLowReservedMB | Amount of low memory (< 4 GB) which gets reserved. 0 == determine at runtime | 0 | 0 | 0 | 4294967295 | False |
| VMkernel.Boot.memmapMaxEarlyPoisonMemMB | Memory that should be poisoned during early initialization. | 65536 | 65536 | 0 | 4294967295 | False |
| VMkernel.Boot.memmapMaxPhysicalMemMB | Maximum physical memory (in MB) addressable by kernel. | 16777216 | 16777216 | 0 | 4294967295 | False |
| VMkernel.Boot.memmapMaxRAMMB | Maximum conventional memory (RAM) supported on the system. Additional RAM above this limit will not be used by the system. | 12582912 | 12582912 | 0 | 4294967295 | False |
| VMkernel.Boot.microcodeUpdate | Update microcode from boot module if available | True | True | N/A | N/A | False |
| VMkernel.Boot.microcodeUpdateForce | Disable check that microcode update is newer than installed microcode and that both are released versions | False | False | N/A | N/A | False |
| VMkernel.Boot.netCoalesceTimerHdlrPcpu | Pcpu that coalesce timeout handler runs on. | 0 | 0 | 0 | 4294967295 | False |
| VMkernel.Boot.netGPHeapMaxMBPerGB | Maximum MB of the general purpose networking heap to be allocated per GB of physical memory. | 4 | 4 | 0 | 4294967295 | False |
| VMkernel.Boot.netMaxPktsToProcess | Maximum number of packets to process in each invocation packet processing routine | 64 | 64 | 0 | 4294967295 | False |
| VMkernel.Boot.netNetqueueEnabled | Enable/Disable NetQueue support. | True | True | N/A | N/A | False |
| VMkernel.Boot.netPagePoolLimitCap | Maximum number of pages period for the packet page pool. | 98304 | 98304 | 0 | 4294967295 | False |
| VMkernel.Boot.netPagePoolLimitPerGB | Maximum number of pages for the packet page pool per gigabyte. | 5120 | 5120 | 0 | 4294967295 | False |
| VMkernel.Boot.netPagePoolResvCap | Maximum number of pages to reserve for the packet page pool. | 0 | 0 | 0 | 4294967295 | False |
| VMkernel.Boot.netPagePoolResvPerGB | Number of pages to reserve for the packet page pool per gigabyte. | 0 | 0 | 0 | 4294967295 | False |
| VMkernel.Boot.netPktHeapMaxMBPerGB | Maximum MB of low-memory packet heap to be allocated per GB of physical memory. Maximum value for this setting is 512. | 6 | 6 | 0 | 4294967295 | False |
| VMkernel.Boot.netPktHeapMinMBPerGB | Minimum MB of low-memory packet heap to be allocated per GB of physical memory. Maximum value for this setting is 512. | 0 | 0 | 0 | 4294967295 | False |
| VMkernel.Boot.netPktPoolMaxMBPerGB | Maximum MB of networking packet buffer pool to be allocated per GB of physical memory. Maximum value for this setting is 512. Net packet pool maximum per system will be at least 656MB. | 75 | 75 | 0 | 4294967295 | False |
| VMkernel.Boot.netPktPoolMinMBPerGB | Minimum MB of networking packet buffer pool to be allocated per GB of physical memory (multiple of 24) | 0 | 0 | 0 | 4294967295 | False |
| VMkernel.Boot.netPreemptionEnabled | Enable/disable preemption support in overall networking area | False | False | N/A | N/A | False |
| VMkernel.Boot.nmiAction | Action on hardware generated NMI: 0=default (panic, unless changed by advanced config option), 1=enter debugger, 2=panic, 3=log and ignore (not recommended) | 0 | 0 | 0 | 4294967295 | False |
| VMkernel.Boot.numaLatencyRemoteThresholdPct | Maximum measured memory access latency difference (in percent units) between 2 pairs of NUMA nodes for the pairs to be considered equidistant | 10 | 10 | 0 | 4294967295 | False |
| VMkernel.Boot.overrideDuplicateImageDetection | Override duplicate ESXi image detection | False | False | N/A | N/A | False |
| VMkernel.Boot.pciBarAllocPolicy | PCI BAR allocation policy; 0=first-fit, 1=smallest-fit | 0 | 0 | 0 | 4294967295 | False |
| VMkernel.Boot.pcipDisablePciErrReporting | Disable error reporting for PCI passthru devices. | True | True | N/A | N/A | False |
| VMkernel.Boot.poisonMarker | Value used to poison memmap pages | -6148914691236517206 | -6148914691236517206 | -9223372036854775808 | 9223372036854775807 | False |
| VMkernel.Boot.poisonPagePool | Poison memmap pages | False | False | N/A | N/A | False |
| VMkernel.Boot.preferVmklinux | Boost priority of vmklinux drivers to trump native drivers. | False | False | N/A | N/A | False |
| VMkernel.Boot.preventFreePageMapping | Prevent mapping of free pages | False | False | N/A | N/A | False |
| VMkernel.Boot.rdmaRoceIPBasedGidGeneration | Use the new IP-based GID generation for RoCE | True | True | N/A | N/A | False |
| VMkernel.Boot.rtcEnableEFI | Enable UEFI Runtime Services as real time clock | True | True | N/A | N/A | False |
| VMkernel.Boot.rtcEnableLegacy | Enable legacy CMOS device as real time clock | True | True | N/A | N/A | False |
| VMkernel.Boot.rtcEnableTAD | Enable ACPI 5.0 Time and Alarm Device as real time clock | True | True | N/A | N/A | False |
| VMkernel.Boot.scrubIgnoredPages | Check pages that were ignored due to vmbIgnoreStartMPN and vmbIgnoreNumMPNs boot options. | False | False | N/A | N/A | False |
| VMkernel.Boot.scrubMemoryAfterModuleLoad | Check all memory after each module load. This causes booting to be very slow. | False | False | N/A | N/A | False |
| VMkernel.Boot.serialUntrusted | Disable serial port if UART misbehaves. | True | True | N/A | N/A | False |
| VMkernel.Boot.skipPartitioningSsds | If enabled, skip auto-partitioning of empty local SSDs. | False | False | N/A | N/A | False |
| VMkernel.Boot.storageHeapMaxSize | Maximum size in bytes of the main storage heap | 0 | 0 | 0 | 4294967295 | False |
| VMkernel.Boot.storageHeapMinSize | Minimum size in bytes of the main storage heap | 0 | 0 | 0 | 4294967295 | False |
| VMkernel.Boot.storageMaxDevices | Maximum number of supported SCSI devices | 512 | 512 | 0 | 4294967295 | False |
| VMkernel.Boot.storageMaxPaths | Maximum number of supported SCSI paths | 2048 | 2048 | 0 | 4294967295 | False |
| VMkernel.Boot.storageMaxVMsPerDevice | Maximum number of VMs expected to use a given device | 32 | 32 | 0 | 4294967295 | False |
| VMkernel.Boot.terminateVMOnPDL | Terminate virtual machine on permanent loss of storage | False | False | N/A | N/A | False |
| VMkernel.Boot.timerEnableACPI | Enable ACPI PM timer as system reference timer. | True | True | N/A | N/A | False |
| VMkernel.Boot.timerEnableHPET | Enable HPET as system reference timer. | True | True | N/A | N/A | False |
| VMkernel.Boot.timerEnableTSC | Enable TSC as system reference timer. | True | True | N/A | N/A | False |
| VMkernel.Boot.timerForceTSC | Always use TSC as system reference timer. | False | False | N/A | N/A | False |
| VMkernel.Boot.tscSpeedMayVary | Allow different TSC speeds on different CPUs. | False | False | N/A | N/A | False |
| VMkernel.Boot.tty1Port | TTY1 port; com1, com2 ... to enable | default | default | N/A | N/A | False |
| VMkernel.Boot.tty2Port | TTY2 port; com1, com2 ... to enable | default | default | N/A | N/A | False |
| VMkernel.Boot.updateBusIRQ | Allow adding/removing busIRQ information | False | False | N/A | N/A | False |
| VMkernel.Boot.useNUMAInfo | Enable/disable NUMA-ness | True | True | N/A | N/A | False |
| VMkernel.Boot.useReliableMem | System is aware of reliable memory. | True | True | N/A | N/A | False |
| VMkernel.Boot.useSLIT | Use NUMA latency information from the SLIT table if available | True | True | N/A | N/A | False |
| VMkernel.Boot.vmkATKeyboard | Enable VMkernel AT keyboard driver. | False | False | N/A | N/A | False |
| VMkernel.Boot.vmkacEnable | 0=Disabled, 1=Enforcing, 2=Do not enforce, just warn | 1 | 1 | N/A | N/A | False |
| VMkernel.Boot.vtdSuperPages | Enables support for VT-d Super Pages (aka 2MB, 1GB large pages); super-page usage is dependent on this option as well as hardware support. | True | True | N/A | N/A | False |
| VSAN-iSCSI.iscsiPingTimeout | Interval between ping (NOP-Out) requests, in seconds | 5 | 5 | 0 | 60 | True |
| VSAN.AutoTerminateGhostVm | Automatically terminate ghost VM(s) during network partition | 1 | 1 | 0 | 1 | True |
| VSAN.ClomMaxComponentSizeGB | Maximum component size used for new placements | 255 | 255 | 180 | 255 | True |
| VSAN.ClomMaxDiskUsageRepairComps | Percentage disk fullness after which no new repair components can be placed on a given disk | 95 | 95 | 0 | 100 | True |
| VSAN.ClomRebalanceThreshold | Percentage disk fullness after which rebalancing is triggered | 80 | 80 | 0 | 100 | True |
| VSAN.ClomRepairDelay | Minutes to wait for absent components to come back before starting repair | 60 | 60 | 0 | 4294967295 | True |
| VSAN.DedupScope | The default deduplication scope for in all-flash disk group | 0 | 0 | 0 | 3 | True |
| VSAN.DefaultHostDecommissionMode | Default host decommission mode for a given node | ensureAccessibility | ensureAccessibility | N/A | N/A | True |
| VSAN.DomBriefIoTraces | Enables a brief set of per-IO DOM traces for debugging | 0 | 0 | 0 | 1 | True |
| VSAN.DomFullIoTraces | Enables the full set of per-IO DOM traces for debugging | 0 | 0 | 0 | 1 | True |
| VSAN.DomLongOpTraceMS | Trace ops that take more than the specified value in milliseconds | 1000 | 1000 | 0 | 600000 | True |
| VSAN.DomLongOpUrgentTraceMS | Urgent trace ops that take more than the specified value in milliseconds | 10000 | 10000 | 0 | 600000 | True |
| VSAN.ObjectScrubsPerYear | Option to set the scrubbing rate as scrubs-per-year | 1 | 1 | 1 | 52 | True |
| VSAN.PerTraceBandwidthLimit | Max number of traces per second (0 to disable limits) | 0 | 0 | 0 | 1000000 | True |
| VSAN.PerTraceBandwidthLimitPeriodMs | Add BANDWIDTH_LIMIT * PERIOD_MS tokens (traces) every PERIOD_MS. | 10000 | 10000 | 0 | 10000000 | True |
| VSAN.PerTraceMaxRolloverPeriods | Maximum number of periods where unused bandwidth can accumulate | 360 | 360 | 0 | 1000000 | True |
| VSAN.SwapThickProvisionDisabled | Turn off default thick provisioning type for VM swap object and allow user to control the provisioning type using policy. | 0 | 0 | 0 | 1 | True |
| VSAN.TraceEnableCmmds | Enables tracing for VSAN CMMDS and CMMDSResolver components | 1 | 1 | 0 | 1 | True |
| VSAN.TraceEnableDom | Enables tracing for VSAN DOM component | 1 | 1 | 0 | 1 | True |
| VSAN.TraceEnableDomIo | Enables tracing for VSAN DOMIO component | 0 | 0 | 0 | 1 | True |
| VSAN.TraceEnableLchk | Enables LCHK tracing | 1 | 1 | 0 | 1 | True |
| VSAN.TraceEnableLsom | Enables tracing for VSAN LSOM component | 1 | 1 | 0 | 1 | True |
| VSAN.TraceEnablePlog | Enables tracing for VSAN PLOG component | 1 | 1 | 0 | 1 | True |
| VSAN.TraceEnableRdt | Enables tracing for VSAN RDT component | 1 | 1 | 0 | 1 | True |
| VSAN.TraceEnableSsdLog | Enables tracing for VSAN SSDLOG component | 1 | 1 | 0 | 1 | True |
| VSAN.TraceEnableVirsto | Enables tracing for VSAN Virsto component | 1 | 1 | 0 | 1 | True |
| VSAN.TraceEnableVsanSparse | Enables tracing for VsanSparse FDS operations | 1 | 1 | 0 | 1 | True |
| VSAN.TraceEnableVsanSparseIO | Enables tracing for VsanSparse I/O operations | 0 | 0 | 0 | 1 | True |
| VSAN.TraceEnableVsanSparseVerbose | Enables tracing for details of VsanSparse I/O operations | 0 | 0 | 0 | 1 | True |
| VSAN.TraceGlobalBandwidthLimit | Max number of traces per second (0 to disable limits) | 0 | 0 | 0 | 1000000 | True |
| VSAN.TraceGlobalBandwidthLimitPeriodMs | Add BANDWIDTH_LIMIT * PERIOD_MS tokens (traces) every PERIOD_MS. | 10000 | 10000 | 0 | 10000000 | True |
| VSAN.TraceGlobalMaxRolloverPeriods | Maximum number of periods where unused bandwidth can accumulate | 360 | 360 | 0 | 1000000 | True |
| VSAN.VsanSparseCacheOverEvict | Percentage of VsanSparseCacheThreshold to add to eviction | 5 | 5 | 0 | 100 | True |
| VSAN.VsanSparseCacheThreshold | Maximum VsanSparse cache size, in cache entries | 1024 | 1024 | 0 | 4294967295 | True |
| VSAN.VsanSparseEnabled | Enable auto-creation of vsanSparse instead of vmfsSparse redologs, for VSAN 2.0 datastore only. | 1 | 1 | 0 | 1 | True |
| VSAN.VsanSparseHeapSize | Maximum heap size for VsanSparse snapshot consolidation buffers (in KiB) | 65536 | 65536 | 256 | 131072 | True |
| VSAN.VsanSparseMaxExtentsPrefetch | Maximum number of extents to fetch during interrogation | 64 | 64 | 0 | 128 | True |
| VSAN.VsanSparseParallelLookup | Request written extent data from each layer in parallel | 1 | 1 | 0 | 1 | True |
| VSAN.VsanSparseRetainCacheOnSnapshots | Try to retain VsanSparse in-memory cache content when taking VM snapshots | 1 | 1 | 0 | 1 | True |
| VSAN.VsanSparseRetainCacheTTL | Maximum time to retain VsanSparse in-memory cache content between snapshots, in seconds | 20 | 20 | 0 | 3600 | True |
| VSAN.VsanSparseSpeculativePrefetch | Number of bytes to add to each extent interrogation request | 4194304 | 4194304 | 0 | 4294967295 | True |
| Virsto.DiskFormatVersion | Virsto Disk Format version | 5 | 5 | 2 | 5 | True |
| Virsto.Enabled | Use Virsto format for new disks | 1 | 1 | 0 | 1 | True |
| Virsto.FlusherRegistryThreshold | Flusher registry data size threshold (percentage) when metadata flush is forced | 50 | 50 | 10 | 100 | True |
| Virsto.GweFetchExtentsFactor | Multiplier controlling how many on-disk extents fetched based on GWE request size | 3 | 3 | 1 | 10 | True |
| Virsto.InstanceHeapLimit | Heap limit for each Virsto instance (disk) in MB | 130 | 130 | 128 | 4095 | True |
| Virsto.MapBlocksFlushThreshold | A threshold for dirty entries of map block cache when metadata flush is forced (in count of 4KB blocks) | 8192 | 8192 | 16 | 4294967295 | True |
| Virsto.MapBlocksMin | Map block cache minimum for each Virsto instance (in count of 4KB blocks) | 16384 | 16384 | 16 | 4294967295 | True |
| Virsto.MaxMFRetryCount | How many times Virsto metadata flusher retries in case of a transient error. | 3 | 3 | 0 | 4294967295 | True |
| Virsto.MsecBeforeMetaFlush | Force Virsto metadata flush after this many msec | 10000 | 10000 | 0 | 86400000 | True |
| Virsto.RecordsPerFormatWrite | Number of (LSAR) records written per format write operation | 16 | 16 | 1 | 128 | True |
| Virsto.SharedHeapLimit | Shared heap limit for Virsto module in MB | 4 | 4 | 2 | 4095 | True |
| XvMotion.VMFSOptimizations | Enable VMFS-specific IO optimizations | 1 | 1 | 0 | 1 | True |

