# week 3 notes
## Day 1

#OS's  Job
security and Access control
Device (I/O) Management 
Memory Management
File System Management Process Management

 Link-local IPv6 Address . . . . . : fe80::1501:595b:a084:1084%17
   IPv4 Address. . . . . . . . . . . : 172.20.10.4
   Subnet Mask . . . . . . . . . . . : 255.255.255.240
   Default Gateway . . . . . . . . . : 172.20.10.1
fe80::945c:9aff:fee6:e64

 1     5 ms     7 ms     7 ms  172.20.10.1
  2     *        *        *     Request timed out.
  3     *        *        *     Request timed out.
  4     *        *        *     Request timed out.
  5   102 ms   114 ms    95 ms  10.208.225.18
  6     *        *        *     Request timed out.
  7   114 ms    95 ms   107 ms  196.201.61.221
  8   116 ms    82 ms    93 ms  105.177.14.19
  9    93 ms    93 ms   100 ms  142.250.174.118
 10    94 ms    96 ms    98 ms  142.250.209.225
 11    98 ms    91 ms    95 ms  172.253.176.237
 12    94 ms    97 ms    94 ms  8.8.8.8

 Windows 11Pro
Version
21H2
OS Build 22000.37

Processor - AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G      2.60 GHz
RAM 8GB

System Type - 64-bit operating system, x64-based processor

Edition = Pro
## Day 2
* **C:\Windows\System32**: The core system directory storing essential Windows OS binaries, device drivers, and DLL files required to run the operating system.
* **C:\Users\<you>**: The personal user profile directory that houses your personal folders (Desktop, Documents, Downloads) and user-specific files.
* **AppData**: A hidden directory within your user profile where installed applications store their local settings, cached data, and configuration files.

whoami
desktop-9qce2u\pablo
Administrator
Standard Account is safer because it helps the user to have full control over his daily routes

The number is 4684
Delecting unknwon files is dangerous because it can instantly corrupt the operating system

#Day 3
fake file name and their real type 
Exam_Timetable.docx.exe - (.exe)
Receipt_August2026.pdf.scr (.scr)
Photo_Album.jpg.bat - (.bat)

### Lab Exercise: File Extensions vs. File Signatures (`Format-Hex`)

* **Commands Executed:**
  ```powershell
  cd ~
  mkdir filelab
  cd filelab
  Set-Content note.txt "Akwaaba"
  Format-Hex note.txt
  Copy-Item note.txt note.jpg
  Format-Hex note.jpg

### Same bytes, new name
* **(a) First row of `Format-Hex note.txt`:**
  ```text
  00000000   41 6B 77 61 61 62 61 0D 0A                       Akwaaba..

  00000000   41 6B 77 61 61 62 61 0D 0A                       Akwaaba..

  Renaming the file did not any change a single byte indicating that file extensions merely labels
Because Even a tiny single-character change completely alters the file's hash

A file name starting with 4D 5A is a windows execuatable

svchost.exe (lowercase s-v-c-h-o-s-t-.-e-x-e, with no extra spaces, numbers, or swapped letters).

OS Name	Microsoft Windows 11 Pro
Version	10.0.22000 Build 22000
BIOS Mode	UEFI
Secure Boot State	On
If Secure Boot State is On, it matches the safe setting from the Week 1 fixes; if it is Off or Unsupported, it does not match and needs to be enabled in UEFI firmware.

Startup apps (same slide): Task Manager (Ctrl + Shift + Esc) → Startup apps (Windows 10: the Startup tab). Write 3 apps with their Publisher and Status. If an app's name or publisher is new to you, write its name and what a search tells you about it. Change nothing.

Google Chrome
VS code

#Day 5 notes
Who posted it 
Do i understand every command
Does it weaken or bypass built-in security controls
Is it relevant to my OS version

Act 1038

VirusTotal shows We currently don't have any comments that fit your search
It is showing not found because it has seen the exact hash before