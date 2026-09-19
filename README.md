# LED Resistor Protection Experiment

## Objective

To experimentally understand why a resistor is required in series with an LED and how it limits current.

## Circuit Comparison

### Circuit A — Without Resistor

**9V Power Supply → LED → Power Supply −**

Measured current: **1.14 A**

The current is extremely high compared with the typical safe LED current of around 20 mA. This can damage an LED in a real circuit.

### Circuit B — With 1 kΩ Resistor

**9V Power Supply → 1 kΩ Resistor → LED → Power Supply −**

Measured current: **7.05 mA**

The resistor significantly reduces the current through the LED, allowing it to operate safely.

## Results

| Circuit | Resistor | Measured Current |
| ------- | -------: | ---------------: |
| A       |     None |           1.14 A |
| B       |     1 kΩ |          7.05 mA |

## What I Learned

* An LED should not normally be connected directly to a 9V supply.
* A resistor limits the current flowing through the LED.
* Increasing resistance reduces current.
* The resistor helps protect the LED from excessive current.

## Engineering Lesson

**Voltage source → Current control → Component protection**

A resistor is a simple but important component used to control current in electronic circuits.

## Tools Used

* **Tinkercad Circuits** — circuit simulation
* **LED** — circuit component
* **Resistor** — current limiting
* **9V Power Supply** — circuit source
* **GitHub** — project documentation and version control
