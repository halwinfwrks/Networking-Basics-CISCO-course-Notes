# **Wireless Standards**

---

## **1. Wi-Fi Networks**

A number of standards have been developed to ensure that wireless devices can communicate. They specify the RF spectrum used, data rates, how the information is transmitted, and more. The main organization responsible for the creation of wireless technical standards is the **Institute of Electrical and Electronics Engineers (IEEE)**.

The **IEEE 802.11 standard** governs the **WLAN** environment. There are amendments to the IEEE 802.11 standard that describe characteristics for different standards of wireless communications. Wireless standards for LANs use the **2.4 GHz** and **5 GHz** frequency bands. Collectively, these technologies are referred to as **Wi-Fi**.

| Standard           | Max Speed | Frequency       | Band Range    |
| ------------------ | --------- | --------------- | ------------- |
| 802.11b            | 11 Mbps   | 2.4 GHz         | Medium        |
| 802.11a            | 54 Mbps   | 5 GHz           | Short         |
| 802.11g            | 54 Mbps   | 2.4 GHz         | Medium        |
| 802.11n            | 600 Mbps  | 2.4 GHz / 5 GHz | Long          |
| 802.11ac           | 1.3 Gbps  | 5 GHz           | Longer        |
| 802.11ax (Wi-Fi 6) | 9.6 Gbps  | 2.4 GHz / 5 GHz | Wide & Stable |

Another organization, known as the **Wi-Fi Alliance**, is responsible for testing wireless LAN devices from different manufacturers. The **Wi-Fi logo** on a device means that this equipment meets standards and should operate with other devices that use the same standard.

Wireless standards are constantly improving the connectivity and speed of Wi-Fi networks. It is important to be aware of new standards as they are introduced because manufacturers of wireless devices will implement these standards quickly in their new products.

---

## **2. Wireless Settings**

The **Packet Tracer Basic Wireless Settings** interface is shown in the figure. Wireless routers using the **802.11** standards have multiple settings that need to be configured. These settings include the following:

### **Network Mode**

The **802.11 protocol** can provide increased throughput based on the wireless network environment. If all wireless devices connect with the same **802.11 standard**, maximum speeds can be obtained for that standard. If the access point is configured to accept only one **802.11 standard**, devices that do not use that standard cannot connect to the access point.

A **mixed-mode wireless network environment** can include devices that use any of the existing Wi-Fi standards. This environment provides easy access for **older devices** that need a wireless connection but do not support the latest standards.

When building a wireless network, it is important that the wireless components connect to the appropriate **WLAN**. This is done using the **SSID**.

### **SSID (Service Set Identifier)**

The **SSID** is a **case-sensitive, alphanumeric string** that contains up to **32 characters**. It is sent in the header of all frames transmitted over the WLAN. The SSID is used to tell wireless devices, called **wireless stations (STAs)**, which WLAN they belong to and with which other devices they can communicate.

We use the **SSID** to identify a specific wireless network. It is essentially the **name of the network**. Wireless routers usually broadcast their configured SSIDs by default. The **SSID broadcast** allows other devices and wireless clients to automatically discover the name of the wireless network. When the **SSID broadcast is disabled**, you must manually enter the **SSID** on wireless devices.

Disabling **SSID broadcasting** can make it more difficult for legitimate clients to find the wireless network. However, simply turning off the **SSID broadcast** is not sufficient to prevent unauthorized clients from connecting to the wireless network. **All wireless networks should use the strongest available encryption to restrict unauthorized access.**
