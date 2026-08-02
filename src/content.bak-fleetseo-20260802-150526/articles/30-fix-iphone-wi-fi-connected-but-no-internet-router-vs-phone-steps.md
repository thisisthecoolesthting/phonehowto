---
title: Fix iPhone Wi-Fi connected but no internet — router vs phone steps
metaDescription: Fix iPhone Wi-Fi connected but no internet — router vs phone steps. Practical guide covering Fix iPhone Wi-Fi connected but no internet — router vs phon...
publishedAt: '2026-06-01'
updatedAt: '2026-06-01'
excerpt: Fix iPhone Wi-Fi connected but no internet — router vs phone steps
author: jordan-reyes
tags:
- iphone
- connected
- internet
- router
- phone
- steps
site: phonehowto
topic: 30. Fix iPhone Wi-Fi connected but no internet — router vs phone steps
tier: mvp
relatedProducts: []
status: published
keyTakeaways:
- Wi-Fi connected but no internet on iPhone often results from router configuration issues or iPhone network settings.
- Restarting or resetting the router can resolve many connectivity problems.
- Checking and adjusting iPhone network settings, like forgetting the network and renewing the lease, may fix device-specific issues.
- Using a methodical approach—starting with router steps and moving to phone steps—helps isolate the problem.
- Keeping software updated on both router firmware and iPhone iOS improves overall network reliability.
heroImage: /images/hero/30-fix-iphone-wi-fi-connected-but-no-internet-router-vs-phone-steps.jpg
---


If your iPhone shows it’s connected to Wi-Fi but there's no internet access, the issue could lie with your router settings or your phone itself. Knowing whether the problem stems from the router or the iPhone helps you troubleshoot efficiently and get back online faster.

## Key takeaways
- Wi-Fi connected but no internet on iPhone often results from router configuration issues or iPhone network settings.
- Restarting or resetting the router can resolve many connectivity problems.
- Checking and adjusting iPhone network settings, like forgetting the network and renewing the lease, may fix device-specific issues.
- Using a methodical approach—starting with router steps and moving to phone steps—helps isolate the problem.
- Keeping software updated on both router firmware and iPhone iOS improves overall network reliability.

## Understanding the Problem: Wi-Fi Connected But No Internet

When your iPhone connects to Wi-Fi but cannot access the internet, you can still see the network name and Wi-Fi symbol, yet web pages, apps, or online services fail to load. This discrepancy means your iPhone is successfully linked to the router but does not have a route to the internet. Such problems can stem from the router, the internet service provider (ISP), or the iPhone itself.

## Step 1: Diagnose Router-Related Causes

The router acts as the gateway between your home devices and the internet. If the router isn’t working properly, every device connected will fail to access external websites or services—even if they successfully connect to the Wi-Fi network.

### Basic router troubleshooting

- **Restart the router:** Power cycle the device by unplugging it from the power outlet, waiting 30 seconds, then plugging it back in. This clears temporary glitches.
- **Check other devices:** Determine if any other devices connected to the same Wi-Fi network can access the internet. If no devices work, the problem is likely with the router or ISP.
- **Verify internet service:** Confirm the ISP is not experiencing service outages through their status page (using mobile data or another network).

### Router settings to check

- **DHCP and IP allocation:** Ensure the router’s DHCP server is on and correctly assigning IP addresses to devices. If the iPhone has a conflicting or static IP, it may fail to reach the internet.
- **MAC filtering or access controls:** Some routers restrict internet access based on device MAC addresses. Make sure your iPhone is allowed.
- **Router firmware:** Outdated firmware can cause connectivity issues. Check for firmware updates on the router’s management interface.
- **DNS configuration:** Incorrect DNS settings can lead to no internet access despite Wi-Fi connection. Try switching to a public DNS such as Google DNS (8.8.8.8 and 8.8.4.4).

### When to reset the router

If basic restarts and setting checks don’t resolve the problem, a factory reset of the router can help. This will erase custom settings, so be prepared to reconfigure Wi-Fi credentials, port forwards, and other preferences.

---

## Step 2: Troubleshooting the iPhone

If your router is working correctly and other devices have internet access, the problem is likely with the iPhone’s network configuration or software.

### Forget and reconnect to Wi-Fi network

1. Go to **Settings > Wi-Fi** on your iPhone.
2. Tap the “i” icon next to the problematic network.
3. Select **Forget This Network**, then confirm.
4. Reconnect by selecting the network and entering the password.

### Renew the DHCP lease

Refreshing your IP address on the iPhone can fix connectivity:

- Open **Settings > Wi-Fi**.
- Tap the “i” next to your connected network.
- Scroll down and tap **Renew Lease**, then confirm.

### Toggle Airplane mode and Wi-Fi

- Swipe down to access Control Center.
- Toggle **Airplane Mode** on, wait 10 seconds, then turn it off.
- Toggle Wi-Fi off and back on.

This resets wireless radios and often resolves temporary stalls.

### Reset network settings on iPhone

If the issue persists, resetting network settings can clear corrupt configurations:

- Go to **Settings > General > Transfer or Reset iPhone > Reset**.
- Tap **Reset Network Settings**.
- Confirm and enter your device passcode.

Warning: This erases Wi-Fi passwords saved, VPN settings, and cellular preferences.

### Check for iOS updates

Bugs affecting Wi-Fi connectivity can be fixed in updates:

- Open **Settings > General > Software Update**.
- Install any pending updates.

### Disable VPN or proxy services

If you use VPN or proxies, these might block internet access despite Wi-Fi connection. Temporarily disable these apps and test connectivity.

---

## Router vs Phone Troubleshooting Checklist

| Troubleshooting Step                  | Router-Related Issue                    | iPhone-Related Issue                      |
|-------------------------------------|----------------------------------------|------------------------------------------|
| Restart device                      | Restart router power                    | Restart iPhone or toggle Airplane mode   |
| Check multiple devices             | Other devices fail internet too         | Only iPhone is affected                   |
| DHCP and IP address setting        | Router DHCP misconfigured               | Renew DHCP lease on iPhone                 |
| Firmware / iOS updates             | Update router firmware                   | Update iOS software                        |
| Wi-Fi credentials                  | Correct SSID and password configured    | Forget and reconnect to Wi-Fi network     |
| MAC filtering/access controls      | MAC filtering blocks device access      | Check if device is blocked by router      |
| VPN / Proxy interference            | Rare, usually router VPN settings       | Disable VPN or proxies on iPhone           |
| Reset to factory defaults          | Reset router if other steps fail        | Reset iPhone network settings if persistent|

---

## FAQ

### Why does my iPhone say Wi-Fi connected but no internet?

This usually means your iPhone successfully communicates with the router but cannot reach outside servers due to router configuration, ISP issues, or phone network settings.

### How do I know if the problem is with my router or iPhone?

Check if other devices connected to the same Wi-Fi can access the internet. If all devices fail, the router or ISP is the cause. If only the iPhone fails, the issue is likely on the phone.

### Will resetting network settings on iPhone fix Wi-Fi connected but no internet?

Resetting network settings often resolves corrupt or conflicting configurations on the iPhone but should be done as a last resort because saved networks and passwords are deleted.

### Can outdated router firmware cause internet issues on iPhone?

Yes, outdated or buggy router firmware can cause connectivity problems for all devices, including iPhones.

### What should I do if my router has no internet but Wi-Fi is working?

Restart your router, check the ISP status, and ensure DHCP settings are correct. If needed, reset the router to factory defaults or contact your ISP.

### Why does renewing the DHCP lease help fix no internet issues?

Renewing the DHCP lease forces the iPhone to request a new IP address and network configuration from the router, potentially fixing IP conflicts or expired leases blocking internet access.
