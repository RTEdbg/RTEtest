### Supplementary library source code and example projects
```FreeRTOS-Plus/Source``` contains source code for additional FreeRTOS component libraries, as well as select partner provided libraries. These subdirectories contain further readme files and links to documentation.

```FreeRTOS-Plus/Demo``` contains pre-configured example projects that demonstrate the FreeRTOS kernel used with the additional FreeRTOS component libraries.

## Previous releases
[Releases](https://github.com/FreeRTOS/FreeRTOS/releases) contains older FreeRTOS releases.


## FreeRTOS Lab Projects
FreeRTOS Lab projects are libraries and demos that are fully functional, but may be experimental or undergoing optimizations and refactorization to improve memory usage, modularity, documentation, demo usability, or test coverage.

Most FreeRTOS Lab libraries can be found in the [FreeRTOS-Labs repository](https://github.com/FreeRTOS/FreeRTOS-Labs).

A number of FreeRTOS Lab Demos can be found in the [FreeRTOS Github Organization](https://github.com/FreeRTOS) by searching for "Lab" or following [this link](https://github.com/FreeRTOS?q=Lab&type=&language=) to the search results.

## coreMQTT Agent Demos
The [FreeRTOS/coreMQTT-Agent-Demos](https://github.com/FreeRTOS/coreMQTT-Agent-Demos) repository contains demos to showcase use of the [coreMQTT-Agent](https://github.com/FreeRTOS/coreMQTT-Agent) library to share an MQTT connection between multiple application tasks.

The demos show a single MQTT connection usage between multiple application tasks for interacting with AWS services (including [Over-the-air-Updates](https://docs.aws.amazon.com/freertos/latest/userguide/freertos-ota-dev.html), [Device Shadow](https://docs.aws.amazon.com/iot/latest/developerguide/iot-device-shadows.html),
 [Device Defender](https://docs.aws.amazon.com/iot/latest/developerguide/device-defender.html)) alongside performing simple Publish-Subscribe operations.
## CBMC

The `FreeRTOS/Test/CBMC/proofs` directory contains CBMC proofs.

To learn more about CBMC and proofs specifically, review the training material [here](https://model-checking.github.io/cbmc-training).

In order to run these proofs you will need to install CBMC and other tools by following the instructions [here](https://model-checking.github.io/cbmc-training/installation.html).
