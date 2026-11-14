TASK 14
# CAT14 – BME Sensor Integration with Node-RED

## Aim
To integrate BME sensor readings with Node-RED using MQTT and visualize environmental data through a dashboard.

## Objective
- Acquire environmental data from the BME sensor.
- Publish sensor readings through MQTT.
- Subscribe to MQTT topics using Node-RED.
- Process incoming sensor messages.
- Display environmental readings through a Node-RED dashboard.

## Working Principle
1. Acquire environmental readings from the BME sensor.
2. Publish sensor values to an MQTT broker.
3. Configure Node-RED MQTT input nodes.
4. Receive and process sensor messages.
5. Display sensor readings using dashboard widgets.

## System Architecture

```text
BME Sensor
    |
    v
Microcontroller
    |
    v
MQTT Broker
    |
    v
Node-RED
    |
    v
Dashboard
```

## Circuit Diagram

![CAT14 Circuit Diagram](circuit.png)

## Result
BME sensor readings are transmitted through MQTT, integrated with Node-RED, and visualized using dashboard components.
