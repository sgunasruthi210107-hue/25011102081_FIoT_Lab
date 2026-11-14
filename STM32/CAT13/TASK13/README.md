TASK 13
# CAT13 – BME Sensor Data Transmission Using MQTT

## Aim
To transmit environmental data acquired from the BME sensor to an MQTT broker.

## Objective
- Acquire environmental readings from the BME sensor.
- Establish Wi-Fi connectivity.
- Configure MQTT communication.
- Publish sensor readings to an MQTT topic.
- Verify the published data using an MQTT client or subscriber.

## Working Principle
1. Read environmental data from the BME sensor.
2. Connect the development board to Wi-Fi.
3. Establish a connection with the MQTT broker.
4. Publish sensor readings to the configured MQTT topic.
5. Verify the received messages.

## System Architecture

```text
BME Sensor
    |
    v
Microcontroller
    |
    v
Wi-Fi
    |
    v
MQTT Broker
    |
    v
MQTT Subscriber
```

## Circuit Diagram

![CAT13 Circuit Diagram](circuit.png)

## Result
Environmental data acquired from the BME sensor is successfully transmitted through MQTT and received by the subscriber.
