[![Documentation Status](https://readthedocs.org/projects/donjonscaffold/badge/?version=latest)](https://donjonscaffold.readthedocs.io/en/latest/?badge=latest)

# Scaffold

Scaffold is an electronic motherboard designed for security evaluation of
integrated circuits and embedded platforms. The board can be controlled through
USB using the Python3 API, enabling easy automation of tests.

![Scaffold board pictures](docs/pictures/board-anim.gif)

The FPGA architecture runs at 100 MHz and embeds many peripherals:

- UART,
- I2C (master),
- ISO7816 (master),
- Power supply controllers for each evaluation socket,
- Delay and pulse generators with 10 ns resolution
- And more to come in the future!

The board also integrates an 11X analog amplifier with 200 MHz bandwidth for
power measurement. The on-board shunt resistor can be tuned from 0 to
100 Ohms.

Scaffold is able to operate from 1.5V to 3.3V devices: power supplies and I/O
bank voltage can be tuned thanks to adjustable voltage regulators. Scaffold can
be powered from USB or external power supplies.

Six special I/Os can generate 5V pulses, which are compatible with
*ALPhANOV PDM* laser sources (50 Ohm TTL).

## Documentation

API documentation is available on [Read the Docs](https://donjonscaffold.readthedocs.io).

## Licensing

Scaffold is released under GNU Lesser General Public Licence version 3 (LGPLv3).
See COPYING and COPYING.LESSER for license details.

