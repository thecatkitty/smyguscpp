# SmygusCPP
Automate your CMake based workflow on Windows NT running inside of DingusPPC.

Requirements:
- Microsoft Windows host system
- Microsoft Visual C++ 4.0 (x86)
- mkisofs in %PATH%
- [Wack0's DingusPPC binaries](https://github.com/Wack0/dingusppc-nt/releases) in dingusppc/
- disabled DPI scaling for dingusppc.exe in compatibility properties

```powershell
# Configure and build
python smyguscpp.py cmake.all path\to\cmake\project

# Alternatively
python smyguscpp.py cmake.configure path\to\cmake\project
python smyguscpp.py cmake.build

# Just boot Windows NT
python smyguscpp.py nt.boot path\to\iso\image
```
