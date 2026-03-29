# Proiect InkTime - Smartwatch

Un smartwatch bazat pe microcontrollerul Nordic nRF52840 cu display e-Paper.

---

## Diagrama bloc

![Diagrama Bloc](Images/diagrama_bloc.png)

---

## Bill of Materials

| Ref | Componenta | Valoare | JLC Parts | Datasheet |
|-----|------------|---------|-----------|-----------|
| U1 | nRF52840 | $5.14 | [JLC](https://jlcpcb.com/parts/componentSearch?searchTxt=nRF52840-QF) | [DS](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8589839228197629952) |
| SWD | TC2030-IDC | $100.26 | [JLC](https://jlcpcb.com/partdetail/MicrochipTech-TC2030_CLIP3PACK/C5444772) | [DS](https://www.lcsc.com/datasheet/lcsc_datasheet_2403201318_Microchip-Tech-TC2030-CLIP-3PACK_C5444772.pdf) |
| ANT1 | 2450AT18B100E | $1.03 | [JLC](https://jlcpcb.com/partdetail/JohansonDielectrics-2450AT18B100E/C2917717) | [DS](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8588940948130156544) |
| X1 | NX2016SA-32MHZ-EXS00A-CS11336 | $9.04 | [JLC](https://jlcpcb.com/partdetail/NDK-NX2016SA_32MHZ_EXS00ACS11336/C6134317) | [DS](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8603064888214908928) |
| L2 | RC0402JR-070RL | $0.01 | [JLC](https://jlcpcb.com/partdetail/YAGEO-RC0402JR070RL/C60485) | [DS](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8717146932348461056) |
| L3 | RC0402JR-070RL | $0.01 | [JLC](https://jlcpcb.com/partdetail/YAGEO-RC0402JR070RL/C60485) | [DS](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8717146932348461056) |
| X2 | FC-135_32.7680KA-A3 | $0.2677 | [JLC](https://jlcpcb.com/partdetail/SeikoEpson-FC_135_32_7680KAA3/C2650472) | [DS](https://jlcpcb.com/partdetail/SeikoEpson-FC_135_32_7680KAA3/C2650472) |
| IC3 | BMA423 | $11.30 | [JLC](https://jlcpcb.com/partdetail/BoschSensortec-BMA423/C189517) | [DS](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8588894317147017216) |
| IC9 | RT6160 | $0.56 | [JLC](https://jlcpcb.com/partdetail/RichtekTech-RT6160AWSC/C7065276) | [DS](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8600398231234883584) |
| L7 | MLP2016SR47MT0S1 | $0.10 | [JLC](https://jlcpcb.com/partdetail/TDK-MLP2016SR47MT0S1/C87545) | [DS](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8588933367512879104) |
| IC1 | BQ25180YBGR | $2.01 | [JLC](https://jlcpcb.com/partdetail/TexasInstruments-BQ25180YBGR/C3682423) | [DS](https://www.ti.com/cn/lit/gpn/bq25180) |
| L5 | 744043680 | $9.53 | [JLC](https://jlcpcb.com/partdetail/WurthElektronik-744043680/C2045671) | [DS](https://www.we-online.com/components/products/datasheet/744043680.pdf) |
| D2 | MBR0530 | $0.03 | [JLC](https://jlcpcb.com/partdetail/78464-MBR0530/C77336) | [DS](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8586175081181818880) |
| D4 | MBR0530 | $0.03 | [JLC](https://jlcpcb.com/partdetail/78464-MBR0530/C77336) | [DS](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8586175081181818880) |
| D5 | MBR0530 | $0.03 | [JLC](https://jlcpcb.com/partdetail/78464-MBR0530/C77336) | [DS](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8586175081181818880) |
| Q3 | SI1308EDL-T1-GE3 | $0.18 | [JLC](https://jlcpcb.com/partdetail/VishayIntertech-SI1308EDL_T1GE3/C469327) | [DS](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8588884784742846464) |
| Q1 | DMG2305UX-7 | $0.10 | [JLC](https://jlcpcb.com/partdetail/DiodesIncorporated-DMG2305UX7/C150470) | [DS](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8560079443617075200) |
| IC2 | DRV2605YZFR | $1.31 | [JLC](https://jlcpcb.com/partdetail/TexasInstruments-DRV2605YZFR/C81079) | [DS](https://www.ti.com/cn/lit/gpn/drv2605) |
| D3 | USBLC6-2SC6Y | $0.24 | [JLC](https://jlcpcb.com/partdetail/STMicroelectronics-USBLC62SC6Y/C2969755) | [DS](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8603165824304111616) |
| J4 | KH-TYPE-C-16P | $0.08 | [JLC](https://jlcpcb.com/partdetail/Shenzhen_KinghelmElec-KH_TYPE_C16P/C709357) | [DS](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8588905154556923904) |
| U3 | MAX17048G-T10 | $2.44 | [JLC](https://jlcpcb.com/partdetail/2777647-MAX17048GT10/C2682616) | [DS](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8588907428524003328) |
| J1 | 503480-2400 | $0.84 | [JLC](https://jlcpcb.com/partdetail/MOLEX-5034802400/C122434) | [DS](https://www.molex.com/content/dam/molex/molex-dot-com/products/automated/en-us/salesdrawingpdf/503/503480/5034802400_sd.pdf?inline) |

---

## Descriere Functionalitate Hardware

### Microcontroller - nRF52840
 Caracteristici principale:
- ARM Cortex-M4 la 64 MHz
- 1MB Flash, 256KB RAM
- Bluetooth 5.0 / BLE integrat
- Radio 2.4GHz cu suport pentru antena externa
- Interfete multiple: SPI, I2C, UART, GPIO
 
### Display E-Paper - Waveshare 1.54" V2
 
Display-ul comunica prin SPI pe 4 fire:
- Rezolutie: 200x200 pixeli
- Consum ultra-redus - retine imaginea fara alimentare
- Conectat la nRF52840 prin conectorul FPC 24 pini (503480-2400)
 
### IMU - BMA423
 
Accelerometrul BMA423 comunica prin I2C:
- Accelerometru pe 3 axe
- Numarare pasi, recunoastere activitate
 
### Incarcator Baterie - BQ25180
 
BQ25180 gestioneaza incarcarea bateriei prin I2C:
- Intrare: USB-C 5V
- Iesire: 3.7V LiPo
- Curent maxim de incarcare: 250mA
 
### Baterie - AKYGA LP502030
 
- Dimensiuni: 32.5mm x 21mm x 5.5mm
- Conectata direct la doua test pad-uri de pe placa
 
### Motor Vibratii - FIT0774
 
- Controlat prin GPIO via driver haptic DRV2605
- Diametru: 10mm, Inaltime: 2.7mm
- Tensiune de operare: 1.5-4.2V
 
### Conector Debug - TC2030-IDC
 
- Conector Tag-Connect 10 pini
- Folosit pentru programare si debugging SWD
- Semnale: SWDIO, SWDCLK, GND, VCC, RESET
 
---
 
## Pinii nRF52840
 
| Pin nRF52840 | Semnal | Componenta | Interfata |
|--------------|--------|-----------|-----------|
| P0.00/XL1 | XL1 | Crystal X2 (32.768kHz) | XTAL |
| P0.01/XL2 | XL2 | Crystal X2 (32.768kHz) | XTAL |
| P0.05/AIN3 | EPD_CS | E-Paper (J1 FPC) | SPI CS |
| P0.06 | SDA | BMA423, BQ25180, MAX17048, DRV2605 | I2C SDA |
| P0.07 | SCL | BMA423, BQ25180, MAX17048, DRV2605 | I2C SCL |
| P0.08 | IMU_INT1 | BMA423 | GPIO Input |
| P1.08 | IMU_INT2 | BMA423 | GPIO Input |
| P0.11 | PMIC_INT | BQ25180 | GPIO Input |
| P0.12 | HAPTIC_EN | DRV2605 | GPIO |
| VBUS | VBUS | USB-C (J4) | Power |
| D- | D- | USB-C (J4) / USBLC6 | USB |
| D+ | D+ | USB-C (J4) / USBLC6 | USB |
| P0.13 | SW_UP | Buton Up | GPIO Input |
| P0.14 | SW_ENT | Buton Enter | GPIO Input |
| P0.15 | EPD_DC | E-Paper (J1 FPC) | SPI DC |
| P0.16 | EPD_RST | E-Paper (J1 FPC) | GPIO |
| P0.17 | EPD_BUSY | E-Paper (J1 FPC) | GPIO Input |
| P0.18/RESET | RESET | TC2030-IDC | SWD/GPIO |
| SWDCLK | SWDCLK | TC2030-IDC | SWD |
| SWDIO | SWDIO | TC2030-IDC | SWD |
| P1.02 | SW_DN | Buton Down | GPIO Input |
| P0.10/NFC2 | ALERT | MAX17048 | GPIO Input |
| ANT | RF | Antena 2450AT18B100E | RF |
| P0.02/AIN0 | SCK | E-Paper (J1 FPC) | SPI SCK |
| P0.03/AIN1 | MOSI | E-Paper (J1 FPC) | SPI MOSI |
 
---

## Jurnal de Design si Pasi de Implementare (Design Log)

### Pasi realizare PCB
* Plasarea componentelor majore: Am inceput prin a pozitiona componentele mari si cele cu constrangeri mecanice stricte (mufa USB, butoanele laterale, conectorul de display si microcontrollerul). Imediat dupa plasarea componentelor principale, am legat componentele mici (condensatoare, rezistente, etc.). In final, am pus Polygon Pour pe toate planurile infara de cel de POWER.

* Dupa plasarea componentelor in PCB, am inceput rutarea mai intai cu traseele de putere, urmand dupa cu restul.

* Rutarea (Top/Bottom): Traseele au fost rutate evitand unghiurile drepte. Liniile de alimentare au fost dimensionate cu latimea de 0.3mm (variind sub zonele dense BGA/QFN), iar cele de date la 0.15mm. Zona de sub antena radio a fost curatata complet de cupru si semnale.

### Erori DRC acceptate
* Copper Clearance: In zona pad-urilor BGA ale nRF52840, distanta minima dintre pad-uri este impusa de producator si nu poate fi modificata. Erorile sunt inevitabile si acceptate de JLCPCB.

* Overlap: Aceste erori apar din cauza tehnicii Via-in-Pad. Via-urile plasate direct in pad-urile componentei se suprapun geometric cu traseele adiacente.

* Drill Size: Via-urile folosite pentru Via-in-Pad au diametrul mai mic decat minimul din regulile DRC standard, ales intentionat pentru a incapea in pad-urile mici ale nRF52840.

* Board Outline Clearance. Erori de la mufa USB-C.
---
