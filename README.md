<h1 align="center">Firmware Marlin Flyingbear Ghost 4s/5</h1>

<p align="center">Firmware adattati da Flyingbear Ghost Club Ita per Firmware Marlin per le stampanti Flying Bear Ghost 4s/5</p>


<h1 align="center"><img src = Image/fbghostitaLogo.png /></h1>

###### Feature

- Adattamento a molte configurazioni su caratterische delle stampanti FlyingBear Ghost
- BLTouch su tutte le configurazioni
- Libero accesso a tutti i Source Code
- Source Code modificato per semplificare la configurazione
- Firmware precompilati disponibili

###### Istruzioni

1) Modificare il "default-envs" in Platformio.ini con quello della propria scheda (default: MKS Robin Nano V1.1 / V1.2)
   <h1 align="left"><img src = Image/Immagine 2023-08-29 210523.png /></h1>
3) Modificare la "MOTHERBOARD" in Configuration.h con quello della propria scheda (default: MKS Robin Nano V1.1 / V1.2)
   <h1 align="left"><img src = Image/Immagine 2023-08-29 210619.png /></h1>
4) Editare i parametri di base inclusi in FlyingBearGhost_ConfigFile.h con i valori personalizzati in base alla vostra configurazione
   <h1 align="left"><img src = Image/Immagine 2023-08-29 210641.png /></h1>
5) Compilare attraverso il Tool "Auto Build Marlin" di Marlin Firmware, disponibile come estrnsione per Virtual Studio Code
   <h1 align="left"><img src = Image/Immagine 2023-08-29 210725.png /></h1>

# Versioni Disponibili
MKS Robin Nano V1.1
###### Versione Marlin 2.1.x
###### LVGL UI
- [Stock](https://github.com/flyingbear-club-ita/flyingbear_ghost_marlin/tree/main/Firmware/MKS_Robin_Nano_V1.1/STOCK)
- [Stock - Bltouch](https://github.com/flyingbear-club-ita/flyingbear_ghost_marlin/tree/main/Firmware/MKS_Robin_Nano_V1.1/STOCK_BLTOUCH)
---
MKS Robin Nano V1.2
###### Versione Marlin 2.1.x
###### LVGL UI
- [Stock](https://github.com/flyingbear-club-ita/flyingbear_ghost_marlin/tree/main/Firmware/MKS_Robin_Nano_V1.2/STOCK)
- [Stock - Bltouch](https://github.com/flyingbear-club-ita/flyingbear_ghost_marlin/tree/main/Firmware/MKS_Robin_Nano_V1.2/STOCK_BLTOUCH)
- [TMC2208](https://github.com/flyingbear-club-ita/flyingbear_ghost_marlin/tree/main/Firmware/MKS_Robin_Nano_V1.2/TMC2208)
- [TMC2208 - Bltouch](https://github.com/flyingbear-club-ita/flyingbear_ghost_marlin/tree/main/Firmware/MKS_Robin_Nano_V1.2/TMC2208_BLTOUCH)
---
MKS Robin Nano V1.3
###### Versione Marlin 2.1.x
###### LVGL UI
- [Stock](https://github.com/flyingbear-club-ita/flyingbear_ghost_marlin/tree/main/Firmware/MKS_Robin_Nano_V1.3/STOCK)
- [TMC2208](https://github.com/flyingbear-club-ita/flyingbear_ghost_marlin/tree/main/Firmware/MKS_Robin_Nano_V1.3/TMC2208)
- [Stock - Bltouch](https://github.com/flyingbear-club-ita/flyingbear_ghost_marlin/tree/main/Firmware/MKS_Robin_Nano_V1.3/STOCK-BLTOUCH) 
- [TMC2208 - Bltouch](https://github.com/flyingbear-club-ita/flyingbear_ghost_marlin/tree/main/Firmware/MKS_Robin_Nano_V1.3/TMC2208-BLTOUCH)
---
MKS Robin Nano-S V1.3
###### Versione Marlin 2.1.x
###### LVGL UI
- [TMC2225](https://github.com/flyingbear-club-ita/flyingbear_ghost_marlin/tree/main/Firmware/MKS_Robin_Nano_V1.3/STOCK)
- [TMC2225 - Bltouch](https://github.com/flyingbear-club-ita/flyingbear_ghost_marlin/tree/main/Firmware/MKS_Robin_Nano_V1.3/STOCK-BLTOUCH)

---

### In caso di problemi nella configurazione non esitate a contattarci!
---

Credits:
- fork from [Marlin Firmware](https://github.com/MarlinFirmware/Marlin)
- [Flyingbear Ghost Wiki](https://flyingbearghost.com)
- [Flyingbear Ghost Community Italia](https://discord.gg/p2gtrKm)
