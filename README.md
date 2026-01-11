# MuxForge
## Description
MuxForge is a custom C++ library that provides a simplified interface for working with FFmpeg, FFplay, FFprobe, HandBrake, yt-dlp, and much more.
## Binaries
* [FFmpeg, FFplay, FFprobe](https://www.gyan.dev/ffmpeg/builds/ffmpeg-git-full.7z)
* [HandBrake](https://handbrake.fr/downloads2.php)
* [yt-dlp](https://github.com/yt-dlp/yt-dlp)
* [python](https://www.python.org/downloads/)
* [VT-PR](https://github.com/chu23465/VT-PR)

## Features
MuxForge has many features, none of which I claim as my own. I have simply wrapped existing tools and libraries to provide a simplified interface for users. I do __not__ claim responsibility for any file or system damage.  Similarly, I do __not__ claim responsibility for creating any DRM bypassing tools.  I __do **not**__ promote piracy in any way shape or form.
* Video and audio encoding and decoding using FFmpeg
* Video and audio transcoding using HandBrake
* Video downloading using yt-dlp
* Video and audio analysis using FFprobe

* For more options, run:
```
MuxForge help
```
* <u>or</u> visit the [advanced help](https://github.com/codester2835/MuxForge/blob/main/Advanced_Help.txt) file

## Installation
__Insure you are running in administrator command prompt.__
1. Clone the repository:
```
git clone https://github.com/codester2835/MuxForge.git
```
2. Navigate to the project directory:
```
cd MuxForge\bin
```
3. Add the `bin` directory to your system PATH.
```
for /f "usebackq tokens=2*" %A in (`reg query "HKLM\SYSTEM\CurrentControlSet\Control\Session Manager\Environment" /v Path`) do reg add "HKLM\SYSTEM\CurrentControlSet\Control\Session Manager\Environment" /v Path /t REG_EXPAND_SZ /d "%B;%CD%" /f
```


__Or__
> Download the latest installer file from the [Releases](https://github.com/codester2835/MuxForge/releases) page and run it.

## Disclaimer
By using this project you agree that:
`The developer shall not be held responsible for any account suspensions, terminations, penalties or legal action taken/imposed by third-party platforms. The User acknowledges and agrees that they are solely responsible for complying with all terms, policies, copyright and guidelines of any such platforms.`

## Usage
Once installed, you can use MuxForge from the command line. Run the following command for options:
```
MuxForge help
```	
For a full list of commands, run:
```
MuxForge help_advanced <insert path here>
```
## How to Contribute

If you want to contribute to this project, follow the steps below:

1. Fork this repository.
2. Create a branch: `git checkout -b main`.
3. Make your changes and confirm them: `git commit -m '<commit_message>'`
4. Send to the original branch: `git push origin <project_name> / <location>`
5. Create the pull request.

Alternatively, consult the GitHub documentation on [how to create a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).


## Licence
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Legal
I (the creator) do __NOT__ promote piracy, or theft in any way.  This project is to be used **ONLY** for archival/personal uses.

## Regarding FFmpeg
This project uses FFmpeg which is licensed to the FFmpeg developers, specifically [gyan.dev](https://www.gyan.dev/ffmpeg/builds/). The lincence is the [<u>Attribution-NonCommercial-NoDerivatives 4.0 International CC BY-NC-ND 4.0 Deed</u>](https://creativecommons.org/licenses/by-nc-nd/4.0/)

## Miscellaneous
1. You are free to distribute this repository under any condition. 
2. If anyone has any requests that they would like to see or ways to make this better, *please* tell me.
3. Please do not expect me to build every [release](https://github.com/codester2835/MuxForge/releases), if you would like the latest updates of the binaries (FFmpeg, yt-dlp, etc.) [clone the repository](https://github.com/codester2835/MuxForge?tab=readme-ov-file#installation). 
4. Repeatedly adding this to PATH is *not* necessary.  

## Status
MuxForge is currently *only* available on 64-bit Windows versions. I apologize for the inconvenience.

