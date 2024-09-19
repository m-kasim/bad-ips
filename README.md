# Bad IPs

This repository contains a manually curated list of IP addresses involved in various **cyber attacks**, **abusive behavior**, and **spam activities**. These IPs have been gathered over time from multiple sources, including logs of attack attempts, abuse reports, and incidents of malicious activities observed on different systems.

## Purpose

The purpose of this repository is to provide a collection of malicious IP addresses for system administrators, security researchers, and other cybersecurity professionals. The list can be used to:
- Block or monitor incoming traffic from known malicious IPs.
- Study patterns in cyber attacks, abuse, and spam activities.
- Contribute to security tools and firewalls, such as **UFW**, **iptables**, or **fail2ban**.

## Usage

You can use the list in various ways to help secure your infrastructure:

1. **Firewall Blocking**: Add the IP addresses to your firewall rules (e.g., `iptables`, `UFW`, etc.) to prevent access from known bad actors.

    For example, using UFW:
   ```bash
    sudo ufw deny from 192.168.1.1 to any
    ```

3. **IDS/IPS Integration**: Integrate this list into your **Intrusion Detection Systems (IDS)** or **Intrusion Prevention Systems (IPS)** for real-time monitoring and blocking.

4. **Monitoring**: Use this list for continuous monitoring of incoming traffic to identify potential threats before they can cause harm.

## Format

The IPs are listed in plain text format, with one IP per line. This makes it easy to parse and integrate into scripts or security tools.

## Contribution

Feel free to contribute to this repository by submitting IP addresses that are confirmed to be involved in cyber attacks, spam, or abusive behavior. When submitting new IPs, please provide a brief description of the source or context in which the IP was identified as malicious.

## Disclaimer

This list is provided **as is**, with no guarantee of completeness or accuracy. The IPs listed may change in behavior over time, and some may no longer be involved in malicious activities. Always ensure that any IP you block is actually causing harm to your network to avoid false positives.
