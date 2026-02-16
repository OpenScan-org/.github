# OpenScan

## Overview
OpenScan is an open source photogrammetry 3D scanning ecosystem focused on affordable digitization of smaller objects.
It combines basic hardware components with open software and can achieve precise results. It is used by makers, researchers, and professionals.

OpenScan consists of community-driven open-source projects as well as DIY hardware kits and software maintained by [openscan.eu](https://openscan.eu).
This GitHub organization collects projects maintained by openscan.eu and by community contributors, covering software platforms, hardware designs, and supporting tools.
# Scanner devices

## Common scanner builds

| Build               | Maintainers | More details                                                                                                     |
| ------------------- | ----------- | ---------------------------------------------------------------------------------------------------------------- |
| OpenScan Mini v1    | openscan.eu | [Documentation](https://openscan-org.github.io/OpenScan-Doc/hardware/OpenScanMini/)                              |
| OpenScan Classic v1 | openscan.eu | [Documentation](https://openscan-org.github.io/OpenScan-Doc/hardware/OpenScanClassic/)                           |
| OpenScan Mini v2    | community   | [OpenScan-Design](https://github.com/OpenScan-org/OpenScan-Design/tree/main?tab=readme-ov-file#openscan-mini-v2) |
| OpenScan Midi v2    | community   | [OpenScan-Design](https://github.com/OpenScan-org/OpenScan-Design/tree/main?tab=readme-ov-file#openscan-mini-v2) |

**Important note:** openscan.eu maintains and supports only the v1 hardware kits and the corresponding reference parts lists for the builds listed above.
Please take care when choosing STL files and ordering parts, as not all components are cross-compatible.
For recent developments or questions, ask on the community channels (for example [Discord](https://discord.gg/eBdqtdkXyF) or [Reddit](https://www.reddit.com/r/OpenScan/)).

### Other builds, modifications and electronics
For additional builds, remixes, modifications, electronics and parts, see the [OpenScan-Design repository](https://github.com/OpenScan-org/OpenScan-Design).

## Firmware

| Firmware           | Status | Maintainers                              | Source code                                                     | Cross-platform      | Notes                                         |
| ------------------ | ------ | ---------------------------------------- | --------------------------------------------------------------- | ------------------- | --------------------------------------------- |
| OpenScan2          | stable | openscan.eu                              | [GitHub](https://github.com/OpenScan-org/OpenScan2)             | yes (web interface) | Ships with kits from openscan.eu              |
| OpenScan3          | alpha  | openscan.eu                              | [GitHub](https://github.com/OpenScan-org/OpenScan3)             | yes (web interface) | Active development, contributions welcome     |
| OpenScan Meanwhile | stable | community                                | [GitHub](https://github.com/stealthizer/OpenScan2/tree/2024-1o) | yes (web interface) | Good fit if you need broader hardware support |
| OpenScan Composer  | beta   | [Rhis](https://www.openscancomposer.com) | proprietary ([website](https://www.openscancomposer.com))       | Windows host        | Host-based processing for higher performance  |

## Documentation
Documentation for hardware and software from openscan.eu can be found here:
[OpenScan Documentation](https://openscan-org.github.io/OpenScan-Doc/)

Something missing or unclear?
Help improve the documentation by opening an issue on
[OpenScan-Doc](https://github.com/OpenScan-org/OpenScan-Doc/issues)
or by writing an email to
[info@openscan.eu](mailto:info@openscan.eu)
