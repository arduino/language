<img src="https://content.arduino.cc/website/Arduino_logo_teal.svg" height="100" align="right" />

Arduino Language
================

The Arduino Language is the de-facto standard for embedded programming on hundreds of architectures and hardware platforms. It is a domain-specific language implemented using a subset of the C++ syntax which makes it abstract enough to be ported to any other programming language.

The aim is to provide a full abstraction API over the lower level calls provided by the various platforms, standardizing the coding experience and promoting reusable content and examples that can be ported easily on any hardware.

The Arduino Language includes:

* the [core API]([ArduinoCore-API](https://github.com/arduino/ArduinoCore-API)), i.e. a set of built-in classes, functions and constants that all platform-specific implementations shall provide (see the [language reference](https://www.arduino.cc/reference/en/) for user-facing documentation - [sources](https://github.com/arduino/reference-en) here)
* the [Arduino official libraries](https://github.com/arduino-libraries) whose goal is to provide abstractions over the most used concepts, devices and data types

## How to contribute

* Join the [discussion](https://github.com/arduino/language/discussions) on the evolution of the language
* Inspect the existing official and third-party Arduino cores to spot inconsistencies or APIs that should be considered for standardization
* Inspect the existing official and third-party Arduino libraries to spot opportunities to make them more portable by extending the Arduino language over concepts that were not standardized yet
* Help us improving the [language reference](https://github.com/arduino/reference-en)
* Help us improving the unit testing coverage of the core API and the official libraries

## See also

* [Sketch specification](https://arduino.github.io/arduino-cli/dev/sketch-specification/)
* [Coding style guide](https://docs.arduino.cc/learn/contributions/arduino-library-style-guide)

## Credits

This project is maintained by the Arduino team with the help of the community. Please consider [donating](https://www.arduino.cc/en/donate/) or [sponsoring](https://github.com/sponsors/arduino) to support our work, as well as [buying original Arduino boards](https://store.arduino.cc) which is the best way to make sure our effort can continue in the long term for the benefit of the entire ecosystem that relies on the Arduino language and framework.
