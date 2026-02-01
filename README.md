# MuxForge

## Description
MuxForge is a C++ utility library that provides a streamlined interface for working with popular media‑processing tools such as FFmpeg, FFplay, FFprobe, HandBrake, yt‑dlp, and others. Its goal is to simplify complex command‑line workflows into a unified, user‑friendly experience.

## Binaries
MuxForge relies on several external tools. You can download them here:

- [FFmpeg, FFplay, FFprobe](https://www.gyan.dev/ffmpeg/builds/ffmpeg-git-full.7z)  
- [HandBrake](https://handbrake.fr/downloads2.php)  
- [yt-dlp](https://github.com/yt-dlp/yt-dlp)  
- [Python](https://www.python.org/downloads/)  
- [VT‑PR](https://github.com/chu23465/VT-PR)

## Features
MuxForge wraps existing open‑source tools to provide a simplified interface. None of the underlying functionality is my own creation; I only provide the wrapper.  
I do **not** claim responsibility for any system or file damage, nor do I claim responsibility for creating or enabling DRM‑bypassing tools. I do **not** promote piracy in any form.

Key capabilities include:
- Video and audio encoding/decoding via FFmpeg  
- Video and audio transcoding via HandBrake  
- Video downloading via yt‑dlp  
- Media analysis via FFprobe  

For more options, run:
```
MuxForge help
```

Or view the [advanced help](https://github.com/codester2835/MuxForge/blob/main/Advanced_Help.txt) file.

## Installation
**Ensure you are running in an Administrator Command Prompt.**

1. Clone the repository:
```
git clone https://github.com/codester2835/MuxForge.git
```

2. Navigate to the project directory:
```
cd MuxForge\bin
```

3. Add the `bin` directory to your system PATH:
```
for /f "usebackq tokens=2*" %A in (`reg query "HKLM\SYSTEM\CurrentControlSet\Control\Session Manager\Environment" /v Path`) do reg add "HKLM\SYSTEM\CurrentControlSet\Control\Session Manager\Environment" /v Path /t REG_EXPAND_SZ /d "%B;%CD%" /f
```

**Or:**  
Download the latest installer from the [Releases](https://github.com/codester2835/MuxForge/releases) page and run it.

## Disclaimer
By using this project, you agree that:

`The developer shall not be held responsible for any account suspensions, terminations, penalties, or legal action taken by third‑party platforms. The user is solely responsible for complying with all terms, policies, copyright rules, and guidelines of any such platforms.`

## Usage
Once installed, run the following command for general options:
```
MuxForge help
```

For a full list of commands:
```
MuxForge help_advanced <path>
```

## How to Contribute
1. Fork the repository.  
2. Create a new branch:  
   ```
   git checkout -b main
   ```
3. Make your changes and commit them:  
   ```
   git commit -m "<commit_message>"
   ```
4. Push your branch:  
   ```
   git push origin <project_name>/<location>
   ```
5. Open a pull request.

For more details, see GitHub’s guide on [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Legal
I (the creator) do **NOT** promote piracy or theft. This project is intended **ONLY** for archival and personal use.

## Regarding FFmpeg
MuxForge uses FFmpeg, which is licensed to the FFmpeg developers, specifically the builds provided by [gyan.dev](https://www.gyan.dev/ffmpeg/builds/).  
FFmpeg is licensed under the **Attribution‑NonCommercial‑NoDerivatives 4.0 International (CC BY‑NC‑ND 4.0)** license:  
[https://creativecommons.org/licenses/by-nc-nd/4.0/](https://creativecommons.org/licenses/by-nc-nd/4.0/)
I am currently working on building a custom FFmpeg, please be patient.  

## Miscellaneous
1. You are free to distribute this repository under any conditions.  
2. Suggestions and feature requests are welcome.  
3. Not all releases will include updated binaries. For the latest versions of FFmpeg, yt‑dlp, etc., please clone the repository.  
4. Re‑adding the `bin` directory to PATH is not necessary after the first setup.
5. Code for this project will be available soon.

## Status
MuxForge is currently available **only** for 64‑bit Windows systems. I apologize for the inconvenience.