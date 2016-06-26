---
layout: default
title: Mach Traps
---

The following was generated via output from [jtool](http://www.newosxbook.com/tools/jtool.html):

```
This is a 64-bit kernel from iOS 10.x, or later (3705.0.0.2.3)
mach_trap_table offset in file/memory (for patching purposes): 0x5ca28/fffffff007460a28
Kern invalid should be fffffff0074c3334. Ignoring those
10 _kernelrpc_mach_vm_allocate_trap fffffff0074997a8 -
11 _kernelrpc_vm_allocate_trap fffffff007499a6c -
12 _kernelrpc_mach_vm_deallocate_trap fffffff007499850 -
14 _kernelrpc_mach_vm_protect_trap fffffff007499908 -
15 _kernelrpc_vm_protect_trap fffffff007499974 -
16 _kernelrpc_mach_port_allocate_trap fffffff007499b38 -
17 _kernelrpc_mach_port_destroy_trap fffffff007499bd4 -
18 _kernelrpc_mach_port_deallocate_trap fffffff007499c38 -
19 _kernelrpc_mach_port_mod_refs_trap fffffff007499c9c -
20 _kernelrpc_mach_port_move_member_trap fffffff007499d08 -
21 _kernelrpc_mach_port_insert_right_trap fffffff007499d70 -
22 _kernelrpc_mach_port_insert_member_trap fffffff007499e60 -
23 _kernelrpc_mach_port_extract_member_trap fffffff007499ec8 -
24 __kernelrpc_mach_port_construct_trap fffffff007499f30 -
25 __kernelrpc_mach_port_destruct_trap fffffff007499fdc -
26 mach_reply_port fffffff0074a6184 -
27 thread_self_trap fffffff0074a615c -
28 task_self_trap fffffff0074a6130 -
29 host_self_trap fffffff0074a48c0 -
31 mach_msg_trap fffffff00749b984 -
32 mach_msg_overwrite_trap fffffff00749b59c -
33 semaphore_signal_trap fffffff0074c1df4 -
34 semaphore_signal_all_trap fffffff0074c1ed0 -
35 semaphore_signal_thread_trap fffffff0074c1d34 -
36 semaphore_wait_trap fffffff0074c21cc -
37 semaphore_wait_signal_trap fffffff0074c24a0 -
38 semaphore_timedwait_trap fffffff0074c2364 -
39 semaphore_timedwait_signal_trap fffffff0074c2550 -
41 __kernelrpc_mach_port_guard_trap fffffff00749a048 -
42 __kernelrpc_mach_port_unguard_trap fffffff00749a0b4 -
43 map_fd fffffff007499694 -
44 task_name_for_pid fffffff0077f1c08 -
45 task_for_pid fffffff0077f15dc -
46 pid_for_task fffffff0077f14b8 -
48 macx_swapon fffffff0077f39cc -
49 macx_swapoff fffffff0077f39d4 -
51 macx_triggers fffffff0077f3930 -
52 macx_backing_store_suspend fffffff0077f3928 -
53 macx_backing_store_recovery fffffff0077f3920 -
58 pfz_exit fffffff0074c26e0 -
59 swtch_pri fffffff0074c2814 -
60 swtch fffffff0074c26e8 -
61 thread_switch fffffff0074c2ac8 -
62 clock_sleep_trap fffffff0074a0880 -
89 mach_timebase_info_trap fffffff00749f638 -
90 mach_wait_until_trap fffffff00749ff50 -
91 mk_timer_create_trap fffffff0074aa1e8 -
92 mk_timer_destroy_trap fffffff0074aa43c -
93 mk_timer_arm_trap fffffff0074aa4bc -
94 mk_timer_cancel_trap fffffff0074aa5d8 -
100 iokit_user_client_trap fffffff0078a80a4 -
host_priv_subsystem is @0xfffffff007461b20!
0: __Xhost_get_boot_info: fffffff0074dcfd0 (400)
1: __Xhost_reboot: fffffff0074dd17c (401)
2: __Xhost_priv_statistics: fffffff0074dd2d0 (402)
3: __Xhost_default_memory_manager: fffffff0074dd46c (403)
4: __Xvm_wire: fffffff0074dd6f4 (404)
5: __Xthread_wire: fffffff0074dd968 (405)
6: __Xvm_allocate_cpm: fffffff0074ddb90 (406)
7: __Xhost_processors: fffffff0074ddd34 (407)
8: __Xhost_get_clock_control: fffffff0074ddf80 (408)
9: __Xkmod_create: fffffff0074de120 (409)
10: __Xkmod_destroy: fffffff0074de234 (410)
11: __Xkmod_control: fffffff0074de3b8 (411)
12: __Xhost_get_special_port: fffffff0074de514 (412)
13: __Xhost_set_special_port: fffffff0074de698 (413)
14: __Xhost_set_exception_ports: fffffff0074de820 (414)
15: __Xhost_get_exception_ports: fffffff0074de9ac (415)
16: __Xhost_swap_exception_ports: fffffff0074ded1c (416)
17: __Xmach_vm_wire: fffffff0074df3d8 (418)
18: __Xhost_processor_sets: fffffff0074df5b4 (419)
19: __Xhost_processor_set_priv: fffffff0074df794 (420)
20: __Xset_dp_control_port: fffffff0074df9b8 (421)
21: __Xget_dp_control_port: fffffff0074dfb68 (422)
22: __Xhost_set_UNDServer: fffffff0074dfd20 (423)
23: __Xhost_get_UNDServer: fffffff0074dfea8 (424)
24: __Xkext_request: fffffff0074e0020 (425)
host_security_subsystem is @0xfffffff007461f50!
0: __Xhost_security_create_task_token: fffffff0074e1e2c (600)
1: __Xhost_security_set_task_token: fffffff0074e2018 (601)
mach_port_subsystem is @0xfffffff007462660!
0: __Xmach_port_names: fffffff0074e5be0 (3200)
1: __Xmach_port_type: fffffff0074e5de4 (3201)
2: __Xmach_port_rename: fffffff0074e6010 (3202)
3: __Xmach_port_allocate_name: fffffff0074e61ac (3203)
4: __Xmach_port_allocate: fffffff0074e639c (3204)
5: __Xmach_port_destroy: fffffff0074e6574 (3205)
6: __Xmach_port_deallocate: fffffff0074e6720 (3206)
7: __Xmach_port_get_refs: fffffff0074e68cc (3207)
8: __Xmach_port_mod_refs: fffffff0074e6b64 (3208)
9: __Xmach_port_peek: fffffff0074e6d14 (3209)
10: __Xmach_port_set_mscount: fffffff0074e7114 (3210)
11: __Xmach_port_get_set_status: fffffff0074e731c (3211)
12: __Xmach_port_move_member: fffffff0074e7950 (3212)
13: __Xmach_port_request_notification: fffffff0074e7afc (3213)
14: __Xmach_port_insert_right: fffffff0074e7e88 (3214)
15: __Xmach_port_extract_right: fffffff0074e80a4 (3215)
16: __Xmach_port_set_seqno: fffffff0074e8308 (3216)
17: __Xmach_port_get_attributes: fffffff0074e8544 (3217)
18: __Xmach_port_set_attributes: fffffff0074e88f0 (3218)
19: __Xmach_port_allocate_qos: fffffff0074e8acc (3219)
20: __Xmach_port_allocate_full: fffffff0074e8cb8 (3220)
21: __Xtask_set_port_space: fffffff0074e8ecc (3221)
22: __Xmach_port_get_srights: fffffff0074e90c0 (3222)
23: __Xmach_port_space_info: fffffff0074e92c4 (3223)
24: __Xmach_port_dnrequest_info: fffffff0074e9808 (3224)
25: __Xmach_port_kernel_object: fffffff0074e9ad4 (3225)
26: __Xmach_port_insert_member: fffffff0074e9cb0 (3226)
27: __Xmach_port_extract_member: fffffff0074e9e5c (3227)
28: __Xmach_port_get_context: fffffff0074ea008 (3228)
29: __Xmach_port_set_context: fffffff0074ea230 (3229)
30: __Xmach_port_kobject: fffffff0074ea4c0 (3230)
31: __Xmach_port_construct: fffffff0074ea684 (3231)
32: __Xmach_port_destruct: fffffff0074ea884 (3232)
33: __Xmach_port_guard: fffffff0074eaa34 (3233)
34: __Xmach_port_unguard: fffffff0074eabe8 (3234)
35: __Xmach_port_space_basic_info: fffffff0074ead98 (3235)
mach_vm_subsystem is @0xfffffff007462c20!
0: __Xmach_vm_allocate: fffffff0074eafec (4800)
1: __Xmach_vm_deallocate: fffffff0074eb120 (4801)
2: __Xmach_vm_protect: fffffff0074eb28c (4802)
3: __Xmach_vm_inherit: fffffff0074eb3a0 (4803)
4: __Xmach_vm_read: fffffff0074eb4b4 (4804)
5: __Xmach_vm_read_list: fffffff0074eb650 (4805)
6: __Xmach_vm_write: fffffff0074eb78c (4806)
7: __Xmach_vm_copy: fffffff0074eb8f0 (4807)
8: __Xmach_vm_read_overwrite: fffffff0074eba04 (4808)
9: __Xmach_vm_msync: fffffff0074ebb2c (4809)
10: __Xmach_vm_behavior_set: fffffff0074ebc54 (4810)
11: __Xmach_vm_map: fffffff0074ebd68 (4811)
12: __Xmach_vm_machine_attribute: fffffff0074ebf4c (4812)
13: __Xmach_vm_remap: fffffff0074ec0d0 (4813)
14: __Xmach_vm_page_query: fffffff0074ec2a8 (4814)
15: __Xmach_vm_region_recurse: fffffff0074ec434 (4815)
16: __Xmach_vm_region: fffffff0074ec5d4 (4816)
17: __X_mach_make_memory_entry: fffffff0074ec798 (4817)
18: __Xmach_vm_purgable_control: fffffff0074ec94c (4818)
19: __Xmach_vm_page_info: fffffff0074ecaac (4819)
processor_subsystem is @0xfffffff0074630b8!
0: __Xprocessor_start: fffffff0074f1858 (3000)
1: __Xprocessor_exit: fffffff0074f19a8 (3001)
2: __Xprocessor_info: fffffff0074f1af8 (3002)
3: __Xprocessor_control: fffffff0074f1cc0 (3003)
4: __Xprocessor_assign: fffffff0074f1e30 (3004)
5: __Xprocessor_get_assignment: fffffff0074f1f44 (3005)
processor_set_subsystem is @0xfffffff0074631c8!
0: __Xprocessor_set_statistics: fffffff0074f2108 (4000)
1: __Xprocessor_set_destroy: fffffff0074f22e0 (4001)
2: __Xprocessor_set_max_priority: fffffff0074f23f0 (4002)
3: __Xprocessor_set_policy_enable: fffffff0074f2500 (4003)
4: __Xprocessor_set_policy_disable: fffffff0074f2610 (4004)
5: __Xprocessor_set_tasks: fffffff0074f2720 (4005)
6: __Xprocessor_set_threads: fffffff0074f2ad4 (4006)
7: __Xprocessor_set_policy_control: fffffff0074f2b9c (4007)
8: __Xprocessor_set_stack_usage: fffffff0074f2cd4 (4008)
9: __Xprocessor_set_info: fffffff0074f2fbc (4009)
thread_act_subsystem is @0xfffffff007463b90!
0: __Xthread_terminate: fffffff0074fa508 (3600)
1: __Xact_get_state: fffffff0074fa670 (3601)
2: __Xact_set_state: fffffff0074fa828 (3602)
3: __Xthread_get_state: fffffff0074fa9d8 (3603)
4: __Xthread_set_state: fffffff0074fab80 (3604)
5: __Xthread_suspend: fffffff0074fad1c (3605)
6: __Xthread_resume: fffffff0074faf40 (3606)
7: __Xthread_abort: fffffff0074fb0a8 (3607)
8: __Xthread_abort_safely: fffffff0074fb210 (3608)
9: __Xthread_depress_abort: fffffff0074fb378 (3609)
10: __Xthread_get_special_port: fffffff0074fb510 (3610)
11: __Xthread_set_special_port: fffffff0074fb730 (3611)
12: __Xthread_info: fffffff0074fb92c (3612)
13: __Xthread_set_exception_ports: fffffff0074fbb20 (3613)
14: __Xthread_get_exception_ports: fffffff0074fc050 (3614)
15: __Xthread_swap_exception_ports: fffffff0074fc580 (3615)
16: __Xthread_policy: fffffff0074fccf0 (3616)
17: __Xthread_policy_set: fffffff0074fd058 (3617)
18: __Xthread_policy_get: fffffff0074fd1f0 (3618)
19: __Xthread_sample: 0 (3619)
20: __Xetap_trace_thread: 0 (3620)
21: __Xthread_assign: fffffff0074fd3ac (3621)
22: __Xthread_assign_default: fffffff0074fd590 (3622)
23: __Xthread_get_assignment: fffffff0074fd6f4 (3623)
24: __Xthread_set_policy: fffffff0074fd884 (3624)
25: __Xthread_get_mach_voucher: fffffff0074fdbb0 (3625)
26: __Xthread_set_mach_voucher: fffffff0074fde64 (3626)
27: __Xthread_swap_mach_voucher: fffffff0074fe0a0 (3627)
```
