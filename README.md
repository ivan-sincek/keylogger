# Keylogger

Windows OS keylogger with a hook mechanism (i.e. with a keyboard hook procedure).

Mapped most of the keys for the standard US keyboard layout.

All the code you need is in this file:

* [/src/Keylogger/Keylogger/main.cpp](https://github.com/ivan-sincek/keylogger/blob/master/src/Keylogger/Keylogger/main.cpp)

Built with Visual Studio Community 2022 v17.5.4 (64-bit) and tested on Windows 10 Enterprise OS (64-bit).

Made for educational purposes. I hope it will help!

## How to Run

Run Keylogger_x86.exe (32-bit) or Keylogger_x64.exe (64-bit).

## Cleanup

If hide window functionality is enabled, do not forget to shutdown the keylogger's process through task manager.

If hide files functionality is enabled, do not forget to delete the hidden keylogger's files after shutting the keylogger down first.

If startup functionality is enabled, do not forget to remove the keylogger's registry key called `keylogger` located at `HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Run`.

**Executable provided does not have these functionalities active. If you want to try them out, uncomment the corresponding methods inside the source code and recompile it.**

## Runtime

```fundamental
C:\Users\W10\Desktop>Keylogger.exe
Keylogger v2.3 by Ivan Sincek.
GitHub repository at github.com/ivan-sincek/keylogger.
Hook procedure has been installed successfully

Keylogger is up and running...

Hook procedure has been uninstalled successfully
```

## Images

<p align="center"><img src="https://github.com/ivan-sincek/keylogger/blob/master/img/log.jpg" alt="Log"></p>

<p align="center">Figure 1 - Log</p>
