# Links
[NTLite](https://www.ntlite.com/download/)

[Windows11 ISO](https://www.microsoft.com/software-download/windows11)

or

[Windows10 ISO](https://www.microsoft.com/software-download/windows10)

## Instruction
1. Extract ISO to folder.
2. Open NTLite and add extracted folder directory.
3. Select Windows version.
3. Import xml's presets.
4. Open command prompt and export drivers to folder ```dism /online /export-driver /destination:"c:\exportdrivers"``` then select drivers folder in NTLite.
5. Select updates folder ```C:\Windows\SoftwareDistribution```.
6. Select registry config file.
7. Trim versions and save ISO then click apply.