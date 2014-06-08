map-file-parser
===============

Parser for MAP files generated by Visual Studio (Tested on VS2008 through VS2012)

Example output below

```
Module Name [metamodule]
EntryPoint [0x0]
Timestamp [1401728088]
Time [Mon Jun 02 11:54:48 2014]
LoadAddress [0x10000000]
Section [.text] = [0x0][0x2CA][CODE]
Section [.idata$5] = [0x0][0x18][DATA]
Section [.CRT$XCA] = [0x18][0x4][DATA]
Section [.CRT$XCZ] = [0x1C][0x4][DATA]
Section [.CRT$XIA] = [0x20][0x4][DATA]
Section [.CRT$XIZ] = [0x24][0x4][DATA]
Section [.CRT$XPA] = [0x28][0x4][DATA]
Section [.CRT$XPZ] = [0x2C][0x4][DATA]
Section [.CRT$XTA] = [0x30][0x4][DATA]
Section [.CRT$XTZ] = [0x34][0x4][DATA]
Section [.rdata] = [0x40][0x9C][DATA]
Section [.idata$2] = [0xDC][0x28][DATA]
Section [.idata$3] = [0x104][0x14][DATA]
Section [.idata$4] = [0x118][0x18][DATA]
Section [.idata$6] = [0x130][0x54][DATA]
Section [.edata] = [0x184][0x0][DATA]
Section [.rdata$debug] = [0x184][0x70][DATA]
Section [.data] = [0x0][0x4][DATA]
Section [.bss] = [0x4][0x4][DATA]
Data [___safe_se_handler_count] = [0x0][<absolute>]
Data [___safe_se_handler_table] = [0x0][<absolute>]
Function [__purecall] = [0x0][clib.obj]
Function [?print@@YAXPAD@Z] = [0x7][dllmain.obj]
Function [?run_tests@@YAXXZ] = [0x55][dllmain.obj]
Function [??0test_vtable_printf@@QAE@XZ] = [0xEF][dllmain.obj]
Function [?one@test_vtable_printf@@UAEXXZ] = [0x10C][dllmain.obj]
Function [?two@test_vtable_printf@@UAEXXZ] = [0x120][dllmain.obj]
Function [??0test_vtable_msgbox@@QAE@XZ] = [0x134][dllmain.obj]
Function [?one@test_vtable_msgbox@@UAEXXZ] = [0x151][dllmain.obj]
Function [?two@test_vtable_msgbox@@UAEXXZ] = [0x16E][dllmain.obj]
Function [??0test_vtable@@QAE@XZ] = [0x18B][dllmain.obj]
Function [_DllMain@12] = [0x1A0][dllmain.obj]
Function [?_initterm_e@@YAHPAP6AHXZ0@Z] = [0x1EA][dllmain.obj]
Function [?_initterm@@YAXPAP6AHXZ0@Z] = [0x21A][dllmain.obj]
Function [__DllMainCRTStartup@12] = [0x23F][dllmain.obj]
Function [??2@YAPAXI@Z] = [0x2B3][dllmain.obj]
Data [__imp__GetStdHandle@4] = [0x0][kernel32:KERNEL32.dll]
Data [__imp__VirtualAlloc@16] = [0x4][kernel32:KERNEL32.dll]
Data [__imp__WriteFile@20] = [0x8][kernel32:KERNEL32.dll]
Data [\177KERNEL32_NULL_THUNK_DATA] = [0xC][kernel32:KERNEL32.dll]
Data [__imp__MessageBoxA@16] = [0x10][user32:USER32.dll]
Data [\177USER32_NULL_THUNK_DATA] = [0x14][user32:USER32.dll]
Data [?__xc_a@@3PAP6AXXZA] = [0x18][dllmain.obj]
Data [?__xc_z@@3PAP6AXXZA] = [0x1C][dllmain.obj]
Data [?__xi_a@@3PAP6AXXZA] = [0x20][dllmain.obj]
Data [?__xi_z@@3PAP6AXXZA] = [0x24][dllmain.obj]
Data [?__xp_a@@3PAP6AXXZA] = [0x28][dllmain.obj]
Data [?__xp_z@@3PAP6AXXZA] = [0x2C][dllmain.obj]
Data [?__xt_a@@3PAP6AXXZA] = [0x30][dllmain.obj]
Data [?__xt_z@@3PAP6AXXZA] = [0x34][dllmain.obj]
Data [??_7test_vtable_printf@@6B@] = [0xA8][dllmain.obj]
Data [??_C@_04ENLFIJAP@one?6?$AA@] = [0xB0][dllmain.obj]
Data [??_C@_04HKADLCFP@two?6?$AA@] = [0xB8][dllmain.obj]
Data [??_7test_vtable_msgbox@@6B@] = [0xC0][dllmain.obj]
Data [??_C@_03OHDNLOHO@one?$AA@] = [0xC8][dllmain.obj]
Data [??_C@_03IJDNBOJF@two?$AA@] = [0xCC][dllmain.obj]
Data [??_7test_vtable@@6B@] = [0xD0][dllmain.obj]
Data [__IMPORT_DESCRIPTOR_KERNEL32] = [0xDC][kernel32:KERNEL32.dll]
Data [__IMPORT_DESCRIPTOR_USER32] = [0xF0][user32:USER32.dll]
Data [__NULL_IMPORT_DESCRIPTOR] = [0x104][kernel32:KERNEL32.dll]
Data [__fltused] = [0x0][clib.obj]
Data [?vt@@3PAUtest_vtable@@A] = [0x4][dllmain.obj]
```
