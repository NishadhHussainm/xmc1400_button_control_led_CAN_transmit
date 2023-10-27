# xmc1400_button_control_led_CAN_transmit

# Microcontroller Application with Pushbuttons and CAN Communication

This repository contains a microcontroller application developed for an XMC microcontroller using the DAVE IDE. The application handles pushbuttons and features CAN communication capabilities. It allows you to control LED states based on button presses and transmit data over a CAN network.

## Prerequisites

Before using this application, ensure you have the following:

- DAVE IDE or a compatible development environment.
- An XMC microcontroller compatible with the provided code.
- Proper hardware setup with pushbuttons, LEDs, and CAN interface.

## Features

- Multiple LED modes controlled by pushbutton presses.
- CAN communication to transmit data to other devices on the network.
- Flexible code structure for customization according to your project's requirements.

## Usage

1. Clone or download this repository to your development environment.
2. Open the project in your DAVE IDE and configure it for your specific target hardware.
3. Build and flash the application to your XMC microcontroller.

### Pushbutton Functionality

- Press the pushbutton connected to `DIGITAL_IO_2` to cycle through LED modes.
- In LED mode 1, press `DIGITAL_IO_0` or `DIGITAL_IO_1` to trigger specific actions.

### LED Modes

- **LED Mode 1**: Based on pushbutton presses.
- **LED Mode 2**: Customizable for other functionality.

### CAN Communication

- The application uses CAN to transmit data. Configure CAN parameters as needed.

## Customization

You can customize the code to add new LED modes, change pushbutton behavior, or extend CAN communication functionality based on your project requirements.

## License

This code is provided under an open-source license. Please refer to the LICENSE file for details.

## Author

- Nishadh Hussain 

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork this repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them to your branch.
4. Create a pull request to submit your changes for review.

## Contact

If you have any questions or need assistance with this project, feel free to contact the maintainers:

-Nishadh Hussain (nishadh2000@gmail.com)

## Acknowledgments

This project is developed for the XMC microcontroller platform and uses the DAVE IDE.

---


