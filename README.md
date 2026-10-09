<div align="center">
    <p align="center">
        <a href="https://learn.microsoft.com/windows/win32/debug/pe-format">
          <img width="90%" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/Portable_Executable_32_bit_Structure.svg" />
        </a>
    </p>

# **`Awesome`** [PE](https://wikipedia.org/wiki/Portable_Executable) (_Portable Executable_) [Feature](https://wikipedia.org/wiki/Feature_(machine_learning)) [Extractor](https://wikipedia.org/wiki/Comparison_of_executable_file_formats) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
</div>

[![Windows](https://custom-icon-badges.demolab.com/badge/Windows-0078D6?style=for-the-badge&logo=windows11&logoColor=white)]()
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtube.com/playlist?list=PL9V4Zu3RroiU7nAvkoC3rN8Y6EQ_17X22&si=c5aU7aJbb4GHg8m-)
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)]()

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefense"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

```mermaid
flowchart TD

    WIN["Windows<br/>Executable<br/>Ecosystem"]

    WIN --> PE["PE<br/>(Portable Executable)<br/>Format"]

    PE --> EXE["EXE Application"]
    PE --> DLL["DLL Library"]
    PE --> SYS["SYS Driver"]
    PE --> CPL["CPL Control Panel"]
    PE --> SCR["SCR Screensaver"]
    PE --> OCX["OCX ActiveX"]
    PE --> COM["COM Server"]
    PE --> EFI["UEFI / EFI Module"]

    WIN --> MSI["MSI Installer"]
    WIN --> BAT["BAT Script"]
    WIN --> PS1["PowerShell"]
    WIN --> VBS["VBScript"]
    WIN --> JS["JavaScript (WSH)"]
    WIN --> LNK["Shortcut"]
    WIN --> REG["Registry Script"]

    MSI --> EXE
    MSI --> DLL

    EXE --> DLL
    EXE --> COM

    COM --> DLL
    COM --> EXE

    SYS --> KERNEL["Windows<br/>Kernel"]

    LNK --> EXE
    LNK --> BAT
    LNK --> PS1

    BAT --> CMD["cmd.exe"]
    PS1 --> POWERSHELL["powershell.exe"]
    VBS --> WSCRIPT["wscript.exe"]
    JS --> WSCRIPT
```

## 📖 Contents
- [My Other Awesome Lists](#my-other-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)


## Online Tools
- [Manalyze](https://github.com/JusticeRage/Manalyze) - A static [analyzer](https://manalyzer.org/) for PE executables.

### My Other Awesome Lists
You can access the my other awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)


### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/awesome-pe-feature-extractor/graphs/contributors)!

### License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

[🔼 Back to top](#awesome-pe-feature-extractor-)
