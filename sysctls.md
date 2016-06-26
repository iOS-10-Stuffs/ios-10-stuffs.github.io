---
layout: default
title: sysctls
---

The following was generated via output from [jtool](http://www.newosxbook.com/tools/jtool.html):

```
This is a 64-bit kernel from iOS 10.x, or later (3705.0.0.2.3)
Dumping sysctl_set from 0xfffffff007913950 (offset in file: 0x50f950), 41d sysctls follow:
0xfffffff0078f4238: kern.nbuf Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff007969144
Arg2: 0x7fff00000000
0xfffffff0078f4288: kern.maxnbuf Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff007969138
Arg2: 0x7fff00000000
0xfffffff0078f43c8: debug.lowpri_throttle_max_iosize Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990158
Arg1: fffffff0078f43c4
Arg2: 0x7fff00000000
0xfffffff0078f4630: vfs.nummntops Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990148
Arg1: fffffff00796dbc4
Arg2: 0x7fff00000000
0xfffffff0078f46d0: vfs.generic.trace_paths Description: trace_paths
Handler: 0xfffffff00759c6b8
Format: -
Parent: 0xfffffff0079900b0
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078f4720: kern.flush_cache_on_write Description: always flush the drive cache on writes to uncached files
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff00796db60
Arg2: 0x7fff00000000
0xfffffff0078f4778: vfs.generic.conf Description: 
Handler: 0xfffffff00759c5b4
Format: N
Parent: 0xfffffff0079900b0
Arg1: fffffff00796db78
Arg2: 0x7fff00000000
0xfffffff0078f47c8: vfs.generic.sync_timeout Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079900b0
Arg1: fffffff0078f49ac
Arg2: 0x7fff00000000
0xfffffff0078f4818: vfs.generic.maxtypenum Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079900b0
Arg1: fffffff0078f4420
Arg2: 0x7fff00000000
0xfffffff0078f4868: vfs.generic.noremotehang Description: noremotehang
Handler: 0xfffffff00759c4b4
Format: I
Parent: 0xfffffff0079900b0
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078f48b8: vfs.generic.ctlbyfsid Description: ctlbyfsid
Handler: 0xfffffff00759be8c
Format: N
Parent: 0xfffffff0079900b0
Arg1: fffffff00796db80
Arg2: 0x7fff00000000
0xfffffff0078f4908: vfs.generic.vfsidlist Description: List of mounted filesystem ids
Handler: 0xfffffff00759bcd4
Format: S,fsid
Parent: 0xfffffff0079900b0
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078f62c0: debug.lowpri_throttle_enabled Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990158
Arg1: fffffff0078f65e0
Arg2: 0x7fff00000000
0xfffffff0078f6310: debug.lowpri_throttle_tier3_io_period_ssd_msecs Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990158
Arg1: fffffff0078f65f0
Arg2: 0x7fff00000000
0xfffffff0078f6360: debug.lowpri_throttle_tier2_io_period_ssd_msecs Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990158
Arg1: fffffff0078f65ec
Arg2: 0x7fff00000000
0xfffffff0078f63b0: debug.lowpri_throttle_tier1_io_period_ssd_msecs Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990158
Arg1: fffffff0078f65e8
Arg2: 0x7fff00000000
0xfffffff0078f6400: debug.lowpri_throttle_tier3_io_period_msecs Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990158
Arg1: fffffff0078f6600
Arg2: 0x7fff00000000
0xfffffff0078f6450: debug.lowpri_throttle_tier2_io_period_msecs Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990158
Arg1: fffffff0078f65fc
Arg2: 0x7fff00000000
0xfffffff0078f64a0: debug.lowpri_throttle_tier1_io_period_msecs Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990158
Arg1: fffffff0078f65f8
Arg2: 0x7fff00000000
0xfffffff0078f64f0: debug.lowpri_throttle_tier3_window_msecs Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990158
Arg1: fffffff0078f6610
Arg2: 0x7fff00000000
0xfffffff0078f6540: debug.lowpri_throttle_tier2_window_msecs Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990158
Arg1: fffffff0078f660c
Arg2: 0x7fff00000000
0xfffffff0078f6590: debug.lowpri_throttle_tier1_window_msecs Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990158
Arg1: fffffff0078f6608
Arg2: 0x7fff00000000
0xfffffff0078f6cd0: debug.bpf_bufsize Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990158
Arg1: fffffff0078f6d20
Arg2: 0x7fff00000000
0xfffffff0078f6d28: debug.bpf_maxbufsize Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990158
Arg1: fffffff0078f6d24
Arg2: 0x7fff00000000
0xfffffff0078f6d78: debug.bpf_maxdevices Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990158
Arg1: fffffff0078f6dc8
Arg2: 0x7fff00000000
0xfffffff0078f6dd0: debug.bpf_wantpktap Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990158
Arg1: fffffff0078f6e20
Arg2: 0x7fff00000000
0xfffffff0078f6e28: debug.bpf_debug Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990158
Arg1: fffffff0079768c4
Arg2: 0x7fff00000000
0xfffffff0078f6f18: net.link.bridge.inherit_mac Description: Inherit MAC address from the first bridge member
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007976920
Arg1: fffffff007976928
Arg2: 0x7fff00000000
0xfffffff0078f6f68: net.link.bridge.rtable_prune_period Description: Interval between pruning of routing table
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007976920
Arg1: fffffff0078f6fb8
Arg2: 0x7fff00000000
0xfffffff0078f6fc0: net.link.bridge.rtable_hash_size_max Description: Maximum size of the routing hash table
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007976920
Arg1: fffffff0078f7010
Arg2: 0x7fff00000000
0xfffffff0078f7018: net.link.bridge.hostfilterstats Description: 
Handler: 0xfffffff00778ea2c
Format: S,bridge_hostfilter_stats
Parent: 0xfffffff007976920
Arg1: fffffff007976930
Arg2: 0x7fff000000c8
0xfffffff0078f7068: net.link.bridge.txstart Description: Bridge interface uses TXSTART model
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007976920
Arg1: fffffff0079769f8
Arg2: 0x7fff00000000
0xfffffff0078f70b8: net.link.bridge.debug Description: Bridge debug
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007976920
Arg1: fffffff0079769fc
Arg2: 0x7fff00000000
0xfffffff0078f71e0: system.if_verbose Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007976e98
Arg1: fffffff007976a50
Arg2: 0x7fff00000000
0xfffffff0078f7248: system.dlil_lladdr_ckreq Description: Require MACF system info check to expose link-layer address
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007976e98
Arg1: fffffff0078f7240
Arg2: 0x7fff00000000
0xfffffff0078f7298: system.dlil_verbose Description: Log DLIL error messages
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007976e98
Arg1: fffffff007976c90
Arg2: 0x7fff00000000
0xfffffff0078f7390: system.get_ports_used Description: 
Handler: 0xfffffff0075e4890
Format: N
Parent: 0xfffffff007976e98
Arg1: fffffff007976d20
Arg2: 0x7fff00000000
0xfffffff0078f73e0: system.tx_chain_len_count Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007976e98
Arg1: fffffff007976e28
Arg2: 0x7fff00000000
0xfffffff0078f7430: system.tx_chain_len_stats Description: 
Handler: 0xfffffff0075e4868
Format: S
Parent: 0xfffffff007976e98
Arg1: 0
Arg2: 0x7fff00000009
0xfffffff0078f7480: system.hwcksum_rx Description: enable receive hardware checksum offload
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007976e98
Arg1: fffffff0078f74d0
Arg2: 0x7fff00000000
0xfffffff0078f74d8: system.hwcksum_tx Description: enable transmit hardware checksum offload
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007976e98
Arg1: fffffff0078f7528
Arg2: 0x7fff00000000
0xfffffff0078f7530: system.hwcksum_dbg_finalized_data Description: finalized payloads
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007976e98
Arg1: fffffff007976cb8
Arg2: 0x7fff00000000
0xfffffff0078f7580: system.hwcksum_dbg_finalized_hdr Description: finalized headers
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007976e98
Arg1: fffffff007976cc0
Arg2: 0x7fff00000000
0xfffffff0078f75d0: system.hwcksum_dbg_adjusted Description: packets with rxoff adjusted
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007976e98
Arg1: fffffff007976cc8
Arg2: 0x7fff00000000
0xfffffff0078f7620: system.hwcksum_dbg_bad_rxoff Description: packets with invalid rxoff
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007976e98
Arg1: fffffff007976cd0
Arg2: 0x7fff00000000
0xfffffff0078f7670: system.hwcksum_dbg_bad_cksum Description: packets with bad hardware calculated checksum
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007976e98
Arg1: fffffff007976cd8
Arg2: 0x7fff00000000
0xfffffff0078f76c0: system.hwcksum_dbg_verified Description: packets verified for having good checksum
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007976e98
Arg1: fffffff007976ce0
Arg2: 0x7fff00000000
0xfffffff0078f7710: system.hwcksum_dbg_partial_rxoff_adj Description: adjusted partial cksum rx offset
Handler: 0xfffffff0075e47f0
Format: I
Parent: 0xfffffff007976e98
Arg1: fffffff007976ce8
Arg2: 0x7fff00000000
0xfffffff0078f7760: system.hwcksum_dbg_partial_rxoff_forced Description: forced partial cksum rx offset
Handler: 0xfffffff0075e4778
Format: I
Parent: 0xfffffff007976e98
Arg1: fffffff007976cec
Arg2: 0x7fff00000000
0xfffffff0078f77b0: system.hwcksum_dbg_partial_forced_bytes Description: bytes forced using partial cksum
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007976e98
Arg1: fffffff007976cf0
Arg2: 0x7fff00000000
0xfffffff0078f7800: system.hwcksum_dbg_partial_forced Description: packets forced using partial cksum
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007976e98
Arg1: fffffff007976cf8
Arg2: 0x7fff00000000
0xfffffff0078f7850: system.hwcksum_dbg_mode Description: hardware cksum debugging mode
Handler: 0xfffffff0075e46e4
Format: I
Parent: 0xfffffff007976e98
Arg1: fffffff007976d00
Arg2: 0x7fff00000000
0xfffffff0078f78a0: system.start_delay_disabled Description: number of times start was delayed
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007976e98
Arg1: fffffff007976e2c
Arg2: 0x7fff00000000
0xfffffff0078f78f0: system.start_delayed Description: number of times start was delayed
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007976e98
Arg1: fffffff007976e30
Arg2: 0x7fff00000000
0xfffffff0078f7940: system.hwcksum_dbg Description: enable hardware cksum debugging
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007976e98
Arg1: fffffff007976e34
Arg2: 0x7fff00000000
0xfffffff0078f7990: system.hwcksum_in_invalidated Description: inbound packets with invalidated hardware cksum
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007976e98
Arg1: fffffff007976d08
Arg2: 0x7fff00000000
0xfffffff0078f79e0: system.delaybased_queue Description: enable delay based dynamic queue sizing
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007976e98
Arg1: fffffff0078f7348
Arg2: 0x7fff00000001
0xfffffff0078f7a30: system.flow_advisory Description: enable flow-advisory mechanism
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007976e98
Arg1: fffffff0078f734c
Arg2: 0x7fff00000001
0xfffffff0078f7a80: system.dlil_input_threads Description: Current number of DLIL input threads
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007976e98
Arg1: fffffff007976d10
Arg2: 0x7fff00000000
0xfffffff0078f7ad0: system.if_bw_measure_size Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007976e98
Arg1: fffffff0078f7b20
Arg2: 0x7fff00000000
0xfffffff0078f7b28: system.if_bw_smoothing_val Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007976e98
Arg1: fffffff0078f7b78
Arg2: 0x7fff00000000
0xfffffff0078f7b80: system.rxpoll Description: enable opportunistic input polling
Handler: 0xfffffff0075e466c
Format: I
Parent: 0xfffffff007976e98
Arg1: fffffff0078f7350
Arg2: 0x7fff00000000
0xfffffff0078f7bd0: system.rxpoll_max Description: max packets per poll call
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007976e98
Arg1: fffffff007976d14
Arg2: 0x7fff00000000
0xfffffff0078f7c20: system.rxpoll_wakeups_hiwat Description: input poll wakeup high watermark
Handler: 0xfffffff0075e45f0
Format: I
Parent: 0xfffffff007976e98
Arg1: fffffff0078f7354
Arg2: 0x7fff00000064
0xfffffff0078f7c70: system.rxpoll_wakeups_lowat Description: input poll wakeup low watermark
Handler: 0xfffffff0075e4574
Format: I
Parent: 0xfffffff007976e98
Arg1: fffffff0078f7358
Arg2: 0x7fff0000000a
0xfffffff0078f7cc0: system.rxpoll_interval_pkts Description: input poll interval (packets)
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007976e98
Arg1: fffffff007976d18
Arg2: 0x7fff00000000
0xfffffff0078f7d10: system.rxpoll_interval_time Description: input poll interval (time)
Handler: 0xfffffff0075e450c
Format: Q
Parent: 0xfffffff007976e98
Arg1: fffffff0078f7360
Arg2: 0x7fff000f4240
0xfffffff0078f7d60: system.rxpoll_sample_time Description: input poll sampling time
Handler: 0xfffffff0075e4498
Format: Q
Parent: 0xfffffff007976e98
Arg1: fffffff0078f7368
Arg2: 0x7fff00989680
0xfffffff0078f7db0: system.rxpoll_freeze_time Description: input poll mode freeze time
Handler: 0xfffffff0075e4424
Format: Q
Parent: 0xfffffff007976e98
Arg1: fffffff0078f7370
Arg2: 0x7fff3b9aca00
0xfffffff0078f7e00: system.rxpoll_decay Description: ilog2 of EWMA decay rate of avg inbound packets
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007976e98
Arg1: fffffff0078f7378
Arg2: 0x7fff00000002
0xfffffff0078f7e50: system.rcvq_maxlen Description: Default receive queue max length
Handler: 0xfffffff0075e43bc
Format: I
Parent: 0xfffffff007976e98
Arg1: fffffff0078f7ea0
Arg2: 0x7fff00000080
0xfffffff0078f72f0: system.sndq_maxlen Description: Default transmit queue max length
Handler: 0xfffffff0075e4354
Format: I
Parent: 0xfffffff007976e98
Arg1: fffffff0078f72e8
Arg2: 0x7fff00000080
0xfffffff0078f7f50: loopback.bw_sleep_usec Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007976e68
Arg1: fffffff0078f7fa0
Arg2: 0x7fff0000000a
0xfffffff0078f7fa8: loopback.bw_measure Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007976e68
Arg1: fffffff007976e70
Arg2: 0x7fff00000000
0xfffffff0078f8050: loopback.dequeue_sc Description: Dequeue a specific SC index
Handler: 0xfffffff0075f398c
Format: I
Parent: 0xfffffff007976e68
Arg1: fffffff007976e7c
Arg2: 0x7fff00000000
0xfffffff0078f80a0: loopback.sched_model Description: Scheduling model
Handler: 0xfffffff0075f3904
Format: I
Parent: 0xfffffff007976e68
Arg1: fffffff007976e80
Arg2: 0x7fff00000000
0xfffffff0078f7ff8: loopback.max_dequeue Description: Maximum number of packets dequeued at a time
Handler: 0xfffffff0075f3890
Format: I
Parent: 0xfffffff007976e68
Arg1: fffffff0078f8048
Arg2: 0x7fff00000100
0xfffffff0078f8140: system.ifcount Description: Number of configured interfaces
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007976e98
Arg1: fffffff007976a68
Arg2: 0x7fff00000000
0xfffffff0078f81e8: generic.ifalldata Description: Interface table
Handler: 0xfffffff0075f4a78
Format: N
Parent: 0xfffffff007976a48
Arg1: fffffff007976ea8
Arg2: 0x7fff00000000
0xfffffff0078f8190: generic.ifdata Description: Interface table
Handler: 0xfffffff0075f4488
Format: N
Parent: 0xfffffff007976a48
Arg1: fffffff007976ea0
Arg2: 0x7fff00000000
0xfffffff0078f8238: net.ndrv_multi_max_count Description: Number of allowed multicast addresses per NRDV socket
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990150
Arg1: fffffff0078f8288
Arg2: 0x7fff00000000
0xfffffff0078f85b0: net.route.verbose Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007977100
Arg1: fffffff007976f44
Arg2: 0x7fff00000000
0xfffffff0078f8630: net.routetable Description: 
Handler: 0xfffffff0075fdaf4
Format: N
Parent: 0xfffffff007990150
Arg1: fffffff0079770f0
Arg2: 0x7fff00000000
0xfffffff0078f8918: net.statistics Description: Collect detailed statistics
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990150
Arg1: fffffff0078f8910
Arg2: 0x7fff00000000
0xfffffff0078f8968: net.statistics_privcheck Description: Entitlement check
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990150
Arg1: fffffff0078f89b8
Arg2: 0x7fff00000000
0xfffffff0078f8a10: net.stats.debug Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007977120
Arg1: fffffff007977128
Arg2: 0x7fff00000000
0xfffffff0078f8a60: net.stats.sendspace Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007977120
Arg1: fffffff0078f8ab0
Arg2: 0x7fff00000000
0xfffffff0078f8ab8: net.stats.recvspace Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007977120
Arg1: fffffff0078f8b08
Arg2: 0x7fff00000000
0xfffffff0078f8b10: net.stats.stats Description: 
Handler: 0xfffffff00778ea2c
Format: S,nstat_stats
Parent: 0xfffffff007977120
Arg1: fffffff00797712c
Arg2: 0x7fff00000040
0xfffffff0078f8b98: system.if_family_ids Description: Interface Family ID table
Handler: 0xfffffff00760d17c
Format: S, if_family_id
Parent: 0xfffffff007976e98
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078f8c58: net.necp.pass_loopback Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079774b8
Arg1: fffffff0078f8c00
Arg2: 0x7fff00000000
0xfffffff0078f8ca8: net.necp.pass_keepalives Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079774b8
Arg1: fffffff0078f8c04
Arg2: 0x7fff00000000
0xfffffff0078f8cf8: net.necp.debug Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079774b8
Arg1: fffffff0079774b0
Arg2: 0x7fff00000000
0xfffffff0078f8dd8: net.necp.session_count Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079774b8
Arg1: fffffff0079774b4
Arg2: 0x7fff00000000
0xfffffff0078f8e28: net.necp.ip_policy_count Description: 
Handler: 0xfffffff00778e8a8
Format: L
Parent: 0xfffffff0079774b8
Arg1: fffffff0079775c8
Arg2: 0x7fff00000000
0xfffffff0078f8e78: net.necp.socket_non_app_policy_count Description: 
Handler: 0xfffffff00778e8a8
Format: L
Parent: 0xfffffff0079774b8
Arg1: fffffff007977610
Arg2: 0x7fff00000000
0xfffffff0078f8ec8: net.necp.socket_policy_count Description: 
Handler: 0xfffffff00778e8a8
Format: L
Parent: 0xfffffff0079774b8
Arg1: fffffff007977618
Arg2: 0x7fff00000000
0xfffffff0078f8d48: net.necp.drop_all_level Description: 
Handler: 0xfffffff007610cb8
Format: IU
Parent: 0xfffffff0079774b8
Arg1: fffffff0079774ac
Arg2: 0x7fff00000000
0xfffffff0078f8fc0: net.netagent.debug Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079776a0
Arg1: fffffff0078f8f68
Arg2: 0x7fff00000000
0xfffffff0078f9010: net.netagent.registered_count Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079776a0
Arg1: fffffff0079776a8
Arg2: 0x7fff00000000
0xfffffff0078f9060: net.netagent.active_count Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079776a0
Arg1: fffffff0079776ac
Arg2: 0x7fff00000000
0xfffffff0078f9258: iptap.total_tap_count Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979418
Arg1: fffffff007979420
Arg2: 0x7fff00000000
0xfffffff0078f92a8: iptap.log Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979418
Arg1: fffffff007979424
Arg2: 0x7fff00000000
0xfffffff0078f9398: pktap.total_tap_count Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979458
Arg1: fffffff007979460
Arg2: 0x7fff00000000
0xfffffff0078f93e8: pktap.count_unknown_if_type Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007979458
Arg1: fffffff007979468
Arg2: 0x7fff00000000
0xfffffff0078f9438: pktap.log Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979458
Arg1: fffffff007979470
Arg2: 0x7fff00000000
0xfffffff0078f94d8: system.llreach_info Description: Per-interface tree of source link-layer reachability records
Handler: 0xfffffff00765bf14
Format: N
Parent: 0xfffffff007976e98
Arg1: fffffff0079794a8
Arg2: 0x7fff00000000
0xfffffff0078f9588: net.cfil.log Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979520
Arg1: fffffff0078f952c
Arg2: 0x7fff00000000
0xfffffff0078f95d8: net.cfil.debug Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979520
Arg1: fffffff0078f9530
Arg2: 0x7fff00000000
0xfffffff0078f9628: net.cfil.sock_attached_count Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007979520
Arg1: fffffff007979514
Arg2: 0x7fff00000000
0xfffffff0078f9678: net.cfil.active_count Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007979520
Arg1: fffffff007979510
Arg2: 0x7fff00000000
0xfffffff0078f96c8: net.cfil.close_wait_timeout Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007979520
Arg1: fffffff0078f9528
Arg2: 0x7fff00000000
0xfffffff0078f9718: net.cfil.sbtrim Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007979520
Arg1: fffffff0078f9768
Arg2: 0x7fff00000000
0xfffffff0078f97c8: net.cfil.stats Description: 
Handler: 0xfffffff00778ea2c
Format: S,cfil_stats
Parent: 0xfffffff007979520
Arg1: fffffff007979558
Arg2: 0x7fff00000130
0xfffffff0078f9818: net.cfil.sock_list Description: 
Handler: 0xfffffff00765f058
Format: S,cfil_sock_stat
Parent: 0xfffffff007979520
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078f9770: net.cfil.filter_list Description: 
Handler: 0xfffffff00765eec0
Format: S,cfil_filter_stat
Parent: 0xfffffff007979520
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078f98c0: net.pktmnglr.log Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979728
Arg1: fffffff0078f98b8
Arg2: 0x7fff00000000
0xfffffff0078f9968: net.classq.verbose Description: Class queue verbosity level
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007979808
Arg1: fffffff007979800
Arg2: 0x7fff00000000
0xfffffff0078f9a08: sfb.holdtime Description: SFB freeze time in nanoseconds
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007979810
Arg1: fffffff007979818
Arg2: 0x7fff00000000
0xfffffff0078f9a58: sfb.pboxtime Description: SFB penalty box time in nanoseconds
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007979810
Arg1: fffffff007979820
Arg2: 0x7fff00000000
0xfffffff0078f9aa8: sfb.hinterval Description: SFB hash interval in nanoseconds
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007979810
Arg1: fffffff007979828
Arg2: 0x7fff00000000
0xfffffff0078f9af8: sfb.increment Description: SFB increment [d1]
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007979810
Arg1: fffffff0078f9b48
Arg2: 0x7fff00000052
0xfffffff0078f9b50: sfb.decrement Description: SFB decrement [d2]
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007979810
Arg1: fffffff0078f9ba0
Arg2: 0x7fff00000010
0xfffffff0078f9ba8: sfb.allocation Description: SFB bin allocation
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007979810
Arg1: fffffff007979830
Arg2: 0x7fff00000000
0xfffffff0078f9bf8: sfb.ratelimit Description: SFB rate limit
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007979810
Arg1: fffffff007979834
Arg2: 0x7fff00000000
0xfffffff0078f9c48: net.classq.target_qdelay Description: target queue delay in nanoseconds
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007979808
Arg1: fffffff007979860
Arg2: 0x7fff00000000
0xfffffff0078f9c98: net.classq.update_interval Description: update interval in nanoseconds
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007979808
Arg1: fffffff007979868
Arg2: 0x7fff00000000
0xfffffff0078f9d40: net.pktsched.verbose Description: Packet scheduler verbosity level
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007979888
Arg1: fffffff007979890
Arg2: 0x7fff00000000
0xfffffff0078f9d98: net.inet.igmp.stats Description: 
Handler: 0xfffffff00778ea2c
Format: S,igmpstat
Parent: 0xfffffff007979e90
Arg1: fffffff0079798d4
Arg2: 0x7fff00000024
0xfffffff0078f9de8: net.inet.igmp.v3stats Description: 
Handler: 0xfffffff00778ea2c
Format: S,igmpstat_v3
Parent: 0xfffffff007979e90
Arg1: fffffff0078f9e38
Arg2: 0x7fff000000a8
0xfffffff0078f9ee0: net.inet.igmp.recvifkludge Description: Rewrite IGMPv1/v2 reports from 0.0.0.0 to contain subnet address
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e90
Arg1: fffffff0078f9f30
Arg2: 0x7fff00000000
0xfffffff0078f9f38: net.inet.igmp.sendra Description: Send IP Router Alert option in IGMPv2/v3 messages
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e90
Arg1: fffffff0078f9f88
Arg2: 0x7fff00000000
0xfffffff0078f9f90: net.inet.igmp.sendlocal Description: Send IGMP membership reports for 224.0.0.0/24 groups
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e90
Arg1: fffffff0078f9fe0
Arg2: 0x7fff00000000
0xfffffff0078f9fe8: net.inet.igmp.v1enable Description: Enable backwards compatibility with IGMPv1
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e90
Arg1: fffffff0078fa038
Arg2: 0x7fff00000000
0xfffffff0078fa040: net.inet.igmp.v2enable Description: Enable backwards compatibility with IGMPv2
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e90
Arg1: fffffff0078fa090
Arg2: 0x7fff00000000
0xfffffff0078fa098: net.inet.igmp.legacysupp Description: Allow v1/v2 reports to suppress v3 group responses
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e90
Arg1: fffffff0079798f8
Arg2: 0x7fff00000000
0xfffffff0078fa150: net.inet.igmp.ifinfo Description: Per-interface IGMPv3 state
Handler: 0xfffffff007671230
Format: N
Parent: 0xfffffff007979e90
Arg1: fffffff007979930
Arg2: 0x7fff00000000
0xfffffff0078fa1a0: net.inet.igmp.debug Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e90
Arg1: fffffff007979948
Arg2: 0x7fff00000000
0xfffffff0078fa1f0: net.inet.igmp.gsrdelay Description: Rate limit for IGMPv3 Group-and-Source queries in seconds
Handler: 0xfffffff00767118c
Format: I
Parent: 0xfffffff007979e90
Arg1: fffffff0078fa140
Arg2: 0x7fff00000000
0xfffffff0078fa0e8: net.inet.igmp.default_version Description: Default version of IGMP to run on each interface
Handler: 0xfffffff0076710cc
Format: I
Parent: 0xfffffff007979e90
Arg1: fffffff0078fa138
Arg2: 0x7fff00000000
0xfffffff0078fa240: net.inet.ip.subnets_are_local Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979eb0
Arg1: fffffff007979968
Arg2: 0x7fff00000000
0xfffffff0078fa2e8: inet.prune_intvl Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079799a8
Arg1: fffffff0078fa338
Arg2: 0x7fff00000000
0xfffffff0078fa340: inet.max_age Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079799a8
Arg1: fffffff0078fa390
Arg2: 0x7fff00000000
0xfffffff0078fa398: inet.host_down_time Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079799a8
Arg1: fffffff0078fa3e8
Arg2: 0x7fff00000000
0xfffffff0078fa3f0: inet.arp_llreach_base Description: default ARP link-layer reachability max lifetime (in seconds)
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079799a8
Arg1: fffffff0078fa440
Arg2: 0x7fff00007530
0xfffffff0078fa448: inet.arp_unicast_lim Description: number of unicast ARP refresh probes before using broadcast
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079799a8
Arg1: fffffff0078fa498
Arg2: 0x7fff00000005
0xfffffff0078fa4a0: inet.maxtries Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079799a8
Arg1: fffffff0078fa4f0
Arg2: 0x7fff00000000
0xfffffff0078fa4f8: inet.useloopback Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079799a8
Arg1: fffffff0078fa548
Arg2: 0x7fff00000000
0xfffffff0078fa550: inet.proxyall Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079799a8
Arg1: fffffff0079799b0
Arg2: 0x7fff00000000
0xfffffff0078fa5a0: inet.sendllconflict Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079799a8
Arg1: fffffff0079799b4
Arg2: 0x7fff00000000
0xfffffff0078fa5f0: inet.log_arp_warnings Description: log arp warning messages
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079799a8
Arg1: fffffff0079799b8
Arg2: 0x7fff00000000
0xfffffff0078fa640: inet.keep_announcements Description: keep arp announcements
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079799a8
Arg1: fffffff0078fa690
Arg2: 0x7fff00000000
0xfffffff0078fa698: inet.send_conflicting_probes Description: send conflicting link-local arp probes
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079799a8
Arg1: fffffff0078fa6e8
Arg2: 0x7fff00000000
0xfffffff0078fa6f0: inet.verbose Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079799a8
Arg1: fffffff0079799bc
Arg2: 0x7fff00000000
0xfffffff0078fa740: inet.stats Description: ARP statistics (struct arpstat, net/if_arp.h)
Handler: 0xfffffff007679b64
Format: S,arpstat
Parent: 0xfffffff0079799a8
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078fa7f8: net.inet.ip.mcast.maxgrpsrc Description: Max source filters per group
Handler: 0xfffffff00778e8a8
Format: L
Parent: 0xfffffff007979a18
Arg1: fffffff0078fa848
Arg2: 0x7fff00000000
0xfffffff0078fa850: net.inet.ip.mcast.maxsocksrc Description: Max source filters per socket
Handler: 0xfffffff00778e8a8
Format: L
Parent: 0xfffffff007979a18
Arg1: fffffff0078fa8a0
Arg2: 0x7fff00000000
0xfffffff0078fa8b0: net.inet.ip.mcast.loop Description: Loopback multicast datagrams by default
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979a18
Arg1: fffffff0078fa8a8
Arg2: 0x7fff00000000
0xfffffff0078fa900: net.inet.ip.mcast.filters Description: Per-interface stack-wide source filters
Handler: 0xfffffff00767d15c
Format: N
Parent: 0xfffffff007979a18
Arg1: fffffff007979a20
Arg2: 0x7fff00000000
0xfffffff0078faa28: net.inet.log_restricted Description: Log network restrictions
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979eb8
Arg1: fffffff007979ac0
Arg2: 0x7fff00000000
0xfffffff0078faa80: net.inet.ip.portrange.hilast Description: 
Handler: 0xfffffff0076813e0
Format: I
Parent: 0xfffffff007979aa0
Arg1: fffffff0078fa970
Arg2: 0x7fff00000000
0xfffffff0078faad0: net.inet.ip.portrange.hifirst Description: 
Handler: 0xfffffff0076813e0
Format: I
Parent: 0xfffffff007979aa0
Arg1: fffffff0078fa96c
Arg2: 0x7fff00000000
0xfffffff0078fab20: net.inet.ip.portrange.last Description: 
Handler: 0xfffffff0076813e0
Format: I
Parent: 0xfffffff007979aa0
Arg1: fffffff0078fa968
Arg2: 0x7fff00000000
0xfffffff0078fab70: net.inet.ip.portrange.first Description: 
Handler: 0xfffffff0076813e0
Format: I
Parent: 0xfffffff007979aa0
Arg1: fffffff0078fa964
Arg2: 0x7fff00000000
0xfffffff0078fabc0: net.inet.ip.portrange.lowlast Description: 
Handler: 0xfffffff0076813e0
Format: I
Parent: 0xfffffff007979aa0
Arg1: fffffff0078fa960
Arg2: 0x7fff00000000
0xfffffff0078fa9c8: net.inet.ip.portrange.lowfirst Description: 
Handler: 0xfffffff0076813e0
Format: I
Parent: 0xfffffff007979aa0
Arg1: fffffff0078fa95c
Arg2: 0x7fff00000000
0xfffffff0078fb770: net.inet.ip.rtexpire Description: Default expiration time on dynamically learned routes
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007979eb0
Arg1: fffffff0078fb7c0
Arg2: 0x7fff00000000
0xfffffff0078fb7c8: net.inet.ip.rtminexpire Description: Minimum time to attempt to hold onto dynamically learned routes
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007979eb0
Arg1: fffffff0078fb818
Arg2: 0x7fff00000000
0xfffffff0078fb820: net.inet.ip.rtmaxcache Description: Upper limit on dynamically learned routes
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007979eb0
Arg1: fffffff0078fb870
Arg2: 0x7fff00000000
0xfffffff0078fb918: policy.capable_enabled Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979ff8
Arg1: fffffff00797a000
Arg2: 0x7fff00000000
0xfffffff0078fb968: policy.wifi_enabled Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979ff8
Arg1: fffffff00797a004
Arg2: 0x7fff00000000
0xfffffff0078fb9b8: policy.restrict_avapps Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979ff8
Arg1: fffffff00797a008
Arg2: 0x7fff00000000
0xfffffff0078fba08: policy.restricted Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979ff8
Arg1: fffffff00797a00c
Arg2: 0x7fff00000000
0xfffffff0078fbaa8: net.qos.verbose Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979ed8
Arg1: fffffff00797a010
Arg2: 0x7fff00000000
0xfffffff0078fbaf8: net.qos.reset_dscp_to_wifi_ac_map Description: 
Handler: 0xfffffff00768a9b4
Format: I
Parent: 0xfffffff007979ed8
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078fbb48: net.qos.dscp_to_wifi_ac_map Description: 
Handler: 0xfffffff00768a43c
Format: S
Parent: 0xfffffff007979ed8
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078fb8c8: net.qos.default_netsvctype_to_dscp_map Description: 
Handler: 0xfffffff00768a124
Format: S
Parent: 0xfffffff007979ed8
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078fbbe8: dummynet.hash_size Description: Default hash table size
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797a028
Arg1: fffffff0078fbc38
Arg2: 0x7fff00000000
0xfffffff0078fbc40: dummynet.curr_time Description: Current tick
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff00797a028
Arg1: fffffff00797a030
Arg2: 0x7fff00000000
0xfffffff0078fbc90: dummynet.ready_heap Description: Size of ready heap
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797a028
Arg1: fffffff00797a038
Arg2: 0x7fff00000000
0xfffffff0078fbce0: dummynet.extract_heap Description: Size of extract heap
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797a028
Arg1: fffffff00797a050
Arg2: 0x7fff00000000
0xfffffff0078fbd30: dummynet.searches Description: Number of queue searches
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797a028
Arg1: fffffff00797a068
Arg2: 0x7fff00000000
0xfffffff0078fbd80: dummynet.search_steps Description: Number of queue search steps
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797a028
Arg1: fffffff00797a06c
Arg2: 0x7fff00000000
0xfffffff0078fbdd0: dummynet.expire Description: Expire queue if empty
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797a028
Arg1: fffffff0078fbe20
Arg2: 0x7fff00000000
0xfffffff0078fbe28: dummynet.max_chain_len Description: Max ratio between dynamic queues and buckets
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797a028
Arg1: fffffff0078fbe78
Arg2: 0x7fff00000000
0xfffffff0078fbe80: dummynet.red_lookup_depth Description: Depth of RED lookup table
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797a028
Arg1: fffffff0078fbed0
Arg2: 0x7fff00000000
0xfffffff0078fbed8: dummynet.red_avg_pkt_size Description: RED Medium packet size
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797a028
Arg1: fffffff0078fbf28
Arg2: 0x7fff00000000
0xfffffff0078fbf30: dummynet.red_max_pkt_size Description: RED Max packet size
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797a028
Arg1: fffffff0078fbf80
Arg2: 0x7fff00000000
0xfffffff0078fbf88: dummynet.debug Description: control debugging printfs
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797a028
Arg1: fffffff00797a070
Arg2: 0x7fff00000000
0xfffffff0078fbfe8: net.inet.icmp.stats Description: 
Handler: 0xfffffff00778ea2c
Format: S,icmpstat
Parent: 0xfffffff007979ea8
Arg1: fffffff00797a26c
Arg2: 0x7fff00000170
0xfffffff0078fc038: net.inet.icmp.maskrepl Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979ea8
Arg1: fffffff00797a3dc
Arg2: 0x7fff00000000
0xfffffff0078fc088: net.inet.icmp.timestamp Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979ea8
Arg1: fffffff00797a3e0
Arg2: 0x7fff00000000
0xfffffff0078fc0d8: net.inet.icmp.drop_redirect Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979ea8
Arg1: fffffff0078fc128
Arg2: 0x7fff00000000
0xfffffff0078fc130: net.inet.icmp.log_redirect Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979ea8
Arg1: fffffff00797a3e4
Arg2: 0x7fff00000000
0xfffffff0078fc180: net.inet.icmp.icmplim Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979ea8
Arg1: fffffff0078fc1d0
Arg2: 0x7fff00000000
0xfffffff0078fc1d8: net.inet.icmp.bmcastecho Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979ea8
Arg1: fffffff0078fc228
Arg2: 0x7fff00000000
0xfffffff0078fc318: net.inet.ip.random_id_statistics Description: Enable IP ID statistics
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007979eb0
Arg1: fffffff00797a428
Arg2: 0x7fff00000000
0xfffffff0078fc368: net.inet.ip.random_id_collisions Description: Count of IP ID collisions
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007979eb0
Arg1: fffffff00797a430
Arg2: 0x7fff00000000
0xfffffff0078fc3b8: net.inet.ip.random_id_total Description: Count of IP IDs created
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007979eb0
Arg1: fffffff00797a438
Arg2: 0x7fff00000000
0xfffffff0078fc470: net.inet.ip.random_id Description: Randomize IP packets IDs
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979eb0
Arg1: fffffff0078fc4c0
Arg2: 0x7fff00000000
0xfffffff0078fc4c8: linklocal.in.allowbadttl Description: Allow incoming link local packets with TTL less than 255
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797a4f0
Arg1: fffffff0078fc518
Arg2: 0x7fff00000000
0xfffffff0078fc570: linklocal.stat Description: Number of link local packets with TTL less than 255
Handler: 0xfffffff00778ea2c
Format: S,ip_linklocal_stat
Parent: 0xfffffff00797a508
Arg1: fffffff00797a4f8
Arg2: 0x7fff00000010
0xfffffff0078fc610: net.inet.ip.stats Description: IP statistics (struct ipstat, netinet/ip_var.h)
Handler: 0xfffffff007691ab4
Format: S,ipstat
Parent: 0xfffffff007979eb0
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078fc660: net.inet.ip.rx_chainsz Description: IP receive side max chaining
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979eb0
Arg1: fffffff0078fc464
Arg2: 0x7fff00000001
0xfffffff0078fc6b0: net.inet.ip.rx_chaining Description: Do receive side ip address based chaining
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979eb0
Arg1: fffffff0078fc468
Arg2: 0x7fff00000001
0xfffffff0078fc700: net.inet.ip.check_interface Description: Verify packet arrives on correct interface
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979eb0
Arg1: fffffff00797a4a0
Arg2: 0x7fff00000000
0xfffffff0078fc750: net.inet.ip.adj_clear_hwcksum Description: Invalidate hwcksum info when adjusting length
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007979eb0
Arg1: fffffff00797a4a4
Arg2: 0x7fff00000000
0xfffffff0078fc7a0: net.inet.ip.maxfragsperpacket Description: Maximum number of IPv4 fragments allowed per packet
Handler: 0xfffffff007691978
Format: I
Parent: 0xfffffff007979eb0
Arg1: fffffff00797ae0c
Arg2: 0x7fff00000000
0xfffffff0078fc7f0: net.inet.ip.fragpackets Description: Current number of IPv4 fragment reassembly queue entries
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007979eb0
Arg1: fffffff00797ae08
Arg2: 0x7fff00000000
0xfffffff0078fc840: net.inet.ip.maxfragpackets Description: Maximum number of IPv4 fragment reassembly queue entries
Handler: 0xfffffff007691564
Format: I
Parent: 0xfffffff007979eb0
Arg1: fffffff00797ae10
Arg2: 0x7fff00000000
0xfffffff0078fc890: net.inet.ip.sendsourcequench Description: Enable the transmission of source quench packets
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979eb0
Arg1: fffffff00797a4a8
Arg2: 0x7fff00000000
0xfffffff0078fc8e0: net.inet.ip.accept_sourceroute Description: Enable accepting source routed IP packets
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979eb0
Arg1: fffffff00797a4ac
Arg2: 0x7fff00000000
0xfffffff0078fc930: net.inet.ip.sourceroute Description: Enable forwarding source routed IP packets
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979eb0
Arg1: fffffff00797a4b0
Arg2: 0x7fff00000000
0xfffffff0078fc980: net.inet.ip.ttl Description: Maximum TTL on IP packets
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979eb0
Arg1: fffffff0078fc9d0
Arg2: 0x7fff00000000
0xfffffff0078fc9d8: net.inet.ip.redirect Description: Enable sending IP redirects
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979eb0
Arg1: fffffff0078fc46c
Arg2: 0x7fff00000000
0xfffffff0078fc410: net.inet.ip.forwarding Description: Enable IP forwarding between interfaces
Handler: 0xfffffff007691414
Format: I
Parent: 0xfffffff007979eb0
Arg1: fffffff00797a490
Arg2: 0x7fff00000000
0xfffffff0078fca28: net.inet.ip.maxchainsent Description: use dlil_output_list
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979eb0
Arg1: fffffff00797b260
Arg2: 0x7fff00000000
0xfffffff0078fca78: net.inet.ip.select_srcif_debug Description: log source interface selection debug info
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979eb0
Arg1: fffffff00797b264
Arg2: 0x7fff00000000
0xfffffff0078fcb18: net.inet.ip.output_perf_data Description: IP output performance data (struct net_perf, net/net_perf.h)
Handler: 0xfffffff0076962b8
Format: S,net_perf
Parent: 0xfffffff007979eb0
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078fcb68: net.inet.ip.output_perf_bins Description: bins for chaining performance data histogram
Handler: 0xfffffff007696234
Format: I
Parent: 0xfffffff007979eb0
Arg1: fffffff00797b270
Arg2: 0x7fff00000000
0xfffffff0078fcac8: net.inet.ip.output_perf Description: Do time measurement
Handler: 0xfffffff007696198
Format: I
Parent: 0xfffffff007979eb0
Arg1: fffffff00797b268
Arg2: 0x7fff00000000
0xfffffff0078fcbc0: net.inet.raw.maxdgram Description: Maximum outgoing raw IP datagram size
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e80
Arg1: fffffff0078fcbb8
Arg2: 0x7fff00000000
0xfffffff0078fcc10: net.inet.raw.recvspace Description: Maximum incoming raw IP datagram size
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e80
Arg1: fffffff0078fcbbc
Arg2: 0x7fff00000000
0xfffffff0078fcc60: net.inet.raw.pcbcount Description: Number of active PCBs
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007979e80
Arg1: fffffff00797b320
Arg2: 0x7fff00000000
0xfffffff0078fce00: net.inet.raw.pcblist_n Description: List of active raw IP sockets
Handler: 0xfffffff00769d23c
Format: S,xinpcb_n
Parent: 0xfffffff007979e80
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078fccb0: net.inet.raw.pcblist Description: List of active raw IP sockets
Handler: 0xfffffff00769cef8
Format: S,xinpcb
Parent: 0xfffffff007979e80
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078fce50: net.inet.tcp.ecn_timeout Description: Initial minutes to wait before re-trying ECN
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fcea0
Arg2: 0x7fff00000000
0xfffffff0078fcea8: net.inet.tcp.disable_tcp_heuristics Description: Set to 1, to disable all TCP heuristics (TFO, ECN, MPTCP)
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b384
Arg2: 0x7fff00000000
0xfffffff0078fcef8: net.inet.tcp.clear_tfocache Description: Toggle to clear the TFO destination based heuristic cache
Handler: 0xfffffff00769e98c
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b388
Arg2: 0x7fff00000000
0xfffffff0078fcf50: net.inet.tcp.log_in_vain Description: Log all incoming TCP connections
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b3dc
Arg2: 0x7fff00000000
0xfffffff0078fcfa0: net.inet.tcp.blackhole Description: Do not send RST when dropping refused connections
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b3e0
Arg2: 0x7fff00000000
0xfffffff0078fcff8: net.inet.tcp.delayed_ack Description: Delay ACK to try and piggyback it onto a data packet
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fcff0
Arg2: 0x7fff00000000
0xfffffff0078fd050: net.inet.tcp.tcp_lq_overflow Description: Listen Queue Overflow
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd048
Arg2: 0x7fff00000000
0xfffffff0078fd0a0: net.inet.tcp.recvbg Description: Receive background
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b3e4
Arg2: 0x7fff00000000
0xfffffff0078fd0f0: net.inet.tcp.drop_synfin Description: Drop TCP packets with SYN+FIN set
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd140
Arg2: 0x7fff00000000
0xfffffff0078fd198: reass.overflows Description: Global number of TCP Segment Reassembly Queue Overflows
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797b3e8
Arg1: fffffff00797b3f0
Arg2: 0x7fff00000000
0xfffffff0078fd1f0: net.inet.tcp.slowlink_wsize Description: Maximum advertised window size for slowlink
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd1e8
Arg2: 0x7fff00000000
0xfffffff0078fd248: net.inet.tcp.maxseg_unacked Description: Maximum number of outstanding segments left unacked
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd240
Arg2: 0x7fff00000000
0xfffffff0078fd2a0: net.inet.tcp.rfc3465 Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd298
Arg2: 0x7fff00000000
0xfffffff0078fd2f8: net.inet.tcp.rfc3465_lim2 Description: Appropriate bytes counting w/ L=2*SMSS
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd2f0
Arg2: 0x7fff00000000
0xfffffff0078fd350: net.inet.tcp.recv_allowed_iaj Description: Allowed inter-packet arrival jiter
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd348
Arg2: 0x7fff00000000
0xfffffff0078fd3a8: net.inet.tcp.doautorcvbuf Description: Enable automatic socket buffer tuning
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd3a0
Arg2: 0x7fff00000000
0xfffffff0078fd400: net.inet.tcp.autorcvbufmax Description: Maximum receive socket buffer size
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd3f8
Arg2: 0x7fff00000000
0xfffffff0078fd458: net.inet.tcp.lro Description: Used to coalesce TCP packets
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd450
Arg2: 0x7fff00000000
0xfffffff0078fd4a8: net.inet.tcp.lrodbg Description: Used to debug SW LRO
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b3f4
Arg2: 0x7fff00000000
0xfffffff0078fd500: net.inet.tcp.lro_startcnt Description: Segments for starting LRO computed as power of 2
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd4f8
Arg2: 0x7fff00000000
0xfffffff0078fd550: net.inet.tcp.obey_ifef_nowindowscale Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b3f8
Arg2: 0x7fff00000000
0xfffffff0078fd5a8: net.inet.tcp.rcvsspktcnt Description: packets to be seen before receiver stretches acks
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd5a4
Arg2: 0x7fff00000000
0xfffffff0078fd648: net.inet.tcp.rexmt_thresh Description: Duplicate ACK Threshold for Fast Retransmit
Handler: 0xfffffff00769f6d4
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd5a0
Arg2: 0x7fff00000000
0xfffffff0078fd5f8: net.inet.tcp.stats Description: TCP statistics (struct tcpstat, netinet/tcp_var.h)
Handler: 0xfffffff00769f69c
Format: S,tcpstat
Parent: 0xfffffff007979e98
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078fd6a0: net.inet.tcp.path_mtu_discovery Description: Enable Path MTU Discovery
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd69c
Arg2: 0x7fff00000001
0xfffffff0078fd6f8: net.inet.tcp.slowstart_flightsize Description: Slow start flight size
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd6f0
Arg2: 0x7fff00000001
0xfffffff0078fd750: net.inet.tcp.local_slowstart_flightsize Description: Slow start flight size for local networks
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd748
Arg2: 0x7fff00000001
0xfffffff0078fd7a8: net.inet.tcp.tso Description: Enable TCP Segmentation Offload
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd7a0
Arg2: 0x7fff00000000
0xfffffff0078fd800: net.inet.tcp.ecn_setup_percentage Description: Max ECN setup percentage
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd7f8
Arg2: 0x7fff00000000
0xfffffff0078fd8a8: net.inet.tcp.enable_tlp Description: Enable Tail loss probe
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd8f8
Arg2: 0x7fff00000001
0xfffffff0078fd900: net.inet.tcp.recv_throttle_minwin Description: Minimum recv win for throttling
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd950
Arg2: 0x7fff00000001
0xfffffff0078fd958: net.inet.tcp.rtt_recvbg Description: Use RTT for bg recv algorithm
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd9a8
Arg2: 0x7fff00000001
0xfffffff0078fd9b0: net.inet.tcp.ack_prioritize Description: Prioritize pure acks
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fda00
Arg2: 0x7fff00000001
0xfffffff0078fda08: net.inet.tcp.autosndbufmax Description: Maximum send socket buffer size
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fda58
Arg2: 0x7fff00000001
0xfffffff0078fda60: net.inet.tcp.autosndbufinc Description: Increment in send socket bufffer size
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fdab0
Arg2: 0x7fff00000001
0xfffffff0078fdab8: net.inet.tcp.doautosndbuf Description: Enable send socket buffer auto-tuning
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fdb08
Arg2: 0x7fff00000001
0xfffffff0078fdb10: net.inet.tcp.acc_iaj_react_limit Description: Accumulated IAJ when receiver starts to react
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fdb60
Arg2: 0x7fff00000001
0xfffffff0078fdb68: net.inet.tcp.min_iaj_win Description: Minimum recv win based on inter-packet arrival jitter
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fdbb8
Arg2: 0x7fff00000001
0xfffffff0078fdbc0: net.inet.tcp.rfc3390 Description: Calculate intial slowstart cwnd depending on MSS
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fdc10
Arg2: 0x7fff00000001
0xfffffff0078fdc18: net.inet.tcp.socket_unlocked_on_output Description: Unlock TCP when sending packets down to IP
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fdc68
Arg2: 0x7fff00000000
0xfffffff0078fdc70: net.inet.tcp.packetchain Description: Enable TCP output packet chaining
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fdcc0
Arg2: 0x7fff00000000
0xfffffff0078fdcc8: net.inet.tcp.ecn_negotiate_in Description: Initiate ECN for inbound connections
Handler: 0xfffffff0076a94a4
Format: IU
Parent: 0xfffffff007979e98
Arg1: fffffff0078fdd18
Arg2: 0x7fff00000000
0xfffffff0078fd858: net.inet.tcp.ecn_initiate_out Description: Initiate ECN for outbound connections
Handler: 0xfffffff0076a94a4
Format: IU
Parent: 0xfffffff007979e98
Arg1: fffffff0078fd850
Arg2: 0x7fff00000000
0xfffffff0078fdd20: net.inet.tcp.sack Description: Enable/Disable TCP SACK support
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fdd1c
Arg2: 0x7fff00000000
0xfffffff0078fdd70: net.inet.tcp.sack_maxholes Description: Maximum number of TCP SACK holes allowed per connection
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fddc0
Arg2: 0x7fff00000000
0xfffffff0078fddc8: net.inet.tcp.sack_globalmaxholes Description: Global maximum number of TCP SACK holes
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fde18
Arg2: 0x7fff00000000
0xfffffff0078fde20: net.inet.tcp.sack_globalholes Description: Global number of TCP SACK holes currently allocated
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b7ec
Arg2: 0x7fff00000000
0xfffffff0078fde78: net.inet.tcp.mssdflt Description: Default TCP Maximum Segment Size
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fde70
Arg2: 0x7fff00000000
0xfffffff0078fded0: net.inet.tcp.v6mssdflt Description: Default TCP Maximum Segment Size for IPv6
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fdec8
Arg2: 0x7fff00000000
0xfffffff0078fdf80: net.inet.tcp.pcblist_n Description: List of active TCP connections
Handler: 0xfffffff0076aee54
Format: S,xtcpcb_n
Parent: 0xfffffff007979e98
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078fdfd0: net.inet.tcp.pcblist Description: List of active TCP connections
Handler: 0xfffffff0076ae92c
Format: S,xtcpcb
Parent: 0xfffffff007979e98
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078fe020: net.inet.tcp.tcbhashsize Description: Size of TCP control-block hashtable
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fe070
Arg2: 0x7fff00000000
0xfffffff0078fe078: net.inet.tcp.win_scale_factor Description: Window scaling factor
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fe0c8
Arg2: 0x7fff00000000
0xfffffff0078fe0d0: net.inet.tcp.randomize_ports Description: Randomize TCP port numbers
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b950
Arg2: 0x7fff00000000
0xfffffff0078fe120: net.inet.tcp.rexmt_slop Description: Slop added to retransmit timeout
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fe170
Arg2: 0x7fff00000000
0xfffffff0078fe178: net.inet.tcp.rtt_min Description: min rtt value allowed
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fe1c8
Arg2: 0x7fff00000000
0xfffffff0078fe1d0: net.inet.tcp.icmp_may_rst Description: Certain ICMP unreachable messages may abort connections in SYN_SENT
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fdf74
Arg2: 0x7fff00000000
0xfffffff0078fe220: net.inet.tcp.tw_pcbcount Description: Number of pcbs in time-wait state
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b74c
Arg2: 0x7fff00000000
0xfffffff0078fe270: net.inet.tcp.pcbcount Description: Number of active PCBs
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b748
Arg2: 0x7fff00000000
0xfffffff0078fe2c0: net.inet.tcp.do_tcpdrain Description: Enable tcp_drain routine for extra help when low on mbufs
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b808
Arg2: 0x7fff00000000
0xfffffff0078fe310: net.inet.tcp.rfc1644 Description: Enable rfc1644 (TTCP) extensions
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b80c
Arg2: 0x7fff00000000
0xfffffff0078fe360: net.inet.tcp.minmss Description: Minmum TCP Maximum Segment Size
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fe3b0
Arg2: 0x7fff00000000
0xfffffff0078fe3b8: net.inet.tcp.fastopen_fallback_min Description: Mininum number of trials without TFO when in fallback mode
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fe408
Arg2: 0x7fff00000000
0xfffffff0078fe410: net.inet.tcp.fastopen Description: Enable TCP Fastopen (RFC 7413)
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fe460
Arg2: 0x7fff00000000
0xfffffff0078fe468: net.inet.tcp.fastopen_backlog Description: Backlog queue for half-open TFO connections
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fe4b8
Arg2: 0x7fff00000000
0xfffffff0078fdf20: net.inet.tcp.fastopen_key Description: TCP Fastopen key
Handler: 0xfffffff0076ae7cc
Format: S
Parent: 0xfffffff007979e98
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078fe518: net.inet.tcp.pmtud_blackhole_mss Description: Path MTU Discovery Black Hole Detection lowered MSS
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fe568
Arg2: 0x7fff00000000
0xfffffff0078fe570: net.inet.tcp.pmtud_blackhole_detection Description: Path MTU Discovery Black Hole Detection
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fe5c0
Arg2: 0x7fff00000000
0xfffffff0078fe5c8: net.inet.tcp.tcp_resched_timerlist Description: Number of times timer list was rescheduled as part of processing a packet
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b964
Arg2: 0x7fff00000000
0xfffffff0078fe618: net.inet.tcp.tcp_timer_advanced Description: Number of times one of the timers was advanced
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b968
Arg2: 0x7fff00000000
0xfffffff0078fe668: net.inet.tcp.broken_peer_syn_rexmit_thres Description: Number of retransmitted SYNs before disabling RFC 1323 options on local connections
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fe510
Arg2: 0x7fff00000000
0xfffffff0078fe6b8: net.inet.tcp.timer_fastmode_idlemax Description: Maximum idle generations in fast mode
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fe708
Arg2: 0x7fff00000000
0xfffffff0078fe710: net.inet.tcp.always_keepalive Description: Assume SO_KEEPALIVE on all TCP connections
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b96c
Arg2: 0x7fff00000000
0xfffffff0078fe760: net.inet.tcp.max_persist_timeout Description: Maximum persistence timeout for ZWP
Handler: 0xfffffff0076b3824
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797ba08
Arg2: 0x7fff00000000
0xfffffff0078fe7b0: net.inet.tcp.msl Description: Maximum segment lifetime
Handler: 0xfffffff0076b3824
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b97c
Arg2: 0x7fff00000000
0xfffffff0078fe800: net.inet.tcp.keepcnt Description: number of times to repeat keepalive
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b980
Arg2: 0x7fff00000000
0xfffffff0078fe850: net.inet.tcp.keepintvl Description: 
Handler: 0xfffffff0076b3824
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b984
Arg2: 0x7fff00000000
0xfffffff0078fe8a0: net.inet.tcp.keepidle Description: 
Handler: 0xfffffff0076b3824
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b988
Arg2: 0x7fff00000000
0xfffffff0078fe4c0: net.inet.tcp.keepinit Description: 
Handler: 0xfffffff0076b3824
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797b960
Arg2: 0x7fff00000000
0xfffffff0078fe940: net.inet.tcp.recvspace Description: Maximum incoming TCP datagram size
Handler: 0xfffffff0076b8aa0
Format: IU
Parent: 0xfffffff007979e98
Arg1: fffffff0078fe9e0
Arg2: 0x7fff00000000
0xfffffff0078fe990: net.inet.tcp.sendspace Description: Maximum outgoing TCP datagram size
Handler: 0xfffffff0076b8aa0
Format: IU
Parent: 0xfffffff007979e98
Arg1: fffffff0078fe9e4
Arg2: 0x7fff00000000
0xfffffff0078fe8f0: net.inet.tcp.info Description: TCP info per tuple
Handler: 0xfffffff0076b62e8
Format: S
Parent: 0xfffffff007979e98
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078febc0: net.inet.tcp.cc_debug Description: Enable debug data collection
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797ba14
Arg2: 0x7fff00000000
0xfffffff0078fec10: net.inet.tcp.newreno_sockets Description: Number of sockets using newreno
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fed68
Arg2: 0x7fff00000000
0xfffffff0078fec60: net.inet.tcp.background_sockets Description: Number of sockets using background transport
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fefe8
Arg2: 0x7fff00000000
0xfffffff0078fecb0: net.inet.tcp.cubic_sockets Description: Number of sockets using cubic
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fedd8
Arg2: 0x7fff00000000
0xfffffff0078fed00: net.inet.tcp.use_newreno Description: Use TCP NewReno by default
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797ba18
Arg2: 0x7fff00000000
0xfffffff0078fee38: net.inet.tcp.cubic_use_minrtt Description: use a min of 5 sec rtt
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797bac0
Arg2: 0x7fff00000000
0xfffffff0078fee88: net.inet.tcp.cubic_fast_convergence Description: Enable fast convergence
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797bac4
Arg2: 0x7fff00000000
0xfffffff0078feed8: net.inet.tcp.cubic_tcp_friendliness Description: Enable TCP friendliness
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff00797bac8
Arg2: 0x7fff00000000
0xfffffff0078fef30: net.inet.tcp.lro_sz Description: Max coalescing size
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fef28
Arg2: 0x7fff00000000
0xfffffff0078fef88: net.inet.tcp.lro_time Description: Max coalescing time
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078fef80
Arg2: 0x7fff00000000
0xfffffff0078ff048: net.inet.tcp.bg_ss_fltsz Description: Initial congestion window for background transport
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078ff098
Arg2: 0x7fff00000002
0xfffffff0078ff0a0: net.inet.tcp.bg_tether_shift Description: Tether shift for max allowed congestion window
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078ff0f0
Arg2: 0x7fff00000001
0xfffffff0078ff0f8: net.inet.tcp.bg_allowed_increase Description: Additive constant used to calculate max allowed congestion window
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078ff148
Arg2: 0x7fff00000001
0xfffffff0078ff150: net.inet.tcp.bg_target_qdelay Description: Target queuing delay
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e98
Arg1: fffffff0078ff1a0
Arg2: 0x7fff00000064
0xfffffff0078ff1a8: net.inet.udp.checksum Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979ea0
Arg1: fffffff0078ff1f8
Arg2: 0x7fff00000000
0xfffffff0078ff200: net.inet.udp.log_in_vain Description: Log all incoming UDP packets
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979ea0
Arg1: fffffff00797c3b0
Arg2: 0x7fff00000000
0xfffffff0078ff250: net.inet.udp.blackhole Description: Do not send port unreachables for refused connects
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979ea0
Arg1: fffffff00797c3b4
Arg2: 0x7fff00000000
0xfffffff0078ff2f8: net.inet.udp.maxdgram Description: Maximum outgoing UDP datagram size
Handler: 0xfffffff0076bdbd0
Format: IU
Parent: 0xfffffff007979ea0
Arg1: fffffff0078ff39c
Arg2: 0x7fff00000000
0xfffffff0078ff348: net.inet.udp.recvspace Description: Maximum incoming UDP datagram size
Handler: 0xfffffff0076bdbd0
Format: IU
Parent: 0xfffffff007979ea0
Arg1: fffffff0078ff398
Arg2: 0x7fff00000000
0xfffffff0078ff3a0: net.inet.udp.pcblist_n Description: List of active UDP sockets
Handler: 0xfffffff0076bdbbc
Format: S,xinpcb_n
Parent: 0xfffffff007979ea0
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078ff3f0: net.inet.udp.pcblist Description: List of active UDP sockets
Handler: 0xfffffff0076bd878
Format: S,xinpcb
Parent: 0xfffffff007979ea0
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078ff530: net.inet.udp.randomize_ports Description: Randomize UDP port numbers
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979ea0
Arg1: fffffff0078ff580
Arg2: 0x7fff00000000
0xfffffff0078ff588: net.inet.udp.pcbcount Description: Number of active PCBs
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979ea0
Arg1: fffffff00797c458
Arg2: 0x7fff00000000
0xfffffff0078ff2a0: net.inet.udp.stats Description: UDP statistics (struct udpstat, netinet/udp_var.h)
Handler: 0xfffffff0076bc28c
Format: S,udpstat
Parent: 0xfffffff007979ea0
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0078ff760: mptcp.enable Description: Enable Multipath TCP Support
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff0078ff758
Arg2: 0x7fff00000000
0xfffffff0078ff7b8: mptcp.mptcp_cap_retr Description: Number of MP Capable SYN Retries
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff0078ff7b0
Arg2: 0x7fff00000000
0xfffffff0078ff808: mptcp.dss_csum Description: Enable DSS checksum
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff00797cc50
Arg2: 0x7fff00000000
0xfffffff0078ff860: mptcp.fail Description: Failover threshold
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff0078ff858
Arg2: 0x7fff00000000
0xfffffff0078ff8b8: mptcp.keepalive Description: Keepalive in seconds
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff0078ff8b0
Arg2: 0x7fff00000000
0xfffffff0078ff910: mptcp.mpprio Description: Enable MP_PRIO option
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff0078ff908
Arg2: 0x7fff00000000
0xfffffff0078ff968: mptcp.remaddr Description: Enable REMOVE_ADDR option
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff0078ff960
Arg2: 0x7fff00000000
0xfffffff0078ff9c0: mptcp.fastjoin Description: Enable FastJoin Option
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff0078ff9b8
Arg2: 0x7fff00000000
0xfffffff0078ffa10: mptcp.zerortt_fastjoin Description: Enable Zero RTT Fast Join
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff00797cc54
Arg2: 0x7fff00000000
0xfffffff0078ffa60: mptcp.rwnotify Description: Enable RW notify on resume
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff00797cc58
Arg2: 0x7fff00000000
0xfffffff0078ffab8: mptcp.rtthist Description: Disable RTT History
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff0078ffab0
Arg2: 0x7fff00000000
0xfffffff0078ffb10: mptcp.rtthist_thresh Description: Rtt threshold
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff0078ffb08
Arg2: 0x7fff00000000
0xfffffff0078ffb68: mptcp.userto Description: Disable RTO for subflow selection
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff0078ffb60
Arg2: 0x7fff00000000
0xfffffff0078ffbc0: mptcp.rto_thresh Description: RTO threshold
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff0078ffbb8
Arg2: 0x7fff00000000
0xfffffff0078ffc18: mptcp.use_peer Description: Use peer
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff0078ffc10
Arg2: 0x7fff00000000
0xfffffff0078ffc70: mptcp.peerswitchno Description: Set threshold based on peer's data arrival
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff00797cc60
Arg1: fffffff0078ffc68
Arg2: 0x7fff00000000
0xfffffff0078ffcc8: mptcp.probeto Description: Disable probing by setting to 0
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff00797cc60
Arg1: fffffff0078ffcc0
Arg2: 0x7fff00000000
0xfffffff0078ffd20: mptcp.probecnt Description: Number of probe writes
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff00797cc60
Arg1: fffffff0078ffd18
Arg2: 0x7fff00000000
0xfffffff0078ffdc0: mptcp.dbg_area Description: MPTCP debug area
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff00797cc60
Arg1: fffffff00797cc68
Arg2: 0x7fff00000000
0xfffffff0078ffe10: mptcp.dbg_level Description: MPTCP debug level
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff00797cc6c
Arg2: 0x7fff00000000
0xfffffff0078ffe60: mptcp.pcbcount Description: Number of active PCBs
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff00797cc60
Arg1: fffffff00797cc90
Arg2: 0x7fff00000000
0xfffffff0078ffeb8: mptcp.sk_lim Description: MPTCP socket limit
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff00797cc60
Arg1: fffffff0078ffeb0
Arg2: 0x7fff00000000
0xfffffff0078fff08: mptcp.delayed Description: MPTCP Delayed Subflow start
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff00797cc60
Arg1: fffffff00797cce8
Arg2: 0x7fff00000000
0xfffffff0078fff60: mptcp.usesymptoms Description: MPTCP Use SymptomsD
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff00797cc60
Arg1: fffffff0078fff58
Arg2: 0x7fff00000000
0xfffffff0078fffb0: mptcp.pcblist Description: List of active MPTCP connections
Handler: 0xfffffff0076ca208
Format: S,conninfo_mptcp_t
Parent: 0xfffffff00797cc60
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0079000f0: mptcp.force_64bit_dsn Description: Force MPTCP 64bit dsn
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff00797d054
Arg2: 0x7fff00000000
0xfffffff007900140: mptcp.rto Description: MPTCP Retransmission Timeout
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff007900190
Arg2: 0x7fff00000000
0xfffffff007900198: mptcp.nrto Description: MPTCP Retransmissions
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff007900190
Arg2: 0x7fff00000000
0xfffffff0079001e8: mptcp.tw Description: MPTCP Timewait Period
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00797cc60
Arg1: fffffff007900238
Arg2: 0x7fff00000000
0xfffffff007900438: net.inet.ipsec.stats Description: 
Handler: 0xfffffff00778ea2c
Format: S,ipsecstat
Parent: 0xfffffff007979e88
Arg1: fffffff00797d070
Arg2: 0x7fff00003090
0xfffffff0079004e0: net.inet6.ipsec6.esp_randpad Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986be0
Arg1: fffffff0079007b0
Arg2: 0x7fff00000000
0xfffffff007900530: net.inet6.ipsec6.debug Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986be0
Arg1: fffffff00797d058
Arg2: 0x7fff00000000
0xfffffff007900580: net.inet6.ipsec6.ecn Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986be0
Arg1: fffffff007983b90
Arg2: 0x7fff00000000
0xfffffff0079005d0: net.inet6.ipsec6.ah_net_deflev Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986be0
Arg1: fffffff0079007b4
Arg2: 0x7fff00000000
0xfffffff007900620: net.inet6.ipsec6.ah_trans_deflev Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986be0
Arg1: fffffff0079007b8
Arg2: 0x7fff00000000
0xfffffff007900670: net.inet6.ipsec6.esp_net_deflev Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986be0
Arg1: fffffff0079007bc
Arg2: 0x7fff00000000
0xfffffff0079006c0: net.inet6.ipsec6.esp_trans_deflev Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986be0
Arg1: fffffff0079007c0
Arg2: 0x7fff00000000
0xfffffff007900710: net.inet6.ipsec6.def_policy Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986be0
Arg1: fffffff0079807b8
Arg2: 0x7fff00000000
0xfffffff007900760: net.inet6.ipsec6.stats Description: 
Handler: 0xfffffff00778ea2c
Format: S,ipsecstat
Parent: 0xfffffff007986be0
Arg1: fffffff007980800
Arg2: 0x7fff00003090
0xfffffff0079007c8: net.inet.ipsec.esp_port Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e88
Arg1: fffffff00797d068
Arg2: 0x7fff00000000
0xfffffff007900818: net.inet.ipsec.bypass Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e88
Arg1: fffffff007900868
Arg2: 0x7fff00000000
0xfffffff007900870: net.inet.ipsec.esp_randpad Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e88
Arg1: fffffff007900430
Arg2: 0x7fff00000000
0xfffffff0079008c0: net.inet.ipsec.debug Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e88
Arg1: fffffff00797d058
Arg2: 0x7fff00000000
0xfffffff007900910: net.inet.ipsec.ecn Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e88
Arg1: fffffff00797d064
Arg2: 0x7fff00000000
0xfffffff007900960: net.inet.ipsec.dfbit Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e88
Arg1: fffffff00797d060
Arg2: 0x7fff00000000
0xfffffff0079009b0: net.inet.ipsec.ah_offsetmask Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e88
Arg1: fffffff00797d05c
Arg2: 0x7fff00000000
0xfffffff007900a00: net.inet.ipsec.ah_cleartos Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e88
Arg1: fffffff00790041c
Arg2: 0x7fff00000000
0xfffffff007900a50: net.inet.ipsec.ah_net_deflev Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e88
Arg1: fffffff00790042c
Arg2: 0x7fff00000000
0xfffffff007900aa0: net.inet.ipsec.ah_trans_deflev Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e88
Arg1: fffffff007900428
Arg2: 0x7fff00000000
0xfffffff007900af0: net.inet.ipsec.esp_net_deflev Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e88
Arg1: fffffff007900424
Arg2: 0x7fff00000000
0xfffffff007900b40: net.inet.ipsec.esp_trans_deflev Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007979e88
Arg1: fffffff007900420
Arg2: 0x7fff00000000
0xfffffff007900488: net.inet.ipsec.def_policy Description: 
Handler: 0xfffffff0076e4bac
Format: I
Parent: 0xfffffff007979e88
Arg1: fffffff007980438
Arg2: 0x7fff00000000
0xfffffff007900be0: net.inet6.ip6.maxfrags Description: Maximum number of IPv6 fragments allowed
Handler: 0xfffffff0076eab68
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007983bac
Arg2: 0x7fff00000000
0xfffffff007900c30: net.inet6.ip6.fragpackets Description: Current number of IPv6 fragment reassembly queue entries
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007986c00
Arg1: fffffff007983bb0
Arg2: 0x7fff00000000
0xfffffff007900b90: net.inet6.ip6.maxfragpackets Description: Maximum number of IPv6 fragment reassembly queue entries
Handler: 0xfffffff0076ea4b4
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007983b94
Arg2: 0x7fff00000000
0xfffffff007900c90: net.inet6.ip6.adj_clear_hwcksum Description: Invalidate hwcksum info when adjusting length
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007986c00
Arg1: fffffff0079853a8
Arg2: 0x7fff00000000
0xfffffff007900d30: net.inet6.ip6.input_perf_data Description: IP6 input performance data (struct net_perf, net/net_perf.h)
Handler: 0xfffffff0076fa0a0
Format: S,net_perf
Parent: 0xfffffff007986c00
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007900d80: net.inet6.ip6.input_perf_bins Description: bins for chaining performance data histogram
Handler: 0xfffffff0076fa01c
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff0079853f0
Arg2: 0x7fff00000000
0xfffffff007900ce0: net.inet6.ip6.input_perf Description: Do time measurement
Handler: 0xfffffff0076f9f80
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff0079853ac
Arg2: 0x7fff00000000
0xfffffff007900e40: net.inet6.ip6.output_perf_data Description: IP6 output performance data (struct net_perf, net/net_perf.h)
Handler: 0xfffffff0076ffc18
Format: S,net_perf
Parent: 0xfffffff007986c00
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007900e90: net.inet6.ip6.output_perf_bins Description: bins for chaining performance data histogram
Handler: 0xfffffff0076ffb94
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007986988
Arg2: 0x7fff00000000
0xfffffff007900dd0: net.inet6.ip6.output_perf Description: Do time measurement
Handler: 0xfffffff0076ffaf8
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007986984
Arg2: 0x7fff00000000
0xfffffff007900ee0: net.inet6.ip6.select_srcif_debug Description: log source interface selection debug info
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff0079869e0
Arg2: 0x7fff00000000
0xfffffff007900f30: net.inet6.ip6.select_srcaddr_debug Description: log source address selection debug info
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff0079869e4
Arg2: 0x7fff00000000
0xfffffff007900f80: net.inet6.ip6.select_src_expensive_secondary_if Description: allow source interface selection to use expensive secondaries
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff0079869e8
Arg2: 0x7fff00000000
0xfffffff007900fd8: net.inet6.ip6.addrctlpolicy Description: 
Handler: 0xfffffff007708914
Format: N
Parent: 0xfffffff007986c00
Arg1: fffffff007986a38
Arg2: 0x7fff00000000
0xfffffff007901080: net.inet6.ip6.mcast.maxgrpsrc Description: Max source filters per group
Handler: 0xfffffff00778e8a8
Format: L
Parent: 0xfffffff007986a50
Arg1: fffffff0079010d0
Arg2: 0x7fff00000000
0xfffffff0079010d8: net.inet6.ip6.mcast.maxsocksrc Description: Max source filters per socket
Handler: 0xfffffff00778e8a8
Format: L
Parent: 0xfffffff007986a50
Arg1: fffffff007901128
Arg2: 0x7fff00000000
0xfffffff007901138: net.inet6.ip6.mcast.loop Description: Loopback multicast datagrams by default
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986a50
Arg1: fffffff007901130
Arg2: 0x7fff00000000
0xfffffff007901188: net.inet6.ip6.mcast.filters Description: Per-interface stack-wide source filters
Handler: 0xfffffff00770b5c0
Format: N
Parent: 0xfffffff007986a50
Arg1: fffffff007986a58
Arg2: 0x7fff00000000
0xfffffff007901ad0: net.inet6.icmp6.nd6_optimistic_dad Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986bf8
Arg1: fffffff007902f08
Arg2: 0x7fff00000000
0xfffffff007901b20: net.inet6.icmp6.nd6_onlink_ns_rfc4861 Description: Accept 'on-link' nd6 NS in compliance with RFC 4861.
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986bf8
Arg1: fffffff007986c1c
Arg2: 0x7fff00000000
0xfffffff007901b70: net.inet6.icmp6.nd6_debug Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986bf8
Arg1: fffffff007986d64
Arg2: 0x7fff00000000
0xfffffff007901bc0: net.inet6.icmp6.rappslimit Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986bf8
Arg1: fffffff007902ac4
Arg2: 0x7fff00000000
0xfffffff007901c10: net.inet6.icmp6.errppslimit Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986bf8
Arg1: fffffff007902ac8
Arg2: 0x7fff00000000
0xfffffff007901c60: net.inet6.icmp6.nodeinfo Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986bf8
Arg1: fffffff007902ac0
Arg2: 0x7fff00000000
0xfffffff007901cb0: net.inet6.icmp6.nd6_accept_6to4 Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986bf8
Arg1: fffffff00790321c
Arg2: 0x7fff00000000
0xfffffff007901d00: net.inet6.icmp6.nd6_useloopback Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986bf8
Arg1: fffffff007902f04
Arg2: 0x7fff00000000
0xfffffff007901d50: net.inet6.icmp6.nd6_mmaxtries Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986bf8
Arg1: fffffff007902f00
Arg2: 0x7fff00000000
0xfffffff007901da0: net.inet6.icmp6.nd6_umaxtries Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986bf8
Arg1: fffffff007902efc
Arg2: 0x7fff00000000
0xfffffff007901df0: net.inet6.icmp6.nd6_delay Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986bf8
Arg1: fffffff007902ef8
Arg2: 0x7fff00000000
0xfffffff007901e40: net.inet6.icmp6.nd6_prune_lazy Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986bf8
Arg1: fffffff007902ef4
Arg2: 0x7fff00000000
0xfffffff007901e90: net.inet6.icmp6.nd6_prune Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986bf8
Arg1: fffffff007902ef0
Arg2: 0x7fff00000000
0xfffffff007901ee0: net.inet6.icmp6.stats Description: 
Handler: 0xfffffff00778ea2c
Format: S,icmp6stat
Parent: 0xfffffff007986bf8
Arg1: fffffff007983c40
Arg2: 0x7fff000010f0
0xfffffff007901f30: net.inet6.icmp6.redirtimeout Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986bf8
Arg1: fffffff007902acc
Arg2: 0x7fff00000000
0xfffffff007901f80: net.inet6.icmp6.rediraccept Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986bf8
Arg1: fffffff007986c18
Arg2: 0x7fff00000000
0xfffffff007901fd0: net.inet6.ip6.only_allow_rfc4193_prefixes Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007986c28
Arg2: 0x7fff00000000
0xfffffff007902020: net.inet6.ip6.maxdynroutes Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007902ad0
Arg2: 0x7fff00000000
0xfffffff007902070: net.inet6.ip6.maxifdefrouters Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007902ad4
Arg2: 0x7fff00000000
0xfffffff0079020c0: net.inet6.ip6.maxifprefixes Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007902ad8
Arg2: 0x7fff00000000
0xfffffff007902110: net.inet6.ip6.neighborgcthresh Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007902adc
Arg2: 0x7fff00000000
0xfffffff007902160: net.inet6.ip6.mcast_pmtu Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007986c30
Arg2: 0x7fff00000000
0xfffffff0079021b0: net.inet6.ip6.use_defaultzone Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007986ef0
Arg2: 0x7fff00000000
0xfffffff007902200: net.inet6.ip6.prefer_tempaddr Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007900fd0
Arg2: 0x7fff00000000
0xfffffff007902250: net.inet6.ip6.rip6stats Description: 
Handler: 0xfffffff00778ea2c
Format: S,rip6stat
Parent: 0xfffffff007986c00
Arg1: fffffff007986eb8
Arg2: 0x7fff00000038
0xfffffff0079022a0: net.inet6.ip6.auto_linklocal Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007900c88
Arg2: 0x7fff00000000
0xfffffff0079022f0: net.inet6.ip6.v6only Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007986c2c
Arg2: 0x7fff00000000
0xfffffff007902340: net.inet6.ip6.tempvltime Description: 
Handler: 0xfffffff007711b58
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007903224
Arg2: 0x7fff00000000
0xfffffff007902390: net.inet6.ip6.temppltime Description: 
Handler: 0xfffffff007711acc
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007903220
Arg2: 0x7fff00000000
0xfffffff0079023e0: net.inet6.ip6.use_tempaddr Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007903218
Arg2: 0x7fff00000000
0xfffffff007902430: net.inet6.ip6.rr_prune Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007902ae0
Arg2: 0x7fff00000000
0xfffffff007902480: net.inet6.ip6.use_deprecated Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007902ae4
Arg2: 0x7fff00000000
0xfffffff0079024d0: net.inet6.ip6.kame_version Description: 
Handler: 0xfffffff00778e994
Format: A
Parent: 0xfffffff007986c00
Arg1: fffffff00744219d
Arg2: 0x7fff00000000
0xfffffff007902520: net.inet6.ip6.gifhlim Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007986c34
Arg2: 0x7fff00000000
0xfffffff007902570: net.inet6.ip6.defmcasthlim Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007902afc
Arg2: 0x7fff00000000
0xfffffff0079025c0: net.inet6.ip6.auto_flowlabel Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007902ae8
Arg2: 0x7fff00000000
0xfffffff007902610: net.inet6.ip6.dad_count Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007902aec
Arg2: 0x7fff00000000
0xfffffff007902660: net.inet6.ip6.hdrnestlimit Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007902af0
Arg2: 0x7fff00000000
0xfffffff0079026b0: net.inet6.ip6.log_interval Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007902af4
Arg2: 0x7fff00000000
0xfffffff007902700: net.inet6.ip6.keepfaith Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007986bd8
Arg2: 0x7fff00000000
0xfffffff007902750: net.inet6.ip6.accept_rtadv Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007902af8
Arg2: 0x7fff00000000
0xfffffff0079027a0: net.inet6.ip6.stats Description: 
Handler: 0xfffffff007711a94
Format: S,ip6stat
Parent: 0xfffffff007986c00
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0079027f0: net.inet6.ip6.hlim Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007902b00
Arg2: 0x7fff00000000
0xfffffff007902840: net.inet6.ip6.redirect Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007902b04
Arg2: 0x7fff00000000
0xfffffff007902890: net.inet6.ip6.forwarding Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007986c38
Arg2: 0x7fff00000000
0xfffffff007902b90: net.inet6.ip6.rtexpire Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007986c00
Arg1: fffffff007902be0
Arg2: 0x7fff00000000
0xfffffff007902be8: net.inet6.ip6.rtminexpire Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007986c00
Arg1: fffffff007902c38
Arg2: 0x7fff00000000
0xfffffff007902c40: net.inet6.ip6.rtmaxcache Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007986c00
Arg1: fffffff007902c90
Arg2: 0x7fff00000000
0xfffffff007902d60: mld.debug Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c50
Arg1: fffffff007986d48
Arg2: 0x7fff00000000
0xfffffff007902db0: mld.use_allow Description: Use ALLOW/BLOCK for RFC 4604 SSM joins/leaves
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c50
Arg1: fffffff007902d50
Arg2: 0x7fff00000000
0xfffffff007902e00: mld.v2enable Description: Enable MLDv2 (debug purposes only)
Handler: 0xfffffff00771324c
Format: I
Parent: 0xfffffff007986c50
Arg1: fffffff007902d54
Arg2: 0x7fff00000000
0xfffffff007902e50: mld.v1enable Description: Enable fallback to MLDv1
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c50
Arg1: fffffff007902d58
Arg2: 0x7fff00000000
0xfffffff007902ea0: mld.ifinfo Description: Per-interface MLDv2 state
Handler: 0xfffffff0077130d8
Format: N
Parent: 0xfffffff007986c50
Arg1: fffffff007986d08
Arg2: 0x7fff00000000
0xfffffff007902ce8: mld.gsrdelay Description: Rate limit for MLDv2 Group-and-Source queries in seconds
Handler: 0xfffffff007713034
Format: I
Parent: 0xfffffff007986c50
Arg1: fffffff007902d38
Arg2: 0x7fff00000000
0xfffffff007902fd0: net.inet6.ip6.maxchainsent Description: use dlil_output_list
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff007986d98
Arg2: 0x7fff00000000
0xfffffff007903020: net.inet6.icmp6.nd6_prlist Description: 
Handler: 0xfffffff007717fac
Format: S,in6_defrouter
Parent: 0xfffffff007986bf8
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007902f60: net.inet6.icmp6.nd6_drlist Description: 
Handler: 0xfffffff007717d78
Format: S,in6_defrouter
Parent: 0xfffffff007986bf8
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007903070: net.inet6.icmp6.nd6_llreach_base Description: default ND6 link-layer reachability max lifetime (in seconds)
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986bf8
Arg1: fffffff0079030c0
Arg2: 0x7fff00007530
0xfffffff0079030c8: net.inet6.ip6.dad_enhanced Description: Enable Enhanced DAD, which adds a random nonce to NS messages for DAD.
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986c00
Arg1: fffffff0079030c4
Arg2: 0x7fff00000000
0xfffffff007903118: net.inet6.icmp6.nd6_maxsolstgt Description: maximum number of outstanding solicited targets per prefix
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007986bf8
Arg1: fffffff007903168
Arg2: 0x7fff00000008
0xfffffff007903170: net.inet6.icmp6.nd6_maxproxiedsol Description: maximum number of outstanding solicitations per target
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007986bf8
Arg1: fffffff0079031c0
Arg2: 0x7fff00000004
0xfffffff0079031c8: net.inet6.icmp6.prproxy_cnt Description: total number of proxied prefixes
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007986bf8
Arg1: fffffff007986e2c
Arg2: 0x7fff00000000
0xfffffff007903280: send.opstate Description: current SEND operating state
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986ea8
Arg1: fffffff007986eb0
Arg2: 0x7fff00000000
0xfffffff0079032d0: send.opmode Description: configured SEND operating mode
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007986ea8
Arg1: fffffff007903320
Arg2: 0x7fff00000000
0xfffffff007903328: send.cga_parameters Description: 
Handler: 0xfffffff00772c7bc
Format: S,nd6_send_nodecfg
Parent: 0xfffffff007986ea8
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0079036a8: net.key.debug Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007988530
Arg1: fffffff007986f68
Arg2: 0x7fff00000000
0xfffffff0079036f8: net.key.spi_trycnt Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007988530
Arg1: fffffff007903748
Arg2: 0x7fff00000000
0xfffffff007903750: net.key.spi_minval Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007988530
Arg1: fffffff0079037a0
Arg2: 0x7fff00000000
0xfffffff0079037a8: net.key.spi_maxval Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007988530
Arg1: fffffff0079037f8
Arg2: 0x7fff00000000
0xfffffff007903800: net.key.int_random Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007988530
Arg1: fffffff007903850
Arg2: 0x7fff00000000
0xfffffff007903858: net.key.larval_lifetime Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007988530
Arg1: fffffff0079038a8
Arg2: 0x7fff00000000
0xfffffff0079038b0: net.key.blockacq_count Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007988530
Arg1: fffffff007903900
Arg2: 0x7fff00000000
0xfffffff007903908: net.key.blockacq_lifetime Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007988530
Arg1: fffffff007903958
Arg2: 0x7fff00000000
0xfffffff007903960: net.key.esp_auth Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007988530
Arg1: fffffff007986f74
Arg2: 0x7fff00000000
0xfffffff0079039b0: net.key.esp_keymin Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007988530
Arg1: fffffff007903a00
Arg2: 0x7fff00000000
0xfffffff007903a08: net.key.ah_keymin Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007988530
Arg1: fffffff007903a58
Arg2: 0x7fff00000000
0xfffffff007903a60: net.key.prefered_oldsa Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007988530
Arg1: fffffff007986f78
Arg2: 0x7fff00000000
0xfffffff007903ab0: net.key.natt_keepalive_interval Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007988530
Arg1: fffffff0079036a0
Arg2: 0x7fff00000000
0xfffffff007903b00: net.key.pfkeystat Description: 
Handler: 0xfffffff00778ea2c
Format: S,pfkeystat
Parent: 0xfffffff007988530
Arg1: fffffff0079874a0
Arg2: 0x7fff00001090
0xfffffff007903f20: kern.clockrate Description: 
Handler: 0xfffffff007755e2c
Format: S,clockinfo
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007903f78: vm.cs_force_kill Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0079894d0
Arg2: 0x7fff00000000
0xfffffff007903fc8: vm.cs_force_hard Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0079894d4
Arg2: 0x7fff00000000
0xfffffff007904018: vm.cs_debug Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00799011c
Arg2: 0x7fff00000000
0xfffffff007904068: vm.cs_all_vnodes Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0079894d8
Arg2: 0x7fff00000000
0xfffffff007904450: systm.kevt.pcblist Description: 
Handler: 0xfffffff007761bd4
Format: S,xkevtpcb
Parent: 0xfffffff007989530
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007904120: systm.kevt.stats Description: 
Handler: 0xfffffff007761b4c
Format: S,kevtstat
Parent: 0xfffffff007989530
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007904770: systm.kctl.debug Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079895e8
Arg1: fffffff0079896b8
Arg2: 0x7fff00000000
0xfffffff0079047c0: systm.kctl.autorcvbufhigh Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079895e8
Arg1: fffffff0079896bc
Arg2: 0x7fff00000000
0xfffffff007904810: systm.kctl.autorcvbufmax Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079895e8
Arg1: fffffff007904860
Arg2: 0x7fff00000000
0xfffffff007904868: systm.kctl.pcblist Description: 
Handler: 0xfffffff0077683a8
Format: S,xkctlpcb
Parent: 0xfffffff0079895e8
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0079048b8: systm.kctl.reg_list Description: 
Handler: 0xfffffff0077680d0
Format: S,xkctl_reg
Parent: 0xfffffff0079895e8
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0079044f0: systm.kctl.stats Description: 
Handler: 0xfffffff007768044
Format: S,kctlstat
Parent: 0xfffffff0079895e8
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007904908: kern.sugid_scripts Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff0079896c0
Arg2: 0x7fff00000000
0xfffffff0079049c8: ktrace.state Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff0079896e0
Arg1: fffffff0079896e8
Arg2: 0x7fff00000000
0xfffffff007904a18: ktrace.owning_pid Description: pid of the process that owns ktrace
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079896e0
Arg1: fffffff0079896ec
Arg2: 0x7fff00000000
0xfffffff007904a68: ktrace.background_pid Description: pid of the background ktrace tool
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff0079896e0
Arg1: fffffff0079896f0
Arg2: 0x7fff00000000
0xfffffff007904ab8: ktrace.configured_by Description: execname of process that last configured ktrace
Handler: 0xfffffff00778e994
Format: A
Parent: 0xfffffff0079896e0
Arg1: fffffff0079896f4
Arg2: 0x7fff00000000
0xfffffff007904b08: ktrace.init_background Description: initialize calling process as background
Handler: 0xfffffff0077767f0
Format: I
Parent: 0xfffffff0079896e0
Arg1: 1
Arg2: 0x7fff00000004
0xfffffff007905738: kern.maxprocperuid Description: Maximum processes allowed per userid
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff00790e98c
Arg2: 0x7fff00000000
0xfffffff007905788: kern.maxfilesperproc Description: Maximum files allowed open per process
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff007905734
Arg2: 0x7fff00000000
0xfffffff007905890: kern.min_audio_buffer_usec Description: Minimum audio buffer size, in microseconds
Handler: 0xfffffff00778da24
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0079058e0: kern.darkboot Description: 
Handler: 0xfffffff00778d934
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007905930: machdep.user_idle_level Description: User idle level heuristic, 0-128
Handler: 0xfffffff00778d8c4
Format: I
Parent: 0xfffffff007990160
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007905980: kern.timer_coalesce_tier5_ns_max Description: 
Handler: 0xfffffff00778d7d4
Format: Q
Parent: 0xfffffff007990138
Arg1: fffffff007934d18
Arg2: 0x7fff00000008
0xfffffff0079059d0: kern.timer_coalesce_tier5_scale Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff007934cec
Arg2: 0x7fff00000000
0xfffffff007905a20: kern.timer_coalesce_tier4_ns_max Description: 
Handler: 0xfffffff00778d7d4
Format: Q
Parent: 0xfffffff007990138
Arg1: fffffff007934d10
Arg2: 0x7fff00000008
0xfffffff007905a70: kern.timer_coalesce_tier4_scale Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff007934ce8
Arg2: 0x7fff00000000
0xfffffff007905ac0: kern.timer_coalesce_tier3_ns_max Description: 
Handler: 0xfffffff00778d7d4
Format: Q
Parent: 0xfffffff007990138
Arg1: fffffff007934d08
Arg2: 0x7fff00000008
0xfffffff007905b10: kern.timer_coalesce_tier3_scale Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff007934ce4
Arg2: 0x7fff00000000
0xfffffff007905b60: kern.timer_coalesce_tier2_ns_max Description: 
Handler: 0xfffffff00778d7d4
Format: Q
Parent: 0xfffffff007990138
Arg1: fffffff007934d00
Arg2: 0x7fff00000008
0xfffffff007905bb0: kern.timer_coalesce_tier2_scale Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff007934ce0
Arg2: 0x7fff00000000
0xfffffff007905c00: kern.timer_coalesce_tier1_ns_max Description: 
Handler: 0xfffffff00778d7d4
Format: Q
Parent: 0xfffffff007990138
Arg1: fffffff007934cf8
Arg2: 0x7fff00000008
0xfffffff007905c50: kern.timer_coalesce_tier1_scale Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff007934cdc
Arg2: 0x7fff00000000
0xfffffff007905ca0: kern.timer_coalesce_tier0_ns_max Description: 
Handler: 0xfffffff00778d7d4
Format: Q
Parent: 0xfffffff007990138
Arg1: fffffff007934cf0
Arg2: 0x7fff00000008
0xfffffff007905cf0: kern.timer_coalesce_tier0_scale Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff007934cd8
Arg2: 0x7fff00000000
0xfffffff007905d40: kern.timer_coalesce_ts_ns_max Description: 
Handler: 0xfffffff00778d7d4
Format: Q
Parent: 0xfffffff007990138
Arg1: fffffff007934cd0
Arg2: 0x7fff00000008
0xfffffff007905d90: kern.timer_coalesce_ts_scale Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff007934ca8
Arg2: 0x7fff00000000
0xfffffff007905de0: kern.timer_coalesce_fp_ns_max Description: 
Handler: 0xfffffff00778d7d4
Format: Q
Parent: 0xfffffff007990138
Arg1: fffffff007934cc8
Arg2: 0x7fff00000008
0xfffffff007905e30: kern.timer_coalesce_fp_scale Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff007934ca4
Arg2: 0x7fff00000000
0xfffffff007905e80: kern.timer_coalesce_kt_ns_max Description: 
Handler: 0xfffffff00778d7d4
Format: Q
Parent: 0xfffffff007990138
Arg1: fffffff007934cc0
Arg2: 0x7fff00000008
0xfffffff007905ed0: kern.timer_coalesce_kt_scale Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff007934ca0
Arg2: 0x7fff00000000
0xfffffff007905f20: kern.timer_coalesce_bg_ns_max Description: 
Handler: 0xfffffff00778d7d4
Format: Q
Parent: 0xfffffff007990138
Arg1: fffffff007934cb8
Arg2: 0x7fff00000008
0xfffffff007905f70: kern.timer_resort_threshold_ns Description: 
Handler: 0xfffffff00778d7d4
Format: Q
Parent: 0xfffffff007990138
Arg1: fffffff007934c94
Arg2: 0x7fff00000004
0xfffffff007905fc0: kern.timer_coalesce_bg_scale Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff007934c9c
Arg2: 0x7fff00000000
0xfffffff007906010: kern.sched Description: Timeshare scheduler implementation
Handler: 0xfffffff00778e994
Format: A
Parent: 0xfffffff007990138
Arg1: fffffff00791ef08
Arg2: 0x7fff00000030
0xfffffff007906060: kern.ipc_portbt Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff007916308
Arg2: 0x7fff00000000
0xfffffff0079060b0: kern.stack_depth_max Description: Max kernel stack depth at interrupt or context switch
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff00791f6d8
Arg2: 0x7fff00000000
0xfffffff007906100: kern.stack_size Description: Kernel stack size
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff00791f6d0
Arg2: 0x7fff00000000
0xfffffff007906150: kern.ipc_voucher_trace_contents Description: Enable tracing voucher contents
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff007916338
Arg2: 0x7fff00000000
0xfffffff0079061a0: vm.vm_pageout_rejected_bq_external Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007964440
Arg2: 0x7fff00000000
0xfffffff0079061f0: vm.vm_pageout_rejected_bq_internal Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007964438
Arg2: 0x7fff00000000
0xfffffff007906240: vm.vm_pageout_considered_bq_external Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007964430
Arg2: 0x7fff00000000
0xfffffff007906290: vm.vm_pageout_considered_bq_internal Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007964428
Arg2: 0x7fff00000000
0xfffffff0079062e0: vm.vm_page_background_promoted_count Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007965bd8
Arg2: 0x7fff00000000
0xfffffff007906330: vm.vm_page_background_external_count Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff007965bd0
Arg2: 0x7fff00000000
0xfffffff007906380: vm.vm_page_background_internal_count Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff007965bcc
Arg2: 0x7fff00000000
0xfffffff0079063d0: vm.vm_page_background_count Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff007965bc8
Arg2: 0x7fff00000000
0xfffffff007906420: vm.vm_page_background_target Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff007965be0
Arg2: 0x7fff00000000
0xfffffff007906470: vm.vm_page_background_limit Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff007965be4
Arg2: 0x7fff00000000
0xfffffff0079064c0: vm.vm_page_background_exclude_external Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff007965bec
Arg2: 0x7fff00000000
0xfffffff007906510: vm.vm_page_background_mode Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff007965be8
Arg2: 0x7fff00000000
0xfffffff007906560: vm.phantom_cache_thrashing_threshold_ssd Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f044c
Arg2: 0x7fff00000000
0xfffffff0079065b0: vm.phantom_cache_thrashing_threshold Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f0450
Arg2: 0x7fff00000000
0xfffffff007906600: vm.phantom_cache_eval_period_in_msecs Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f0448
Arg2: 0x7fff00000000
0xfffffff007906650: vm.lz4_profitable_bytes Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f0440
Arg2: 0x7fff00000000
0xfffffff0079066a0: vm.lz4_run_continue_bytes Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f043c
Arg2: 0x7fff00000000
0xfffffff0079066f0: vm.lz4_run_preselection_threshold Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f0438
Arg2: 0x7fff00000000
0xfffffff007906740: vm.lz4_max_preselects Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f0434
Arg2: 0x7fff00000000
0xfffffff007906790: vm.lz4_max_failure_run_length Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f0430
Arg2: 0x7fff00000000
0xfffffff0079067e0: vm.lz4_max_failure_skips Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f042c
Arg2: 0x7fff00000000
0xfffffff007906830: vm.wkdm_reeval_threshold Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f0424
Arg2: 0x7fff00000000
0xfffffff007906880: vm.lz4_threshold Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f0428
Arg2: 0x7fff00000000
0xfffffff0079068d0: vm.wk_sv_decompressions Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f618
Arg2: 0x7fff00000000
0xfffffff007906920: vm.wk_decompressed_bytes Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f610
Arg2: 0x7fff00000000
0xfffffff007906970: vm.wk_decompressions Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f608
Arg2: 0x7fff00000000
0xfffffff0079069c0: vm.wk_compressed_bytes_total Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f5d8
Arg2: 0x7fff00000000
0xfffffff007906a10: vm.wk_compressed_bytes_exclusive Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f5e8
Arg2: 0x7fff00000000
0xfffffff007906a60: vm.wk_compression_failures Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f5d0
Arg2: 0x7fff00000000
0xfffffff007906ab0: vm.wk_mzv_compressions Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f5c8
Arg2: 0x7fff00000000
0xfffffff007906b00: vm.wk_sv_compressions Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f5c0
Arg2: 0x7fff00000000
0xfffffff007906b50: vm.wk_compressions_exclusive Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f5e0
Arg2: 0x7fff00000000
0xfffffff007906ba0: vm.wk_compressions Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f5b8
Arg2: 0x7fff00000000
0xfffffff007906bf0: vm.uc_decompressions Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f600
Arg2: 0x7fff00000000
0xfffffff007906c40: vm.lz4_decompressed_bytes Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f5f8
Arg2: 0x7fff00000000
0xfffffff007906c90: vm.lz4_decompressions Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f5f0
Arg2: 0x7fff00000000
0xfffffff007906ce0: vm.lz4_wk_compression_negative_delta Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f5a8
Arg2: 0x7fff00000000
0xfffffff007906d30: vm.lz4_wk_compression_delta Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f5a0
Arg2: 0x7fff00000000
0xfffffff007906d80: vm.lz4_compressed_bytes Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f598
Arg2: 0x7fff00000000
0xfffffff007906dd0: vm.lz4_compression_failures Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f590
Arg2: 0x7fff00000000
0xfffffff007906e20: vm.lz4_compressions Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f588
Arg2: 0x7fff00000000
0xfffffff007906e70: vm.compressor_thread_runtime Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff0079645b0
Arg2: 0x7fff00000000
0xfffffff007906ec0: vm.compressor_timing_enabled Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0079645a8
Arg2: 0x7fff00000000
0xfffffff007906f10: vm.swapfileprefix Description: 
Handler: 0xfffffff00778e994
Format: A
Parent: 0xfffffff007990140
Arg1: fffffff00794f158
Arg2: 0x7fff000003ff
0xfffffff007906f60: vm.compressor_catchup_threshold_divisor Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f03e4
Arg2: 0x7fff00000000
0xfffffff007906fb0: vm.compressor_unthrottle_threshold_divisor Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f03e0
Arg2: 0x7fff00000000
0xfffffff007907000: vm.compressor_majorcompact_threshold_divisor Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f03dc
Arg2: 0x7fff00000000
0xfffffff007907050: vm.compressor_minorcompact_threshold_divisor Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f03d8
Arg2: 0x7fff00000000
0xfffffff0079070a0: vm.compressor_thrashing_min_per_10msecs Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f03fc
Arg2: 0x7fff00000000
0xfffffff0079070f0: vm.compressor_thrashing_threshold_per_10msecs Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f03f8
Arg2: 0x7fff00000000
0xfffffff007907140: vm.compressor_sample_max_in_msecs Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f03f4
Arg2: 0x7fff00000000
0xfffffff007907190: vm.compressor_sample_min_in_msecs Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f03f0
Arg2: 0x7fff00000000
0xfffffff0079071e0: vm.compressor_eval_period_in_msecs Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f03ec
Arg2: 0x7fff00000000
0xfffffff007907230: vm.vm_ripe_target_age_in_secs Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f03e8
Arg2: 0x7fff00000000
0xfffffff007907280: vm.compressor_available Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00794aea8
Arg2: 0x7fff00000000
0xfffffff0079072d0: vm.compressor_swapout_target_age Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00794af28
Arg2: 0x7fff00000000
0xfffffff007907320: vm.compressor_is_active Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00794aea0
Arg2: 0x7fff00000000
0xfffffff007907370: vm.compressor_mode Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f03d0
Arg2: 0x7fff00000000
0xfffffff0079073c0: vm.compressor_bytes_used Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794af40
Arg2: 0x7fff00000000
0xfffffff007907410: vm.compressor_compressed_bytes Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794af38
Arg2: 0x7fff00000000
0xfffffff007907460: vm.compressor_input_bytes Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794af30
Arg2: 0x7fff00000000
0xfffffff0079074b0: vm.vm_page_filecache_min Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00796444c
Arg2: 0x7fff00000000
0xfffffff007907500: vm.vm_page_external_count Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00796483c
Arg2: 0x7fff00000000
0xfffffff007907550: vm.vm_copy_src_large Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00794f864
Arg2: 0x7fff00000000
0xfffffff0079075a0: vm.vm_copy_src_not_symmetric Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00794f860
Arg2: 0x7fff00000000
0xfffffff0079075f0: vm.vm_copy_src_not_internal Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00794f85c
Arg2: 0x7fff00000000
0xfffffff007907640: vm.user_wire_limit Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007989820
Arg2: 0x7fff00000000
0xfffffff007907690: vm.global_user_wire_limit Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007989828
Arg2: 0x7fff00000000
0xfffffff0079076e0: vm.global_no_user_wire_amount Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007989830
Arg2: 0x7fff00000000
0xfffffff007907730: kern.slide Description: 
Handler: 0xfffffff00778d75c
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007907780: kern.affinity_sets_mapping Description: mapping policy
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff007917444
Arg2: 0x7fff00000000
0xfffffff0079077d0: kern.affinity_sets_enabled Description: hinting enabled
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff007917440
Arg2: 0x7fff00000000
0xfffffff007907820: kern.minimalboot Description: 
Handler: 0xfffffff00778d6f4
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007907870: kern.singleuser Description: 
Handler: 0xfffffff00778d688
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0079078c0: kern.safeboot Description: 
Handler: 0xfffffff00778d61c
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007907910: sysctl.proc_cputype Description: proc_cputype
Handler: 0xfffffff00778d578
Format: I
Parent: 0xfffffff007990130
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007907960: sysctl.proc_native Description: proc_native
Handler: 0xfffffff00778d4d0
Format: I
Parent: 0xfffffff007990130
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0079079b0: kern.shreg_private Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007907a00: vm.freeze_enabled Description: 
Handler: 0xfffffff00778d430
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff007989bf4
Arg2: 0x7fff00000000
0xfffffff007907a50: vm.swapusage Description: 
Handler: 0xfffffff00778d36c
Format: S,xsw_usage
Parent: 0xfffffff007990140
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007907aa0: debug.toggle_address_reuse Description: 
Handler: 0xfffffff00778d228
Format: I
Parent: 0xfffffff007990158
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007907af0: vm.loadavg Description: 
Handler: 0xfffffff00778d130
Format: S,loadavg
Parent: 0xfffffff007990140
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007907b40: kern.nx Description: 
Handler: 0xfffffff00778d128
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007907b90: kern.check_openevt Description: set the per-process check-open-evt flag
Handler: 0xfffffff00778d098
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007907be0: kern.setthread_cpupercent Description: set thread cpu percentage limit
Handler: 0xfffffff00778d014
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007907c30: kern.rage_vnode Description: 
Handler: 0xfffffff00778cec4
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007907c80: kern.delayterm Description: 
Handler: 0xfffffff00778ce04
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007907cd0: kern.usrstack64 Description: 
Handler: 0xfffffff00778cde8
Format: Q
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007907d20: kern.usrstack Description: 
Handler: 0xfffffff00778cd74
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007907d70: kern.timer.longterm.qlen Description: 
Handler: 0xfffffff00778cbe4
Format: Q
Parent: 0xfffffff007989838
Arg1: 1
Arg2: 0x7fff00000000
0xfffffff007907dc0: kern.timer.longterm.threshold Description: 
Handler: 0xfffffff00778cbe4
Format: Q
Parent: 0xfffffff007989838
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007907e60: kern.timer.deadline_tracking_bin_2 Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007989840
Arg1: fffffff00791efb0
Arg2: 0x7fff00000000
0xfffffff007907eb0: kern.timer.deadline_tracking_bin_1 Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007989840
Arg1: fffffff00791efa8
Arg2: 0x7fff00000000
0xfffffff007907f00: kern.timer.coalescing_enabled Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007989840
Arg1: fffffff0078f0318
Arg2: 0x7fff00000000
0xfffffff007907fa0: kern.symfile Description: 
Handler: 0xfffffff00778cbdc
Format: A
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007907ff0: kern.boottime Description: 
Handler: 0xfffffff00778cadc
Format: S,timeval
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007908040: kern.bootsessionuuid Description: 
Handler: 0xfffffff00778e994
Format: A
Parent: 0xfffffff007990138
Arg1: fffffff00798f4a8
Arg2: 0x7fff00000025
0xfffffff007908090: kern.vm_max_batch Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990138
Arg1: fffffff0078f0464
Arg2: 0x7fff00000000
0xfffffff0079080e0: kern.vm_max_delayed_work_limit Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990138
Arg1: fffffff0078f04b0
Arg2: 0x7fff00000000
0xfffffff007908130: kern.vm_page_speculative_q_age_ms Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990138
Arg1: fffffff0078f0480
Arg2: 0x7fff00000000
0xfffffff007908180: kern.vm_page_speculative_percentage Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990138
Arg1: fffffff0078f0484
Arg2: 0x7fff00000000
0xfffffff0079081d0: kern.vm_page_free_reserved Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990138
Arg1: fffffff007964870
Arg2: 0x7fff00000000
0xfffffff007908220: kern.vm_page_free_min Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990138
Arg1: fffffff007964858
Arg2: 0x7fff00000000
0xfffffff007908270: kern.vm_page_free_target Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990138
Arg1: fffffff007964854
Arg2: 0x7fff00000000
0xfffffff0079082c0: kern.speculative_prefetch_max_iosize Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990138
Arg1: fffffff0078f43c0
Arg2: 0x7fff00000000
0xfffffff007908310: kern.speculative_prefetch_max Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990138
Arg1: fffffff0078f43bc
Arg2: 0x7fff00000000
0xfffffff007908360: kern.preheat_min_bytes Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990138
Arg1: fffffff0078f046c
Arg2: 0x7fff00000000
0xfffffff0079083b0: kern.preheat_max_bytes Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990138
Arg1: fffffff0078f0468
Arg2: 0x7fff00000000
0xfffffff007908400: kern.ignore_is_ssd Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff00796d750
Arg2: 0x7fff00000000
0xfffffff007908450: kern.speculative_reads_disabled Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff00796d754
Arg2: 0x7fff00000000
0xfffffff0079084a0: kern.procname Description: 
Handler: 0xfffffff00778cabc
Format: A
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0079084f0: kern.hostname Description: 
Handler: 0xfffffff00778ca68
Format: A
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007908540: kern.hostid Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff0079890e0
Arg2: 0x7fff00000000
0xfffffff007908590: kern.nisdomainname Description: 
Handler: 0xfffffff00778ca30
Format: A
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0079085e0: kern.securelevel Description: 
Handler: 0xfffffff00778c994
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007908630: kern.aiothreads Description: 
Handler: 0xfffffff00778c8e8
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007908680: kern.aioprocmax Description: 
Handler: 0xfffffff00778c87c
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0079086d0: kern.aiomax Description: 
Handler: 0xfffffff00778c810
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007908720: kern.maxproc Description: 
Handler: 0xfffffff00778c7a4
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007908770: kern.maxvnodes Description: 
Handler: 0xfffffff00778c5bc
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0079087c0: kern.namecache_disabled Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff0079692a8
Arg2: 0x7fff00000000
0xfffffff007908810: kern.num_taskthreads Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff0078f02f4
Arg2: 0x7fff00000000
0xfffffff007908860: kern.num_threads Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff0078f02f0
Arg2: 0x7fff00000000
0xfffffff0079088b0: kern.num_tasks Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff0078f02d8
Arg2: 0x7fff00000000
0xfffffff007908900: kern.num_vnodes Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff00796dbb0
Arg2: 0x7fff00000000
0xfffffff007908950: kern.num_files Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff00798950c
Arg2: 0x7fff00000000
0xfffffff0079089a0: kern.saved_ids Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000001
0xfffffff0079089f0: kern.job_control Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000001
0xfffffff007908a40: kern.ngroups Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000010
0xfffffff007908a90: kern.posix1version Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00030db0
0xfffffff007908ae0: kern.argmax Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00040000
0xfffffff007908b30: kern.maxfiles Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff00790e994
Arg2: 0x7fff00000000
0xfffffff007908b80: kern.bootargs Description: bootargs
Handler: 0xfffffff00778c53c
Format: A
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007908bd0: kern.osversion Description: 
Handler: 0xfffffff00778c4c0
Format: A
Parent: 0xfffffff007990138
Arg1: fffffff00798fa30
Arg2: 0x7fff00000100
0xfffffff007908c20: kern.uuid Description: 
Handler: 0xfffffff00778e994
Format: A
Parent: 0xfffffff007990138
Arg1: fffffff0079177c8
Arg2: 0x7fff00000000
0xfffffff007908c70: kern.version Description: 
Handler: 0xfffffff00778e994
Format: A
Parent: 0xfffffff007990138
Arg1: fffffff00741f6d8
Arg2: 0x7fff00000000
0xfffffff007908cc0: kern.osrevision Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00030b52
0xfffffff007908d10: kern.osrelease Description: 
Handler: 0xfffffff00778e994
Format: A
Parent: 0xfffffff007990138
Arg1: fffffff00741f756
Arg2: 0x7fff00000000
0xfffffff007908d60: kern.ostype Description: 
Handler: 0xfffffff00778e994
Format: A
Parent: 0xfffffff007990138
Arg1: fffffff00741f75d
Arg2: 0x7fff00000000
0xfffffff007908db0: kern.procargs2 Description: 
Handler: 0xfffffff00778c084
Format: ?
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007908e00: kern.kdebug Description: 
Handler: 0xfffffff00778b0c0
Format: ?
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007908e50: kern.proc.lcid Description: 
Handler: 0xfffffff00778a900
Format: ?
Parent: 0xfffffff007989848
Arg1: 0
Arg2: 0x7fff00000007
0xfffffff007908ea0: kern.proc.ruid Description: 
Handler: 0xfffffff00778a900
Format: ?
Parent: 0xfffffff007989848
Arg1: 0
Arg2: 0x7fff00000006
0xfffffff007908ef0: kern.proc.uid Description: 
Handler: 0xfffffff00778a900
Format: ?
Parent: 0xfffffff007989848
Arg1: 0
Arg2: 0x7fff00000005
0xfffffff007908f40: kern.proc.pgrp Description: 
Handler: 0xfffffff00778a900
Format: ?
Parent: 0xfffffff007989848
Arg1: 0
Arg2: 0x7fff00000002
0xfffffff007908f90: kern.proc.tty Description: 
Handler: 0xfffffff00778a900
Format: ?
Parent: 0xfffffff007989848
Arg1: 0
Arg2: 0x7fff00000004
0xfffffff007908fe0: kern.proc.pid Description: 
Handler: 0xfffffff00778a900
Format: ?
Parent: 0xfffffff007989848
Arg1: 0
Arg2: 0x7fff00000001
0xfffffff007909030: kern.proc.all Description: 
Handler: 0xfffffff00778a900
Format: ?
Parent: 0xfffffff007989848
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0079090d0: debug.sched Description: scheduler debug
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990158
Arg1: fffffff00791ef38
Arg2: 0x7fff00000000
0xfffffff007909120: kern.sched_stats_enable Description: 
Handler: 0xfffffff00778a8b0
Format: -
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007909170: kern.sched_stats Description: 
Handler: 0xfffffff00778a694
Format: -
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007905838: kern.threadname Description: 
Handler: 0xfffffff00778a56c
Format: A
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007909218: sysctl.oidfmt Description: 
Handler: 0xfffffff00778e190
Format: N
Parent: 0xfffffff007990130
Arg1: fffffff007989868
Arg2: 0x7fff00000000
0xfffffff007909268: sysctl.name2oid Description: 
Handler: 0xfffffff00778df04
Format: I
Parent: 0xfffffff007990130
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0079092b8: sysctl.next Description: 
Handler: 0xfffffff00778dcb0
Format: N
Parent: 0xfffffff007990130
Arg1: fffffff007989870
Arg2: 0x7fff00000000
0xfffffff007909308: sysctl.name Description: 
Handler: 0xfffffff00778dacc
Format: N
Parent: 0xfffffff007990130
Arg1: fffffff007989878
Arg2: 0x7fff00000000
0xfffffff0079091c0: sysctl.debug Description: 
Handler: 0xfffffff00778da9c
Format: -
Parent: 0xfffffff007990130
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0079093c8: kern.memorystatus_policy_more_free Description: 
Handler: 0xfffffff007790964
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007909418: kern.memorystatus_purge_on_critical Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff0078f047c
Arg2: 0x7fff00000000
0xfffffff007909468: kern.memorystatus_purge_on_urgent Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff0078f0478
Arg2: 0x7fff00000000
0xfffffff0079094b8: kern.memorystatus_purge_on_warning Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff0078f0474
Arg2: 0x7fff00000000
0xfffffff007909508: kern.memorypressure_manual_trigger Description: 
Handler: 0xfffffff00778fcf0
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007909558: kern.memorystatus_vm_pressure_level Description: 
Handler: 0xfffffff00778fc80
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0079095b8: kern.memorystatus_level Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff007989c30
Arg2: 0x7fff00000000
0xfffffff007909608: kern.max_task_pmem Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff00791f7c4
Arg2: 0x7fff00000000
0xfffffff007909658: kern.jetsam_aging_policy Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff007909748
Arg2: 0x7fff00000000
0xfffffff0079096a8: kern.memorystatus_apps_idle_delay_time Description: Aging window for applications
Handler: 0xfffffff00778fb94
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff0079096f8: kern.memorystatus_sysprocs_idle_delay_time Description: Aging window for system processes
Handler: 0xfffffff00778faa8
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007909a70: optional.arm64 Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007989c50
Arg1: fffffff007909c50
Arg2: 0x7fff00000000
0xfffffff007909ac0: optional.vfp_shortvector Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007989c50
Arg1: fffffff007909c54
Arg2: 0x7fff00000000
0xfffffff007909b10: optional.neon_hpfp Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007989c50
Arg1: fffffff007909c58
Arg2: 0x7fff00000000
0xfffffff007909b60: optional.neon Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007989c50
Arg1: fffffff007909c5c
Arg2: 0x7fff00000000
0xfffffff007909bb0: optional.breakpoint Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007989c50
Arg1: fffffff007909c60
Arg2: 0x7fff00000000
0xfffffff007909c00: optional.watchpoint Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007989c50
Arg1: fffffff007909c64
Arg2: 0x7fff00000000
0xfffffff007909c68: hw.cputhreadtype Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007989c40
Arg1: fffffff007989d08
Arg2: 0x7fff00000000
0xfffffff007909cb8: hw.l3settings Description: 
Handler: 0xfffffff0077965b8
Format: I
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff00000015
0xfffffff007909d08: hw.l2settings Description: 
Handler: 0xfffffff0077965b8
Format: I
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff00000013
0xfffffff007909d58: hw.vectorunit Description: 
Handler: 0xfffffff0077965b8
Format: I
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff0000000d
0xfffffff007909da8: hw.epoch Description: 
Handler: 0xfffffff0077965b8
Format: I
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff0000000a
0xfffffff007909df8: hw.usermem Description: 
Handler: 0xfffffff0077965b8
Format: I
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff00000006
0xfffffff007909e48: hw.physmem Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007989c40
Arg1: fffffff007990080
Arg2: 0x7fff00000000
0xfffffff007909e98: hw.model Description: 
Handler: 0xfffffff0077965b8
Format: A
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff00000002
0xfffffff007909ee8: hw.machine Description: 
Handler: 0xfffffff0077965b8
Format: A
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff00000001
0xfffffff007909f38: hw.tbfrequency_compat Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007989c40
Arg1: fffffff007991088
Arg2: 0x7fff00000000
0xfffffff007909f88: hw.l3cachesize_compat Description: 
Handler: 0xfffffff0077965b8
Format: I
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff00000016
0xfffffff007909fd8: hw.l2cachesize_compat Description: 
Handler: 0xfffffff0077965b8
Format: I
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff00000014
0xfffffff00790a028: hw.l1dcachesize_compat Description: 
Handler: 0xfffffff0077965b8
Format: I
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff00000012
0xfffffff00790a078: hw.l1icachesize_compat Description: 
Handler: 0xfffffff0077965b8
Format: I
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff00000011
0xfffffff00790a0c8: hw.cachelinesize_compat Description: 
Handler: 0xfffffff0077965b8
Format: I
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff00000010
0xfffffff00790a118: hw.pagesize_compat Description: 
Handler: 0xfffffff0077965b8
Format: I
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff00000007
0xfffffff00790a1b8: optional.floatingpoint Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007989c50
Arg1: 0
Arg2: 0x7fff00000001
0xfffffff00790a258: hw.packages Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007989c40
Arg1: fffffff007989c58
Arg2: 0x7fff00000000
0xfffffff00790a2a8: hw.memsize Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007989c40
Arg1: fffffff007990090
Arg2: 0x7fff00000000
0xfffffff00790a2f8: hw.tbfrequency Description: 
Handler: 0xfffffff007796a4c
Format: Q
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff00790a348: hw.l3cachesize Description: 
Handler: 0xfffffff0077965b8
Format: Q
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff80000016
0xfffffff00790a398: hw.l2cachesize Description: 
Handler: 0xfffffff0077965b8
Format: Q
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff80000014
0xfffffff00790a3e8: hw.l1dcachesize Description: 
Handler: 0xfffffff0077965b8
Format: Q
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff80000012
0xfffffff00790a438: hw.l1icachesize Description: 
Handler: 0xfffffff0077965b8
Format: Q
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff80000011
0xfffffff00790a488: hw.cachelinesize Description: 
Handler: 0xfffffff0077965b8
Format: Q
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff80000010
0xfffffff00790a4d8: hw.pagesize32 Description: 
Handler: 0xfffffff007796a20
Format: Q
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff00790a528: hw.pagesize Description: 
Handler: 0xfffffff0077969dc
Format: Q
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff00790a578: hw.cachesize Description: 
Handler: 0xfffffff00778ea2c
Format: Q
Parent: 0xfffffff007989c40
Arg1: fffffff007989c60
Arg2: 0x7fff00000050
0xfffffff00790a5c8: hw.cacheconfig Description: 
Handler: 0xfffffff00778ea2c
Format: Q
Parent: 0xfffffff007989c40
Arg1: fffffff007989cb0
Arg2: 0x7fff00000050
0xfffffff00790a618: hw.cpufamily Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007989c40
Arg1: fffffff007989d04
Arg2: 0x7fff00000000
0xfffffff00790a668: hw.cpu64bit_capable Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007989c40
Arg1: fffffff007989d00
Arg2: 0x7fff00000000
0xfffffff00790a6b8: hw.cpusubtype Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007989c40
Arg1: fffffff007989d0c
Arg2: 0x7fff00000000
0xfffffff00790a708: hw.cputype Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007989c40
Arg1: fffffff007989d10
Arg2: 0x7fff00000000
0xfffffff00790a758: hw.byteorder Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff000004d2
0xfffffff00790a7a8: hw.logicalcpu_max Description: 
Handler: 0xfffffff0077965b8
Format: I
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff40000005
0xfffffff00790a7f8: hw.logicalcpu Description: 
Handler: 0xfffffff0077965b8
Format: I
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff40000004
0xfffffff00790a848: hw.physicalcpu_max Description: 
Handler: 0xfffffff0077965b8
Format: I
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff40000003
0xfffffff00790a898: hw.physicalcpu Description: 
Handler: 0xfffffff0077965b8
Format: I
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff40000002
0xfffffff00790a8e8: hw.activecpu Description: 
Handler: 0xfffffff0077965b8
Format: I
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff00000019
0xfffffff007909a20: hw.ncpu Description: 
Handler: 0xfffffff0077965b8
Format: I
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff00000003
0xfffffff00790aae0: kern.msgbuf Description: 
Handler: 0xfffffff00779e23c
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff00790ace8: kern.coalition_pid_list Description: list of PIDS which are members of the coalition of the current process
Handler: 0xfffffff0077a8194
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff00790ad38: kern.coalition_page_count Description: coalition page count of a specified process
Handler: 0xfffffff0077a8060
Format: Q
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff00790ad88: kern.coalition_roles Description: coalition roles of a given process
Handler: 0xfffffff0077a7f04
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff00790ac98: kern.coalitions Description: coalition ids of a given process
Handler: 0xfffffff0077a7e34
Format: Q
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff00790b048: tty.ptmx_max Description: ptmx_max
Handler: 0xfffffff0077b260c
Format: I
Parent: 0xfffffff00798d088
Arg1: fffffff00790b098
Arg2: 0x7fff00000000
0xfffffff00790b188: vm.cs_blob_count Description: Current number of code signature blobs
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00798da70
Arg2: 0x7fff00000000
0xfffffff00790b1d8: vm.cs_blob_size Description: Current size of all code signature blobs
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00798da74
Arg2: 0x7fff00000000
0xfffffff00790b228: vm.cs_blob_count_peak Description: Peak number of code signature blobs
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00798da78
Arg2: 0x7fff00000000
0xfffffff00790b278: vm.cs_blob_size_peak Description: Peak size of code signature blobs
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00798da7c
Arg2: 0x7fff00000000
0xfffffff00790b2c8: vm.cs_blob_size_max Description: Size of biggest code signature blob
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00798da80
Arg2: 0x7fff00000000
0xfffffff00790b658: ipc.mb_drain_maxint Description: Minimum time interval between garbage collection
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00790b444
Arg2: 0x7fff00000000
0xfffffff00790b6a8: ipc.mb_drain_force Description: Forces the mbuf garbage collection to run
Handler: 0xfffffff0077ba560
Format: I
Parent: 0xfffffff00798e0d0
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff00790b6f8: ipc.mb_watchdog Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00790b440
Arg2: 0x7fff00000000
0xfffffff00790b748: ipc.mb_normalized Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798ded0
Arg2: 0x7fff00000000
0xfffffff00790b798: ipc.mleak_sample_factor Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798de5c
Arg2: 0x7fff00000000
0xfffffff00790b7e8: ipc.mleak_table Description: 
Handler: 0xfffffff0077ba4e8
Format: S,mleak_table
Parent: 0xfffffff00798e0d0
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff00790b838: ipc.mleak_top_trace Description: 
Handler: 0xfffffff0077ba1f4
Format: S,mb_top_trace
Parent: 0xfffffff00798e0d0
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff00790b888: ipc.mb_stat Description: 
Handler: 0xfffffff0077b9ec4
Format: S,mb_stat
Parent: 0xfffffff00798e0d0
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff00790b3f0: ipc.mbstat Description: 
Handler: 0xfffffff0077b9cbc
Format: S,mbstat
Parent: 0xfffffff00798e0d0
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff00790bc30: ipc.socket_debug Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798df68
Arg2: 0x7fff00000000
0xfffffff00790bc88: ipc.somaxconn Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00790bc80
Arg2: 0x7fff00000000
0xfffffff00790bcd8: ipc.sosendminchain Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00790bd28
Arg2: 0x7fff00000000
0xfffffff00790bd30: ipc.sorecvmincopy Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00790bd80
Arg2: 0x7fff00000000
0xfffffff00790bd88: ipc.sosendjcl Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00790bd84
Arg2: 0x7fff00000000
0xfffffff00790bdd8: ipc.sosendjcl_ignore_capab Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798df6c
Arg2: 0x7fff00000000
0xfffffff00790be28: ipc.sosendbigcl_ignore_capab Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798df70
Arg2: 0x7fff00000000
0xfffffff00790be78: ipc.sodefunctlog Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798df74
Arg2: 0x7fff00000000
0xfffffff00790bec8: ipc.sothrottlelog Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798df78
Arg2: 0x7fff00000000
0xfffffff00790bf20: ipc.sorestrictrecv Description: Enable inbound interface restrictions
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00790bf18
Arg2: 0x7fff00000000
0xfffffff00790bf78: ipc.sorestrictsend Description: Enable outbound interface restrictions
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00790bf70
Arg2: 0x7fff00000000
0xfffffff00790bfd0: ipc.soreserveheadroom Description: To allocate contiguous datagram buffers
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00790bfc8
Arg2: 0x7fff00000000
0xfffffff00790c020: ipc.maxextbkidleperproc Description: Maximum of extended background idle sockets per process
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798df7c
Arg2: 0x7fff00000000
0xfffffff00790c070: ipc.extbkidletime Description: Time in seconds to keep extended background idle sockets
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798df80
Arg2: 0x7fff00000000
0xfffffff00790c0c0: ipc.extbkidlercvhiwat Description: High water mark for extended background idle sockets
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798df84
Arg2: 0x7fff00000000
0xfffffff00790c110: ipc.extbkidlestat Description: 
Handler: 0xfffffff00778ea2c
Format: S,soextbkidlestat
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798df7c
Arg2: 0x7fff0000003c
0xfffffff00790c160: ipc.sotcdb Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798dfb8
Arg2: 0x7fff00000000
0xfffffff00790c298: ipc.throttle_best_effort Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798e0cc
Arg2: 0x7fff00000000
0xfffffff00790c3a0: io_policy.uuid Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e108
Arg1: fffffff00790c2f0
Arg2: 0x7fff00000000
0xfffffff00790c3f0: io_policy.log Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e108
Arg1: fffffff00798e0fc
Arg2: 0x7fff00000000
0xfffffff00790c440: io_policy.throttled Description: 
Handler: 0xfffffff0077d27a4
Format: I
Parent: 0xfffffff00798e108
Arg1: fffffff00798e0f8
Arg2: 0x7fff00000000
0xfffffff00790c4e0: ipc.sbmb_limreached Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798e0f0
Arg2: 0x7fff00000000
0xfffffff00790c530: ipc.sbmb_cnt_floor Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798e0e0
Arg2: 0x7fff00000000
0xfffffff00790c580: ipc.sbmb_cnt_peak Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798e0e8
Arg2: 0x7fff00000000
0xfffffff00790c5d0: ipc.sbmb_cnt Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798e0d8
Arg2: 0x7fff00000000
0xfffffff00790c620: ipc.soqlencomp Description: Listen backlog represents only complete queue
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798e100
Arg2: 0x7fff00000000
0xfffffff00790c670: ipc.soqlimitcompat Description: Enable socket queue limit compatibility
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00790c398
Arg2: 0x7fff00000001
0xfffffff00790c6c0: ipc.njclbytes Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798deb0
Arg2: 0x7fff00000000
0xfffffff00790c710: ipc.njcl Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00798db08
Arg2: 0x7fff00000000
0xfffffff00790c760: ipc.nmbclusters Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00790e998
Arg2: 0x7fff00000000
0xfffffff00790c7b0: ipc.sockbuf_waste_factor Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e0d0
Arg1: fffffff00790c39c
Arg2: 0x7fff00000000
0xfffffff00790c348: ipc.maxsockbuf Description: Maximum socket buffer size
Handler: 0xfffffff0077d2724
Format: IU
Parent: 0xfffffff00798e0d0
Arg1: fffffff00790c2e8
Arg2: 0x7fff00000000
0xfffffff00790c808: ipc.maxsendmsgx Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff00798e0d0
Arg1: fffffff00790c858
Arg2: 0x7fff00000000
0xfffffff00790c860: ipc.maxrecvmsgx Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff00798e0d0
Arg1: fffffff00790c8b0
Arg2: 0x7fff00000000
0xfffffff00790c9d8: local.stream.pcblist Description: List of active local stream sockets
Handler: 0xfffffff0077dd1fc
Format: S,xunpcb
Parent: 0xfffffff00798df58
Arg1: 1
Arg2: 0x7fff00000000
0xfffffff00790ca28: local.dgram.pcblist Description: List of active local datagram sockets
Handler: 0xfffffff0077dd1fc
Format: S,xunpcb
Parent: 0xfffffff00798df50
Arg1: 2
Arg2: 0x7fff00000000
0xfffffff00790ca78: local.inflight Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798df60
Arg1: fffffff00798e140
Arg2: 0x7fff00000000
0xfffffff00790cac8: local.dgram.recvspace Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798df50
Arg1: fffffff00790c9b4
Arg2: 0x7fff00000000
0xfffffff00790cb18: local.dgram.maxdgram Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798df50
Arg1: fffffff00790c9b8
Arg2: 0x7fff00000000
0xfffffff00790cb68: local.stream.tracemdns Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798df58
Arg1: fffffff00798e144
Arg2: 0x7fff00000000
0xfffffff00790cbb8: local.stream.recvspace Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798df58
Arg1: fffffff00790c9bc
Arg2: 0x7fff00000000
0xfffffff00790cc08: local.stream.sendspace Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798df58
Arg1: fffffff00790c9c0
Arg2: 0x7fff00000000
0xfffffff00790cd08: sem.max Description: max
Handler: 0xfffffff00778e8a8
Format: L
Parent: 0xfffffff00798e1a8
Arg1: fffffff00790cc60
Arg2: 0x7fff00000000
0xfffffff00790cd90: debug.sys_override_enabled Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990158
Arg1: fffffff00798e268
Arg2: 0x7fff00000000
0xfffffff00790cde8: vm.log_executable_mem_entry Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00796675c
Arg2: 0x7fff00000000
0xfffffff00790ce38: vm.cs_executable_create_upl Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff007964580
Arg2: 0x7fff00000000
0xfffffff00790ce88: vm.cs_executable_mem_entry Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff007966758
Arg2: 0x7fff00000000
0xfffffff00790ced8: vm.cs_executable_wire Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00794f858
Arg2: 0x7fff00000000
0xfffffff00790cf28: vm.vm_do_collapse_compressor Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00794fc98
Arg2: 0x7fff00000000
0xfffffff00790cf78: vm.vm_do_collapse_compressor_pages Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00794fc9c
Arg2: 0x7fff00000000
0xfffffff00790cfc8: vm.vm_do_collapse_terminate Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00794fca0
Arg2: 0x7fff00000000
0xfffffff00790d018: vm.vm_do_collapse_terminate_failure Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00794fca4
Arg2: 0x7fff00000000
0xfffffff00790d068: vm.vm_should_cow_but_wired Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00794fca8
Arg2: 0x7fff00000000
0xfffffff00790d0b8: vm.vm_create_upl_extra_cow Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00794fcac
Arg2: 0x7fff00000000
0xfffffff00790d108: vm.vm_create_upl_extra_cow_pages Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00794fcb0
Arg2: 0x7fff00000000
0xfffffff00790d158: vm.vm_create_upl_lookup_failure_write Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00794fcb4
Arg2: 0x7fff00000000
0xfffffff00790d1a8: vm.vm_create_upl_lookup_failure_copy Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00794fcb8
Arg2: 0x7fff00000000
0xfffffff00790d1f8: vm.vm_debug_events Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff007964298
Arg2: 0x7fff00000000
0xfffffff00790d250: vm.shared_region_unnest_logging Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00790d248
Arg2: 0x7fff00000000
0xfffffff00790d2a0: kern.secure_kernel Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990138
Arg1: fffffff00790d2f0
Arg2: 0x7fff00000000
0xfffffff00790d3a0: vm.pageout_secluded_burst_count Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007964460
Arg2: 0x7fff00000000
0xfffffff00790d3f0: vm.pageout_secluded_reactivated Description: Secluded pages reactivated
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007964458
Arg2: 0x7fff00000000
0xfffffff00790d440: vm.pageout_freed_from_secluded Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007964450
Arg2: 0x7fff00000000
0xfffffff00790d490: vm.page_secluded_grab_for_iokit_success Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007965cbc
Arg2: 0x7fff00000000
0xfffffff00790d4e0: vm.page_secluded_grab_for_iokit Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007965cb8
Arg2: 0x7fff00000000
0xfffffff00790d530: vm.page_secluded_grab_failure_dirty Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007965cb4
Arg2: 0x7fff00000000
0xfffffff00790d580: vm.page_secluded_grab_failure_state Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007965cb0
Arg2: 0x7fff00000000
0xfffffff00790d5d0: vm.page_secluded_grab_failure_locked Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007965cac
Arg2: 0x7fff00000000
0xfffffff00790d620: vm.page_secluded_grab_success_other Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007965ca8
Arg2: 0x7fff00000000
0xfffffff00790d670: vm.page_secluded_grab_success_free Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007965ca4
Arg2: 0x7fff00000000
0xfffffff00790d6c0: vm.page_secluded_eligible Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007965ca0
Arg2: 0x7fff00000000
0xfffffff00790d710: vm.page_secluded_count_inuse Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007965d84
Arg2: 0x7fff00000000
0xfffffff00790d760: vm.page_secluded_count_free Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007965d80
Arg2: 0x7fff00000000
0xfffffff00790d7b0: vm.page_secluded_count Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007965d70
Arg2: 0x7fff00000000
0xfffffff00790d800: vm.page_secluded_target Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007964864
Arg2: 0x7fff00000000
0xfffffff00790d850: vm.num_tasks_can_use_secluded_mem Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff00791f950
Arg2: 0x7fff00000000
0xfffffff00790d8a0: vm.prefault_nb_bailout Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f848
Arg2: 0x7fff00000000
0xfffffff00790d8f0: vm.prefault_nb_pages Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff00794f840
Arg2: 0x7fff00000000
0xfffffff00790d940: vm.pageout_cleaned_nolock Description: Cleaned pages no-lock (deactivated)
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff00796420c
Arg2: 0x7fff00000000
0xfffffff00790d990: vm.pageout_cleaned_busy Description: Cleaned pages busy (deactivated)
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007964208
Arg2: 0x7fff00000000
0xfffffff00790d9e0: vm.pageout_cleaned_commit_reactivated Description: Cleaned pages commit reactivated
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007964204
Arg2: 0x7fff00000000
0xfffffff00790da30: vm.pageout_cleaned_fault_reactivated Description: Cleaned pages fault reactivated
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007964200
Arg2: 0x7fff00000000
0xfffffff00790da80: vm.pageout_cleaned_volatile_reactivated Description: Cleaned pages volatile reactivated
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff0079641fc
Arg2: 0x7fff00000000
0xfffffff00790dad0: vm.pageout_cleaned_reference_reactivated Description: Cleaned pages reference reactivated
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff0079641f8
Arg2: 0x7fff00000000
0xfffffff00790db20: vm.pageout_cleaned_reactivated Description: Cleaned pages reactivated
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff0079641f4
Arg2: 0x7fff00000000
0xfffffff00790db70: vm.pageout_cleaned Description: Cleaned pages reclaimed
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff0079641f0
Arg2: 0x7fff00000000
0xfffffff00790dbc0: vm.pageout_enqueued_cleaned_from_inactive_dirty Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff0079641ec
Arg2: 0x7fff00000000
0xfffffff00790dc10: vm.pageout_enqueued_cleaned_from_inactive_clean Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff0079641e8
Arg2: 0x7fff00000000
0xfffffff00790dc60: vm.pageout_enqueued_cleaned Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007964850
Arg2: 0x7fff00000000
0xfffffff00790dcb0: vm.pageout_freed_from_cleaned Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff0079641dc
Arg2: 0x7fff00000000
0xfffffff00790dd00: vm.pageout_freed_from_speculative Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff0079641e0
Arg2: 0x7fff00000000
0xfffffff00790dd50: vm.pageout_freed_from_inactive_clean Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff0079641e4
Arg2: 0x7fff00000000
0xfffffff00790dda0: vm.pageout_inactive_used Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff0079641cc
Arg2: 0x7fff00000000
0xfffffff00790ddf0: vm.pageout_speculative_clean Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff0079641d8
Arg2: 0x7fff00000000
0xfffffff00790de40: vm.pageout_inactive_clean Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff0079641d4
Arg2: 0x7fff00000000
0xfffffff00790de90: vm.pageout_inactive_dirty_external Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007964214
Arg2: 0x7fff00000000
0xfffffff00790dee0: vm.pageout_inactive_dirty_internal Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007964210
Arg2: 0x7fff00000000
0xfffffff00790df30: vm.page_pageable_external_count Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007964844
Arg2: 0x7fff00000000
0xfffffff00790df80: vm.page_pageable_internal_count Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007964848
Arg2: 0x7fff00000000
0xfffffff00790dfd0: vm.page_cleaned_count Description: Cleaned queue size
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff00796484c
Arg2: 0x7fff00000000
0xfffffff00790e020: vm.page_speculative_count Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007965d7c
Arg2: 0x7fff00000000
0xfffffff00790e070: vm.page_free_count Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990140
Arg1: fffffff007965c80
Arg2: 0x7fff00000000
0xfffffff00790e0c0: vm.free_shared Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007965d58
Arg2: 0x7fff00000000
0xfffffff00790e110: vm.reusable_shared Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007965d50
Arg2: 0x7fff00000000
0xfffffff00790e160: vm.reusable_nonwritable Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007965d48
Arg2: 0x7fff00000000
0xfffffff00790e1b0: vm.reusable_reclaimed Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007965d40
Arg2: 0x7fff00000000
0xfffffff00790e200: vm.can_reuse_failure Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007965d38
Arg2: 0x7fff00000000
0xfffffff00790e250: vm.can_reuse_success Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007965d30
Arg2: 0x7fff00000000
0xfffffff00790e2a0: vm.partial_reuse_calls Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007965d00
Arg2: 0x7fff00000000
0xfffffff00790e2f0: vm.all_reuse_calls Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007965cf8
Arg2: 0x7fff00000000
0xfffffff00790e340: vm.reuse_failure Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007965d28
Arg2: 0x7fff00000000
0xfffffff00790e390: vm.reuse_success Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007965d20
Arg2: 0x7fff00000000
0xfffffff00790e3e0: vm.partial_reusable_calls Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007965cf0
Arg2: 0x7fff00000000
0xfffffff00790e430: vm.all_reusable_calls Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007965ce8
Arg2: 0x7fff00000000
0xfffffff00790e480: vm.reusable_pages_shared Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007965d18
Arg2: 0x7fff00000000
0xfffffff00790e4d0: vm.reusable_failure Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007965d10
Arg2: 0x7fff00000000
0xfffffff00790e520: vm.reusable_success Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990140
Arg1: fffffff007965d08
Arg2: 0x7fff00000000
0xfffffff00790e570: vm.page_reusable_count Description: Reusable page count
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff007965cc0
Arg2: 0x7fff00000000
0xfffffff00790e5c0: vm.madvise_free_debug Description: zero-fill on madvise(MADV_FREE*)
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff00794fc88
Arg2: 0x7fff00000000
0xfffffff00790e610: vm.pageout_purged_objects Description: System purged object count
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff007964224
Arg2: 0x7fff00000000
0xfffffff00790e660: vm.page_purgeable_wired_count Description: Wired purgeable page count
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff007964828
Arg2: 0x7fff00000000
0xfffffff00790e6b0: vm.page_purgeable_count Description: Purgeable page count
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff007964824
Arg2: 0x7fff00000000
0xfffffff00790e700: vm.page_free_wanted Description: 
Handler: 0xfffffff0077f0e38
Format: I
Parent: 0xfffffff007990140
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff00790e750: vm.memory_pressure Description: Memory pressure indicator
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0079643fc
Arg2: 0x7fff00000000
0xfffffff00790e7a0: vm.vm_page_free_target Description: Pageout daemon free target
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff007964854
Arg2: 0x7fff00000000
0xfffffff00790e7f0: vm.pagesize Description: vm page size
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff007990050
Arg2: 0x7fff00000000
0xfffffff00790e840: vm.shared_region_persistence Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0079665d0
Arg2: 0x7fff00000000
0xfffffff00790e890: vm.shared_region_version Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f04b8
Arg2: 0x7fff00000000
0xfffffff00790e8e0: vm.shared_region_trace_level Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990140
Arg1: fffffff0078f04bc
Arg2: 0x7fff00000000
0xfffffff00790d348: tfp.policy Description: policy
Handler: 0xfffffff0077f0d7c
Format: I
Parent: 0xfffffff00798e2d0
Arg1: fffffff00790d398
Arg2: 0x7fff00000004
0xfffffff00790e938: kern.next_ecc_event Description: 
Handler: 0xfffffff0077f3ff8
Format: -
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff00790eaa8: kperf.debug_level Description: debug level
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff00798e318
Arg1: fffffff00798e310
Arg2: 0x7fff00000000
0xfffffff00790eaf8: kperf.lightweight_pet Description: Status of lightweight PET mode
Handler: 0xfffffff0077f480c
Format: I
Parent: 0xfffffff00798e318
Arg1: 14
Arg2: 0x7fff00000004
0xfffffff00790eb48: kperf.pet_idle_rate Description: Rate at which unscheduled threads are forced to be sampled in PET mode
Handler: 0xfffffff0077f480c
Format: I
Parent: 0xfffffff00798e318
Arg1: d
Arg2: 0x7fff00000004
0xfffffff00790eb98: kperf.kdbg_cswitch Description: Generate context switch info
Handler: 0xfffffff0077f480c
Format: I
Parent: 0xfffffff00798e318
Arg1: f
Arg2: 0x7fff00000004
0xfffffff00790ebe8: kperf.blessed_preempt Description: Blessed preemption
Handler: 0xfffffff0077f480c
Format: I
Parent: 0xfffffff00798e318
Arg1: e
Arg2: 0x7fff00000004
0xfffffff00790ec38: kperf.blessed_pid Description: Blessed pid
Handler: 0xfffffff0077f591c
Format: I
Parent: 0xfffffff00798e318
Arg1: 8
Arg2: 0x7fff00000004
0xfffffff00790ec88: kperf.reset Description: Reset kperf
Handler: 0xfffffff0077f480c
Format: -
Parent: 0xfffffff00798e318
Arg1: 10
Arg2: 0x7fff00000000
0xfffffff00790ecd8: kperf.sampling Description: Sampling running
Handler: 0xfffffff0077f480c
Format: I
Parent: 0xfffffff00798e318
Arg1: 1
Arg2: 0x7fff00000004
0xfffffff00790ed28: kdebug.filter Description: The filter that determines which kdebug events trigger a sample
Handler: 0xfffffff0077f480c
Format: P
Parent: 0xfffffff00798e328
Arg1: 16
Arg2: 0x7fff00000004
0xfffffff00790ed78: kdebug.action Description: ID of action to trigger on kdebug events
Handler: 0xfffffff0077f480c
Format: I
Parent: 0xfffffff00798e328
Arg1: 15
Arg2: 0x7fff00000004
0xfffffff00790ee18: timer.pet_timer Description: Which timer ID does PET
Handler: 0xfffffff0077f480c
Format: I
Parent: 0xfffffff00798e330
Arg1: 6
Arg2: 0x7fff00000004
0xfffffff00790ee68: timer.action Description: Timer number and actionid
Handler: 0xfffffff0077f480c
Format: UQ
Parent: 0xfffffff00798e330
Arg1: 7
Arg2: 0x7fff00000010
0xfffffff00790eeb8: timer.period Description: Timer number and period
Handler: 0xfffffff0077f480c
Format: UQ
Parent: 0xfffffff00798e330
Arg1: 5
Arg2: 0x7fff00000010
0xfffffff00790ef08: timer.count Description: Number of time triggers
Handler: 0xfffffff0077f480c
Format: I
Parent: 0xfffffff00798e330
Arg1: 4
Arg2: 0x7fff00000004
0xfffffff00790efa8: action.kcallstack_depth Description: Maximum number of frames to include in kernel callstacks
Handler: 0xfffffff0077f480c
Format: I
Parent: 0xfffffff00798e320
Arg1: 13
Arg2: 0x7fff00000004
0xfffffff00790eff8: action.ucallstack_depth Description: Maximum number of frames to include in user callstacks
Handler: 0xfffffff0077f480c
Format: I
Parent: 0xfffffff00798e320
Arg1: 12
Arg2: 0x7fff00000004
0xfffffff00790f048: action.filter_by_pid Description: Apply a pid filter to the action
Handler: 0xfffffff0077f480c
Format: UQ
Parent: 0xfffffff00798e320
Arg1: b
Arg2: 0x7fff00000018
0xfffffff00790f098: action.filter_by_task Description: Apply a task filter to the action
Handler: 0xfffffff0077f480c
Format: UQ
Parent: 0xfffffff00798e320
Arg1: a
Arg2: 0x7fff00000018
0xfffffff00790f0e8: action.userdata Description: User data to attribute to action
Handler: 0xfffffff0077f480c
Format: UQ
Parent: 0xfffffff00798e320
Arg1: 9
Arg2: 0x7fff00000018
0xfffffff00790f138: action.samplers Description: What to sample when a trigger fires an action
Handler: 0xfffffff0077f480c
Format: UQ
Parent: 0xfffffff00798e320
Arg1: 3
Arg2: 0x7fff00000018
0xfffffff00790ea58: action.count Description: Number of actions
Handler: 0xfffffff0077f480c
Format: I
Parent: 0xfffffff00798e320
Arg1: 2
Arg2: 0x7fff00000004
0xfffffff00790f230: kpc.force_all_ctrs Description: Force kperf to allow config of all counters
Handler: 0xfffffff0077f5b14
Format: I
Parent: 0xfffffff00798e338
Arg1: c
Arg2: 0x7fff00000004
0xfffffff00790f280: kpc.actionid Description: Set counter actionids
Handler: 0xfffffff0077f5b14
Format: QU
Parent: 0xfffffff00798e338
Arg1: b
Arg2: 0x7fff00000004
0xfffffff00790f2d0: kpc.period Description: Set counter periods
Handler: 0xfffffff0077f5b14
Format: QU
Parent: 0xfffffff00798e338
Arg1: a
Arg2: 0x7fff00000008
0xfffffff00790f320: kpc.config Description: Set counter configs
Handler: 0xfffffff0077f5b14
Format: QU
Parent: 0xfffffff00798e338
Arg1: 9
Arg2: 0x7fff00000008
0xfffffff00790f370: kpc.shadow_counters Description: Current shadow counters
Handler: 0xfffffff0077f5b14
Format: QU
Parent: 0xfffffff00798e338
Arg1: 8
Arg2: 0x7fff00000008
0xfffffff00790f3c0: kpc.counters Description: Current counters
Handler: 0xfffffff0077f5b14
Format: QU
Parent: 0xfffffff00798e338
Arg1: 7
Arg2: 0x7fff00000008
0xfffffff00790f410: kpc.thread_counters Description: Current thread counters
Handler: 0xfffffff0077f5b14
Format: QU
Parent: 0xfffffff00798e338
Arg1: 6
Arg2: 0x7fff00000008
0xfffffff00790f460: kpc.sw_inc Description: Software increment
Handler: 0xfffffff0077f5b14
Format: S
Parent: 0xfffffff00798e338
Arg1: e
Arg2: 0x7fff00000004
0xfffffff00790f4b0: kpc.counter_count Description: Counter count
Handler: 0xfffffff0077f5b14
Format: S
Parent: 0xfffffff00798e338
Arg1: 5
Arg2: 0x7fff00000004
0xfffffff00790f500: kpc.config_count Description: Config count
Handler: 0xfffffff0077f5b14
Format: S
Parent: 0xfffffff00798e338
Arg1: 4
Arg2: 0x7fff00000004
0xfffffff00790f550: kpc.pmu_version Description: PMU version for hardware
Handler: 0xfffffff0077f5b14
Format: I
Parent: 0xfffffff00798e338
Arg1: f
Arg2: 0x7fff00000004
0xfffffff00790f5a0: kpc.thread_counting Description: Thread accumulation
Handler: 0xfffffff0077f5b14
Format: I
Parent: 0xfffffff00798e338
Arg1: 3
Arg2: 0x7fff00000004
0xfffffff00790f5f0: kpc.counting Description: PMCs counting
Handler: 0xfffffff0077f5b14
Format: I
Parent: 0xfffffff00798e338
Arg1: 2
Arg2: 0x7fff00000004
0xfffffff00790f1d8: kpc.classes Description: Available classes
Handler: 0xfffffff0077f5b14
Format: I
Parent: 0xfffffff00798e338
Arg1: 1
Arg2: 0x7fff00000004
0xfffffff00790f698: skywalk.features Description: Skywalk features
Handler: 0xfffffff00778ea2c
Format: -
Parent: 0xfffffff00798e3b0
Arg1: fffffff00790f6e8
Arg2: 0x7fff00000008
0xfffffff007910080: skywalk.nexus_channel_list Description: 
Handler: 0xfffffff0077ffd64
Format: S,nexus_channel_entry_t
Parent: 0xfffffff00798e3b0
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff00790fff0: skywalk.nexus_provider_list Description: 
Handler: 0xfffffff0077ffbf8
Format: S,nexus_provider_info_t
Parent: 0xfffffff00798e3b0
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007911f38: machdep.alignmenttrap Description: trap on alignment faults (number of alignment faults per trap)
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990160
Arg1: fffffff0079689d4
Arg2: 0x7fff00000000
0xfffffff007911f88: machdep.swptrap Description: trap on SWP instructions (number of SWP instructions per trap)
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990160
Arg1: fffffff0079689e0
Arg2: 0x7fff00000000
0xfffffff007911fd8: machdep.wake_abstime Description: Absolute Time at the last wakeup
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990160
Arg1: fffffff007967d40
Arg2: 0x7fff00000000
0xfffffff007912110: debug.kextlog Description: kernel kext logging
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990158
Arg1: fffffff007912160
Arg2: 0x7fff00000000
0xfffffff007912220: debug.swd_kext_name Description: 
Handler: 0xfffffff00778e994
Format: A
Parent: 0xfffffff007990158
Arg1: fffffff00798ef59
Arg2: 0x7fff00000080
0xfffffff007912270: debug.swd_delay_type Description: 
Handler: 0xfffffff00778e994
Format: A
Parent: 0xfffffff007990158
Arg1: fffffff00798efd9
Arg2: 0x7fff00000010
0xfffffff0079122c0: debug.swd_delay_duration Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990158
Arg1: fffffff00798efec
Arg2: 0x7fff00000000
0xfffffff007912310: kern.pmtimeout Description: Power Management Timeout
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007990138
Arg1: fffffff00798f018
Arg2: 0x7fff00000000
0xfffffff007912858: debug.iokit Description: boot_arg io
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990158
Arg1: fffffff007990e18
Arg2: 0x7fff00000000
0xfffffff0079128a8: debug.iotrace Description: trace io
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990158
Arg1: fffffff00798f3c0
Arg2: 0x7fff00000000
0xfffffff0079128f8: kern.iokittest Description: 
Handler: 0xfffffff0078aaca0
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007912ae0: kern.sleeptime Description: 
Handler: 0xfffffff0078bc3f4
Format: S,timeval
Parent: 0xfffffff007990138
Arg1: fffffff00798f4d0
Arg2: 0x7fff00000000
0xfffffff007912b30: kern.waketime Description: 
Handler: 0xfffffff0078bc3f4
Format: S,timeval
Parent: 0xfffffff007990138
Arg1: fffffff00798f4e0
Arg2: 0x7fff00000000
0xfffffff007912d88: kern.wake_abs_time Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990138
Arg1: fffffff00798f600
Arg2: 0x7fff00000000
0xfffffff007912dd8: kern.sleep_abs_time Description: 
Handler: 0xfffffff00778e8d0
Format: Q
Parent: 0xfffffff007990138
Arg1: fffffff00798f5f8
Arg2: 0x7fff00000000
0xfffffff007912b80: kern.willshutdown Description: 
Handler: 0xfffffff0078bc314
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007912c20: kern.consoleoptions Description: 
Handler: 0xfffffff0078bc1c0
Format: I
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007912c70: kern.progressoptions Description: 
Handler: 0xfffffff0078bc15c
Format: S,vc_progress_user_options
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007912e28: kern.wakereason Description: wakereason
Handler: 0xfffffff0078bebfc
Format: A
Parent: 0xfffffff007990138
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007912bd0: hw.targettype Description: targettype
Handler: 0xfffffff0078bc210
Format: A
Parent: 0xfffffff007989c40
Arg1: 0
Arg2: 0x7fff00000000
0xfffffff007912e78: debug.darkwake Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990158
Arg1: fffffff007912958
Arg2: 0x7fff00000000
0xfffffff007912ec8: debug.noidle Description: 
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007990158
Arg1: fffffff00798f60c
Arg2: 0x7fff00000000
0xfffffff0079133a8: mac.max_slots Description: 
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007991110
Arg1: fffffff0079133f8
Arg2: 0x7fff00000000
0xfffffff007913400: mac.labelvnodes Description: Label all vnodes
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007991110
Arg1: fffffff00798f9fc
Arg2: 0x7fff00000000
0xfffffff007913450: mac.mmap_revocation Description: Revoke mmap access to files on subject relabel
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007991110
Arg1: fffffff00798fa00
Arg2: 0x7fff00000000
0xfffffff0079134a0: mac.mmap_revocation_via_cow Description: Revoke mmap access to files via copy-on-write semantics, or by removing all write access
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007991110
Arg1: fffffff00798fa04
Arg2: 0x7fff00000000
0xfffffff0079134f8: mac.device_enforce Description: Enforce MAC policy on device operations
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007991110
Arg1: fffffff0079134f0
Arg2: 0x7fff00000000
0xfffffff007913550: mac.pipe_enforce Description: Enforce MAC policy on pipe operations
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007991110
Arg1: fffffff007913548
Arg2: 0x7fff00000000
0xfffffff0079135a8: mac.posixsem_enforce Description: Enforce MAC policy on POSIX semaphores
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007991110
Arg1: fffffff0079135a0
Arg2: 0x7fff00000000
0xfffffff007913600: mac.posixshm_enforce Description: Enforce MAC policy on Posix Shared Memory
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007991110
Arg1: fffffff0079135f8
Arg2: 0x7fff00000000
0xfffffff007913658: mac.proc_enforce Description: Enforce MAC policy on process operations
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007991110
Arg1: fffffff007913650
Arg2: 0x7fff00000000
0xfffffff0079136b0: mac.socket_enforce Description: Enforce MAC policy on socket operations
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007991110
Arg1: fffffff0079136a8
Arg2: 0x7fff00000000
0xfffffff007913708: mac.system_enforce Description: Enforce MAC policy on system-wide interfaces
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007991110
Arg1: fffffff007913700
Arg2: 0x7fff00000000
0xfffffff007913760: mac.sysvmsg_enforce Description: Enforce MAC policy on System V IPC message queues
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007991110
Arg1: fffffff007913758
Arg2: 0x7fff00000000
0xfffffff0079137b8: mac.sysvsem_enforce Description: Enforce MAC policy on System V IPC semaphores
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007991110
Arg1: fffffff0079137b0
Arg2: 0x7fff00000000
0xfffffff007913810: mac.sysvshm_enforce Description: Enforce MAC policy on System V Shared Memory
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007991110
Arg1: fffffff007913808
Arg2: 0x7fff00000000
0xfffffff007913868: mac.vm_enforce Description: Enforce MAC policy on VM operations
Handler: 0xfffffff00778e884
Format: I
Parent: 0xfffffff007991110
Arg1: fffffff007913860
Arg2: 0x7fff00000000
0xfffffff0079138c0: mac.vnode_enforce Description: Enforce MAC policy on vnode operations
Handler: 0xfffffff00778e884
Format: IU
Parent: 0xfffffff007991110
Arg1: fffffff0079138b8
Arg2: 0x7fff00000000
```
