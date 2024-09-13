# Bluetooth Pentesting and Exploitation Guide

## Disclaimer

**This project is for educational purposes only.**  
All activities described in this documentation should only be carried out in environments where you have **explicit permission** to conduct testing. Unauthorized access, scanning, or exploitation of Bluetooth devices is **illegal** and can result in severe penalties. Please ensure you comply with all applicable laws and regulations in your jurisdiction before proceeding.

---

## Purpose

This documentation provides a comprehensive guide to exploring **Bluetooth** functionality on various devices (e.g., ECUs, smartwatches, mobile phones), with a focus on **reconnaissance** and **injection** activities.

### Covered Topics:
- Setting up and installing necessary tools
- Performing Bluetooth reconnaissance
- Injecting data into target devices
- Executing Denial of Service (DoS) attacks

---

## Bluetooth Classic Overview

**Bluetooth Classic** is a widely used wireless communication protocol for short-range data transmission. It is optimized for higher data throughput and continuous connection, making it ideal for applications that require ongoing data streaming.

### Key Features:
- **Higher energy consumption** compared to Bluetooth Low Energy (BLE).
- **Quick connection** establishment with continuous communication.
- **Supports fewer devices** compared to BLE, due to higher power usage.

---

## Initial Setup and Installations

### Things Achieved:
- **Bluetooth Service Scanning** and exploitation
- **Exploiting the OBject EXchange (OBEX) Service**
- **Exploiting OBEX - PBAP** to fetch Personally Identifiable Information (PII)
- **Performing a Denial of Service (DoS) attack**
- **Implementing CarWhisperer**
- **Ubertooth tool exploration**
- **Future scope** in Bluetooth testing

---

## Generalized Mitigations for Bluetooth Attacks

To prevent Bluetooth-based attacks, apply the following measures:

1. **Secure Pairing**  
   Implement modern pairing methods with passkeys or PIN authentication.

2. **Service Restrictions**  
   Whitelist only necessary services to limit access to critical ones.

3. **Data Validation**  
   Ensure data sanitization and validation, and use antivirus software.

4. **User Awareness**  
   Educate users on the risks of accepting unknown files and emphasize safe Bluetooth practices.

5. **Rate Limiting**  
   Implement rate-limiting to avoid resource exhaustion attacks.

6. **Connection Management**  
   Set timeouts for unresponsive connections and blacklist suspicious devices.

7. **Regular Updates**  
   Keep firmware and software up to date with the latest security patches.

8. **Traffic Monitoring**  
   Use Intrusion Detection Systems (IDS) to monitor Bluetooth traffic for abnormal activities.

9. **Enhanced Security**  
   Prefer secure, encrypted profiles and consider **Bluetooth Low Energy (BLE)** for added security.

---

## Tools and Technologies Used

- **OBEX**: For file exchange and exploiting data sharing vulnerabilities.
- **CarWhisperer**: For intercepting and injecting audio into Bluetooth car kits.
- **Ubertooth**: A tool for Bluetooth signal capture and analysis.
- **BlueToolkit**: A framework for scanning and testing Bluetooth vulnerabilities.

---

## References

- [GeeksForGeeks: Bluetooth](https://www.geeksforgeeks.org/bluetooth/)
- [Mankier: bt-obex](https://www.mankier.com/1/bt-obex)
- [Trifinite.org: CarWhisperer](https://trifinite.org/stuff/carwhisperer/)

