# Sensor Net
A sensor network for the home.

## High-level architecture
The anticipated architecture is made up of four parts:
  * Sensor nodes
  * Gateways
  * Repository
  * Front-end

## Sensor Nodes
The sensor nodes are split into two modules: the controller including the radio and the sensor itself.

### Controller
Details about the controller can be found in a separate [repository](https://github.com/hannes-hochreiner/sensor-node-core).

### Sensors
There are two sensors breakout boards that are designed to work with the available controller:
  * [Temperature, humidity, and pressure sensor (BME-280)](https://github.com/hannes-hochreiner/sensor-node-bme280)
  * [Acceleration and magnetometer (LSM303AGR)](https://github.com/hannes-hochreiner/sensor-node-lsm303agr)

## Gateway
Details about the gateway can be found in a separate [repository](https://github.com/hannes-hochreiner/ism-gateway).

## Repository
Yet to be created.

## Front-end
Yet to be created.
