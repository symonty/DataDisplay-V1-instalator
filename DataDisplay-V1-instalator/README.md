# DataDisplay V1 Installer

## Overview
The DataDisplay V1 Installer project is designed for the ESP32 CYD ESP32-2432S028 platform. This project utilizes the LovyanGFX library to manage a TFT display with touch functionality. The main goal of this project is to provide a simple interface for displaying data on the screen and interacting with it through touch input.

## Project Structure
```
DataDisplay-V1-instalator
├── src
│   ├── main.cpp          # Entry point for the application
│   └── lgfx_2432s028.hpp # Header file for the LGFX class
├── lib
│   └── README            # Documentation for libraries used
├── include
│   └── README            # Documentation for additional header files
├── test
│   └── README            # Documentation for testing framework
├── platformio.ini        # PlatformIO configuration file
└── README.md             # Project documentation
```

## Setup Instructions
1. **Install PlatformIO**: Ensure you have PlatformIO installed in your development environment.
2. **Clone the Repository**: Clone this repository to your local machine.
   ```
   git clone https://github.com/lachimalaif/DataDisplay-V1-instalator.git
   ```
3. **Open the Project**: Open the project folder in your IDE with PlatformIO support.
4. **Install Dependencies**: PlatformIO will automatically install the required libraries specified in the `platformio.ini` file.
5. **Compile the Project**: Use the PlatformIO build command to compile the project.
6. **Upload to ESP32**: Connect your ESP32 device and upload the compiled firmware.

## Usage
- The `main.cpp` file contains the setup and loop functions necessary for initializing the display and handling touch input.
- The `lgfx_2432s028.hpp` file defines the LGFX class, which configures the display settings.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.