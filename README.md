# LCD-StandardFirmata

This project demonstrates how to control an I2C LCD display connected to an Arduino using the PyFirmata library.

## Prerequisites

Before running this project, make sure you have the following:

- Arduino board
- I2C LCD display
- Python installed on your computer
- PyFirmata library installed (`pip install pyfirmata2`)
- The following Arduino libraries installed:
  - LiquidCrystal_I2C
  - Firmata

## Connection Diagram

- Gnd pin of the LCD to Gnd of the Arduino
- Vcc pin of the LCD to 5V of the Arduino
- SDA pin of the LCD to A4 of the Arduino
- SCL pin of the LCD to A5 of the Arduino

## Installation

1. Clone this repository:

```bash
git clone https://github.com/zowest/LCD-StandardFirmata.git
```

2. Change into the project directory:

```bash
cd LCD-StandardFirmata
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Connect your Arduino board to your computer.
2. Upload the `LCD-StandardFirmata.ino` sketch to your Arduino using the Arduino IDE.
3. Run the Python script: `python main.py`

Feel free to modify the `main.py` script to suit your needs and add more commands if necessary.
