# Lab 8: Firewalls and Intrusion Detection

Work with iptables filtering and Snort rules for traffic monitoring in the lab network.

## How It Works

The files include several firewall-rule sets, a reset script, Snort configuration, custom alerts, and a captured alert log. Rule conditions identify traffic by address, port, direction, and flags, while the alert output records matches for inspection.

## Main Tasks

- Compare the iptables policies and their filtering conditions.
- Inspect custom Snort rules and their identifiers.
- Read the alert log alongside the configuration and traffic rules.

## Files

- [shimate.rules](shimate.rules): packet-detection rule definitions.
- [iptables/flushRules.sh](iptables/flushRules.sh): shell commands for the lab configuration.
- [additional-rules.txt](additional-rules.txt): supporting lab file.
- [rules.txt](rules.txt): supporting lab file.
- [iptables/iptables1.txt](iptables/iptables1.txt): supporting lab file.
- [iptables/iptables2.txt](iptables/iptables2.txt): supporting lab file.
- [iptables/iptables3.txt](iptables/iptables3.txt): supporting lab file.
- [iptables/iptables4.txt](iptables/iptables4.txt): supporting lab file.
- [iptables/iptables5.txt](iptables/iptables5.txt): supporting lab file.
- [snort.alert.fast](snort.alert.fast): supporting lab file.
- [snort.conf](snort.conf): supporting lab file.
