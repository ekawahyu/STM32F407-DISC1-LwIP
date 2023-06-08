# STM32F407-DISC1-LwIP

## Hardware Requirement

This project uses DP83848 Ethernet extension board to get STM32F4 Discovery connected to the Internet. In case you do not own the hardware, it can be emulated with Renode.

## Software Requirement

- GCC ARM Embedded Toolchain, varies depending on your host OS.
- [STM32CubeMX](https://www.st.com/en/development-tools/stm32cubemx.html) v6.7.0 (with patch) to generate the Makefile project. Installation of STM32CubeMX is optional unless you need to regenerate the project.
- [Renode](https:///renode.io) installation is optional, in case you want to run it in emulator.
- [Visual Studio Code](https://code.visualstudio.com/download) installation is recommended. This project includes debugging support with Cortex-Debug extension in VSCode.

## Supported OS

Currently the firmware build support macOS, Linux, and Windows. In case you want to use Renode on Windows, the recommended installation is within WSL2 instead of native one.

## Getting Started

### Installing

Download or clone this repository to any location. Cloning instruction is as follows:

```
git clone https://github.com/ekawahyu/STM32F407-DISC1-LwIP
```

Change into STM32F407-DISC1-LwIP directory and build the firmware. For example, to build `tcp_echoserver` application, run the following:

```
make APP=tcp_echoserver
```

You are done! The binary will be available in `build` directory with the name of STM32F407-DISC1-LwIP.elf,bin,hex

## Deployment

### Actual STM32F4 Discovery

TBD

### Renode

TBD

## Contributing

Fork this repo and please do pull-request when you have made modification or improvement.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/ekawahyu/STM32F407-DISC1-LwIP/tags).

## Authors

* **Ekawahyu Susilo** - *Initial work* - [Eka](https://github.com/ekawahyu)

See also the list of [contributors](https://github.com/ekawahyu/STM32F407-DISC1-LwIP/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

We appreciate your opinion, both users and coders! When you made substantial contribution on this project, your name will show up here.

