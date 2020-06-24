# OIDs

| oid | type | value | description |
|-----|------|-------|-------------|
| compat.ia32.maxdsiz | unsigned long | 536870912 |  |
| compat.ia32.maxssiz | unsigned long | 67108864 |  |
| compat.ia32.maxvmem | unsigned long | 0 |  |
| debug.acpi.batt.batt_sleep_ms | integer | 0 | Sleep during battery status updates to prevent keystroke loss. |
| debug.acpi.ec.burst | integer | 0 | Enable use of burst mode (faster for nearly all systems) |
| debug.acpi.ec.polled | integer | 0 | Force use of polled mode (only if interrupt mode doesn't work) |
| debug.acpi.ec.timeout | integer | 750 | Total time spent waiting for a response (poll+sleep) |
| debug.acpi.enable_debug_objects | integer | 0 | Enable Debug objects |
| debug.acpi.resume_beep | integer | 0 | Beep the PC speaker when resuming |
| debug.acpi.suspend_bounce | integer | 0 | Don't actually suspend, just test devices. |
| debug.adaptive_machine_arch | integer | 1 | Adapt reported machine architecture to the ABI of the binary |
| debug.allow_insane_settime | integer | 0 | do not perform possibly restrictive checks on settime(2) args |
| debug.bigcgs | integer | 0 |  |
| debug.bioq_batchsize | integer | 0 | BIOQ batch size |
| debug.bootverbose | integer | 0 | Control the output of verbose kernel messages |
| debug.clock_do_io | integer | 0 | Trigger one-time IO on RTC clocks; 1=read (and discard), 2=write |
| debug.clock_show_io | integer | 0 | Enable debug printing of RTC clock I/O; 1=reads, 2=writes, 3=both. |
| debug.clocktime | integer | 0 | Enable printing of clocktime debugging |
| debug.collectsnapstats | integer | 0 |  |
| debug.cpufreq.lowest | integer | 0 | Don't provide levels below this frequency. |
| debug.cpufreq.verbose | integer | 0 | Print verbose debugging messages |
| debug.crypto_timing | integer | 0 | Enable/disable crypto timing support |
| debug.debugger_on_panic | integer | 1 | Run debugger on kernel panic |
| debug.debugger_on_trap | integer | 0 | Run debugger on kernel trap before panic |
| debug.devfs_iosize_max_clamp | integer | 1 | Clamp max i/o size to INT_MAX for devices |
| debug.dircheck | integer | 0 |  |
| debug.disablecwd | integer | 0 | Disable the getcwd syscall |
| debug.disablefullpath | integer | 0 | Disable the vn_fullpath function |
| debug.dobkgrdwrite | integer | 1 | Do background writes (honoring the BV_BKGRDWRITE flag)? |
| debug.dopersistence | integer | 0 |  |
| debug.efi_time | integer | 0 |  |
| debug.elf32_legacy_coredump | integer | 0 | include all and only RW pages in core dumps |
| debug.elf64_legacy_coredump | integer | 0 | include all and only RW pages in core dumps |
| debug.fail_point.fill_kinfo_vnode__random_path | string | off |  |
| debug.fail_point.nfscl_force_fileid_warning | string | off |  |
| debug.fail_point.nlm_deny_grant | string | off |  |
| debug.fail_point.sysctl_running | string | off |  |
| debug.fail_point.test_fail_point | string | off |  |
| debug.fdc.debugflags | integer | 0 | Debug flags |
| debug.fdc.fifo | integer | 8 | FIFO threshold setting |
| debug.fdc.retries | integer | 10 | Number of retries to attempt |
| debug.fdc.settle | integer | 0 | Head settling time in sec/hz |
| debug.fdc.spec1 | integer | 175 | Specification byte one (step-rate + head unload) |
| debug.fdc.spec2 | integer | 16 | Specification byte two (head load time + no-dma) |
| debug.fsckcmds | integer | 0 |  |
| debug.hwpstate_verbose | integer | 0 | Debug hwpstate |
| debug.hwpstate_verify | integer | 0 | Verify P-state after setting |
| debug.if_tun_debug | integer | 0 |  |
| debug.iosize_max_clamp | integer | 0 | Clamp max i/o size to INT_MAX |
| debug.ipw | integer | 0 | ipw debug level |
| debug.iwi | integer | 0 | iwi debug level |
| debug.kdb.alt_break_to_debugger | integer | 0 | Enable alternative break to debugger |
| debug.kdb.break_to_debugger | integer | 0 | Enable break to debugger |
| debug.kdb.current | string |  | currently selected KDB backend |
| debug.kdb.enter | integer | 0 | set to enter the debugger |
| debug.kdb.panic | integer | 0 | set to panic the kernel |
| debug.kdb.stack_overflow | integer | 0 | set to cause a stack overflow |
| debug.kdb.trap | integer | 0 | set to cause a page fault via data access |
| debug.kdb.trap_code | integer | 0 | set to cause a page fault via code access |
| debug.lock.delay.restrict_starvation | integer | 0 |  |
| debug.lock.delay.starvation_limit | integer | 131072 |  |
| debug.max_vnlru_free | integer | 10000 | limit on vnode free requests per call to the vnlru_free routine |
| debug.mddebug | integer | 0 | Enable md(4) debug messages |
| debug.minidump | integer | 1 | Enable mini crash dumps |
| debug.mtx.delay_base | integer | 1 |  |
| debug.mtx.delay_max | integer | 512 |  |
| debug.mtx_spin.delay_base | integer | 1 |  |
| debug.mtx_spin.delay_max | integer | 512 |  |
| debug.ncores | integer | 5 | Maximum number of generated process corefiles while using index format |
| debug.nlm_debug | integer | 0 |  |
| debug.obsolete_panic | integer | 0 | Panic when obsolete features are used (0 = never, 1 = if osbolete, 2 = if deprecated) |
| debug.osd | integer | 0 | OSD debug level |
| debug.psm.errsecs | integer | 2 | Number of seconds during which packets will dropped after a sync error |
| debug.psm.errusecs | integer | 0 | Microseconds to add to psmerrsecs |
| debug.psm.hz | integer | 20 | Frequency of the softcallout (in hz) |
| debug.psm.loglevel | integer | 0 | Verbosity level |
| debug.psm.pkterrthresh | integer | 2 | Number of error packets allowed before reinitializing the mouse |
| debug.psm.secs | integer | 0 | Max number of seconds between soft interrupts |
| debug.psm.usecs | integer | 500000 | Microseconds to add to psmsecs |
| debug.rman_debug | integer | 0 | rman debug |
| debug.rush_requests | integer | 0 | Number of times I/O speeded up (rush requests) |
| debug.rwlock.delay_base | integer | 1 |  |
| debug.rwlock.delay_max | integer | 512 |  |
| debug.rwlock.loops | integer | 10000 |  |
| debug.rwlock.retry | integer | 10 |  |
| debug.snapdebug | integer | 0 |  |
| debug.softdep.blk_limit_hit | integer | 0 |  |
| debug.softdep.blk_limit_push | integer | 0 |  |
| debug.softdep.cleanup_blkrequests | integer | 0 |  |
| debug.softdep.cleanup_failures | integer | 0 |  |
| debug.softdep.cleanup_high_delay | integer | 0 |  |
| debug.softdep.cleanup_inorequests | integer | 0 |  |
| debug.softdep.cleanup_retries | integer | 0 |  |
| debug.softdep.direct_blk_ptrs | integer | 0 |  |
| debug.softdep.dir_entry | integer | 0 |  |
| debug.softdep.flushcache | integer | 0 |  |
| debug.softdep.indir_blk_ptrs | integer | 0 |  |
| debug.softdep.inode_bitmap | integer | 0 |  |
| debug.softdep.ino_limit_hit | integer | 0 |  |
| debug.softdep.ino_limit_push | integer | 0 |  |
| debug.softdep.jaddref_rollback | integer | 0 |  |
| debug.softdep.jnewblk_rollback | integer | 0 |  |
| debug.softdep.journal_low | integer | 0 |  |
| debug.softdep.journal_min | integer | 0 |  |
| debug.softdep.journal_wait | integer | 0 |  |
| debug.softdep.jwait_filepage | integer | 0 |  |
| debug.softdep.jwait_freeblks | integer | 0 |  |
| debug.softdep.jwait_inode | integer | 0 |  |
| debug.softdep.jwait_newblk | integer | 0 |  |
| debug.softdep.max_softdeps | integer | 51652 |  |
| debug.softdep.print_threads | integer | 0 | Notify flusher thread start/stop |
| debug.softdep.sync_limit_hit | integer | 0 |  |
| debug.softdep.tickdelay | integer | 2 |  |
| debug.softdep.worklist_push | integer | 0 |  |
| debug.sx.delay_base | integer | 1 |  |
| debug.sx.delay_max | integer | 512 |  |
| debug.sx.loops | unsigned integer | 10000 |  |
| debug.sx.retries | unsigned integer | 10 |  |
| debug.trace_all_panics | uint8_t | 1 | Print stack traces on secondary kernel panics |
| debug.trace_on_panic | integer | 1 | Print stack trace on kernel panic |
| debug.umtx.robust_faults_verbose | integer | 1 |  |
| debug.vfscache | integer | 1 | VFS namecache enabled |
| debug.vm_lowmem | integer | 0 | set to trigger vm_lowmem event with given flags |
| debug.vn_io_fault_enable | integer | 1 | Enable vn_io_fault lock avoidance |
| debug.vn_io_fault_prefault | integer | 0 | Enable vn_io_fault prefaulting |
| debug.vnlru_nowhere | integer | 0 | Number of times the vnlru process ran without success |
| debug.vnode_domainset | string | &lt;NULL&gt; | Default vnode NUMA policy |
| debug.x86bios.call | integer | 0 | Trace far function calls |
| debug.x86bios.int | integer | 0 | Trace software interrupt handlers |
| dev.cpu.0.cx_lowest | string | C1 | lowest Cx sleep state to use |
| dev.em.0.debug | integer | -1 | Debug Information |
| dev.em.0.eee_control | integer | 1 | Disable Energy Efficient Ethernet |
| dev.em.0.fc | integer | 3 | Flow Control |
| dev.em.0.iflib.disable_msix | integer | 0 | disable MSI-X (default 0) |
| dev.em.0.iflib.override_nrxds | string | 0 | list of # of RX descriptors to use, 0 = use default # |
| dev.em.0.iflib.override_nrxqs | uint16_t | 0 | # of rxqs to use, 0 =&gt; use default # |
| dev.em.0.iflib.override_ntxds | string | 0 | list of # of TX descriptors to use, 0 = use default # |
| dev.em.0.iflib.override_ntxqs | uint16_t | 0 | # of txqs to use, 0 =&gt; use default # |
| dev.em.0.iflib.override_qs_enable | uint16_t | 0 | permit #txq != #rxq |
| dev.em.0.iflib.rx_budget | uint16_t | 0 | set the RX budget |
| dev.em.0.iflib.tx_abdicate | uint16_t | 0 | cause TX to abdicate instead of running to completion |
| dev.em.0.itr | integer | 488 | interrupt delay limit in usecs/4 |
| dev.em.0.nvm | integer | -1 | NVM Information |
| dev.em.0.rs_dump | integer | 0 | Dump RS indexes |
| dev.em.0.rx_abs_int_delay | integer | 66 | receive interrupt delay limit in usecs |
| dev.em.0.rx_int_delay | integer | 0 | receive interrupt delay in usecs |
| dev.em.0.tx_abs_int_delay | integer | 66 | transmit interrupt delay limit in usecs |
| dev.em.0.tx_int_delay | integer | 66 | transmit interrupt delay in usecs |
| dev.netmap.admode | integer | 0 | Adapter mode. 0 selects the best option available,1 forces native adapter, 2 forces emulated adapter |
| dev.netmap.bridge_batch | integer | 1024 | Max batch size to be used in the bridge |
| dev.netmap.buf_num | integer | 163840 | Requested number of netmap bufs |
| dev.netmap.buf_size | integer | 2048 | Requested size of netmap bufs |
| dev.netmap.default_pipes | integer | 0 | For compatibility only |
| dev.netmap.fwd | integer | 0 | Force NR_FORWARD mode |
| dev.netmap.generic_hwcsum | integer | 0 | Hardware checksums. 0 to disable checksum generation by the NIC (default),1 to enable checksum generation by the NIC |
| dev.netmap.generic_mit | integer | 100000 | RX notification interval in nanoseconds |
| dev.netmap.generic_rings | integer | 1 | Number of TX/RX queues for emulated netmap adapters |
| dev.netmap.generic_ringsize | integer | 1024 | Number of per-ring slots for emulated netmap mode |
| dev.netmap.iflib_crcstrip | integer | 1 | strip CRC on RX frames |
| dev.netmap.iflib_rx_miss | integer | 0 | potentially missed RX intr |
| dev.netmap.iflib_rx_miss_bufs | integer | 0 | potentially missed RX intr bufs |
| dev.netmap.if_num | integer | 100 | Requested number of netmap ifs |
| dev.netmap.if_size | integer | 1024 | Requested size of netmap ifs |
| dev.netmap.no_pendintr | integer | 1 | Always look for new received packets. |
| dev.netmap.no_timestamp | integer | 0 | no_timestamp |
| dev.netmap.priv_buf_num | integer | 4098 | Default number of private netmap bufs |
| dev.netmap.priv_buf_size | integer | 2048 | Default size of private netmap bufs |
| dev.netmap.priv_if_num | integer | 2 | Default number of private netmap ifs |
| dev.netmap.priv_if_size | integer | 1024 | Default size of private netmap ifs |
| dev.netmap.priv_ring_num | integer | 4 | Default number of private netmap rings |
| dev.netmap.priv_ring_size | integer | 20480 | Default size of private netmap rings |
| dev.netmap.ptnet_vnet_hdr | integer | 1 | Allow ptnet devices to use virtio-net headers |
| dev.netmap.ring_num | integer | 200 | Requested number of netmap rings |
| dev.netmap.ring_size | integer | 36864 | Requested size of netmap rings |
| dev.netmap.txsync_retry | integer | 2 | Number of txsync loops in bridge's flush. |
| dev.netmap.verbose | integer | 0 | Verbose mode |
| hptmv.status | string | RocketRAID 18xx SATA Controller driver Version v1.16 | Get/Set hptmv state |
| hw.acpi.cpu.cx_lowest | string | C1 | Global lowest Cx sleep state to use |
| hw.acpi.disable_on_reboot | integer | 0 | Disable ACPI when rebooting/halting system |
| hw.acpi.handle_reboot | integer | 1 | Use ACPI Reset Register to reboot |
| hw.acpi.lid_switch_state | string | NONE | Lid ACPI sleep state. Set to S3 if you want to suspend your laptop when close the Lid. |
| hw.acpi.power_button_state | string | S5 | Power button ACPI sleep state. |
| hw.acpi.reset_video | integer | 0 | Call the VESA reset BIOS vector on the resume path |
| hw.acpi.s4bios | integer | 0 | S4BIOS mode |
| hw.acpi.sleep_button_state | string | NONE | Sleep button ACPI sleep state. |
| hw.acpi.sleep_delay | integer | 1 | sleep delay in seconds |
| hw.acpi.standby_state | string | NONE |  |
| hw.acpi.suspend_state | string | NONE |  |
| hw.acpi.verbose | integer | 0 | verbose mode |
| hw.an.an_cache_iponly | integer | 1 |  |
| hw.an.an_cache_mcastonly | integer | 0 |  |
| hw.an.an_cache_mode | string | dbm |  |
| hw.an.an_dump | string | off |  |
| hw.ata.ata_dma_check_80pin | integer | 1 | Check for 80pin cable before setting ATA DMA mode |
| hw.ath.anical | integer | 100 | ANI calibration (msecs) |
| hw.ath.bstuck | integer | 4 | max missed beacon xmits before chip reset |
| hw.ath.longcal | integer | 30 | long chip calibration interval (secs) |
| hw.ath.resetcal | integer | 1200 | reset chip calibration results (secs) |
| hw.ath.rxbuf | integer | 512 | rx buffers allocated |
| hw.ath.shortcal | integer | 100 | short chip calibration interval (msecs) |
| hw.ath.txbuf | integer | 512 | tx buffers allocated |
| hw.ath.txbuf_mgmt | integer | 32 | tx (mgmt) buffers allocated |
| hw.broken_txfifo | integer | 0 | UART FIFO has QEMU emulation bug |
| hw.bus.devctl_disable | integer | 0 | devctl disable -- deprecated |
| hw.bus.devctl_queue | integer | 1000 | devctl queue length |
| hw.bus.info | node | Format:N Length:8 Dump:0x0200000003240000... | bus-related data |
| hw.cardbus.cis_debug | integer | 0 | CardBus CIS debug |
| hw.cardbus.debug | integer | 0 | CardBus debug |
| hw.cbb.debug | integer | 0 | Verbose cardbus bridge debugging |
| hw.cbb.start_16_io | unsigned long | 256 | Starting ioport for 16-bit cards |
| hw.cbb.start_32_io | unsigned long | 4096 | Starting ioport for 32-bit cards |
| hw.cbb.start_memory | unsigned long | 2281701376 | Starting address for memory allocations |
| hw.dmar.batch_coalesce | integer | 100 | Number of qi batches between interrupt |
| hw.dmar.timeout | uint64_t | 1000000 | Timeout for command wait, in nanoseconds |
| hw.hn.udpcs_fixup | uint64_t | 0 | # of UDP checksum fixup |
| hw.hn.udpcs_fixup_mtu | integer | 1420 | UDP checksum fixup MTU threshold |
| hw.hn.vf_xpnt_attwait | integer | 2 | Extra wait for transparent VF attach routing; unit |
| hw.hvtimesync.ignore_sync | integer | 0 | Ignore the sync request. |
| hw.hvtimesync.sample_thresh | integer | 100 | Threshold that makes sample request trigger the sync (unit |
| hw.hvtimesync.sample_verbose | integer | 0 | Increase sample request verbosity. |
| hw.ibrs_disable | integer | 1 | Disable Indirect Branch Restricted Speculation |
| hw.intrbalance | integer | 0 | Interrupt auto-balance interval (seconds).  Zero disables. |
| hw.intrs | string | irq0 | interrupt:number @cpu |
| hw.intr_storm_threshold | integer | 1000 | Number of consecutive interrupts before storm protection is enabled |
| hw.kbd.keymap_restrict_change | integer | 0 | restrict ability to change keymap |
| hw.malo.pci.msi_disable | integer | 0 | MSI disabled |
| hw.malo.rxbuf | integer | 256 | rx buffers allocated |
| hw.malo.rxquota | integer | 256 | max rx buffers to process per interrupt |
| hw.malo.txbuf | integer | 256 | tx buffers allocated |
| hw.malo.txcoalesce | integer | 8 | tx buffers to send at once |
| hw.mca.force_scan | integer | 0 | Force an immediate scan for machine checks |
| hw.mca.interval | integer | 3600 | Periodic interval in seconds to scan for machine checks |
| hw.mds_disable | integer | 0 | Microarchitectural Data Sampling Mitigation (0 - off, 1 - on VERW, 2 - on SW, 3 - on AUTO |
| hw.mfi.cmd_timeout | integer | 30 | Command timeout (in seconds) |
| hw.mfi.detect_jbod_change | integer | 1 | Detect a change to a JBOD |
| hw.mfi.event_class | integer | 0 | event message class |
| hw.mfi.event_locale | integer | 65535 | event message locale |
| hw.mfi.polled_cmd_timeout | integer | 60 | Polled command timeout - used for firmware flash etc (in seconds) |
| hw.midi.debug | integer | 0 |  |
| hw.midi.dumpraw | integer | 0 |  |
| hw.midi.instroff | integer | 0 |  |
| hw.midi.seq.debug | integer | 0 |  |
| hw.midi.stat.verbose | integer | 0 |  |
| hw.mmc.debug | integer | 0 | Debug level |
| hw.mwl.rxbuf | integer | 640 | rx buffers allocated |
| hw.mwl.rxdesc | integer | 256 | rx descriptors allocated |
| hw.mwl.rxdmalow | integer | 3 | min free rx buffers before restarting traffic |
| hw.mwl.rxquota | integer | 640 | max rx buffers to process per interrupt |
| hw.mwl.txbuf | integer | 256 | tx buffers allocated |
| hw.mwl.txcoalesce | integer | 8 | tx buffers to send at once |
| hw.nvme.verbose_cmd_dump | uint8_t | 0 | enable verbose command printting when a command fails |
| hw.pccard.cis_debug | integer | 0 | pccard CIS debug |
| hw.pccard.debug | integer | 0 | pccard debug |
| hw.pci.clear_aer_on_attach | integer | 0 | Clear port and device AER state on driver attach |
| hw.pci.do_power_nodriver | integer | 0 | Place a function into D3 state when no driver attaches to it.  0 means disable.  1 means conservatively place devices into D3 state.  2 means aggressively place devices into D3 state.  3 means put absolutely everything in D3 state. |
| hw.pci.do_power_resume | integer | 1 | Transition from D3 -&gt; D0 on resume. |
| hw.pci.do_power_suspend | integer | 1 | Transition from D0 -&gt; D3 on suspend. |
| hw.pci.enable_io_modes | integer | 1 | Enable I/O and memory bits in the config register.  Some BIOSes do not enable these bits correctly.  We'd like to do this all the time, but there are some peripherals that this causes problems with. |
| hw.pci.enable_msi | integer | 1 | Enable support for MSI interrupts |
| hw.pci.enable_msix | integer | 1 | Enable support for MSI-X interrupts |
| hw.pci.iov_max_config | unsigned long | 1048576 | Maximum allowed size of SR-IOV configuration. |
| hw.pci.msix_rewrite_table | integer | 0 | Rewrite entire MSI-X table when updating MSI-X entries |
| hw.pci.realloc_bars | integer | 0 | Attempt to allocate a new range for any BARs whose original firmware-assigned ranges fail to allocate during the initial device scan. |
| hw.psm.tap_enabled | integer | -1 | Enable tap and drag gestures |
| hw.psm.tap_threshold | integer | 25 | Button tap threshold |
| hw.psm.tap_timeout | integer | 125000 | Tap timeout for touchpads |
| hw.sdhci.debug | integer | 0 | Debug level |
| hw.sdhci.quirk_clear | integer | 0 | Mask of quirks to clear |
| hw.sdhci.quirk_set | integer | 0 | Mask of quirks to set |
| hw.snd.basename_clone | integer | 1 | DSP basename cloning (0 |
| hw.snd.compat_linux_mmap | integer | 0 | linux mmap compatibility (-1=force disable 0=auto 1=force enable) |
| hw.snd.default_auto | integer | -1 | assign default unit to a newly attached device |
| hw.snd.default_unit | integer | -1 | default sound device |
| hw.snd.feeder_eq_exact_rate | integer | 0 | force exact rate validation |
| hw.snd.feeder_rate_max | integer | 2016000 | maximum allowable rate |
| hw.snd.feeder_rate_min | integer | 1 | minimum allowable rate |
| hw.snd.feeder_rate_polyphase_max | integer | 183040 | maximum allowable polyphase entries |
| hw.snd.feeder_rate_quality | integer | 1 | sample rate converter quality (0=low .. 4=high) |
| hw.snd.feeder_rate_round | integer | 25 | sample rate converter rounding threshold |
| hw.snd.latency | integer | 2 | buffering latency (0=low ... 10=high) |
| hw.snd.latency_profile | integer | 1 | buffering latency profile (0=aggressive 1=safe) |
| hw.snd.maxautovchans | integer | 16 | maximum virtual channel |
| hw.snd.report_soft_formats | integer | 1 | report software-emulated formats |
| hw.snd.report_soft_matrix | integer | 1 | report software-emulated channel matrixing |
| hw.snd.syncdelay | integer | -1 | append (0-1000) millisecond trailing buffer delay on each sync |
| hw.snd.timeout | integer | 5 | interrupt timeout (1 - 10) seconds |
| hw.snd.usefrags | integer | 0 | prefer setfragments() over setblocksize() |
| hw.snd.verbose | integer | 0 | verbosity level |
| hw.snd.vpc_0db | integer | 45 | 0db relative level |
| hw.snd.vpc_autoreset | integer | 1 | automatically reset channels volume to 0db |
| hw.snd.vpc_mixer_bypass | integer | 1 | control channel pcm/rec volume, bypassing real mixer device |
| hw.snd.vpc_reset | integer | 0 | reset volume on all channels |
| hw.spec_store_bypass_disable | integer | 0 | Speculative Store Bypass Disable (0 - off, 1 - on, 2 - auto |
| hw.storvsc.use_win8ext_flags | unsigned integer | 1 | Use win8 extension flags or not |
| hw.syscons.bell | integer | 1 | enable bell |
| hw.syscons.kbd_debug | integer | 1 | enable keyboard debug |
| hw.syscons.kbd_reboot | integer | 1 | enable keyboard reboot |
| hw.syscons.saver.keybonly | integer | 1 | screen saver interrupted by input only |
| hw.syscons.sc_no_suspend_vtswitch | integer | 0 | Disable VT switch before suspend. |
| hw.usb.ctrl.debug | integer | 0 | Debug level |
| hw.usb.debug | integer | 0 | Debug level |
| hw.usb.dev.debug | integer | 0 | Debug Level |
| hw.usb.disable_enumeration | integer | 0 | Set to disable all USB device enumeration. This can secure against USB devices turning evil, for example a USB memory stick becoming a USB keyboard. |
| hw.usb.disable_port_power | integer | 0 | Set to disable all USB port power. |
| hw.usb.ehci.debug | integer | 0 | Debug level |
| hw.usb.ehci.iaadbug | integer | 0 | Enable doorbell bug workaround |
| hw.usb.ehci.lostintrbug | integer | 0 | Enable lost interrupt bug workaround |
| hw.usb.ehci.no_hs | integer | 0 | Disable High Speed USB |
| hw.usb.full_ddesc | integer | 0 | USB always read complete device descriptor, if set |
| hw.usb.no_cs_fail | integer | 0 | USB clear stall failures are ignored, if set |
| hw.usb.no_shutdown_wait | integer | 0 | No USB device waiting at system shutdown. |
| hw.usb.no_suspend_wait | integer | 0 | No USB device waiting at system suspend. |
| hw.usb.ohci.debug | integer | 0 | ohci debug level |
| hw.usb.power_timeout | integer | 30 | USB power timeout |
| hw.usb.proc.debug | integer | 0 | Debug level |
| hw.usb.template | integer | -1 | Selected USB device side template |
| hw.usb.timings.extra_power_up_time | unsigned integer | 20 | Extra PowerUp Time |
| hw.usb.timings.port_powerup_delay | unsigned integer | 300 | Port PowerUp Delay |
| hw.usb.timings.port_reset_delay | unsigned integer | 50 | Port Reset Delay |
| hw.usb.timings.port_reset_recovery | unsigned integer | 250 | Port Reset Recovery |
| hw.usb.timings.port_resume_delay | unsigned integer | 40 | Port Resume Delay |
| hw.usb.timings.port_root_reset_delay | unsigned integer | 200 | Root Port Reset Delay |
| hw.usb.timings.resume_delay | unsigned integer | 250 | Resume Delay |
| hw.usb.timings.resume_recovery | unsigned integer | 50 | Resume Recovery |
| hw.usb.timings.resume_wait | unsigned integer | 50 | Resume Wait |
| hw.usb.timings.set_address_settle | unsigned integer | 10 | Set Address Settle |
| hw.usb.ugen.debug | integer | 0 | Debug level |
| hw.usb.uhci.debug | integer | 0 | uhci debug level |
| hw.usb.uhci.loop | integer | 0 | uhci noloop |
| hw.usb.uhub.debug | integer | 0 | Debug level |
| hw.usb.ukbd.debug | integer | 0 | Debug level |
| hw.usb.ukbd.no_leds | integer | 0 | Disables setting of keyboard leds |
| hw.usb.ukbd.pollrate | integer | 0 | Force this polling rate, 1-1000Hz |
| hw.usb.umass.debug | integer | 0 | umass debug level |
| hw.usb.umass.throttle | integer | 0 | Forced delay between commands in milliseconds |
| hw.usb.usb_lang_id | integer | 9 | Preferred USB language ID |
| hw.usb.usb_lang_mask | integer | 255 | Preferred USB language mask |
| hw.usb.xhci.ctlstep | integer | 0 | Set to enable control endpoint status stage stepping |
| hw.usb.xhci.debug | integer | 0 | Debug level |
| hw.usb.xhci.dma32 | integer | 0 | Set to only use 32-bit DMA for the XHCI controller |
| hw.usb.xhci.streams | integer | 0 | Set to enable streams mode support |
| hw.usb.xhci.use_polling | integer | 0 | Set to enable software interrupt polling for the XHCI controller |
| hw.usb.xhci.xhci_port_route | integer | 0 | Routing bitmap for switching EHCI ports to the XHCI controller |
| hw.wi.debug | integer | 0 | control debugging printfs |
| hw.wi.txerate | integer | 0 | max tx error msgs/sec; 0 to disable msgs |
| kern.acct_chkfreq | integer | 15 | frequency for checking the free space |
| kern.acct_resume | integer | 4 | percentage of free disk space above which accounting resumes |
| kern.acct_suspend | integer | 2 | percentage of free disk space below which accounting stops |
| kern.always_console_output | integer | 0 | Always output to console despite TIOCCONS |
| kern.bootfile | string | /boot/kernel/kernel | Name of kernel file booted |
| kern.callout_stat | integer | 0 | Dump immediate statistic snapshot of the scheduled callouts |
| kern.cam.ada.0.delete_method | string | NONE | BIO_DELETE execution method |
| kern.cam.ada.0.read_ahead | integer | -1 | Enable disk read ahead. |
| kern.cam.ada.0.sort_io_queue | integer | -1 | Sort IO queue to try and optimise disk access patterns |
| kern.cam.ada.0.write_cache | integer | -1 | Enable disk write cache. |
| kern.cam.ada.default_timeout | integer | 30 | Normal I/O timeout (in seconds) |
| kern.cam.ada.read_ahead | integer | 1 | Enable disk read-ahead |
| kern.cam.ada.retry_count | integer | 4 | Normal I/O retry count |
| kern.cam.ada.send_ordered | integer | 1 | Send Ordered Tags |
| kern.cam.ada.spindown_shutdown | integer | 1 | Spin down upon shutdown |
| kern.cam.ada.spindown_suspend | integer | 1 | Spin down upon suspend |
| kern.cam.ada.write_cache | integer | 1 | Enable disk write cache |
| kern.cam.announce_nosbuf | integer | 0 | Don't use sbuf for announcements |
| kern.cam.cam_srch_hi | integer | 0 | allow search above LUN 7 for SCSI3 and greater devices |
| kern.cam.cd.poll_period | integer | 3 | Media polling period in seconds |
| kern.cam.cd.retry_count | integer | 4 | Normal I/O retry count |
| kern.cam.cd.timeout | integer | 30000 | Timeout, in us, for read operations |
| kern.cam.da.default_softtimeout | unsigned integer | 0 | Soft I/O timeout (ms) |
| kern.cam.da.default_timeout | integer | 60 | Normal I/O timeout (in seconds) |
| kern.cam.da.disable_wp_detection | integer | 0 | Disable detection of write-protected disks |
| kern.cam.da.poll_period | integer | 3 | Media polling period in seconds |
| kern.cam.da.retry_count | integer | 4 | Normal I/O retry count |
| kern.cam.da.send_ordered | integer | 1 | Send Ordered Tags |
| kern.cam.debug_delay | unsigned integer | 0 | Delay in us after each debug message |
| kern.cam.dflags | unsigned integer | 0 | Enabled debug flags |
| kern.cam.enc.emulate_array_devices | integer | 1 | Emulate Array Devices for SAF-TE |
| kern.cam.enc.verbose | integer | 0 | Enable verbose logging |
| kern.cam.mapmem_thresh | unsigned integer | 65536 | Threshold for user-space buffer mapping |
| kern.cam.pmp.default_timeout | integer | 30 | Normal I/O timeout (in seconds) |
| kern.cam.pmp.hide_special | integer | 1 | Hide extra ports |
| kern.cam.pmp.retry_count | integer | 1 | Normal I/O retry count |
| kern.cam.scsi_delay | integer | 5000 | Delay to allow devices to settle after a SCSI bus reset (ms) |
| kern.cam.sort_io_queues | integer | 1 | Sort IO queues to try and optimise disk access patterns |
| kern.capmode_coredump | integer | 0 | Allow processes in capability mode to dump core |
| kern.chroot_allow_open_directories | integer | 1 | Allow a process to chroot(2) if it has a directory open |
| kern.compress_user_cores | integer | 0 | Enable compression of user corefiles (1 = gzip, 2 = zstd) |
| kern.compress_user_cores_level | integer | 6 | Corefile compression level |
| kern.consmsgbuf_size | integer | 8192 | Console tty buffer size |
| kern.consmute | integer | 0 | State of the console muting |
| kern.console | string | ttyv0,/ttyv0, | Console device control |
| kern.constty_wakeups_per_second | integer | 5 | Times per second to check for pending console tty messages |
| kern.coredump | integer | 1 | Enable/Disable coredumps |
| kern.coredump_devctl | integer | 0 | Generate a devctl notification when processes coredump |
| kern.coredump_pack_fileinfo | integer | 1 | Enable file path packing in 'procstat -f' coredump notes |
| kern.coredump_pack_vmmapinfo | integer | 1 | Enable file path packing in 'procstat -v' coredump notes |
| kern.corefile | string | %N.core | Process corefile name format string |
| kern.cryptodevallowsoft | integer | 0 | Enable/disable use of software crypto by /dev/crypto |
| kern.crypto_stats | opaque | Format:S,cryptostats Length:256 Dump:0x00000000000000000000000000000000... | Crypto system statistics |
| kern.dfldsiz | unsigned long | 34359738368 | Initial data size limit |
| kern.dflssiz | unsigned long | 8388608 | Initial stack size limit |
| kern.dirdelay | integer | 29 | Time to delay syncing directories (in seconds) |
| kern.disallow_high_osrel | integer | 0 | Disallow execution of binaries built for higher version of the world |
| kern.domainname | string |  | Name of the current YP/NIS domain |
| kern.dummy | integer | 0 |  |
| kern.elf32.aslr.enable | integer | 0 | ELF32 |
| kern.elf32.aslr.honor_sbrk | integer | 1 | ELF32 |
| kern.elf32.aslr.pie_enable | integer | 0 | ELF32 |
| kern.elf32.aslr.stack_gap | integer | 3 | ELF32 |
| kern.elf32.fallback_brand | integer | -1 | ELF32 brand of last resort |
| kern.elf32.nxstack | integer | 1 | ELF32 |
| kern.elf32.read_exec | integer | 0 | enable execution from readable segments |
| kern.elf64.aslr.enable | integer | 0 | ELF64 |
| kern.elf64.aslr.honor_sbrk | integer | 1 | ELF64 |
| kern.elf64.aslr.pie_enable | integer | 0 | ELF64 |
| kern.elf64.aslr.stack_gap | integer | 3 | ELF64 |
| kern.elf64.fallback_brand | integer | -1 | ELF64 brand of last resort |
| kern.elf64.nxstack | integer | 1 | ELF64 |
| kern.epoch.stats.epoch_calls | uint64_t | 98 | # of times a callback was deferred |
| kern.epoch.stats.epoch_call_tasks | uint64_t | 31 | # of times a callback task was run |
| kern.epoch.stats.migrations | uint64_t | 0 | # of times thread was migrated to another CPU in epoch_wait |
| kern.epoch.stats.nblocked | uint64_t | 0 | # of times a thread was in an epoch when epoch_wait was called |
| kern.epoch.stats.ncontended | uint64_t | 0 | # of times a thread was blocked on a lock in an epoch during an epoch_wait |
| kern.epoch.stats.switches | uint64_t | 0 | # of times a thread voluntarily context switched in epoch_wait |
| kern.evdev.rcpt_mask | integer | 3 | Who is receiving events |
| kern.evdev.sysmouse_t_axis | integer | 0 | Extract T-axis from 0-none, 1-ums, 2-psm |
| kern.eventtimer.idletick | unsigned integer | 0 | Run periodic events when idle |
| kern.eventtimer.periodic | integer | 0 | Enable event timer periodic mode |
| kern.eventtimer.singlemul | integer | 4 | Multiplier for periodic mode |
| kern.eventtimer.timer | string | LAPIC | Chosen event timer |
| kern.fallback_elf_brand | integer | -1 | compatibility for kern.fallback_elf_brand |
| kern.filedelay | integer | 30 | Time to delay syncing files (in seconds) |
| kern.forcesigexit | integer | 1 | Force trap signal to be handled |
| kern.geom.collectstats | integer | 1 | Control statistics collection on GEOM providers and consumers |
| kern.geom.debugflags | integer | 0 | Set various trace levels for GEOM debugging |
| kern.geom.dev.delete_max_sectors | int64_t | 262144 | Maximum number of sectors in a single delete request sent to the provider. Larger requests are chunked so they can be interrupted. (0 = disable chunking) |
| kern.geom.disk.ada0.led | string |  | LED name |
| kern.geom.label.debug | unsigned integer | 0 | Debug level |
| kern.geom.label.disk_ident.enable | integer | 0 | Create device nodes for drives which export a disk identification string |
| kern.geom.label.ext2fs.enable | integer | 1 | Create device nodes for EXT2FS volumes |
| kern.geom.label.flashmap.enable | integer | 1 | Create device nodes for Flashmap labels |
| kern.geom.label.gpt.enable | integer | 1 | Create device nodes for GPT labels |
| kern.geom.label.gptid.enable | integer | 0 | Create device nodes for GPT UUIDs |
| kern.geom.label.iso9660.enable | integer | 1 | Create device nodes for ISO9660 volume names |
| kern.geom.label.msdosfs.enable | integer | 1 | Create device nodes for MSDOSFS volumes |
| kern.geom.label.ntfs.enable | integer | 1 | Create device nodes for NTFS volumes |
| kern.geom.label.reiserfs.enable | integer | 1 | Create device nodes for REISERFS volumes |
| kern.geom.label.ufs.enable | integer | 1 | Create device nodes for UFS volume names |
| kern.geom.label.ufsid.enable | integer | 1 | Create device nodes for UFS file system IDs |
| kern.geom.notaste | integer | 0 | Prevent GEOM tasting |
| kern.geom.part.allow_nesting | unsigned integer | 0 | Allow additional levels of nesting |
| kern.geom.part.auto_resize | unsigned integer | 1 | Enable auto resize |
| kern.geom.part.check_integrity | unsigned integer | 1 | Enable integrity checking |
| kern.geom.part.gpt.allow_nesting | unsigned integer | 0 | Allow GPT to be nested inside other schemes |
| kern.geom.part.mbr.enforce_chs | unsigned integer | 0 | Enforce alignment to CHS addressing |
| kern.geom.raid.aggressive_spare | unsigned integer | 0 | Use disks without metadata as spare |
| kern.geom.raid.clean_time | unsigned integer | 5 | Mark volume as clean when idling |
| kern.geom.raid.concat.enable | integer | 1 | Enable CONCAT transformation module taste |
| kern.geom.raid.ddf.enable | integer | 1 | Enable DDF metadata format taste |
| kern.geom.raid.debug | unsigned integer | 0 | Debug level |
| kern.geom.raid.disconnect_on_failure | unsigned integer | 1 | Disconnect component on I/O failure. |
| kern.geom.raid.enable | integer | 1 | Enable on-disk metadata taste |
| kern.geom.raid.idle_threshold | unsigned integer | 1000000 | Time in microseconds to consider a volume idle. |
| kern.geom.raid.intel.enable | integer | 1 | Enable Intel metadata format taste |
| kern.geom.raid.jmicron.enable | integer | 1 | Enable JMicron metadata format taste |
| kern.geom.raid.name_format | unsigned integer | 0 | Providers name format. |
| kern.geom.raid.nvidia.enable | integer | 1 | Enable NVIDIA metadata format taste |
| kern.geom.raid.promise.enable | integer | 1 | Enable Promise metadata format taste |
| kern.geom.raid.raid0.enable | integer | 1 | Enable RAID0 transformation module taste |
| kern.geom.raid.raid1e.enable | integer | 1 | Enable RAID1E transformation module taste |
| kern.geom.raid.raid1.enable | integer | 1 | Enable RAID1 transformation module taste |
| kern.geom.raid.raid1e.rebuild_cluster_idle | unsigned integer | 100 | Number of slabs to do each time we trigger a rebuild cycle |
| kern.geom.raid.raid1e.rebuild_fair_io | unsigned integer | 20 | Fraction of the I/O bandwidth to use when disk busy for rebuild. |
| kern.geom.raid.raid1e.rebuild_meta_update | unsigned integer | 1024 | When to update the meta data. |
| kern.geom.raid.raid1e.rebuild_slab_size | unsigned integer | 1048576 | Amount of the disk to rebuild each read/write cycle of the rebuild. |
| kern.geom.raid.raid1.rebuild_cluster_idle | unsigned integer | 100 | Number of slabs to do each time we trigger a rebuild cycle |
| kern.geom.raid.raid1.rebuild_fair_io | unsigned integer | 20 | Fraction of the I/O bandwidth to use when disk busy for rebuild. |
| kern.geom.raid.raid1.rebuild_meta_update | unsigned integer | 1024 | When to update the meta data. |
| kern.geom.raid.raid1.rebuild_slab_size | unsigned integer | 1048576 | Amount of the disk to rebuild each read/write cycle of the rebuild. |
| kern.geom.raid.raid5.enable | integer | 1 | Enable RAID5 transformation module taste |
| kern.geom.raid.read_err_thresh | unsigned integer | 10 | Number of read errors equated to disk failure |
| kern.geom.raid.sii.enable | integer | 1 | Enable SiI metadata format taste |
| kern.geom.raid.start_timeout | unsigned integer | 30 | Time to wait for all array components |
| kern.geom.transient_map_retries | unsigned integer | 10 | Max count of retries used before giving up on creating transient map |
| kern.hostid | unsigned long | 976342924 | Host ID |
| kern.hostname | string |  | Hostname |
| kern.hostuuid | string | 617e3893-9d2f-1641-b908-ef3b0d7ce0cd | Host UUID |
| kern.init_shutdown_timeout | integer | 120 | Shutdown timeout of init(8). Unused within kernel, but used to control init(8) |
| kern.ipc.aio.lifetime | integer | 3000 | Maximum lifetime for idle aiod |
| kern.ipc.aio.max_procs | integer | 32 | Maximum number of kernel processes to use for async socket IO |
| kern.ipc.maxsockbuf | unsigned long | 2097152 | Maximum socket buffer size |
| kern.ipc.maxsockets | integer | 15028 | Maximum number of sockets available |
| kern.ipc.nmbclusters | integer | 12800 | Maximum number of mbuf clusters allowed |
| kern.ipc.nmbjumbo16 | integer | 1066 | Maximum number of mbuf 16k jumbo clusters allowed |
| kern.ipc.nmbjumbo9 | integer | 1896 | Maximum number of mbuf 9k jumbo clusters allowed |
| kern.ipc.nmbjumbop | integer | 6400 | Maximum number of mbuf page size jumbo clusters allowed |
| kern.ipc.nmbufs | integer | 81930 | Maximum number of mbufs allowed |
| kern.ipc.piperesizeallowed | integer | 1 | Pipe resizing allowed |
| kern.ipc.semaem | integer | 16384 | Adjust on exit max value |
| kern.ipc.semmsl | integer | 340 | Max semaphores per id |
| kern.ipc.semvmx | integer | 32767 | Semaphore maximum value |
| kern.ipc.sfstat | opaque | Format:I Length:88 Dump:0x00000000000000000000000000000000... | sendfile statistics |
| kern.ipc.shmall | unsigned long | 131072 | Maximum number of pages available for shared memory |
| kern.ipc.shm_allow_removed | integer | 1 | Enable/Disable attachment to attached segments marked for removal |
| kern.ipc.shmmax | unsigned long | 536870912 | Maximum shared memory segment size |
| kern.ipc.shmmin | unsigned long | 1 | Minimum shared memory segment size |
| kern.ipc.shm_use_phys | integer | 0 | Enable/Disable locking of shared memory pages in core |
| kern.ipc.soacceptqueue | unsigned integer | 128 | Maximum listen socket pending connection accept queue size |
| kern.ipc.sockbuf_waste_factor | unsigned long | 8 | Socket buffer size waste factor |
| kern.ipc.umtx_max_robust | integer | 1000 |  |
| kern.ipc.umtx_vnode_persistent | integer | 0 | False forces destruction of umtx attached to file, on last close |
| kern.kerneldump_gzlevel | integer | 6 | Kernel crash dump compression level |
| kern.kq_calloutmax | unsigned integer | 4096 | Maximum number of callouts allocated for kqueue |
| kern.ktrace.genio_size | unsigned integer | 4096 | Maximum size of genio event payload |
| kern.ktrace.request_pool | unsigned integer | 100 | Pool buffer size for ktrace(1) |
| kern.log_console_add_linefeed | integer | 0 | log_console() adds extra newlines |
| kern.log_console_output | integer | 1 | Duplicate console output to the syslog |
| kern.lognosys | integer | 0 | Log invalid syscalls |
| kern.logsigexit | integer | 1 | Log processes quitting on abnormal signals to syslog(3) |
| kern.log_wakeups_per_second | integer | 5 |  |
| kern.maxdsiz | unsigned long | 34359738368 | Maximum data size |
| kern.maxfiles | integer | 15025 | Maximum number of files |
| kern.maxfilesperproc | integer | 13518 | Maximum files allowed open per process |
| kern.maxprocperuid | integer | 3387 | Maximum processes allowed per userid |
| kern.maxssiz | unsigned long | 536870912 | Maximum stack size |
| kern.maxtsiz | unsigned long | 34359738368 | Maximum text size |
| kern.maxvnodes | integer | 12913 | Target for maximum number of vnodes |
| kern.metadelay | integer | 28 | Time to delay syncing metadata (in seconds) |
| kern.minvnodes | unsigned long | 3228 | Old name for vfs.wantfreevnodes (legacy) |
| kern.module_path | string | /boot/kernel;/boot/modules;/boot/dtb;/boot/dtb/overlays | module load search path |
| kern.msgbuf_clear | integer | 0 | Clear kernel message buffer |
| kern.msgbuf_show_timestamp | integer | 0 | Show timestamp in msgbuf |
| kern.nodump_coredump | integer | 0 | Enable setting the NODUMP flag on coredump files |
| kern.panic_reboot_wait_time | integer | 15 | Seconds to wait before rebooting after a panic |
| kern.pid_max | integer | 99999 | Maximum allowed pid |
| kern.powercycle_on_panic | uint8_t | 0 | Do a power cycle instead of a reboot on a panic |
| kern.poweroff_on_panic | uint8_t | 0 | Do a power off instead of a reboot on a panic |
| kern.proc_vmmap_skip_resident_count | integer | 0 | Skip calculation of the pages resident count in kern.proc.vmmap |
| kern.ps_arg_cache_limit | unsigned long | 256 |  |
| kern.racct.pcpu_threshold | unsigned integer | 1 | Processes with higher %cpu usage than this value can be throttled. |
| kern.racct.rctl.devctl_rate_limit | unsigned integer | 10 | Maximum number of devctl messages per second |
| kern.racct.rctl.log_rate_limit | unsigned integer | 10 | Maximum number of log messages per second |
| kern.racct.rctl.maxbufsize | unsigned integer | 16777216 | Maximum output buffer size |
| kern.racct.rctl.throttle_max | unsigned integer | 4294967295 | Longest throttling duration, in hz |
| kern.racct.rctl.throttle_min | unsigned integer | 4294967295 | Shortest throttling duration, in hz |
| kern.racct.rctl.throttle_pct | unsigned integer | 4294967295 | Throttling penalty for process consumption, in percent |
| kern.racct.rctl.throttle_pct2 | unsigned integer | 4294967295 | Throttling penalty for container consumption, in percent |
| kern.random.fortuna.minpoolsize | unsigned integer | 64 | Minimum pool size necessary to cause a reseed |
| kern.random.harvest.mask | unsigned integer | 66047 | Entropy harvesting mask |
| kern.randompid | integer | 0 | Random PID modulus. Special values |
| kern.sched.affinity | integer | 1 | Number of hz ticks to keep thread affinity for |
| kern.sched.always_steal | integer | 0 | Always run the stealer from the idle thread |
| kern.sched.balance | integer | 1 | Enables the long-term load balancer |
| kern.sched.balance_interval | integer | 127 | Average period in stathz ticks to run the long-term balancer |
| kern.sched.idlespins | integer | 10000 | Number of times idle thread will spin waiting for new work |
| kern.sched.idlespinthresh | integer | 157 | Threshold before we will permit idle thread spinning |
| kern.sched.interact | integer | 30 | Interactivity score threshold |
| kern.sched.preempt_thresh | integer | 80 | Maximal (lowest) priority for preemption |
| kern.sched.quantum | integer | 94488 | Quantum for timeshare threads in microseconds |
| kern.sched.slice | integer | 12 | Quantum for timeshare threads in stathz ticks |
| kern.sched.static_boost | integer | 152 | Assign static kernel priorities to sleeping threads |
| kern.sched.steal_idle | integer | 1 | Attempts to steal work from other cores before idling |
| kern.sched.steal_thresh | integer | 2 | Minimum load on remote CPU before we'll steal |
| kern.sched.trysteal_limit | integer | 2 | Topological distance limit for stealing threads in sched_switch() |
| kern.securelevel | integer | -1 | Current secure level |
| kern.sgrowsiz | unsigned long | 131072 | Amount to grow stack on a stack fault |
| kern.shutdown.kproc_shutdown_wait | integer | 60 | Max wait time (sec) to stop for each process |
| kern.shutdown.poweroff_delay | integer | 5000 | Delay before poweroff to write disk caches (msec) |
| kern.shutdown.show_busybufs | integer | 0 |  |
| kern.sigqueue.max_pending_per_proc | integer | 128 | Max pending signals per proc |
| kern.smp.forward_signal_enabled | integer | 1 | Forwarding of a signal to a process on a different CPU |
| kern.sugid_coredump | integer | 0 | Allow setuid and setgid processes to dump core |
| kern.suspend_blocked | integer | 0 | Block suspend due to a pending shutdown |
| kern.sync_on_panic | integer | 0 | Do a sync before rebooting from a panic |
| kern.threads.max_threads_per_proc | integer | 1500 | Limit on threads per proc |
| kern.timecounter.alloweddeviation | integer | 5 | Allowed time interval deviation in percents |
| kern.timecounter.fast_gettime | integer | 1 | Enable fast time of day |
| kern.timecounter.hardware | string | TSC-low | Timecounter hardware selected |
| kern.timecounter.stepwarnings | integer | 0 | Log time steps |
| kern.trap_enotcap | uint8_t | 0 | Deliver SIGTRAP on ENOTCAPABLE |
| kern.tty_drainwait | integer | 300 | Default output drain timeout in seconds |
| kern.tty_inq_flush_secure | integer | 1 | Zero buffers while flushing |
| kern.userasymcrypto | integer | 1 | Enable/disable user-mode access to asymmetric crypto support |
| kern.vt.deadtimer | integer | 15 | Time to wait busy process in VT_PROCESS mode |
| kern.vt.debug | integer | 0 | vt(9) debug level |
| kern.vt.enable_altgr | integer | 1 | Enable AltGr key (Do not assume R.Alt as Alt) |
| kern.vt.enable_bell | integer | 1 | Enable bell |
| kern.vt.kbd_debug | integer | 1 | Enable key combination to enter debugger.  See kbdmap(5) to configure (typically Ctrl-Alt-Esc). |
| kern.vt.kbd_halt | integer | 1 | Enable halt keyboard combination.  See kbdmap(5) to configure. |
| kern.vt.kbd_panic | integer | 0 | Enable request to panic.  See kbdmap(5) to configure. |
| kern.vt.kbd_poweroff | integer | 1 | Enable Power Off keyboard combination.  See kbdmap(5) to configure. |
| kern.vt.kbd_reboot | integer | 1 | Enable reboot keyboard combination.  See kbdmap(5) to configure (typically Ctrl-Alt-Delete). |
| kern.vt.splash_cpu | integer | 0 | Show logo CPUs during boot |
| kern.vt.splash_cpu_duration | integer | 10 | Hide logos after (seconds) |
| kern.vt.splash_cpu_style | integer | 2 | Draw logo style (0 = Alternate beastie, 1 = Beastie, 2 = Orb) |
| kern.vt.splash_ncpu | integer | 0 | Override number of logos displayed (0 = do not override) |
| kern.vt.suspendswitch | integer | 1 | Switch to VT0 before suspend |
| machdep.acpi_timer_freq | integer | 3579545 | ACPI timer frequency |
| machdep.adjkerntz | integer | 0 | Local offset from UTC in seconds |
| machdep.disable_rtc_set | integer | 0 | Disallow adjusting time-of-day clock |
| machdep.dump_retry_count | integer | 5 | Number of times dump has to retry before bailing out |
| machdep.efi_rt_handle_faults | integer | 1 | Call EFI RT methods with fault handler wrapper around |
| machdep.enable_panic_key | integer | 0 | Enable panic via keypress specified in kbdmap(5) |
| machdep.i8254_freq | integer | 1193182 | i8254 timer frequency |
| machdep.idle | string | acpi | currently selected idle function |
| machdep.idle_apl31 | integer | 0 | Apollo Lake APL31 MWAIT bug workaround |
| machdep.idle_mwait | integer | 1 | Use MONITOR/MWAIT for short idle |
| machdep.kdb_on_nmi | integer | 1 | Go to KDB on NMI with unknown source |
| machdep.nmi_flush_l1d_sw | integer | 0 | Flush L1 Data Cache on NMI exit, software bhyve L1TF mitigation assist |
| machdep.nmi_is_broadcast | integer | 1 | Chipset NMI is broadcast |
| machdep.panic_on_nmi | integer | 1 | Panic on NMI raised by hardware failure |
| machdep.prot_fault_translation | integer | 0 | Select signal to deliver on protection fault |
| machdep.rtc_save_period | integer | 1800 | Save system time to RTC with this period (in seconds) |
| machdep.syscall_ret_flush_l1d | integer | 0 | Flush L1D on syscall return with error (0 - off, 1 - on, 2 - use hw only, 3 - use sw only |
| machdep.tsc_freq | uint64_t | 3593284362 | Time Stamp Counter frequency |
| machdep.uprintf_signal | integer | 0 | Print debugging information on trap signal to ctty |
| machdep.vga_aspect_scale | integer | 100 | Aspect scale ratio (3:4):actual times 100 |
| machdep.wall_cmos_clock | integer | 0 | Enables application of machdep.adjkerntz |
| net.accf.unloadable | integer | 0 | Allow unload of accept filters (not recommended) |
| net.add_addr_allfibs | unsigned integer | 1 |  |
| net.bpf.bufsize | integer | 4096 | Default capture buffer size in bytes |
| net.bpf.maxbufsize | integer | 524288 | Maximum capture buffer in bytes |
| net.bpf.maxinsns | integer | 512 | Maximum bpf program instructions |
| net.bpf.optimize_writers | integer | 0 | Do not send packets until BPF program is set |
| net.bpf.stats | node | Format:N Length:336 Dump:0xa8000000000000000000000000000000... | bpf statistics portal |
| net.bpf.zerocopy_enable | integer | 0 | Enable new zero-copy BPF buffer sessions |
| net.ifdescr_maxlen | unsigned integer | 1024 | administrative maximum length for interface description |
| net.iflib.min_tx_latency | integer | 0 | minimize transmit latency at the possible expense of throughput |
| net.iflib.no_tx_batch | integer | 0 | minimize transmit latency at the possible expense of throughput |
| net.inet6.icmp6.errppslimit | integer | 100 | Maximum number of ICMPv6 error messages per second |
| net.inet6.icmp6.nd6_debug | integer | 0 | Log NDP debug messages |
| net.inet6.icmp6.nd6_delay | integer | 5 | Delay in seconds before probing for reachability |
| net.inet6.icmp6.nd6_gctimer | integer | 86400 |  |
| net.inet6.icmp6.nd6_maxnudhint | integer | 0 |  |
| net.inet6.icmp6.nd6_maxqueuelen | integer | 1 |  |
| net.inet6.icmp6.nd6_mmaxtries | integer | 3 | Number of ICMPv6 NS messages sent during address resolution |
| net.inet6.icmp6.nd6_onlink_ns_rfc4861 | integer | 0 | Accept 'on-link' ICMPv6 NS messages in compliance with RFC 4861 |
| net.inet6.icmp6.nd6_prune | integer | 1 | Frequency in seconds of checks for expired prefixes and routers |
| net.inet6.icmp6.nd6_umaxtries | integer | 3 | Number of ICMPv6 NS messages sent during reachability detection |
| net.inet6.icmp6.nd6_useloopback | integer | 1 | Create a loopback route when configuring an IPv6 address |
| net.inet6.icmp6.nodeinfo | integer | 3 | Mask of enabled RF4620 node information query types |
| net.inet6.icmp6.nodeinfo_oldmcprefix | integer | 1 | Join old IPv6 NI group address in draft-ietf-ipngwg-icmp-name-lookup for compatibility with KAME implementation |
| net.inet6.icmp6.rediraccept | integer | 1 | Accept ICMPv6 redirect messages |
| net.inet6.icmp6.redirtimeout | integer | 600 |  |
| net.inet6.icmp6.stats | opaque | Format:I Length:4328 Dump:0x00000000000000000000000000000000... | ICMPv6 statistics (struct icmp6stat, netinet/icmp6.h) |
| net.inet6.ip6.accept_rtadv | integer | 0 | Default value of per-interface flag for accepting ICMPv6 RA messages |
| net.inet6.ip6.auto_flowlabel | integer | 1 | Provide an IPv6 flowlabel in outbound packets |
| net.inet6.ip6.auto_linklocal | integer | 1 | Default value of per-interface flag for automatically adding an IPv6 link-local address to interfaces when attached |
| net.inet6.ip6.dad_count | integer | 1 | Number of ICMPv6 NS messages sent during duplicate address detection |
| net.inet6.ip6.dad_enhanced | integer | 1 | Enable Enhanced DAD, which adds a random nonce to NS messages for DAD. |
| net.inet6.ip6.deembed_scopeid | integer | 1 | Extract embedded zone ID and set it to sin6_scope_id in sockaddr_in6. |
| net.inet6.ip6.defmcasthlim | integer | 1 | Default hop limit for IPv6 multicast packets originating from this node |
| net.inet6.ip6.forwarding | integer | 0 | Enable forwarding of IPv6 packets between interfaces |
| net.inet6.ip6.gifhlim | integer | 30 | Default hop limit for encapsulated packets |
| net.inet6.ip6.hdrnestlimit | integer | 15 | Default maximum number of IPv6 extension headers permitted on incoming IPv6 packets, 0 for no artificial limit |
| net.inet6.ip6.hlim | integer | 64 | Default hop limit to use for outgoing IPv6 packets |
| net.inet6.ip6.intr_queue_maxlen | integer | 256 | Maximum size of the IPv6 input queue |
| net.inet6.ip6.log_interval | integer | 5 | Frequency in seconds at which to log IPv6 forwarding errors |
| net.inet6.ip6.maxfragbucketsize | integer | 1 | Maximum number of reassembly queues per hash bucket |
| net.inet6.ip6.maxfragpackets | integer | 400 | Default maximum number of outstanding fragmented IPv6 packets. A value of 0 means no fragmented packets will be accepted, while a a value of -1 means no limit |
| net.inet6.ip6.maxfrags | integer | 400 | Maximum allowed number of outstanding IPv6 packet fragments. A value of 0 means no fragmented packets will be accepted, while a a value of -1 means no limit |
| net.inet6.ip6.maxfragsperpacket | integer | 64 | Maximum allowed number of fragments per packet |
| net.inet6.ip6.mcast.loop | integer | 1 | Loopback multicast datagrams by default |
| net.inet6.ip6.mcast.maxgrpsrc | unsigned long | 512 | Max source filters per group |
| net.inet6.ip6.mcast.maxsocksrc | unsigned long | 128 | Max source filters per socket |
| net.inet6.ip6.mcast_pmtu | integer | 0 | Enable path MTU discovery for multicast packets |
| net.inet6.ip6.no_radr | integer | 0 | Default value of per-interface flag to control whether routers sending ICMPv6 RA messages on that interface are added into the default router list |
| net.inet6.ip6.norbit_raif | integer | 0 | Always set clear the R flag in ICMPv6 NA messages when accepting RA on the interface |
| net.inet6.ip6.prefer_tempaddr | integer | 0 | Prefer RFC3041 temporary addresses in source address selection |
| net.inet6.ip6.redirect | integer | 1 | Send ICMPv6 redirects for unforwardable IPv6 packets |
| net.inet6.ip6.rfc6204w3 | integer | 0 | Accept the default router list from ICMPv6 RA messages even when packet forwarding is enabled |
| net.inet6.ip6.rip6stats | opaque | Format:I Length:56 Dump:0x00000000000000000000000000000000... | Raw IP6 statistics (struct rip6stat, netinet6/raw_ip6.h) |
| net.inet6.ip6.rr_prune | integer | 5 |  |
| net.inet6.ip6.stats | opaque | Format:I Length:3312 Dump:0x00000000000000000000000000000000... | IP6 statistics (struct ip6stat, netinet6/ip6_var.h) |
| net.inet6.ip6.temppltime | integer | 86400 | Maximum preferred lifetime for temporary addresses |
| net.inet6.ip6.tempvltime | integer | 604800 | Maximum valid lifetime for temporary addresses |
| net.inet6.ip6.use_defaultzone | integer | 0 | Use the default scope zone when none is specified |
| net.inet6.ip6.use_deprecated | integer | 1 | Allow the use of addresses whose preferred lifetimes have expired |
| net.inet6.ip6.use_tempaddr | integer | 0 | Create RFC3041 temporary addresses for autoconfigured addresses |
| net.inet6.ip6.v6only | integer | 1 | Restrict AF_INET6 sockets to IPv6 addresses only |
| net.inet6.ipsec6.ah_net_deflev | integer | 1 | AH tunnel mode default level. |
| net.inet6.ipsec6.ah_trans_deflev | integer | 1 | AH transfer mode default level. |
| net.inet6.ipsec6.debug | integer | 0 | Enable IPsec debugging output when set. |
| net.inet6.ipsec6.def_policy | integer | 1 | IPsec default policy. |
| net.inet6.ipsec6.ecn | integer | 0 | Explicit Congestion Notification handling. |
| net.inet6.ipsec6.esp_net_deflev | integer | 1 | Default ESP tunnel mode level. |
| net.inet6.ipsec6.esp_trans_deflev | integer | 1 | Default ESP transport mode level. |
| net.inet6.ipsec6.filtertunnel | integer | 0 | If set, filter packets from an IPsec tunnel. |
| net.inet6.ipsec6.ipsecstats | opaque | Format:I Length:128 Dump:0x00000000000000000000000000000000... | IPsec IPv6 statistics. |
| net.inet6.mld.gsrdelay | integer | 10 | Rate limit for MLDv2 Group-and-Source queries in seconds |
| net.inet6.mld.use_allow | integer | 1 | Use ALLOW/BLOCK for RFC 4604 SSM joins/leaves |
| net.inet6.mld.v1enable | integer | 1 | Enable fallback to MLDv1 |
| net.inet6.mld.v2enable | integer | 1 | Enable MLDv2 |
| net.inet.ah.ah_cleartos | integer | 1 |  |
| net.inet.ah.ah_enable | integer | 1 |  |
| net.inet.ah.stats | opaque | Format:I Length:280 Dump:0x00000000000000000000000000000000... | AH statistics (struct ahstat, netipsec/ah_var.h) |
| net.inet.esp.esp_enable | integer | 1 |  |
| net.inet.esp.stats | opaque | Format:I Length:2208 Dump:0x00000000000000000000000000000000... | ESP statistics (struct espstat, netipsec/esp_var.h |
| net.inet.icmp.bmcastecho | integer | 0 | Reply to multicast ICMP Echo Request and Timestamp packets |
| net.inet.icmp.drop_redirect | integer | 0 | Ignore ICMP redirects |
| net.inet.icmp.error_keeptags | integer | 0 | ICMP error response keeps copy of mbuf_tags of original packet |
| net.inet.icmp.icmplim | integer | 200 | Maximum number of ICMP responses per second |
| net.inet.icmp.icmplim_output | integer | 1 | Enable logging of ICMP response rate limiting |
| net.inet.icmp.log_redirect | integer | 0 | Log ICMP redirects to the console |
| net.inet.icmp.maskfake | unsigned integer | 0 | Fake reply to ICMP Address Mask Request packets |
| net.inet.icmp.maskrepl | integer | 0 | Reply to ICMP Address Mask Request packets |
| net.inet.icmp.quotelen | integer | 548 | Number of bytes from original packet to quote in ICMP reply |
| net.inet.icmp.reply_from_interface | integer | 0 | ICMP reply from incoming interface for non-local packets |
| net.inet.icmp.reply_src | string |  | ICMP reply source for non-local packets |
| net.inet.icmp.stats | opaque | Format:I Length:752 Dump:0x00000000000000000000000000000000... | ICMP statistics (struct icmpstat, netinet/icmp_var.h) |
| net.inet.icmp.tstamprepl | integer | 1 | Respond to ICMP Timestamp packets |
| net.inet.igmp.default_version | integer | 3 | Default version of IGMP to run on each interface |
| net.inet.igmp.gsrdelay | integer | 10 | Rate limit for IGMPv3 Group-and-Source queries in seconds |
| net.inet.igmp.legacysupp | integer | 0 | Allow v1/v2 reports to suppress v3 group responses |
| net.inet.igmp.recvifkludge | integer | 1 | Rewrite IGMPv1/v2 reports from 0.0.0.0 to contain subnet address |
| net.inet.igmp.sendlocal | integer | 1 | Send IGMP membership reports for 224.0.0.0/24 groups |
| net.inet.igmp.sendra | integer | 1 | Send IP Router Alert option in IGMPv2/v3 messages |
| net.inet.igmp.stats | opaque | Format:S,igmpstat Length:168 Dump:0x03000000a80000000000000000000000... |  |
| net.inet.igmp.v1enable | integer | 1 | Enable backwards compatibility with IGMPv1 |
| net.inet.igmp.v2enable | integer | 1 | Enable backwards compatibility with IGMPv2 |
| net.inet.ip.accept_sourceroute | integer | 0 | Enable accepting source routed IP packets |
| net.inet.ip.check_interface | integer | 0 | Verify packet arrives on correct interface |
| net.inet.ipcomp.ipcomp_enable | integer | 1 |  |
| net.inet.ipcomp.stats | opaque | Format:I Length:200 Dump:0x00000000000000000000000000000000... | IPCOMP statistics (struct ipcompstat, netipsec/ipcomp_var.h |
| net.inet.ip.forwarding | integer | 0 | Enable IP forwarding between interfaces |
| net.inet.ip.gifttl | integer | 30 | Default TTL value for encapsulated packets |
| net.inet.ip.intr_queue_maxlen | integer | 256 | Maximum size of the IP input queue |
| net.inet.ip.maxfragbucketsize | integer | 1 | Maximum number of IPv4 fragment reassembly queue entries per bucket |
| net.inet.ip.maxfragpackets | integer | 426 | Maximum number of IPv4 fragment reassembly queue entries |
| net.inet.ip.maxfrags | integer | 400 | Maximum number of IPv4 fragments allowed across all reassembly queues |
| net.inet.ip.maxfragsperpacket | integer | 16 | Maximum number of IPv4 fragments allowed per packet |
| net.inet.ip.mcast.loop | integer | 1 | Loopback multicast datagrams by default |
| net.inet.ip.mcast.maxgrpsrc | unsigned long | 512 | Max source filters per group |
| net.inet.ip.mcast.maxsocksrc | unsigned long | 128 | Max source filters per socket |
| net.inet.ip.no_same_prefix | integer | 0 | Refuse to create same prefixes on different interfaces |
| net.inet.ip.portrange.first | integer | 10000 |  |
| net.inet.ip.portrange.hifirst | integer | 49152 |  |
| net.inet.ip.portrange.hilast | integer | 65535 |  |
| net.inet.ip.portrange.last | integer | 65535 |  |
| net.inet.ip.portrange.lowfirst | integer | 1023 |  |
| net.inet.ip.portrange.lowlast | integer | 600 |  |
| net.inet.ip.portrange.randomcps | integer | 10 | Maximum number of random port allocations before switching to a sequental one |
| net.inet.ip.portrange.randomized | integer | 1 | Enable random port allocation |
| net.inet.ip.portrange.randomtime | integer | 45 | Minimum time to keep sequental port allocation before switching to a random one |
| net.inet.ip.portrange.reservedhigh | integer | 1023 |  |
| net.inet.ip.portrange.reservedlow | integer | 0 |  |
| net.inet.ip.process_options | integer | 1 | Enable IP options processing ([LS]SRR, RR, TS) |
| net.inet.ip.random_id | integer | 0 | Assign random ip_id values |
| net.inet.ip.random_id_period | integer | 0 | IP ID Array size |
| net.inet.ip.redirect | integer | 1 | Enable sending IP redirects |
| net.inet.ip.rfc6864 | integer | 1 | Use constant IP ID for atomic datagrams |
| net.inet.ipsec.ah_cleartos | integer | 1 | If set, clear type-of-service field when doing AH computation. |
| net.inet.ipsec.ah_net_deflev | integer | 1 | AH tunnel mode default level. |
| net.inet.ipsec.ah_trans_deflev | integer | 1 | AH transfer mode default level. |
| net.inet.ipsec.async_crypto | integer | 0 | Use asynchronous mode to parallelize crypto jobs. |
| net.inet.ipsec.check_policy_history | integer | 0 | Use strict check of inbound packets to security policy compliance. |
| net.inet.ipsec.crypto_support | integer | 50331648 | Crypto driver selection. |
| net.inet.ipsec.crypto_warn_interval | integer | 1 | Delay in seconds between warnings of deprecated IPsec crypto algorithms. |
| net.inet.ipsec.debug | integer | 0 | Enable IPsec debugging output when set. |
| net.inet.ipsec.def_policy | integer | 1 | IPsec default policy. |
| net.inet.ipsec.dfbit | integer | 0 | Do not fragment bit on encap. |
| net.inet.ipsec.ecn | integer | 0 | Explicit Congestion Notification handling. |
| net.inet.ipsec.esp_net_deflev | integer | 1 | Default ESP tunnel mode level. |
| net.inet.ipsec.esp_trans_deflev | integer | 1 | Default ESP transport mode level |
| net.inet.ipsec.filtertunnel | integer | 0 | If set, filter packets from an IPsec tunnel. |
| net.inet.ipsec.ipsecstats | opaque | Format:I Length:128 Dump:0x00000000000000000000000000000000... | IPsec IPv4 statistics. |
| net.inet.ipsec.natt_cksum_policy | integer | 0 | Method to fix TCP/UDP checksum for transport mode IPsec after NAT. |
| net.inet.ip.sourceroute | integer | 0 | Enable forwarding source routed IP packets |
| net.inet.ip.stats | opaque | Format:I Length:232 Dump:0xfa000000000000000000000000000000... | IP statistics (struct ipstat, netinet/ip_var.h) |
| net.inet.ip.ttl | integer | 64 | Maximum TTL on IP packets |
| net.inet.raw.maxdgram | unsigned long | 9216 | Maximum outgoing raw IP datagram size |
| net.inet.raw.recvspace | unsigned long | 9216 | Maximum space for incoming raw IP datagrams |
| net.inet.sctp.abc_l_var | unsigned integer | 2 | SCTP ABC max increase per SACK (L) |
| net.inet.sctp.abort_at_limit | unsigned integer | 0 | Abort when one-to-one hits qlimit |
| net.inet.sctp.add_more_on_output | unsigned integer | 1452 | When space-wise is it worthwhile to try to add more to a socket send buffer |
| net.inet.sctp.asconf_enable | unsigned integer | 1 | Enable SCTP ASCONF |
| net.inet.sctp.asoc_resource | unsigned integer | 10 | Max number of cached resources in an asoc |
| net.inet.sctp.assoc_rtx_max | unsigned integer | 10 | Default maximum number of retransmissions per association |
| net.inet.sctp.auth_enable | unsigned integer | 1 | Enable SCTP AUTH function |
| net.inet.sctp.auto_asconf | unsigned integer | 1 | Enable SCTP Auto-ASCONF |
| net.inet.sctp.blackhole | unsigned integer | 0 | Enable SCTP blackholing, see blackhole(4) for more details |
| net.inet.sctp.buffer_splitting | unsigned integer | 0 | Enable send/receive buffer splitting |
| net.inet.sctp.chunkscale | unsigned integer | 10 | Tunable for scaling of number of chunks and messages |
| net.inet.sctp.cmt_on_off | unsigned integer | 0 | CMT settings |
| net.inet.sctp.cmt_use_dac | unsigned integer | 0 | CMT DAC on/off flag |
| net.inet.sctp.cwnd_maxburst | unsigned integer | 1 | Adjust congestion control window to limit maximum burst when sending |
| net.inet.sctp.default_cc_module | unsigned integer | 0 | Default congestion control module |
| net.inet.sctp.default_frag_interleave | unsigned integer | 1 | Default fragment interleave level |
| net.inet.sctp.default_ss_module | unsigned integer | 0 | Default stream scheduling module |
| net.inet.sctp.delayed_sack_time | unsigned integer | 200 | Default delayed SACK timer in ms |
| net.inet.sctp.diag_info_code | unsigned integer | 0 | Diagnostic information error cause code |
| net.inet.sctp.do_sctp_drain | unsigned integer | 1 | Should SCTP respond to the drain calls |
| net.inet.sctp.ecn_enable | unsigned integer | 1 | Enable SCTP ECN |
| net.inet.sctp.enable_sack_immediately | unsigned integer | 1 | Enable sending of the SACK-IMMEDIATELY-bit |
| net.inet.sctp.fr_maxburst | unsigned integer | 4 | Default max burst for SCTP endpoints when fast retransmitting |
| net.inet.sctp.hb_max_burst | unsigned integer | 4 | Confirmation Heartbeat max burst |
| net.inet.sctp.heartbeat_interval | unsigned integer | 30000 | Default heartbeat interval in ms |
| net.inet.sctp.incoming_streams | unsigned integer | 2048 | Default number of incoming streams |
| net.inet.sctp.initial_cwnd | unsigned integer | 3 | Defines the initial congestion window size in MTUs |
| net.inet.sctp.init_rto_max | unsigned integer | 60000 | Default maximum retransmission timeout during association setup in ms |
| net.inet.sctp.init_rtx_max | unsigned integer | 8 | Default maximum number of retransmissions for INIT chunks |
| net.inet.sctp.log_level | unsigned integer | 0 | Ltrace/KTR trace logging level |
| net.inet.sctp.maxburst | unsigned integer | 4 | Default max burst for sctp endpoints |
| net.inet.sctp.max_chained_mbufs | unsigned integer | 5 | Default max number of small mbufs on a chain |
| net.inet.sctp.maxchunks | unsigned integer | 1600 | Default max chunks on queue per asoc |
| net.inet.sctp.max_retran_chunk | unsigned integer | 30 | Maximum times an unlucky chunk can be retransmitted before assoc abort |
| net.inet.sctp.min_residual | unsigned integer | 1452 | Minimum residual data chunk in second part of split |
| net.inet.sctp.min_split_point | unsigned integer | 2904 | Minimum size when splitting a chunk |
| net.inet.sctp.mobility_base | unsigned integer | 0 | Enable SCTP base mobility |
| net.inet.sctp.mobility_fasthandoff | unsigned integer | 0 | Enable SCTP fast handoff |
| net.inet.sctp.nat_friendly | unsigned integer | 1 | SCTP NAT friendly operation |
| net.inet.sctp.nat_friendly_init | unsigned integer | 0 | Enable sending of the nat-friendly SCTP option on INITs |
| net.inet.sctp.nrsack_enable | unsigned integer | 0 | Enable SCTP NR-SACK |
| net.inet.sctp.outgoing_streams | unsigned integer | 10 | Default number of outgoing streams |
| net.inet.sctp.path_pf_threshold | unsigned integer | 65535 | Default potentially failed threshold |
| net.inet.sctp.path_rtx_max | unsigned integer | 5 | Default maximum of retransmissions per path |
| net.inet.sctp.pcbhashsize | unsigned integer | 256 | Tunable for PCB hash table sizes |
| net.inet.sctp.peer_chkoh | unsigned integer | 256 | Amount to debit peers rwnd per chunk sent |
| net.inet.sctp.pktdrop_enable | unsigned integer | 0 | Enable SCTP PKTDROP |
| net.inet.sctp.pmtu_raise_time | unsigned integer | 600 | Default PMTU raise timer in seconds |
| net.inet.sctp.pr_enable | unsigned integer | 1 | Enable PR-SCTP |
| net.inet.sctp.reconfig_enable | unsigned integer | 1 | Enable SCTP RE-CONFIG |
| net.inet.sctp.recvspace | unsigned integer | 1864135 | Maximum incoming SCTP buffer size |
| net.inet.sctp.rto_initial | unsigned integer | 3000 | Default initial retransmission timeout in ms |
| net.inet.sctp.rto_max | unsigned integer | 60000 | Default maximum retransmission timeout in ms |
| net.inet.sctp.rto_min | unsigned integer | 1000 | Default minimum retransmission timeout in ms |
| net.inet.sctp.rttvar_bw | unsigned integer | 4 | Shift amount DCCC uses for bw smoothing on rtt calc |
| net.inet.sctp.rttvar_eqret | unsigned integer | 0 | Whether DCCC increases cwnd when the rtt and bw are unchanged |
| net.inet.sctp.rttvar_rtt | unsigned integer | 5 | Shift amount DCCC uses for rtt smoothing on rtt calc |
| net.inet.sctp.rttvar_steady_step | unsigned integer | 20 | Number of identical bw measurements DCCC takes to try step down of cwnd |
| net.inet.sctp.sack_freq | unsigned integer | 2 | Default SACK frequency |
| net.inet.sctp.secret_lifetime | unsigned integer | 3600 | Default secret lifetime in seconds |
| net.inet.sctp.sendspace | unsigned integer | 1864135 | Maximum outgoing SCTP buffer size |
| net.inet.sctp.shutdown_guard_time | unsigned integer | 0 | Shutdown guard timer in seconds (0 means 5 times RTO.Max) |
| net.inet.sctp.stats | opaque | Format:S,sctpstat Length:664 Dump:0x01000000fd0000000000000000000000... | SCTP statistics (struct sctp_stat) |
| net.inet.sctp.sys_resource | unsigned integer | 1000 | Max number of cached resources in the system |
| net.inet.sctp.tcbhashsize | unsigned integer | 1024 | Tunable for TCB hash table sizes |
| net.inet.sctp.udp_tunneling_port | unsigned integer | 0 | Set the SCTP/UDP tunneling port |
| net.inet.sctp.use_dcccecn | unsigned integer | 1 | Enable ECN for DCCC. |
| net.inet.sctp.valid_cookie_life | unsigned integer | 60000 | Default cookie lifetime in seconds |
| net.inet.sctp.vtag_time_wait | unsigned integer | 60 | Vtag time wait time in seconds, 0 disables it |
| net.inet.tcp.abc_l_var | integer | 2 | Cap the max cwnd increment during slow-start to this number of segments |
| net.inet.tcp.always_keepalive | integer | 1 | Assume SO_KEEPALIVE on all TCP connections |
| net.inet.tcp.bb.log_auto_all | uint8_t | 0 | Auto-select from all sessions (rather than just those with IDs) |
| net.inet.tcp.bb.log_auto_mode | uint32_t | 1 | Logging mode for auto-selected sessions (default is TCP_LOG_STATE_HEAD_AUTO) |
| net.inet.tcp.bb.log_auto_ratio | unsigned long | 0 | Do auto capturing for 1 out of N sessions |
| net.inet.tcp.bb.log_global_limit | integer | 1000000 | Maximum number of events maintained for all TCP sessions |
| net.inet.tcp.bb.log_id_limit | integer | 0 | Maximum number of log IDs |
| net.inet.tcp.bb.log_id_tcpcb_limit | integer | 0 | Maximum number of tcpcbs with log IDs |
| net.inet.tcp.bb.log_session_limit | integer | 10000 | Maximum number of events maintained for each TCP session |
| net.inet.tcp.bb.log_verbose | uint8_t | 0 | Force verbose logging for TCP traces |
| net.inet.tcp.blackhole | integer | 0 | Do not send RST on segments to closed ports |
| net.inet.tcp.cc.abe | integer | 0 | Enable draft-ietf-tcpm-alternativebackoff-ecn (TCP Alternative Backoff with ECN) |
| net.inet.tcp.cc.abe_frlossreduce | integer | 0 | Apply standard beta instead of ABE-beta during ECN-signalled congestion recovery episodes if loss also needs to be repaired |
| net.inet.tcp.cc.algorithm | string | newreno | Default congestion control algorithm |
| net.inet.tcp.cc.newreno.beta | unsigned integer | 50 | New Reno beta, specified as number between 1 and 100 |
| net.inet.tcp.cc.newreno.beta_ecn | unsigned integer | 80 | New Reno beta ecn, specified as number between 1 and 100 |
| net.inet.tcp.delacktime | integer | 100 | Time before a delayed ACK is sent |
| net.inet.tcp.delayed_ack | integer | 1 | Delay ACK to try and piggyback it onto a data packet |
| net.inet.tcp.do_tcpdrain | integer | 1 | Enable tcp_drain routine for extra help when low on mbufs |
| net.inet.tcp.drop_synfin | integer | 0 | Drop TCP packets with SYN+FIN set |
| net.inet.tcp.ecn.enable | integer | 2 | TCP ECN support |
| net.inet.tcp.ecn.maxretries | integer | 1 | Max retries before giving up on ECN |
| net.inet.tcp.fast_finwait2_recycle | integer | 0 | Recycle closed FIN_WAIT_2 connections faster |
| net.inet.tcp.fastopen.acceptany | integer | 0 | Accept any non-empty cookie |
| net.inet.tcp.fastopen.autokey | unsigned integer | 120 | Number of seconds between auto-generation of a new key; zero disables |
| net.inet.tcp.fastopen.ccache_bucket_limit | unsigned integer | 16 | Max entries per bucket in client cookie cache |
| net.inet.tcp.fastopen.client_enable | unsigned integer | 1 | Enable/disable TCP Fast Open client functionality |
| net.inet.tcp.fastopen.path_disable_time | unsigned integer | 900 | Seconds a TFO failure disables a {client_ip, server_ip, server_port} path |
| net.inet.tcp.fastopen.psk_enable | unsigned integer | 0 | Enable/disable TCP Fast Open server pre-shared key mode |
| net.inet.tcp.fastopen.server_enable | unsigned integer | 0 | Enable/disable TCP Fast Open server functionality |
| net.inet.tcp.finwait2_timeout | integer | 60000 | FIN-WAIT2 timeout |
| net.inet.tcp.functions_default | string | freebsd | Set/get the default TCP functions |
| net.inet.tcp.functions_inherit_listen_socket_stack | integer | 1 | Inherit listen socket's stack |
| net.inet.tcp.hostcache.enable | integer | 1 | Enable the TCP hostcache |
| net.inet.tcp.hostcache.expire | integer | 3600 | Expire time of TCP hostcache entries |
| net.inet.tcp.hostcache.prune | integer | 300 | Time between purge runs |
| net.inet.tcp.hostcache.purge | integer | 0 | Expire all entires on next purge run |
| net.inet.tcp.hostcache.purgenow | integer | 0 | Immediately purge all entries |
| net.inet.tcp.icmp_may_rst | integer | 1 | Certain ICMP unreachable messages may abort connections in SYN_SENT |
| net.inet.tcp.initcwnd_segments | integer | 10 | Slow-start flight size (initial congestion window) in number of segments |
| net.inet.tcp.insecure_rst | integer | 0 | Follow RFC793 instead of RFC5961 criteria for accepting RST packets |
| net.inet.tcp.insecure_syn | integer | 0 | Follow RFC793 instead of RFC5961 criteria for accepting SYN packets |
| net.inet.tcp.isn_reseed_interval | integer | 0 | Seconds between reseeding of ISN secret |
| net.inet.tcp.keepcnt | integer | 8 | Number of keepalive probes to send |
| net.inet.tcp.keepidle | integer | 7200000 | time before keepalive probes begin |
| net.inet.tcp.keepinit | integer | 75000 | time to establish connection |
| net.inet.tcp.keepintvl | integer | 75000 | time between keepalive probes |
| net.inet.tcp.log_debug | integer | 0 | Log errors caused by incoming TCP segments |
| net.inet.tcp.log_in_vain | integer | 0 | Log all incoming TCP segments to closed ports |
| net.inet.tcp.maxtcptw | integer | 3005 | Maximum number of compressed TCP TIME_WAIT entries |
| net.inet.tcp.minmss | integer | 216 | Minimum TCP Maximum Segment Size |
| net.inet.tcp.msl | integer | 30000 | Maximum segment lifetime |
| net.inet.tcp.mssdflt | integer | 536 | Default TCP Maximum Segment Size |
| net.inet.tcp.nolocaltimewait | integer | 0 | Do not create compressed TCP TIME_WAIT entries for local connections |
| net.inet.tcp.path_mtu_discovery | integer | 1 | Enable Path MTU Discovery |
| net.inet.tcp.per_cpu_timers | integer | 0 | run tcp timers on all cpus |
| net.inet.tcp.persmax | integer | 60000 | maximum persistence interval |
| net.inet.tcp.persmin | integer | 5000 | minimum persistence interval |
| net.inet.tcp.pmtud_blackhole_detection | integer | 0 | Path MTU Discovery Black Hole Detection Enabled |
| net.inet.tcp.pmtud_blackhole_mss | integer | 1200 | Path MTU Discovery Black Hole Detection lowered MSS |
| net.inet.tcp.reass.maxqueuelen | unsigned integer | 100 | Maximum number of TCP Segments per Reassembly Queue |
| net.inet.tcp.reass.new_limit | integer | 0 | Do we use the new limit method we are discussing? |
| net.inet.tcp.reass.queueguard | unsigned integer | 16 | Number of TCP Segments in Reassembly Queue where we flip over to guard mode |
| net.inet.tcp.recvbuf_auto | integer | 1 | Enable automatic receive buffer sizing |
| net.inet.tcp.recvbuf_inc | integer | 16384 | Incrementor step size of automatic receive buffer |
| net.inet.tcp.recvbuf_max | integer | 2097152 | Max size of automatic receive buffer |
| net.inet.tcp.recvspace | integer | 65536 | Initial receive socket buffer size |
| net.inet.tcp.rexmit_drop_options | integer | 0 | Drop TCP options from 3rd and later retransmitted SYN |
| net.inet.tcp.rexmit_initial | integer | 1000 | Initial Retransmission Timeout |
| net.inet.tcp.rexmit_min | integer | 30 | Minimum Retransmission Timeout |
| net.inet.tcp.rexmit_slop | integer | 200 | Retransmission Timer Slop |
| net.inet.tcp.rfc1323 | integer | 1 | Enable rfc1323 (high performance TCP) extensions |
| net.inet.tcp.rfc3042 | integer | 1 | Enable RFC 3042 (Limited Transmit) |
| net.inet.tcp.rfc3390 | integer | 1 | Enable RFC 3390 (Increasing TCP's Initial Congestion Window) |
| net.inet.tcp.rfc3465 | integer | 1 | Enable RFC 3465 (Appropriate Byte Counting) |
| net.inet.tcp.rfc6675_pipe | integer | 0 | Use calculated pipe/in-flight bytes per RFC 6675 |
| net.inet.tcp.sack.enable | integer | 1 | Enable/Disable TCP SACK support |
| net.inet.tcp.sack.globalmaxholes | integer | 65536 | Global maximum number of TCP SACK holes |
| net.inet.tcp.sack.maxholes | integer | 128 | Maximum number of TCP SACK holes allowed per connection |
| net.inet.tcp.sendbuf_auto | integer | 1 | Enable automatic send buffer sizing |
| net.inet.tcp.sendbuf_auto_lowat | integer | 0 | Modify threshold for auto send buffer growth to account for SO_SNDLOWAT |
| net.inet.tcp.sendbuf_inc | integer | 8192 | Incrementor step size of automatic send buffer |
| net.inet.tcp.sendbuf_max | integer | 2097152 | Max size of automatic send buffer |
| net.inet.tcp.sendspace | integer | 32768 | Initial send socket buffer size |
| net.inet.tcp.stats | opaque | Format:I Length:904 Dump:0x00000000000000000400000000000000... | TCP statistics (struct tcpstat, netinet/tcp_var.h) |
| net.inet.tcp.syncache.rexmtlimit | unsigned integer | 3 | Limit on SYN/ACK retransmissions |
| net.inet.tcp.syncache.rst_on_sock_fail | integer | 1 | Send reset on socket allocation failure |
| net.inet.tcp.syncookies | integer | 1 | Use TCP SYN cookies if the syncache overflows |
| net.inet.tcp.syncookies_only | integer | 0 | Use only TCP SYN cookies |
| net.inet.tcp.tso | integer | 1 | Enable TCP Segmentation Offload |
| net.inet.tcp.ts_offset_per_conn | integer | 1 | Initialize TCP timestamps per connection instead of per host pair |
| net.inet.tcp.v6mssdflt | integer | 1220 | Default TCP Maximum Segment Size for IPv6 |
| net.inet.tcp.v6pmtud_blackhole_mss | integer | 1220 | Path MTU Discovery IPv6 Black Hole Detection lowered MSS |
| net.inet.udp.blackhole | integer | 0 | Do not send port unreachables for refused connects |
| net.inet.udp.checksum | integer | 1 | compute udp checksum |
| net.inet.udp.log_in_vain | integer | 0 | Log all incoming UDP packets |
| net.inet.udp.maxdgram | unsigned long | 9216 | Maximum outgoing UDP datagram size |
| net.inet.udp.recvspace | unsigned long | 42080 | Maximum space for incoming UDP datagrams |
| net.inet.udp.stats | opaque | Format:I Length:112 Dump:0x07000000000000000000000000000000... | UDP statistics (struct udpstat, netinet/udp_var.h) |
| net.isr.dispatch | string | direct | netisr dispatch policy |
| net.key.ah_keymin | integer | 128 |  |
| net.key.blockacq_count | integer | 10 |  |
| net.key.blockacq_lifetime | integer | 20 |  |
| net.key.debug | integer | 0 |  |
| net.key.esp_auth | integer | 0 |  |
| net.key.esp_keymin | integer | 256 |  |
| net.key.int_random | integer | 60 |  |
| net.key.larval_lifetime | integer | 30 |  |
| net.key.preferred_oldsa | integer | 1 |  |
| net.key.spi_maxval | integer | 268435455 |  |
| net.key.spi_minval | integer | 256 |  |
| net.key.spi_trycnt | integer | 1000 |  |
| net.link.ether.arp.stats | opaque | Format:I Length:96 Dump:0x03000000000000000000000000000000... | ARP statistics (struct arpstat, net/if_arp.h) |
| net.link.ether.inet.allow_multicast | integer | 0 | accept multicast addresses |
| net.link.ether.inet.garp_rexmit_count | integer | 0 | Number of times to retransmit GARP packets; 0 to disable, maximum of 16 |
| net.link.ether.inet.log_arp_movements | integer | 1 | log arp replies from MACs different than the one in the cache |
| net.link.ether.inet.log_arp_permanent_modify | integer | 1 | log arp replies from MACs different than the one in the permanent arp entry |
| net.link.ether.inet.log_arp_wrong_iface | integer | 1 | log arp packets arriving on the wrong interface |
| net.link.ether.inet.max_age | integer | 1200 | ARP entry lifetime in seconds |
| net.link.ether.inet.maxhold | integer | 1 | Number of packets to hold per ARP entry |
| net.link.ether.inet.max_log_per_second | integer | 1 | Maximum number of remotely triggered ARP messages that can be logged per second |
| net.link.ether.inet.maxtries | integer | 5 | ARP resolution attempts before returning error |
| net.link.ether.inet.proxyall | integer | 0 | Enable proxy ARP for all suitable requests |
| net.link.ether.inet.wait | integer | 20 | Incomplete ARP entry lifetime in seconds |
| net.link.gif.max_nesting | integer | 1 | Max nested tunnels |
| net.link.log_link_state_change | integer | 1 | log interface link state change events |
| net.link.tun.devfs_cloning | integer | 1 | Enable legacy devfs interface creation. |
| net.link.vlan.mtag_pcp | integer | 0 | Retain VLAN PCP information as packets are passed up the stack |
| net.link.vlan.soft_pad | integer | 0 | pad short frames before tagging |
| net.local.dgram.maxdgram | unsigned long | 2048 | Default datagram send space. |
| net.local.dgram.recvspace | unsigned long | 4096 | Default datagram receive space. |
| net.local.seqpacket.maxseqpacket | unsigned long | 8192 | Default seqpacket send space. |
| net.local.seqpacket.recvspace | unsigned long | 8192 | Default seqpacket receive space. |
| net.local.stream.recvspace | unsigned long | 8192 | Default stream receive space. |
| net.local.stream.sendspace | unsigned long | 8192 | Default stream send space. |
| net.netdump.arp_retries | integer | 3 | Number of ARP attempts before giving up |
| net.netdump.debug | integer | 0 | Debug message verbosity |
| net.netdump.path | string |  | Server path for output files |
| net.netdump.polls | integer | 2000 | Number of times to poll before assuming packet loss (0.5ms per poll) |
| net.netdump.retries | integer | 10 | Number of retransmit attempts before giving up |
| net.raw.recvspace | unsigned long | 8192 | Default raw socket receive space |
| net.raw.sendspace | unsigned long | 8192 | Default raw socket send space |
| net.route.netisr_maxqlen | integer | 256 | maximum routing socket dispatch queue length |
| net.wlan.addba_backoff | integer | 10000 | ADDBA request backoff (ms) |
| net.wlan.addba_maxtries | integer | 3 | max ADDBA requests sent before backoff |
| net.wlan.addba_timeout | integer | 250 | ADDBA request timeout (ms) |
| net.wlan.ampdu_age | integer | 500 | AMPDU max reorder age (ms) |
| net.wlan.cac_timeout | integer | 60 | CAC timeout (secs) |
| net.wlan.debug | integer | 0 | debugging printfs |
| net.wlan.hwmp.inact | integer | 5000 | mesh route inactivity timeout (ms) |
| net.wlan.hwmp.maxpreq_retries | integer | 30 | maximum number of preq retries |
| net.wlan.hwmp.net_diameter_traversal_time | integer | 510 | estimate travelse time across the MBSS (ms) |
| net.wlan.hwmp.pathlifetime | integer | 5000 | path entry lifetime (ms) |
| net.wlan.hwmp.rannint | integer | 1000 | root announcement interval (ms) |
| net.wlan.hwmp.rootint | integer | 2000 | root interval (ms) |
| net.wlan.hwmp.roottimeout | integer | 5000 | root PREQ timeout (ms) |
| net.wlan.hwmp.targetonly | integer | 0 | Set TO bit on generated PREQs |
| net.wlan.mesh.backofftimeout | integer | 5000 | Backoff timeout (msec). This is to throutles peering forever when not receiving answer or is rejected by a neighbor |
| net.wlan.mesh.confirmtimeout | integer | 40 | Confirm state timeout (msec) |
| net.wlan.mesh.gateint | integer | 10000 | mesh gate interval (ms) |
| net.wlan.mesh.holdingtimeout | integer | 40 | Holding state timeout (msec) |
| net.wlan.mesh.maxholding | integer | 2 | Maximum times we are allowed to transition to HOLDING state before backinoff during peer link establishment |
| net.wlan.mesh.maxretries | integer | 2 | Maximum retries during peer link establishment |
| net.wlan.mesh.retrytimeout | integer | 40 | Retry timeout (msec) |
| net.wlan.nol_timeout | integer | 1800 | NOL timeout (secs) |
| net.wlan.recv_bar | integer | 1 | BAR frame processing (ena/dis) |
| p1003_1b.sem_nsems_max | integer | 0 |  |
| security.bsd.conservative_signals | integer | 1 | Unprivileged processes prevented from sending certain signals to processes whose credentials have changed |
| security.bsd.hardlink_check_gid | integer | 0 | Unprivileged processes cannot create hard links to files owned by other groups |
| security.bsd.hardlink_check_uid | integer | 0 | Unprivileged processes cannot create hard links to files owned by other users |
| security.bsd.map_at_zero | integer | 0 | Permit processes to map an object at virtual address 0. |
| security.bsd.see_jail_proc | integer | 1 | Unprivileged processes may see subjects/objects with different jail ids |
| security.bsd.see_other_gids | integer | 1 | Unprivileged processes may see subjects/objects with different real gid |
| security.bsd.see_other_uids | integer | 1 | Unprivileged processes may see subjects/objects with different real uid |
| security.bsd.stack_guard_page | integer | 1 | Specifies the number of guard pages for a stack that grows |
| security.bsd.suser_enabled | integer | 1 | processes with uid 0 have privilege |
| security.bsd.unprivileged_get_quota | integer | 0 | Unprivileged processes may retrieve quotas for other uids and gids |
| security.bsd.unprivileged_idprio | integer | 0 | Allow non-root users to set an idle priority |
| security.bsd.unprivileged_mlock | integer | 1 | Allow non-root users to call mlock(2) |
| security.bsd.unprivileged_proc_debug | integer | 1 | Unprivileged processes may use process debugging facilities |
| security.bsd.unprivileged_read_msgbuf | integer | 1 | Unprivileged processes may read the kernel message buffer |
| security.jail.allow_raw_sockets | integer | 0 | Prison root can create raw sockets (deprecated) |
| security.jail.chflags_allowed | integer | 0 | Processes in jail can alter system file flags (deprecated) |
| security.jail.enforce_statfs | integer | 2 | Processes in jail cannot see all mounted file systems (deprecated) |
| security.jail.jail_max_af_ips | unsigned integer | 255 | Number of IP addresses a jail may have at most per address family (deprecated) |
| security.jail.mount_allowed | integer | 0 | Processes in jail can mount/unmount jail-friendly file systems (deprecated) |
| security.jail.mount_devfs_allowed | integer | 0 | Jail may mount the devfs file system (deprecated) |
| security.jail.mount_procfs_allowed | integer | 0 | Jail may mount the procfs file system (deprecated) |
| security.jail.mount_zfs_allowed | integer | 0 | Jail may mount the zfs file system (deprecated) |
| security.jail.param.allow.chflags | integer | 0 | Jail may alter system file flags |
| security.jail.param.allow.mlock | integer | 0 | Jail may lock (unlock) physical pages in memory |
| security.jail.param.allow.mount. | integer | 0 | Jail may mount/unmount jail-friendly file systems in general |
| security.jail.param.allow.mount.devfs | integer | 0 | Jail may mount the devfs file system |
| security.jail.param.allow.mount.procfs | integer | 0 | Jail may mount the procfs file system |
| security.jail.param.allow.mount.zfs | integer | 0 | Jail may mount the zfs file system |
| security.jail.param.allow.quotas | integer | 0 | Jail may set file quotas |
| security.jail.param.allow.raw_sockets | integer | 0 | Jail may create raw sockets |
| security.jail.param.allow.read_msgbuf | integer | 0 | Jail may read the kernel message buffer |
| security.jail.param.allow.reserved_ports | integer | 0 | Jail may bind sockets to reserved ports |
| security.jail.param.allow.set_hostname | integer | 0 | Jail may set hostname |
| security.jail.param.allow.socket_af | integer | 0 | Jail may create sockets other than just UNIX/IPv4/IPv6/route |
| security.jail.param.allow.sysvipc | integer | 0 | Jail may use SYSV IPC |
| security.jail.param.children.max | integer | 0 | Maximum number of child jails |
| security.jail.param.devfs_ruleset | integer | 0 | Ruleset for in-jail devfs mounts |
| security.jail.param.enforce_statfs | integer | 0 | Jail cannot see all mounted file systems |
| security.jail.param.host. | integer | 0 | Jail host info |
| security.jail.param.host.domainname | string | 256 | Jail NIS domainname |
| security.jail.param.host.hostid | unsigned long | 0 | Jail host ID |
| security.jail.param.host.hostname | string | 256 | Jail hostname |
| security.jail.param.host.hostuuid | string | 64 | Jail host UUID |
| security.jail.param.ip4.addr | opaque | Format:S,in_addr,a Length:8 Dump:0x0400000000000000... | Jail IPv4 addresses |
| security.jail.param.ip4.saddrsel | integer | 0 | Do (not) use IPv4 source address selection rather than the primary jail IPv4 address. |
| security.jail.param.ip6.addr | opaque | Format:S,in6_addr,a Length:8 Dump:0x1000000000000000... | Jail IPv6 addresses |
| security.jail.param.ip6.saddrsel | integer | 0 | Do (not) use IPv6 source address selection rather than the primary jail IPv6 address. |
| security.jail.param.name | string | 256 | Jail name |
| security.jail.param.persist | integer | 0 | Jail persistence |
| security.jail.param.securelevel | integer | 0 | Jail secure level |
| security.jail.param.sysvmsg. | integer | 0 | SYSV message queues |
| security.jail.param.sysvsem. | integer | 0 | SYSV semaphores |
| security.jail.param.sysvshm. | integer | 0 | SYSV shared memory |
| security.jail.set_hostname_allowed | integer | 1 | Processes in jail can set their hostnames (deprecated) |
| security.jail.socket_unixiproute_only | integer | 1 | Processes in jail are limited to creating UNIX/IP/route sockets only (deprecated) |
| security.jail.sysvipc_allowed | integer | 0 | Processes in jail can use System V IPC primitives (deprecated) |
| security.mac.mmap_revocation | integer | 1 | Revoke mmap access to files on subject relabel |
| security.mac.mmap_revocation_via_cow | integer | 0 | Revoke mmap access to files via copy-on-write semantics, or by removing all write access |
| vfs.acl_nfs4_old_semantics | integer | 0 | Use pre-PSARC/2010/029 NFSv4 ACL semantics |
| vfs.aio.aiod_lifetime | integer | 3000 | Maximum lifetime for idle aiod |
| vfs.aio.enable_unsafe | integer | 0 | Permit asynchronous IO on all file types, not just known-safe types |
| vfs.aio.max_aio_per_proc | integer | 32 | Maximum active aio requests per process |
| vfs.aio.max_aio_procs | integer | 32 | Maximum number of kernel processes to use for handling async IO  |
| vfs.aio.max_aio_queue | integer | 1024 | Maximum number of aio requests to queue, globally |
| vfs.aio.max_aio_queue_per_proc | integer | 256 | Maximum queued aio requests per process |
| vfs.aio.max_buf_aio | integer | 16 | Maximum buf aio requests per process |
| vfs.aio.target_aio_procs | integer | 4 | Preferred number of ready kernel processes for async IO |
| vfs.aio.unsafe_warningcnt | unsigned integer | 1 | Warnings that will be triggered upon failed IO requests on unsafe files |
| vfs.altbufferflushes | integer | 0 | Number of fsync flushes to limit dirty buffers |
| vfs.barrierwrites | long integer | 0 | Number of barrier writes |
| vfs.bdwriteskip | integer | 0 | Number of buffers supplied to bdwrite with snapshot deadlock risk |
| vfs.bufdefragcnt | uint64_t | 0 | Number of times we have had to repeat buffer allocation to defragment |
| vfs.buffreekvacnt | uint64_t | 0 | Number of times we have freed the KVA space from some buffer |
| vfs.buf_pager_relbuf | integer | 0 | Make buffer pager release buffers after reading |
| vfs.bufspacethresh | long integer | 57971090 | Bufspace consumed before waking the daemon to free some |
| vfs.cd9660.use_buf_pager | integer | 1 | Use buffer pager instead of bmap |
| vfs.default_autoro | uint8_t | 0 | Retry failed r/w mount as r/o if no explicit ro/rw option is specified |
| vfs.devfs.dotimes | integer | 0 | Update timestamps on DEVFS with default precision |
| vfs.devfs.rule_depth | unsigned integer | 1 | Max depth of ruleset include |
| vfs.dirtybufferflushes | integer | 0 | Number of bdwrite to bawrite conversions to limit dirty buffers |
| vfs.dirtybufthresh | integer | 843 | Number of bdwrite to bawrite conversions to clear dirty buffers |
| vfs.ffs.compute_summary_at_mount | integer | 0 | Recompute summary at mount |
| vfs.ffs.doasyncfree | integer | 1 | do not force synchronous writes when blocks are reallocated |
| vfs.ffs.doasyncinodeinit | integer | 1 | Perform inode block initialization using asynchronous writes |
| vfs.ffs.doreallocblks | integer | 1 | enable block reallocation |
| vfs.ffs.dotrimcons | integer | 1 | enable BIO_DELETE / TRIM consolidation |
| vfs.ffs.maxclustersearch | integer | 10 | max number of cylinder group to search for contigous blocks |
| vfs.ffs.use_buf_pager | integer | 1 | Always use buffer pager instead of bmap |
| vfs.flushbufqtarget | integer | 100 | Amount of work to do in flushbufqueues when helping bufdaemon |
| vfs.flushwithdeps | integer | 0 | Number of buffers flushed with dependecies that require rollbacks |
| vfs.hibufspace | long integer | 59457536 | Maximum allowed value of bufspace (excluding metadata) |
| vfs.hidirtybuffers | integer | 937 | When the number of dirty buffers is considered severe |
| vfs.hifreebuffers | integer | 192 | Threshold for clean buffer recycling |
| vfs.hirunningspace | long integer | 1048576 | Maximum amount of space to use for in-progress I/O |
| vfs.ino64_trunc_error | integer | 0 | Error on truncation of device, file or inode number, or link count |
| vfs.lobufspace | long integer | 56484644 | Minimum amount of buffers we want to have |
| vfs.lodirtybuffers | integer | 468 | How many buffers we want to have free before bufdaemon can sleep |
| vfs.lofreebuffers | integer | 128 | Target number of free buffers |
| vfs.lookup_cap_dotdot | integer | 1 | enables ".." components in path lookup in capability mode |
| vfs.lookup_cap_dotdot_nonlocal | integer | 1 | enables ".." components in path lookup in capability mode on non-local mount |
| vfs.lorunningspace | long integer | 720896 | Minimum preferred space used for in-progress I/O |
| vfs.maxbufspace | long integer | 60112896 | Maximum allowed value of bufspace (including metadata) |
| vfs.maxmallocbufspace | long integer | 2972876 | Maximum amount of malloced memory for buffers |
| vfs.mnt_free_list_batch | unsigned long | 128 | Limit of vnodes held on mnt's free list |
| vfs.msdosfs.use_buf_pager | integer | 1 | Use buffer pager instead of bmap |
| vfs.ncnegfactor | unsigned long | 12 | Ratio of negative namecache entries |
| vfs.ncneghitsrequeue | unsigned integer | 8 | Number of hits to requeue a negative entry in the LRU list |
| vfs.ncpurgeminvnodes | unsigned integer | 128 | Number of vnodes below which purgevfs ignores the request |
| vfs.ncsizefactor | unsigned integer | 2 | Size factor for namecache |
| vfs.nfs.access_cache_timeout | integer | 60 | NFS ACCESS cache timeout |
| vfs.nfs.bufpackets | integer | 4 | Buffer reservation size 2 &lt; x &lt; 64 |
| vfs.nfs.callback_addr | string |  | NFSv4 callback addr for server to use |
| vfs.nfs.clean_pages_on_close | integer | 1 | NFS clean dirty pages on close |
| vfs.nfs.commit_on_close | integer | 0 | write+commit on close, else only write |
| vfs.nfsd.allowreadforwriteopen | integer | 1 | Allow Reads to be done with Write Access StateIDs |
| vfs.nfsd.async | integer | 0 | Tell client that writes were synced even though they were not |
| vfs.nfsd.cachetcp | unsigned integer | 1 | Enable the DRC for NFS over TCP |
| vfs.nfsd.commit_blks | integer | 0 |  |
| vfs.nfsd.commit_miss | integer | 0 |  |
| vfs.nfsd.debuglevel | integer | 0 | Debug level for NFS server |
| vfs.nfsd.default_flexfile | integer | 0 | Make Flex File Layout the default for pNFS |
| vfs.nfsd.dsdirsize | unsigned integer | 20 | Number of dsN subdirs on the DS servers |
| vfs.nfs.debuglevel | integer | 0 | Debug level for NFS client |
| vfs.nfs.defect | integer | 0 | Allow nfsiods to migrate serving different mounts |
| vfs.nfsd.enable_checkutf8 | integer | 1 | Enable the NFSv4 check for the UTF8 compliant name required by rfc3530 |
| vfs.nfsd.enable_locallocks | integer | 0 | Enable nfsd to acquire local locks on files |
| vfs.nfsd.enable_nobodycheck | integer | 1 | Enable the NFSv4 check when setting user nobody as owner |
| vfs.nfsd.enable_nogroupcheck | integer | 1 | Enable the NFSv4 check when setting group nogroup as owner |
| vfs.nfsd.enable_stringtouid | integer | 0 | Enable nfsd to accept numeric owner_names |
| vfs.nfsd.fha.bin_shift | unsigned integer | 22 | Maximum locality distance 2^(bin_shift) bytes |
| vfs.nfsd.fha.enable | unsigned integer | 1 | Enable NFS File Handle Affinity (FHA) |
| vfs.nfsd.fha.max_nfsds_per_fh | unsigned integer | 8 | Maximum nfsd threads that should be working on requests for the same file handle |
| vfs.nfsd.fha.max_reqs_per_nfsd | unsigned integer | 0 | Maximum requests that single nfsd thread should be working on at any time |
| vfs.nfsd.fha.read | unsigned integer | 1 | Enable NFS FHA read locality |
| vfs.nfsd.fha.write | unsigned integer | 1 | Enable NFS FHA write locality |
| vfs.nfsd.flexlinuxhack | integer | 0 | For Linux clients, hack around Flex File Layout bug |
| vfs.nfsd.issue_delegations | integer | 0 | Enable nfsd to issue delegations |
| vfs.nfsd.maxthreads | integer | 8 | Maximal number of threads |
| vfs.nfsd.minthreads | integer | 8 | Minimal number of threads |
| vfs.nfsd.mirrormnt | integer | 1 | Enable nfsd to cross mount points |
| vfs.nfsd.nfs_privport | integer | 0 | Only allow clients using a privileged port for NFSv2, 3 and 4 |
| vfs.nfs.downdelayinitial | integer | 12 |  |
| vfs.nfs.downdelayinterval | integer | 30 |  |
| vfs.nfsd.pnfsgetdsattr | integer | 1 | When set getattr gets DS attributes via RPC |
| vfs.nfsd.pnfsstrictatime | integer | 0 | For pNFS service, do Getattr ops to keep atime up-to-date |
| vfs.nfsd.request_space_high | unsigned long | 6553600 | Maximum space in parsed but not handled requests. |
| vfs.nfsd.request_space_low | unsigned long | 4369066 | Low water mark for request space. |
| vfs.nfsd.server_max_nfsvers | integer | 3 | The highest version of NFS handled by the server |
| vfs.nfsd.server_min_nfsvers | integer | 2 | The lowest version of NFS handled by the server |
| vfs.nfs.dsretries | integer | 2 | Number of retries for a DS RPC before failure |
| vfs.nfs.dssameconn | integer | 0 | Use same TCP connection to multiple DSs |
| vfs.nfsd.tcpcachetimeo | unsigned integer | 43200 | Timeout for TCP entries in the DRC |
| vfs.nfsd.tcphighwater | unsigned integer | 0 | High water mark for TCP cache entries |
| vfs.nfsd.udphighwater | unsigned integer | 500 | High water mark for UDP cache entries |
| vfs.nfsd.v4statelimit | integer | 500000 | High water limit for NFSv4 opens+locks+delegations |
| vfs.nfsd.writedelegifpos | integer | 0 | Issue a write delegation for read opens if possible |
| vfs.nfs.enable_uidtostring | integer | 0 | Make nfs always send numeric owner_names |
| vfs.nfs.fileid_maxwarnings | integer | 10 | Limit fileid corruption warnings; 0 is off; -1 is unlimited |
| vfs.nfs.ignore_eexist | integer | 0 | NFS ignore EEXIST replies for mkdir/symlink |
| vfs.nfs.iodmax | unsigned integer | 20 | Max number of nfsiod kthreads |
| vfs.nfs.iodmaxidle | unsigned integer | 120 | Max number of seconds an nfsiod kthread will sleep before exiting |
| vfs.nfs.iodmin | unsigned integer | 0 | Min number of nfsiod kthreads to keep as spares |
| vfs.nfs.nfs3_jukebox_delay | integer | 10 | Number of seconds to delay a retry after receiving EJUKEBOX |
| vfs.nfs.nfs_directio_allow_mmap | integer | 1 | Enable mmaped IO on file with O_DIRECT opens |
| vfs.nfs.nfs_directio_enable | integer | 0 | Enable NFS directio |
| vfs.nfs.nfs_ip_paranoia | integer | 1 |  |
| vfs.nfs.nfs_keep_dirty_on_error | integer | 0 | Retry pageout if error returned |
| vfs.nfs.pnfsiothreads | integer | -1 | Number of pNFS mirror I/O threads |
| vfs.nfs.prime_access_cache | integer | 0 | Prime NFS ACCESS cache when fetching attributes |
| vfs.nfs.realign_count | integer | 0 | Number of mbuf realignments done |
| vfs.nfs.realign_test | integer | 0 | Number of realign tests done |
| vfs.nfs.skip_wcc_data_onerr | integer | 1 | Disable weak cache consistency checking when server returns an error |
| vfs.nfs.use_buf_pager | integer | 1 | Use buffer pager instead of direct readrpc call |
| vfs.numbufallocfails | uint64_t | 0 | Number of times buffer allocations failed |
| vfs.read_max | integer | 64 | Cluster read-ahead max block count |
| vfs.read_min | integer | 1 | Cluster read min block count |
| vfs.reassignbufcalls | integer | 0 | Number of calls to reassignbuf |
| vfs.recursiveflushes | integer | 0 | Number of flushes skipped due to being recursive |
| vfs.timestamp_precision | integer | 2 | File timestamp precision (0 |
| vfs.ufs.dirhash_docheck | integer | 0 | enable extra sanity tests |
| vfs.ufs.dirhash_maxmem | integer | 2097152 | maximum allowed dirhash memory usage |
| vfs.ufs.dirhash_minsize | integer | 2560 | minimum directory size in bytes for which to use hashed lookup |
| vfs.ufs.dirhash_reclaimpercent | integer | 10 | set percentage of dirhash cache to be removed in low VM events |
| vfs.usermount | integer | 0 | Unprivileged users may mount and unmount file systems |
| vfs.vmiodirenable | integer | 1 | Use the VM system for directory writes |
| vfs.wantfreevnodes | unsigned long | 3228 | Target for minimum number of "free" vnodes |
| vfs.write_behind | integer | 1 | Cluster write-behind; 0 |
| vfs.zfs.abd_scatter_enabled | integer | 1 | Enable scattered ARC data buffers |
| vfs.zfs.arc_free_target | unsigned integer | 2545 | Desired number of free pages below which ARC triggers reclaim |
| vfs.zfs.arc_grow_retry | integer | 60 | Wait in seconds before considering growing ARC |
| vfs.zfs.arc_kmem_cache_reap_retry_ms | integer | 1000 | Interval between ARC kmem_cache reapings |
| vfs.zfs.arc_max | uint64_t | 41943040 | Maximum ARC size |
| vfs.zfs.arc_meta_limit | uint64_t | 10485760 | ARC metadata limit |
| vfs.zfs.arc_meta_strategy | integer | 0 | ARC metadata reclamation strategy (0 = metadata only, 1 = balance data and metadata) |
| vfs.zfs.arc_min | uint64_t | 16777216 | Minimum ARC size |
| vfs.zfs.arc_min_prefetch_ms | unsigned integer | 1 | Min life of prefetch block in ms |
| vfs.zfs.arc_min_prescient_prefetch_ms | unsigned integer | 6 | Min life of prescient prefetched block in ms |
| vfs.zfs.arc_no_grow_shift | uint32_t | 5 | log2(fraction of ARC which must be free to allow growing) |
| vfs.zfs.arc_shrink_shift | integer | 7 | log2(fraction of arc to reclaim) |
| vfs.zfs.cache_flush_disable | integer | 0 | Disable cache flush |
| vfs.zfs.ccw_retry_interval | integer | 300 | Configuration cache file write, retry after failure, interval (seconds) |
| vfs.zfs.check_hostid | integer | 1 | Check hostid on import? |
| vfs.zfs.condense_pct | integer | 200 | Condense on-disk spacemap when it is more than this many percents of in-memory counterpart |
| vfs.zfs.dbuf_cache_hiwater_pct | unsigned integer | 10 | max percents above the dbuf cache size |
| vfs.zfs.dbuf_cache_lowater_pct | unsigned integer | 10 | max percents below the dbuf cache size |
| vfs.zfs.dbuf_cache_max_bytes | int64_t | 1310720 | dbuf cache size in bytes |
| vfs.zfs.dbuf_metadata_cache_max_bytes | int64_t | 655360 | dbuf metadata cache size in bytes |
| vfs.zfs.deadman_checktime_ms | uint64_t | 5000 | Period of checks for stalled ZFS I/O in milliseconds |
| vfs.zfs.deadman_enabled | integer | 0 | Kernel panic on stalled ZFS I/O |
| vfs.zfs.deadman_synctime_ms | uint64_t | 1000000 | Stalled ZFS I/O expiration time in milliseconds |
| vfs.zfs.debug | integer | 0 | Debug level |
| vfs.zfs.debugflags | unsigned integer | 0 | Debug flags for ZFS testing. |
| vfs.zfs.dedup.prefetch | integer | 1 | Enable/disable prefetching of dedup-ed blocks which are going to be freed |
| vfs.zfs.default_bs | integer | 9 | Default dnode block shift |
| vfs.zfs.default_ibs | integer | 17 | Default dnode indirect block shift |
| vfs.zfs.delay_min_dirty_percent | integer | 60 | The limit of outstanding dirty data before transactions are delayed |
| vfs.zfs.delay_scale | uint64_t | 500000 | Controls how quickly the delay approaches infinity |
| vfs.zfs.dirty_data_max | uint64_t | 49235148 | The maximum amount of dirty data in bytes after which new writes are halted until space becomes available |
| vfs.zfs.dirty_data_max_percent | integer | 10 | The percent of physical memory used to auto calculate dirty_data_max |
| vfs.zfs.dirty_data_sync_pct | uint64_t | 20 | Force a txg if the percent of dirty buffer bytes exceed this value |
| vfs.zfs.free_bpobj_enabled | integer | 1 | Enable free_bpobj processing |
| vfs.zfs.free_max_blocks | uint64_t | 18446744073709551615 | Maximum number of blocks to free in one TXG |
| vfs.zfs.free_min_time_ms | unsigned integer | 1000 | Min millisecs to free per txg |
| vfs.zfs.immediate_write_sz | long integer | 32768 | Minimal size for indirect log write |
| vfs.zfs.l2arc_feed_again | integer | 1 | turbo warmup |
| vfs.zfs.l2arc_feed_min_ms | uint64_t | 200 | min interval milliseconds |
| vfs.zfs.l2arc_feed_secs | uint64_t | 1 | interval seconds |
| vfs.zfs.l2arc_headroom | uint64_t | 2 | number of dev writes |
| vfs.zfs.l2arc_noprefetch | integer | 1 | don't cache prefetch bufs |
| vfs.zfs.l2arc_norw | integer | 1 | no reads during writes |
| vfs.zfs.l2arc_write_boost | uint64_t | 8388608 | extra write during warmup |
| vfs.zfs.l2arc_write_max | uint64_t | 8388608 | max write size |
| vfs.zfs.max_auto_ashift | uint64_t | 13 | Max ashift used when optimising for logical -&gt; physical sectors size on new top-level vdevs. |
| vfs.zfs.max_missing_tvds | uint64_t | 0 | allow importing pools with missing top-level vdevs |
| vfs.zfs.max_missing_tvds_cachefile | uint64_t | 2 | allow importing pools with missing top-level vdevs in cache file |
| vfs.zfs.max_missing_tvds_scan | uint64_t | 0 | allow importing pools with missing top-level vdevs during scan |
| vfs.zfs.max_recordsize | integer | 1048576 | Maximum block size.  Expect dragons when tuning this. |
| vfs.zfs.mdcomp_disable | integer | 0 | Disable metadata compression |
| vfs.zfs.metaslab.bias_enabled | integer | 1 | Enable metaslab group biasing |
| vfs.zfs.metaslab.debug_load | integer | 0 | Load all metaslabs when pool is first opened |
| vfs.zfs.metaslab.debug_unload | integer | 0 | Prevent metaslabs from being unloaded |
| vfs.zfs.metaslab.df_alloc_threshold | int64_t | 131072 | Minimum size which forces the dynamic allocator to change it's allocation strategy |
| vfs.zfs.metaslab.df_free_pct | integer | 4 | The minimum free space, in percent, which must be available in a space map to continue allocations in a first-fit fashion |
| vfs.zfs.metaslab.force_ganging | int64_t | 16777217 | Force gang block allocation for blocks larger than or equal to this value |
| vfs.zfs.metaslab.fragmentation_factor_enabled | integer | 1 | Enable fragmentation weighting on metaslabs |
| vfs.zfs.metaslab.fragmentation_threshold | integer | 70 | Maximum percentage of metaslab fragmentation level to keep their active state |
| vfs.zfs.metaslab.lba_weighting_enabled | integer | 1 | Enable LBA weighting (i.e. outer tracks are given preference) |
| vfs.zfs.metaslab.load_pct | integer | 50 | Percentage of cpus that can be used by the metaslab taskq |
| vfs.zfs.metaslab.min_alloc_size | int64_t | 33554432 | A metaslab is considered "free" if it contains a contiguous segment which is greater than vfs.zfs.metaslab.min_alloc_size |
| vfs.zfs.metaslab.preload_enabled | integer | 1 | Max number of metaslabs per group to preload |
| vfs.zfs.metaslab.preload_limit | integer | 3 | Max number of metaslabs per group to preload |
| vfs.zfs.metaslab.unload_delay | integer | 8 | Number of TXGs that an unused metaslab can be kept in memory |
| vfs.zfs.mg_fragmentation_threshold | integer | 85 | Percentage of metaslab group size that should be considered eligible for allocations unless all metaslab groups within the metaslab class have also crossed this threshold |
| vfs.zfs.mg_noalloc_threshold | integer | 0 | Percentage of metaslab group size that should be free to make it eligible for allocation |
| vfs.zfs.min_auto_ashift | uint64_t | 12 | Min ashift used when creating new top-level vdevs. |
| vfs.zfs.no_scrub_io | integer | 0 | Disable scrub I/O |
| vfs.zfs.no_scrub_prefetch | integer | 0 | Disable scrub prefetching |
| vfs.zfs.per_txg_dirty_frees_percent | integer | 30 | Percentage of dirtied blocks from frees in one txg |
| vfs.zfs.prefetch_disable | integer | 1 | Disable prefetch |
| vfs.zfs.recover | integer | 0 | Try to recover from otherwise-fatal errors. |
| vfs.zfs.resilver_delay | unsigned integer | 2 | Number of ticks to delay resilver |
| vfs.zfs.resilver_min_time_ms | unsigned integer | 3000 | Min millisecs to resilver per txg |
| vfs.zfs.scan_idle | unsigned integer | 50 | Idle scan window in clock ticks |
| vfs.zfs.scan_min_time_ms | unsigned integer | 1000 | Min millisecs to scrub per txg |
| vfs.zfs.scrub_delay | unsigned integer | 4 | Number of ticks to delay scrub |
| vfs.zfs.send_holes_without_birth_time | unsigned integer | 1 | Send holes without birth time |
| vfs.zfs.spa_allocators | integer | 4 | Number of allocators per metaslab group |
| vfs.zfs.spa_asize_inflation | integer | 24 | Worst case inflation factor for single sector writes |
| vfs.zfs.space_map_ibs | integer | 14 | Space map indirect block shift |
| vfs.zfs.spa_load_print_vdev_tree | integer | 0 | print out vdev tree during pool import |
| vfs.zfs.spa_load_verify_data | integer | 1 | Check user data on import? |
| vfs.zfs.spa_load_verify_maxinflight | integer | 10000 | Maximum number of concurrent scrub I/Os to create while verifying a pool while importing it |
| vfs.zfs.spa_load_verify_metadata | integer | 1 | Check metadata on import? |
| vfs.zfs.spa_min_slop | uint64_t | 134217728 | Minimal value of reserved space |
| vfs.zfs.spa_slop_shift | integer | 5 | Shift value of reserved space (1/(2^spa_slop_shift)). |
| vfs.zfs.super_owner | integer | 0 | File system owner can perform privileged operation on his file systems |
| vfs.zfs.top_maxinflight | unsigned integer | 32 | Maximum I/Os per top-level vdev |
| vfs.zfs.trim.max_interval | unsigned integer | 1 | Maximum interval between TRIM queue processing (seconds) |
| vfs.zfs.trim.timeout | unsigned integer | 30 | Delay TRIMs by up to this many seconds |
| vfs.zfs.trim.txg_delay | unsigned integer | 32 | Delay TRIMs by up to this many TXGs |
| vfs.zfs.txg.timeout | integer | 5 | Maximum seconds worth of delta per txg |
| vfs.zfs.vdev.aggregation_limit | integer | 1048576 | I/O requests are aggregated up to this size |
| vfs.zfs.vdev.aggregation_limit_non_rotating | integer | 131072 | I/O requests are aggregated up to this size for non-rotating media |
| vfs.zfs.vdev.async_read_max_active | unsigned integer | 3 | Maximum number of I/O requests of type async_read active for each device |
| vfs.zfs.vdev.async_read_min_active | unsigned integer | 1 | Initial number of I/O requests of type async_read active for each device |
| vfs.zfs.vdev.async_write_active_max_dirty_percent | unsigned integer | 60 | Percentage of async write dirty data above which async_write_max_active is used. |
| vfs.zfs.vdev.async_write_active_min_dirty_percent | unsigned integer | 30 | Percentage of async write dirty data below which async_write_min_active is used. |
| vfs.zfs.vdev.async_write_max_active | unsigned integer | 10 | Maximum number of I/O requests of type async_write active for each device |
| vfs.zfs.vdev.async_write_min_active | unsigned integer | 1 | Initial number of I/O requests of type async_write active for each device |
| vfs.zfs.vdev.bio_delete_disable | integer | 0 | Disable BIO_DELETE |
| vfs.zfs.vdev.bio_flush_disable | integer | 0 | Disable BIO_FLUSH |
| vfs.zfs.vdev.default_ms_shift | integer | 29 | Default shift between vdev size and number of metaslabs |
| vfs.zfs.vdev.def_queue_depth | integer | 32 | Default queue depth for each allocator |
| vfs.zfs.vdev.initializing_max_active | unsigned integer | 1 | Maximum number of I/O requests of type initializing active for each device |
| vfs.zfs.vdev.initializing_min_active | unsigned integer | 1 | Initial number of I/O requests of type initializing active for each device |
| vfs.zfs.vdev.max_active | unsigned integer | 1000 | The maximum number of I/Os of all types active for each device. |
| vfs.zfs.vdev.max_ms_count | integer | 200 | Target number of metaslabs per top-level vdev |
| vfs.zfs.vdev.max_ms_count_limit | integer | 131072 | Maximum number of metaslabs per top-level vdev |
| vfs.zfs.vdev.max_ms_shift | integer | 38 | Maximum shift between vdev size and number of metaslabs |
| vfs.zfs.vdev.min_ms_count | integer | 16 | Minimum number of metaslabs per top-level vdev |
| vfs.zfs.vdev.mirror.non_rotating_inc | integer | 0 | Non-rotating media load increment for non-seeking I/O's |
| vfs.zfs.vdev.mirror.non_rotating_seek_inc | integer | 1 | Non-rotating media load increment for seeking I/O's |
| vfs.zfs.vdev.mirror.rotating_inc | integer | 0 | Rotating media load increment for non-seeking I/O's |
| vfs.zfs.vdev.mirror.rotating_seek_inc | integer | 5 | Rotating media load increment for seeking I/O's |
| vfs.zfs.vdev.mirror.rotating_seek_offset | integer | 1048576 | Offset in bytes from the last I/O which triggers a reduced rotating media seek increment |
| vfs.zfs.vdev.queue_depth_pct | integer | 1000 | Queue depth percentage for each top-level |
| vfs.zfs.vdev.read_gap_limit | integer | 32768 | Acceptable gap between two reads being aggregated |
| vfs.zfs.vdev.removal_max_active | unsigned integer | 2 | Maximum number of I/O requests of type removal active for each device |
| vfs.zfs.vdev.removal_min_active | unsigned integer | 1 | Initial number of I/O requests of type removal active for each device |
| vfs.zfs.vdev.scrub_max_active | unsigned integer | 2 | Maximum number of I/O requests of type scrub active for each device |
| vfs.zfs.vdev.scrub_min_active | unsigned integer | 1 | Initial number of I/O requests of type scrub active for each device |
| vfs.zfs.vdev.sync_read_max_active | unsigned integer | 10 | Maximum number of I/O requests of type sync_read active for each device |
| vfs.zfs.vdev.sync_read_min_active | unsigned integer | 10 | Initial number of I/O requests of type sync_read active for each device |
| vfs.zfs.vdev.sync_write_max_active | unsigned integer | 10 | Maximum number of I/O requests of type sync_write active for each device |
| vfs.zfs.vdev.sync_write_min_active | unsigned integer | 10 | Initial number of I/O requests of type sync_write active for each device |
| vfs.zfs.vdev.trim_max_active | unsigned integer | 64 | Maximum number of I/O requests of type trim active for each device |
| vfs.zfs.vdev.trim_max_pending | unsigned integer | 10000 | Maximum pending TRIM segments for a vdev |
| vfs.zfs.vdev.trim_min_active | unsigned integer | 1 | Initial number of I/O requests of type trim active for each device |
| vfs.zfs.vdev.trim_on_init | integer | 1 | Enable/disable full vdev trim on initialisation |
| vfs.zfs.vdev.validate_skip | integer | 0 | Bypass vdev validation |
| vfs.zfs.vdev.write_gap_limit | integer | 4096 | Acceptable gap between two writes being aggregated |
| vfs.zfs.vol.immediate_write_sz | long integer | 32768 | Minimal size for indirect log write |
| vfs.zfs.vol.mode | integer | 1 | Expose as GEOM providers (1), device files (2) or neither |
| vfs.zfs.vol.recursive | integer | 0 | Allow zpools to use zvols as vdevs (DANGEROUS) |
| vfs.zfs.vol.unmap_enabled | integer | 1 | Enable UNMAP functionality |
| vfs.zfs.vol.unmap_sync_enabled | integer | 0 | UNMAPs requested as sync are executed synchronously |
| vfs.zfs.zfetch.array_rd_sz | uint64_t | 1048576 | Number of bytes in a array_read at which we stop prefetching |
| vfs.zfs.zfetch.max_distance | unsigned integer | 8388608 | Max bytes to prefetch per stream |
| vfs.zfs.zfetch.max_idistance | unsigned integer | 67108864 | Max bytes to prefetch indirects for per stream |
| vfs.zfs.zfetch.max_streams | unsigned integer | 8 | Max # of streams per zfetch |
| vfs.zfs.zfetch.min_sec_reap | unsigned integer | 2 | Min time before stream reclaim |
| vfs.zfs.zfs_scan_checkpoint_interval | unsigned integer | 7200 | Scan progress on-disk checkpointing interval |
| vfs.zfs.zfs_scan_legacy | unsigned integer | 0 | Scrub using legacy non-sequential method |
| vfs.zfs.zil_nocacheflush | integer | 0 | Disable ZIL cache flush |
| vfs.zfs.zil_replay_disable | integer | 0 | Disable intent logging replay |
| vfs.zfs.zil_slog_bulk | int64_t | 786432 | Maximal SLOG commit size with sync priority |
| vfs.zfs.zio.dva_throttle_enabled | integer | 1 | Enable allocation throttling |
| vm.act_scan_laundry_weight | integer | 3 | weight given to clean vs. dirty pages in active queue scans |
| vm.background_launder_max | unsigned integer | 20480 | background laundering cap, in kilobytes |
| vm.background_launder_rate | unsigned integer | 4096 | background laundering rate, in kilobytes per second |
| vm.cluster_anon | integer | 1 | Cluster anonymous mappings |
| vm.disable_swapspace_pageouts | integer | 0 | Disallow swapout of dirty pages |
| vm.domain.0.pidctrl.bound | integer | 40720 | Integral wind-up limit |
| vm.domain.0.pidctrl.kdd | integer | 8 | Inverse of derivative gain |
| vm.domain.0.pidctrl.kid | integer | 4 | Inverse of integral gain |
| vm.domain.0.pidctrl.kpd | integer | 3 | Inverse of proportional gain |
| vm.domain.0.pidctrl.setpoint | integer | 2545 | Desired level for process variable |
| vm.kstack_cache_size | integer | 128 |  |
| vm.lowmem_period | integer | 10 | Low memory callback period |
| vm.max_wired | integer | 37626 | System-wide limit to wired page count |
| vm.md_malloc_wait | integer | 0 | Allow malloc to wait for memory allocations |
| vm.mincore_mapped | integer | 1 | mincore reports mappings, not residency |
| vm.old_mlock | integer | 0 | Do not apply RLIMIT_MEMLOCK on mlockall |
| vm.old_msync | integer | 0 | Use old (insecure) msync behavior |
| vm.oom_pf_secs | integer | 10 |  |
| vm.overcommit | integer | 0 | Configure virtual memory overcommit behavior. See tuning(7) for details. |
| vm.pageout_oom_seq | integer | 12 | back-to-back calls to oom detector to start OOM |
| vm.pageout_update_period | integer | 600 | Maximum active LRU update period |
| vm.panic_on_oom | integer | 0 | panic on out of memory instead of killing the largest process |
| vm.pfault_oom_attempts | integer | 3 | Number of page allocation attempts in page fault handler before it triggers OOM handling |
| vm.pfault_oom_wait | integer | 10 | Number of seconds to wait for free pages before retrying the page fault handler |
| vm.phys_pager_cluster | integer | 1024 | prefault window size for phys pager |
| vm.pmap.allow_2m_x_ept | integer | 0 | Allow executable superpage mappings in EPT |
| vm.swap_async_max | integer | 4 | Maximum running async swap ops |
| vm.swap_enabled | integer | 1 | Enable entire process swapout |
| vm.swap_idle_enabled | integer | 0 | Allow swapout on idle criteria |
| vm.swap_idle_threshold1 | integer | 2 | Guaranteed swapped in time for a process |
| vm.swap_idle_threshold2 | integer | 10 | Time before a process will be swapped out |
| vm.v_free_min | unsigned integer | 799 | Minimum low-free-pages threshold |
| vm.v_free_reserved | unsigned integer | 217 | Pages reserved for deadlock |
| vm.v_free_severe | unsigned integer | 508 | Severe page depletion point |
| vm.v_free_target | unsigned integer | 2545 | Desired free pages |
| vm.v_inactive_target | unsigned integer | 3817 | Pages desired inactive |
| vm.v_pageout_free_min | unsigned integer | 34 | Min pages reserved for kernel |
| vm.zone_warnings | integer | 1 | Warn when UMA zones becomes full |
