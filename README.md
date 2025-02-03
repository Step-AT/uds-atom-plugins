# 🧩 UDS Atom - Open Source Plugins

Welcome to the **UDS Atom** plugin collection! 🎉
UDS Atom is an "on the edge" application to collect and process industrial data.
These plugins add connectivity features for different devices and protocols.

## 📂 List of Plugins

Plugins are classified into three categories:

### 🟢 **Sourcers** (Data Acquisition)
| Plugin | Description | Repo |
|--------|------------|------|
| **Modbus TCP** | Retrieves data from Modbus TCP devices | [uds-atom-sourcer-modbus-tcp](https://github.com/step-at/uds-atom-sourcer-modbus-tcp) |
| **Modbus RTU** | Retrieves data from Modbus RTU devices | [uds-atom-sourcer-modbus-tcp](https://github.com/step-at/uds-atom-sourcer-modbus-RTU) |
| **OPC UA** | Collects data from OPC UA servers | [uds-atom-sourcer-opcua](https://github.com/step-at/uds-atom-sourcer-opcua) |
| **OPC DA** | Collects data from OPC DA servers | [uds-atom-sourcer-opcda](https://github.com/step-at/uds-atom-sourcer-opcda) |
| **Siemens S7** | Communication with Siemens PLCs via S7 | [uds-atom-sourcer-siemens-s7](https://github.com/step-at/uds-atom-sourcer-siemens-s7) |
| **SNMP** | Communication with Siemens PLCs via S7 | [uds-atom-sourcer-siemens-s7](https://github.com/step-at/uds-atom-sourcer-siemens-s7) |

### 🔵 **Modules** (Processing and calculations)
| Plugin | Description | Repo |
|--------|------------|------|
| **Trigger** | Rules engine to apply business logic | [uds-atom-module-trigger](https://github.com/step-at/uds-atom-module-trigger) |
| **Formula** | Executes Excel-like formulas on data | [uds-atom-module-formula](https://github.com/step-at/uds-atom-module-formula) |

### 🔴 **Pushers** (Sending data)
| Plugin | Description | Repo |
|--------|------------|------|
| **MQTT** | Sends data to a MQTT broker | [uds-atom-pusher-mqtt](https://github.com/step-at/uds-atom-pusher-mqtt) |
| **TimeScaleDB** | Connects UDS Atom to a TimeScaleDB Database | [uds-atom-pusher-tsdb](https://github.com/step-at/uds-atom-pusher-tsdb) |
| **InfluxDB** | Connects UDS Atom to an Influx Database | [uds-atom-pusher-influxdb](https://github.com/step-at/uds-atom-pusher-influxdb) |

---

## 🚀 **How ​​to use a plugin?**
Each plugin is hosted in an independent repository. 1. **Clone the desired plugin**
```bash
git clone https://github.com/step-at/uds-atom-plugin-modbus.git
```

2. Read the plugin's README.md to see how to install and use it.

## **How ​​to contribute?**
We encourage the community to contribute to plugins! 🎉

### 🛠 Steps to contribute
1. Fork the plugin repository
2. Create a branch for your modification:
```bash
git checkout -b feature-my-functionality
```

3. Make your modifications and test
4. Submit a Pull Request (PR)
👉 See our contribution guide: CONTRIBUTING.md

## 📩 Need help?
🔹 GitHub Discussions
🔹 Contact: contact@step-at.com

## ⚖ License
All plugins are under Apache 2.0 license.
UDS Atom and its basic building blocks remain proprietary.
