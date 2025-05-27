ProcStrings
A Windows memory scanner for extracting readable strings from running processes. Unlike traditional dump-based approaches, ProcStrings accesses live process memory for real-time analysis.

Overview
ProcStrings scans .text, .data, and other sections of a process to retrieve string literals, debug messages, and potential configuration data. It leverages low-level Windows APIs (ReadProcessMemory, EnumProcessModules) to directly access memory regions without requiring full process dumps.

Features
✅ Extracts strings directly from memory ✅ Scans .data, .bss, and other writable sections ✅ real-time scanning of live processes ✅ Filters printable characters for cleaner output ✅ Validates PE headers before extraction

This is great for RE and digging deeping into a running process

