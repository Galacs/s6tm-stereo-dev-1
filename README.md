# S6TM Stereo Dev 1

ESP32S3 based stereo audio developement board with oled display

## IC List

- ESP32-S3FH4R2 (Main MCU)
- x4 LDL212 (LDOs)
- LM74502H (RPP, OCP)
- TPS629330 (5V out of audio SMPS)
- TLV320AIC (CODEC)
- TPA3116D2 (2x 30W audio amplifier)
- TPA3116D2 (OLED display)

## Top preview

<img width="925" height="857" alt="image" src="https://github.com/user-attachments/assets/6265014d-7aae-4dde-a030-087c65539a98" />

## Preview 3d render

<img width="1108" height="880" alt="image" src="https://github.com/user-attachments/assets/c90eed34-7a75-4b4b-92df-34b655f65c67" />

## Pictures

## Pin definitions

```c
#define SD_DAT0_PIN 33
#define SD_DAT1_PIN 47
#define SD_DAT2_PIN 37
#define SD_DAT3_PIN 36
#define SD_CLK_PIN 34
#define SD_CMD_PIN 35

#define SW_A_PIN 2
#define BTN_A_PIN 4
#define BTN_B_PIN 3

#define PG_PIN 5
#define VSNS_PIN 6

#define I2C_SDA_PIN 8
#define I2C_SCL_PIN 7

#define ENC_A_PIN 38
#define ENC_B_PIN 39
#define ENC_SW 40

#define FAULTZ_PIN 17
#define MUTE_PIN 21

#define GPIO1_PIN 15
#define RESET_PIN 16
#define BCLK_PIN 10
#define DOUT_PIN 13
#define DIN_PIN 12
#define MCLK_PIN 9
#define WCLK_PIN 11
```
