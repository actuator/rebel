# Vulnerability Report: Pops Rebel Bluetooth Glucose Monitoring System

**Status:** FDA cleared

## Vulnerability Details

An unauthenticated remote attacker in BLE proximity can remotely aggregate unencrypted diabetic data from the **Pops Rebel Bluetooth Glucose Monitoring System** for users of Pops Rebel version 5.0 for Android. This vulnerability is classified as [CWE-319: Cleartext Transmission of Sensitive Information](https://cwe.mitre.org/data/definitions/319.html).

![Pops Rebel Glucose Monitoring System](https://github.com/actuator/pops/assets/78701239/58f2416c-17f0-408b-8254-1705b3fc0075)

### Vulnerability Evidence

Here are some images and details related to the vulnerability:



The static code analysis below depicts the correlation between the app source code and an actual BLE capture in Wireshark:

![Static Code Analysis](https://github.com/actuator/pops/assets/78701239/b6660541-cf16-4aa5-ba39-f3d8fcb32369)

This issue was reported to the vendor, **POPS! Diabetes Care Inc.**, in April 2023.

![Vendor Notification](https://github.com/actuator/pops/assets/78701239/7f57259b-b1ae-49c8-94e3-0f6cb6f0b002)

### Discoverer

The vulnerability was discovered by **Edward Warren**.

---
