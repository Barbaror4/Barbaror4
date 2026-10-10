Barbaror4

<p align="center">
  <b>Embedded Systems • Firmware • Reverse Engineering • Android • Audio DSP</b>
</p><p align="center">
  <img src="https://komarev.com/ghpvc/?username=Barbaror4&style=flat-square" alt="Profile views">
</p>---

"whoami"

Elektronik, gömülü sistemler, firmware, Android/Linux modlama ve reverse engineering ile ilgileniyorum.

Bir cihazı yalnızca kullanmak yerine genelde şu sorular daha çok ilgimi çekiyor:

İçinde ne var?
Firmware ne yapıyor?
Hangi protokolü kullanıyor?
Neden böyle davranıyor?
Üreticinin koyduğu sınır nerede?
Ve en önemlisi:

Bundan başka ne yaptırabilirim?

Projelerimin büyük kısmı pahalı laboratuvar ekipmanları olmadan geliştiriliyor.

Osiloskop, logic analyzer veya profesyonel RE ekipmanları yerine çoğu zaman:

UART
USB descriptors
ADB / kernel logs
multimeter
datasheets
SDK source code
firmware dumps
software diagnostics
trial & error

kullanıyorum.

«Elimde ne varsa onunla maksimum işi çıkarmaya çalışıyorum.»

---

Hardware

<p align="center">
  <img src="./assets/stm32.png" height="60" alt="STM32">
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./assets/jieli.png" height="60" alt="JieLi">
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./assets/nationalchip.png" height="60" alt="NationalChip">
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./assets/generalplus.png" height="60" alt="Generalplus">
</p>Platformlar ve üreticiler arasında özellikle:

- STM32
- JieLi
- NationalChip
- Generalplus
- ESP32
- ESP8266

ile ilgileniyorum.

"STM32" (https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
"ESP32" (https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
"ESP8266" (https://img.shields.io/badge/ESP8266-E7352C?style=flat-square&logo=espressif&logoColor=white)
"Embedded" (https://img.shields.io/badge/Embedded-Systems-555555?style=flat-square)
"Firmware" (https://img.shields.io/badge/Firmware-Development-007ACC?style=flat-square)

---

STM32

STM32 tarafında özellikle:

STM32F103
STM32F411
STM32F746

üzerinde çalışıyorum.

En çok ilgimi çeken konular:

- DMA
- USB
- USB Audio
- SDIO
- SPI / I²C / UART / I²S
- Ethernet
- DSP
- FFT
- Audio playback
- Touchscreen UI
- External flash
- Bare-metal / HAL tabanlı sistemler

Bir MCU'yu yalnızca GPIO yakıp söndürmek için kullanmak yerine, mümkün olduğunca gerçek bir cihaz haline getirmek daha çok ilgimi çekiyor.

---

JieLi / Generalplus / NationalChip

Ucuz tüketici elektroniğinde kullanılan SoC'ler özellikle ilgimi çekiyor.

Çünkü çoğu zaman küçük ve ucuz bir cihazın içinde beklenenden çok daha güçlü bir çip çıkabiliyor.

JieLi tarafında özellikle:

AC69xx
Bluetooth Audio
USB Audio
Firmware SDKs
Codec support
Chip identification
BR platform mappings

gibi konuları araştırıyorum.

NationalChip ve Generalplus tarafında da eski cihazlar, firmware yapıları, undocumented özellikler ve yeniden kullanılabilecek donanımlar ilgimi çekiyor.

---

Embedded Audio

"Audio DSP" (https://img.shields.io/badge/Audio-DSP-FF5F5F?style=for-the-badge)
"USB Audio" (https://img.shields.io/badge/USB-Audio-blue?style=for-the-badge)
"FFT" (https://img.shields.io/badge/FFT-Spectrum-purple?style=for-the-badge)

Gömülü ses sistemleri en çok ilgilendiğim alanlardan biri.

Çalıştığım veya denediğim konular:

MP3
WAV
FLAC
HE-AAC
USB Audio
I²S
PWM Audio
Bluetooth Audio
FFT
Spectrum Visualizers
Parametric EQ
Hardware EQ
Pitch / Speed Processing
Stereo Recording
Internet Radio
Audio Codecs
DACs

---

Projects

STM32F746G-DISCO Media Player

STM32F746 + WM8994 tabanlı, mümkün olduğunca tam özellikli bir medya sistemi.

SD Card
USB Mass Storage
exFAT
USB Audio / PC Mode
Ethernet Internet Radio
MP3
WAV
HE-AAC
AUX Input
Stereo Recording
Parametric EQ
WM8994 Hardware EQ
FFT Visualizers
Pitch / Speed Control
Touchscreen UI

Amaç yalnızca ses çalmak değil.

Amaç:

«Bir STM32'nin nereye kadar götürülebileceğini görmek.»

---

STM32F411 Audio Player

Daha düşük kaynaklı bir MCU üzerinde ses ve DSP deneyleri.

STM32F411
SDIO
MP3 / WAV
PWM Stereo Audio
FFT
ST7789
External SPI Flash
USB Audio experiments

Kısıtlı donanımda bir özelliği çalıştırmak bazen çok daha güçlü bir MCU'da aynı şeyi yapmaktan daha eğlenceli.

---

Android

"Android" (https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
"Linux" (https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
"Samsung" (https://img.shields.io/badge/Samsung-1428A0?style=flat-square&logo=samsung&logoColor=white)

Android tarafında özellikle Samsung / Exynos cihazlarında:

Root
Custom Kernels
Kernel Tuning
Overclocking
Recovery
Firmware
ADB
Android internals
Linux
System modification

ile ilgileniyorum.

Telefonları sadece telefon olarak değil, üzerinde deney yapılabilen küçük Linux makineleri olarak görüyorum.

---

Reverse Engineering

"Reverse Engineering" (https://img.shields.io/badge/Reverse-Engineering-8A2BE2?style=for-the-badge)

En sevdiğim senaryo:

Unknown device
+
Unknown chip
+
Barely documented firmware
+
Old Chinese SDK
+
"Bu ne lan?"
=
Perfect

Bir cihaz hakkında yeterli doküman yoksa genelde ilgim azalmak yerine artıyor.

Firmware dump'ları, descriptor'lar, SDK'lar, datasheet'ler ve cihaz davranışlarından platformu anlamaya çalışmayı seviyorum.

---

Budget Engineering

"Budget Engineering" (https://img.shields.io/badge/Budget-Engineering-success?style=for-the-badge)
"DIY" (https://img.shields.io/badge/DIY-Hardware-orange?style=for-the-badge)

Profesyonel elektronik laboratuvarım yok.

Ve açıkçası bu bazen projeleri daha ilginç hale getiriyor.

No oscilloscope.
No logic analyzer.
No expensive debugger setup.

Still debugging.

Bir problemi:

"hangi pahalı ekipmanı almalıyım?"

yerine:

"elimdeki şeylerle bunu nasıl anlayabilirim?"

şeklinde çözmeye çalışıyorum.

My engineering philosophy

Expensive != Interesting
New      != Better
Old      != Useless
Cheap    != Simple

Ucuz veya eski bir donanım bazen çok daha ilginç olabilir.

---
# `./tools`

<div align="center">

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Code::Blocks](https://img.shields.io/badge/Code::Blocks-IDE-2C3E50?style=flat-square)
![STM32CubeIDE](https://img.shields.io/badge/STM32CubeIDE-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)

</div>

```yaml
languages:
  - C
  - C++
  - Python

ides:
  - STM32CubeIDE
  - Code::Blocks
  - Visual Studio Code

embedded:
  - STM32 HAL
  - ESP32
  - ESP8266

interfaces:
  - UART
  - USB
  - SPI
  - I2C
  - I2S
  - SDIO

debugging:
  - UART logs
  - ADB
  - Linux logs
  - USB descriptors
  - Multimeter
  - CH341A
  - Firmware dumps

software:
  - Git
  - GitHub
  - Linux
  - STM32CubeIDE
  - Code::Blocks

research:
  - Datasheets
  - SDK source code
  - Firmware analysis
  - SDK archaeology
  - Trial & error

C
C++
Python
STM32CubeIDE
Git
GitHub
Linux
ADB
UART
CH341A
Multimeter
Datasheets
SDK archaeology

---

Current Interests

[+] Embedded audio
[+] STM32
[+] JieLi SoCs
[+] Firmware reverse engineering
[+] Android kernels
[+] Exynos
[+] USB internals
[+] Audio DSP
[+] Old / obscure SoCs
[+] Reusing cheap hardware

---

GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Barbaror4&show_icons=true&hide_border=true&include_all_commits=true" alt="GitHub stats">
</p><p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Barbaror4&layout=compact&hide_border=true" alt="Top languages">
</p>---

if (device.works())
{
    understand(device);
    modify(device);
    push_it_further(device);
}
else
{
    debug_until_it_does();
}

<p align="center">
  <b>Hardware is more fun when you're not supposed to touch it.</b>
</p>
