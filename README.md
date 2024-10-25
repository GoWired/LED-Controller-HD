# LED Controller HD

Welcome to the **GoWired LED Controller HD** repository! This repository hosts the open-source software and configuration files for the GoWired LED Controller HD, designed to deliver flexible, high-power, multi-channel LED control for both wireless and wired setups.

## Project Overview

The GoWired LED Controller HD is a robust, expandable controller suitable for residential and industrial use. It supports both **wireless communication** options through Tasmota or ESPHome, as well as a custom **GoWired-based firmware** for users who prefer wired setups.

### Key Features
- **Multi-channel LED control**: Precise control over multiple high-power LED channels.
- **Wireless communication**: Easy integration with Tasmota and ESPHome for seamless wireless operation.
- **Wired communication**: Our custom GoWired-based firmware offers a robust option for wired communication enthusiasts.
- **Open-source**: Software is licensed under **GPL 3.0**; hardware design is licensed under **CERN Open Hardware License**.

## Repository Structure

- `Tasmota_configs/`: Configuration files for Tasmota to set up and customize your wireless GoWired controller.
- `ESPHome_configs/`: YAML configuration files for ESPHome, tailored to the GoWired LED Controller HD hardware.
- `GoWired_firmware/`: Our custom firmware developed specifically for wired communication, based on the GoWired platform.
- `Docs/`: Detailed documentation on installation, configuration, and usage for both wired and wireless setups.
- `Examples/`: Example projects and sample code for integrating the controller.
- `Tests/`: Tests for validating code stability and performance.

## Hardware Repository

The hardware design files for the GoWired LED Controller HD are hosted separately and are licensed under the **CERN Open Hardware License v2**. Access the hardware files, including schematics, PCB layouts, and the BOM, in the [GoWired hardware repository on GitLab](https://gitlab.com/gowired/led-controller-hd).

## License

- **Software License**: The code in this repository is licensed under the **GNU General Public License v3.0 (GPL-3.0)**.
- **Hardware License**: Hardware designs are available under the **CERN Open Hardware License v2**.

## Firmware Options

- **Wireless (Tasmota and ESPHome)**: This repository includes configuration files for Tasmota and ESPHome, making it easy to set up the controller with popular wireless protocols. No need to fork; simply use these config files to integrate with your GoWired hardware.
- **Wired (GoWired Firmware)**: For wired setups, we offer a custom GoWired firmware. This option provides a reliable, wired communication alternative for advanced users.

## Contributing

We welcome contributions to improve the GoWired LED Controller HD! Here’s how to get started:
1. Fork this repository.
2. Create a branch for your feature or fix.
3. Submit a pull request with a detailed description of changes.

## Getting Started

1. Clone this repository.
2. Follow the setup instructions in the `docs/` folder.
3. Choose your preferred communication method:
   - For wireless setups, refer to `tasmota_configs/` or `esphome_configs/` for configuration files.
   - For wired setups, navigate to `gowired_firmware/` for the custom firmware.

## Support and Contact

For any questions, issues, or suggestions, please open an issue in this repository or reach out to us via email <hello@gowired.dev>.

Thank you for being a part of the GoWired project!
