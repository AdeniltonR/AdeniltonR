<!-- Header -->
<img src="https://capsule-render.vercel.app/api?type=rect&height=8&color=00FF41" width="100%"/>

<!-- Título e Saudação -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=26&duration=1&pause=100000&color=00FF41&center=true&vCenter=true&width=700&height=60&lines=ADENILTON+RIBEIRO" alt="ADENILTON RIBEIRO"/>
  <br/>
  <img src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=12&duration=3000&pause=900&color=FFD700&center=true&vCenter=true&width=700&height=40&lines=%E2%96%BA+ENGENHEIRO+MECATRONICO;%E2%96%BA+SISTEMAS+EMBARCADOS;%E2%96%BA+HARDWARE+%2B+FIRMWARE+%2B+LINUX;%E2%96%BA+PRESS+START+TO+CONTINUE..." alt="Typing SVG"/>
</p>

<!-- Contatos -->
<p align="center">
  <a href="mailto:adeniltonribeiro.r4@gmail.com"><img src="https://img.shields.io/badge/►_EMAIL-000000?style=flat-square&logo=gmail&logoColor=00FF41" height="28"/></a>
  <a href="https://www.linkedin.com/in/adenilton-ribeiro-92551b156"><img src="https://img.shields.io/badge/►_LINKEDIN-000000?style=flat-square&logo=linkedin&logoColor=00FF41" height="28"/></a>
  <a href="https://www.instagram.com/adenilton_ribeiro4"><img src="https://img.shields.io/badge/►_INSTAGRAM-000000?style=flat-square&logo=instagram&logoColor=00FF41" height="28"/></a>
</p>

<!-- Contadores -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=AdeniltonR&style=flat-square&color=00FF41&label=PLAYERS" height="22"/>
  <a href="https://github.com/AdeniltonR?tab=followers"><img src="https://img.shields.io/github/followers/AdeniltonR?style=flat-square&label=PARTY&labelColor=000000&color=FFD700" height="22"/></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=00FF41" width="100%"/>

<!-- Sobre Mim -->
### `[ LEVEL 01 ]` ▸ PLAYER.C

```c
#include "embedded.h"
#include "hardware.h"

/* ============ PLAYER 1 SELECTED ============ */
typedef struct {
    const char *nome;
    const char *classe;
    const char *skills[4];
    const char *xp[4];
    const char *quests[2];
} player_t;

const player_t p1 = {
    .nome    = "Adenilton Ribeiro",
    .classe  = "Hardware & Firmware Engineer",
    .skills  = { "Eletronica", "Firmware",
                 "Linux Embarcado", "PCB + EMC" },
    .xp      = { "Pos em Seguranca Cibernetica",
                 "Engenharia Mecatronica",
                 "Tec. Automacao Industrial",
                 "Tec. Mecatronica" },
    .quests  = { "Linux Embarcado", "FPGA" },
};

int main(void) {
    hw_init();
    for (;;) build_reliable_systems();   /* no game over */
}
```

<!-- Status / Skills -->
### `[ LEVEL 02 ]` ▸ STATUS.SYS

```text
┌────────────────────────────────────────────────────┐
│  PLAYER: ADENILTON        CLASS: EMBEDDED ENGINEER │
├────────────────────────────────────────────────────┤
│  HARDWARE / PCB   [████████████████████]  MAX      │
│  FIRMWARE C/C++   [████████████████████]  MAX      │
│  MICROCONTROLLERS [██████████████████░░]           │
│  RTOS             [██████████████████░░]           │
│  LINUX EMBARCADO  [████████████████░░░░]  ▲ LVL UP │
│  FPGA             [████████░░░░░░░░░░░░]  ▲ LVL UP │
└────────────────────────────────────────────────────┘
```

<!-- Tecnologias e Ferramentas -->
### `[ LEVEL 03 ]` ▸ INVENTARIO.H

<table>
<tr>
<td width="24%"><b>🕹️ LINGUAGENS</b></td>
<td>
  <img src="https://img.shields.io/badge/C-000000?style=flat-square&logo=c&logoColor=00FF41" height="24"/>
  <img src="https://img.shields.io/badge/C++-000000?style=flat-square&logo=cplusplus&logoColor=00FF41" height="24"/>
  <img src="https://img.shields.io/badge/PYTHON-000000?style=flat-square&logo=python&logoColor=00FF41" height="24"/>
  <img src="https://img.shields.io/badge/GO-000000?style=flat-square&logo=go&logoColor=00FF41" height="24"/>
</td>
</tr>
<tr>
<td><b>⏱️ BARE-METAL & RTOS</b></td>
<td>
  <img src="https://img.shields.io/badge/BARE--METAL-000000?style=flat-square&logoColor=00FF41" height="24"/>
  <img src="https://img.shields.io/badge/RTOS-000000?style=flat-square&logoColor=00FF41" height="24"/>
  <img src="https://img.shields.io/badge/FREERTOS-000000?style=flat-square&logoColor=00FF41" height="24"/>
  <img src="https://img.shields.io/badge/ZEPHYR-000000?style=flat-square&logoColor=00FF41" height="24"/>
</td>
</tr>
<tr>
<td><b>🔌 MICROCONTROLADORES</b></td>
<td>
  <img src="https://img.shields.io/badge/ESP32-000000?style=flat-square&logo=espressif&logoColor=00FF41" height="24"/>
  <img src="https://img.shields.io/badge/ESP8266-000000?style=flat-square&logo=espressif&logoColor=00FF41" height="24"/>
  <img src="https://img.shields.io/badge/STM32-000000?style=flat-square&logo=stmicroelectronics&logoColor=00FF41" height="24"/>
  <img src="https://img.shields.io/badge/STM8-000000?style=flat-square&logo=stmicroelectronics&logoColor=00FF41" height="24"/>
  <img src="https://img.shields.io/badge/NORDIC-000000?style=flat-square&logo=nordicsemiconductor&logoColor=00FF41" height="24"/>
  <img src="https://img.shields.io/badge/PSOC™-000000?style=flat-square&logo=infineon&logoColor=00FF41" height="24"/>
  <img src="https://img.shields.io/badge/PIC-000000?style=flat-square&logo=microchip&logoColor=00FF41" height="24"/>
  <img src="https://img.shields.io/badge/AVR-000000?style=flat-square&logo=microchip&logoColor=00FF41" height="24"/>
  <img src="https://img.shields.io/badge/RASPBERRY_PICO-000000?style=flat-square&logo=raspberrypi&logoColor=00FF41" height="24"/>
  <img src="https://img.shields.io/badge/8051-000000?style=flat-square&logoColor=00FF41" height="24"/>
</td>
</tr>
<tr>
<td><b>🖥️ SBCs</b></td>
<td>
  <img src="https://img.shields.io/badge/RPI_ZERO_|_3_|_4-000000?style=flat-square&logo=raspberrypi&logoColor=00FF41" height="24"/>
  <img src="https://img.shields.io/badge/RADXA-000000?style=flat-square&logo=linux&logoColor=00FF41" height="24"/>
  <img src="https://img.shields.io/badge/ORANGE_PI_ZERO_3-000000?style=flat-square&logo=linux&logoColor=00FF41" height="24"/>
</td>
</tr>
<tr>
<td><b>🧰 IDEs & SDKs</b></td>
<td>
  <img src="https://img.shields.io/badge/ESP--IDF-000000?style=flat-square&logo=espressif&logoColor=FFD700" height="24"/>
  <img src="https://img.shields.io/badge/ARDUINO_IDE-000000?style=flat-square&logo=arduino&logoColor=FFD700" height="24"/>
  <img src="https://img.shields.io/badge/VS_CODE-000000?style=flat-square&logo=vscodium&logoColor=FFD700" height="24"/>
  <img src="https://img.shields.io/badge/STM32CUBEIDE-000000?style=flat-square&logo=stmicroelectronics&logoColor=FFD700" height="24"/>
  <img src="https://img.shields.io/badge/CUBEMX_STM32%2FSTM8-000000?style=flat-square&logo=stmicroelectronics&logoColor=FFD700" height="24"/>
  <img src="https://img.shields.io/badge/MPLAB_X-000000?style=flat-square&logo=microchip&logoColor=FFD700" height="24"/>
  <img src="https://img.shields.io/badge/MICROCHIP_STUDIO-000000?style=flat-square&logo=microchip&logoColor=FFD700" height="24"/>
  <img src="https://img.shields.io/badge/MIKROC_PIC%2F8051-000000?style=flat-square&logoColor=FFD700" height="24"/>
  <img src="https://img.shields.io/badge/NRF_CONNECT-000000?style=flat-square&logo=nordicsemiconductor&logoColor=FFD700" height="24"/>
  <img src="https://img.shields.io/badge/PSOC™_CREATOR-000000?style=flat-square&logo=infineon&logoColor=FFD700" height="24"/>
</td>
</tr>
<tr>
<td><b>📐 HARDWARE / PCB</b></td>
<td>
  <img src="https://img.shields.io/badge/KICAD-000000?style=flat-square&logo=kicad&logoColor=FFD700" height="24"/>
  <img src="https://img.shields.io/badge/EASYEDA-000000?style=flat-square&logoColor=FFD700" height="24"/>
  <img src="https://img.shields.io/badge/PADS-000000?style=flat-square&logoColor=FFD700" height="24"/>
  <img src="https://img.shields.io/badge/PROTEUS-000000?style=flat-square&logoColor=FFD700" height="24"/>
  <img src="https://img.shields.io/badge/EMC_EM_LAYOUT-000000?style=flat-square&logoColor=FFD700" height="24"/>
</td>
</tr>
</table>

<!-- GitHub Stats -->
### `[ LEVEL 04 ]` ▸ HIGH_SCORE.LOG

<div align="center">
<table>
  <tr>
    <td valign="top">
      <img src="https://github-stats-extended.vercel.app/api?username=AdeniltonR&show_icons=true&hide_border=false&border_color=00FF41&bg_color=000000&title_color=00FF41&icon_color=FFD700&text_color=00FF41&ring_color=00FF41" width="330" alt="GitHub Stats"/>
      <br/>
      <img src="https://streak-stats.demolab.com/?user=AdeniltonR&hide_border=false&border=00FF41&background=000000&stroke=00FF41&ring=FFD700&fire=FFD700&currStreakNum=00FF41&sideNums=00FF41&currStreakLabel=FFD700&sideLabels=00FF41&dates=00A82B" width="330" alt="GitHub Streak"/>
      <br/>
      <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=AdeniltonR&layout=compact&hide_border=false&border_color=00FF41&bg_color=000000&title_color=00FF41&text_color=00FF41&langs_count=6" width="330" alt="Top Languages"/>
    </td>
    <td valign="middle" align="center">
      <img src="eletronica.gif" width="460" alt="Gif centralizado"/>
    </td>
  </tr>
</table>
</div>

<!-- Activity Graph -->
<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=AdeniltonR&bg_color=000000&color=00FF41&line=00FF41&point=FFD700&title_color=FFD700&area=true&area_color=00FF41&hide_border=false" width="100%" alt="Activity Graph"/>
</div>

<!-- Rodapé -->
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=00FF41" width="100%"/>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=14&duration=2500&pause=700&color=00FF41&center=true&vCenter=true&width=700&height=40&lines=THANKS+FOR+PLAYING!;INSERT+COIN+TO+CONTINUE+%E2%96%88" alt="Obrigado pela visita"/>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&height=8&color=00FF41" width="100%"/>
