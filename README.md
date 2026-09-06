# AssilOS (Codenamed Aurès) 💾
[![Made in Algeria](https://www.madeinalgeria.dev/badge/assilos.svg)](https://www.madeinalgeria.dev/projects/assilos) [![License](https://img.shields.io/badge/License-apache--2.0-orange.svg)](https://opensource.org/licenses/BSD-2-Clause) [![Made in Algeria](https://img.shields.io/badge/Made%20in-Algeria-green.svg)](https://en.wikipedia.org/wiki/Batna,_Algeria)
[![Stand With Palestine](https://raw.githubusercontent.com/TheBSD/StandWithPalestine/main/banner-no-action.svg)](https://thebsd.github.io/StandWithPalestine)


AssilOS is monolithc boot-sector operating system that based on bootOS, is it not linux-based.

### license
AssilOS is released under BSD 3-Clause license, you can modify, sell, redistribute under BSD 3-Clause terms, see [License](LICENSE).

### screenshot
![screenshot](SCREENSHOT.PNG)

### requirements
- linux distros/BSD/macOS/windows/Android (via Termux)
- CSM enabled
- QEMU (recommanded)
- virtualbox (opetional)
- DOSBox-X (optional)
- NASM assembler

### Can it run bootOS programs and bootOS games?
- yes!, it can run programs or games because AssilOS is based on bootOS, you can get them from [nanochess](https://github.com/nanochess/)
- also, you can create your own programs or games (they must fit to 512-bytes!) 
- avoid use DOS programs, as they won't fit into 512-bytes

### limitations
- USB and CD booting are not supported
- Legacy BIOS-only, no UEFI support
- 16-bits

### rules

- you can: study, modify, distribute AssilOS (with requirements), use it in commercial products, use it for retro computing.
- you cannot: remove copyright notice of nanochess or AssilOS Project, claim as your own, use it for illegal actions, use names and copyright holders name to endorse

### build instruction
nasm -f bin os.asm -l os.lst -o os.img
