# 💡 STM32 GPIO Input to Control LED

This project demonstrates how to use an **input pin (PA0)** on the STM32F4Discovery board to control an **output pin (PD12)** connected to an onboard LED (LED4).

When the input pin is pulled high (connected to VDD), the LED turns on.

When the pin is pulled low (connected to GND), the LED turns off.

## 📷 Demo

#### The input pin is connected to VDD
![image](https://github.com/Weber0531/Pin-read/blob/main/images/VDD.jpeg)

#### The input pin is connected to GND
![image](https://github.com/Weber0531/Pin-read/blob/main/images/GND.jpeg)

#### Video
👉 [觀看完整影片](https://drive.google.com/file/d/1jtoagCr1yVu1ZuOBov_DwjW_nLjcj-cc/view?usp=sharing)

## 🔧 Platform & Hardware Requirements

- STM32CubeIDE
- STM32F4 Discovery board
- Jumper wires(F/F)

## 🚀 Features

- If PA0 is **high (1)** → turn **ON** LED4 (PD12)
- If PA0 is **low (0)** → turn **OFF** LED4 (PD12)

## 🧪 How to Run

1. Clone this repo
```bash
git clone https://github.com/Weber0531/Pin-read.git
```
2. Open STM32CubeIDE → File → Import → General → Existing Projects into Workspace
3. Select the folder you just cloned
4. Connect STM32F4Discovery
5. Build & Run
