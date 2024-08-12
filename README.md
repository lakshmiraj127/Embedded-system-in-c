# 8051 LCD Interfacing

This project demonstrates interfacing an LCD with the 8051 microcontroller using assembly language. The code includes functions to send commands, data, and display strings on the LCD.

## Hardware Requirements

- 8051 microcontroller
- LCD display
- 10K ohm potentiometer
- Connecting wires

## Instructions

1. Connect the LCD data lines to Port 2 of the 8051 microcontroller.
2. Connect RS and EN pins of the LCD to P3^0 and P3^1 pins of the microcontroller, respectively.
3. Ensure proper power supply connections and configure the 8051 microcontroller.
4. Compile and flash the code to the microcontroller.
5. Observe the output on the LCD display.

## Functions

- `lcd_cmd(char ch)`: Send a command to the LCD.
- `lcd_data(char ch)`: Send data to be displayed on the LCD.
- `lcd_str(char *str)`: Display a string on the LCD.
- `delay()`: Delay function for timing requirements.

## Usage

1. Include the `reg51.h` header file in your project.
2. Define the necessary connections for RS and EN pins.
3. Call the `lcd_cmd()`, `lcd_data()`, or `lcd_str()` functions as needed in your main code.
4. Customize the code and strings to display specific content on the LCD.

## Troubleshooting

- If the LCD does not display the expected output, check the hardware connections and the initialization sequence in the code.
- Ensure proper timing delays are implemented using the `delay()` function.


  

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
