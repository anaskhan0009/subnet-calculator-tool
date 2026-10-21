# Free Online Subnet Calculator — IPv4 CIDR, Network & Broadcast Address Calculator

A free **IPv4 subnet calculator** that runs instantly in your browser. Enter any IP address and CIDR prefix to get the **network address, broadcast address, subnet mask, wildcard mask, first and last usable hosts, total addresses and usable host count** — plus binary views and a plain-English networking basics guide.

**Live Demo:** https://anaskhan0009.github.io/subnet-calculator-tool/

## Features

- **Full subnet results** — network, broadcast, mask, wildcard mask, host range, total and usable hosts
- **CIDR ⇄ subnet-mask pickers** kept in sync — choose whichever form you have
- **Binary view** of the IP and its network address, for really *seeing* where the network/host split falls
- **IP classification** — private (RFC 1918), loopback, link-local, multicast or public
- **Correct edge cases** — /31 point-to-point links and /32 host routes handled the way network engineers expect
- **Quick presets** — home LAN /24, private /8, office /20, point-to-point /30
- **Quick-reference table** of common prefixes and a **Networking Basics** section explaining subnets, CIDR and the hosts = 2^(32−prefix) formula

## How to Use

1. Type an IPv4 address, e.g. `192.168.1.10`.
2. Pick the CIDR prefix (e.g. `/24`) or a subnet mask — results update as you type.
3. Read off the network address, broadcast address and usable host range for your configuration.

## Why Subnetting Matters

Subnetting divides one network into smaller, faster, safer segments: it limits broadcast traffic, lets you isolate guest Wi-Fi from office servers, and is a core skill for networking and cybersecurity certifications (Network+, CCNA, Security+). This calculator makes the math instant and — with the binary view and basics guide — actually teaches you what the numbers mean.

## Privacy

Everything runs locally in your browser. No IP address you enter is ever stored, logged or transmitted.

## Tech

Single self-contained `index.html` — HTML, CSS, vanilla JavaScript. No dependencies.

## Ethical Use

This is a **network-planning and learning tool** for networks you own or administer, and for certification study. Calculating subnets is a normal part of legitimate network administration and education.

## About

Built by **Dinal Studios** — digital agency for video editing, design, web & app development.
GitHub: https://github.com/anaskhan0009

*Keywords: subnet calculator, cidr calculator, ip subnet calculator online, network address calculator, broadcast address calculator, subnet mask calculator, how many hosts in a /24, ipv4 subnet calculator, subnetting practice*
