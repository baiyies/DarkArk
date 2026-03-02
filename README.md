# DarkArk
[中文说明][url-docen]

DarkArk is a Windows Anti-Rootkit (ARK) tool, tested successfully on Windows 10 and Windows 11. Currently, the project is in the **early development stage**.

[Download DarkArk](https://github.com/baiyies/DarkArk/releases)

# Disclaimer
This project is intended strictly for personal learning and research purposes; please do not use it for any commercial activities. You must comply with local laws and regulations when using it, and it must not be used for malicious purposes. Meanwhile, the author assumes no responsibility for any BSOD, data loss, or other potential issues caused by using DarkArk.
Unless you have fully read, completely understood, and accepted all terms of this agreement, please do not install or use this tool. Your use of the tool, or your acceptance of this agreement in any other express or implied manner, shall be deemed as you having read and agreed to be bound by this agreement.

# Features
Some implemented features are as follows:
- Process Enumeration, Driver Enumeration, Dispatch Function Query, System Threads, System Callbacks, MiniFilter, SSDT, Shadow SSDT, Driver Traces, System Monitoring, ETW-TI, Anti-screenshot / Anti-anti-screenshot, Handle Elevate, DLL injection, Shellcode injection, EXE/DLL/SYS Block, Directory Protection, Manual Map Driver...

# Screenshots
![](images/1_en.png)
![](images/2_en.png)
![](images/3_en.png)
![](images/4_en.png)
![](images/5_en.png)
![](images/6_en.png)
![](images/7_en.png)
![](images/8_en.png)
![](images/9_en.png)
![](images/10_en.png)
![](images/11_en.png)
![](images/12_en.png)

# Update Log
v0.1
- Initial release

v0.2
- Added English translation, Optimized some details

v0.3
- Added Window Finder
- Added Anti-screenshot / Anti-anti-screenshot
- Added Handle Elevate
- Added ETW-TI Monitoring

v0.4
- Added driver trace cleaning
- Added Enable/Disable/Remove callbacks
- Added Disassembly View
- Fixed known bugs

v1.0
- Major update, updated a large number of basic features, beautified the interface
- Added registry browsing
- Added suspend, resume, and terminate system threads
- Added process DLL injection, Shellcode injection, and DLL unloading
- Added interception of specified EXE/DLL/SYS loading
- Added directory protection
- Added disabling of vulnerable drivers
- Added driver mapping
- Added KDMapper-dumper
- Optimized MiniFilter information display

v1.1
- Fixed 32-bit process module enumeration issue
- Optimized file management performance
- Optimized Inline Hook/IAT Hook detection logic
- Optimized ETW-TI UI interaction
- Added file unlocking
- Added startup item management
- Added DSE Patch
- Added global disable for Notify callbacks
- Added WFP Callout/WFP Filter/Hosts
- Added ETW Hook detection

[url-docen]: README_CN.md
