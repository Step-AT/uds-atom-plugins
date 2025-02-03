# 🧩 UDS Atom - Plugins Open Source  

Bienvenue dans la collection de plugins **UDS Atom** ! 🎉  
UDS Atom est une application "on the edge" permettant de collecter et traiter des données industrielles.  
Ces plugins ajoutent des fonctionnalités de connectivité pour différents équipements et protocoles.  

## 📂 Liste des Plugins  

Les plugins sont classés en trois catégories :  

### 🟢 **Sourcers** (Acquisition des données)  
| Plugin | Description | Repo |
|--------|------------|------|
| **Modbus** | Récupère des données depuis des équipements Modbus TCP/RTU | [uds-atom-plugin-modbus](https://github.com/step-at/uds-atom-plugin-modbus) |
| **OPC UA** | Collecte de données depuis des serveurs OPC UA | [uds-atom-plugin-opcua](https://github.com/step-at/uds-atom-plugin-opcua) |
| **Siemens S7** | Communication avec des automates Siemens via S7 | [uds-atom-plugin-siemens-s7](https://github.com/step-at/uds-atom-plugin-siemens-s7) |

### 🔵 **Modules** (Traitements et calculs)  
| Plugin | Description | Repo |
|--------|------------|------|
| **Rules Engine** | Moteur de règles pour appliquer des logiques métier | [uds-atom-plugin-rules-engine](https://github.com/step-at/uds-atom-plugin-rules-engine) |
| **Formula Processor** | Exécute des formules type Excel sur les données | [uds-atom-plugin-formula](https://github.com/step-at/uds-atom-plugin-formula) |

### 🔴 **Pushers** (Envoi des données)  
| Plugin | Description | Repo |
|--------|------------|------|
| **MQTT** | Envoie les données vers un broker MQTT | [uds-atom-plugin-mqtt](https://github.com/step-at/uds-atom-plugin-mqtt) |
| **SCADA Connector** | Connecte UDS Atom à un SCADA | [uds-atom-plugin-scada](https://github.com/step-at/uds-atom-plugin-scada) |

---

## 🚀 **Comment utiliser un plugin ?**  
Chaque plugin est hébergé dans un dépôt indépendant.  
1. **Cloner le plugin souhaité**  
   ```bash
   git clone https://github.com/step-at/uds-atom-plugin-modbus.git
