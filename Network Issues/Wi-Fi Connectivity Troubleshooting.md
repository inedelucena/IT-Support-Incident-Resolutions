# Incident Playbook: Wi-Fi Connectivity Troubleshooting

---

## 📝 Description

This playbook outlines the steps to diagnose and resolve common Wi-Fi connectivity issues for end-users.

## ❗ Symptoms

* User cannot connect to any Wi-Fi network.
* User is connected but has "No Internet Access."
* Slow or intermittent Wi-Fi connection.
* Wi-Fi adapter not detected.

## ⚙️ Troubleshooting Steps

1.  **Check Physical Switch/Key:**
    * Verify if the physical Wi-Fi switch (on laptops) or function key (Fn + Wi-Fi icon) is enabled.

2.  **Restart Router/Modem:**
    * Instruct the user to power cycle their Wi-Fi router and modem (unplug for 30 seconds, then plug back in).

3.  **Restart Device:**
    * Have the user restart their computer or mobile device. This often resolves temporary glitches.

4.  **Forget Network and Reconnect:**
    * Go to Wi-Fi settings, "forget" the problematic network, and then try to reconnect, entering the password again.

5.  **Check Wi-Fi Adapter Status (Windows):**
    * Open "Network and Sharing Center" > "Change adapter settings."
    * Ensure "Wi-Fi" adapter is enabled. If disabled, right-click and enable.
    * If missing, check Device Manager for driver issues.

6.  **Run Network Troubleshooter (Windows):**
    * Right-click the network icon in the system tray and select "Troubleshoot problems."

7.  **Renew IP Address (Windows Command Prompt):**
    * Open Command Prompt as Administrator.
    * Run `ipconfig /release`
    * Run `ipconfig /renew`
    * Run `ipconfig /flushdns`

8.  **Check DHCP Settings:**
    * Verify that the Wi-Fi adapter is set to obtain IP address automatically (DHCP).

9.  **Update Wi-Fi Drivers:**
    * Go to Device Manager, locate the Wi-Fi adapter, and try to update its driver. If issues persist, consider uninstalling and reinstalling the driver.

10. **Check for Interference:**
    * Suggest moving closer to the router or checking for other devices causing interference.

## ✅ Resolution

By following these steps, most common Wi-Fi connectivity issues can be resolved. If the problem persists, escalate to a network specialist or consider hardware failure.

## 🧰 Tools/Commands Used

* `ipconfig`
* Device Manager
* Network and Sharing Center
* Standard Wi-Fi settings in OS

## 🗒️ Notes

* Always confirm if the issue is isolated to one device or affects multiple devices.
* Verify the Wi-Fi password with the user.
* Consider asking about recent changes made to the network or device.
