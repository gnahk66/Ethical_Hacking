# Lab environment and boundaries

[Back to portfolio](../README.md)

The source describes VirtualBox virtual machines separated using pfSense and named internal networks. Kali supplied security tools; Windows 10 served as a target and intermediate host; deliberately vulnerable web/Linux systems occupied the second segment. Later exercises added an Android lab target and a Mosquitto broker.

| Component | Role in the recorded exercises |
| --- | --- |
| Kali Linux | Scanning, traffic capture, web proxy and controlled test tooling |
| pfSense | Routing/filtering between lab segments and setup connectivity |
| Windows 10 | Target services, browser client, monitoring and dual-homed intermediate host |
| OWASP Broken Web Apps / DVWA / BodgeIt | Intentionally vulnerable application targets |
| Android lab device | APK analysis, controlled session and debugging exercises |
| Mosquitto | MQTT publication, subscription and permissive-access investigation |

The configuration evolved, and addresses changed between tasks. Do not treat one address observed in a screenshot as a stable inventory. `intnet` and `intnet2` are the source's network names; exact connectivity depends on interface attachments and configured routes/rules. A dual-homed host can undermine intended separation if broadly permitted to communicate on both sides.

## Conditions affecting interpretation

The targets intentionally used insecure settings. Some exercises disabled endpoint protection or enabled anonymous access. Windows was 32-bit in the HTTP availability exercise. These choices constrain what the results show about modern production systems.

The source does not provide a complete reproducible inventory of OS builds, tool versions, VM resources and snapshots. Those details are not invented here. The documentation preserves reported outcomes and identifies where further evidence is needed.

## Future lab record

Record each VM's version, interface attachment, address, routes, active services and security exceptions before testing. Keep vulnerable services on a dedicated lab network, retain clean snapshots and confirm recovery after disruptive work. Use only synthetic accounts and data.
