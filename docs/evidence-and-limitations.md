# Evidence standards and technical corrections

[Back to portfolio](../README.md)

These notes are based on the submitted PDF and its embedded evidence. No command was rerun against a target while preparing this repository. The original PDF remains the detailed private evidence record; most screenshots are not republished.

## How to read the task pages

**Observed/reported results** refer to evidence or descriptions in the portfolio. **Recommendations** describe proposed improvements. **Limitations** identify what cannot be concluded. Assessment status is kept separate from technical success: a completed academic task can include an unsuccessful experiment, and an unresolved status does not erase submitted work.

| Task | Correction or unresolved issue |
| --- | --- |
| 1.1P | Unconfirmed employment/certification claims excluded. |
| 2.1P | TTL, banners and timing are clues, not conclusive OS, exploitability or patch-age proof. |
| 2.2C | Website mirroring does not normally recover backend source; Ctrl+Z suspends a process. |
| 2.3D | Increased timeout allows more time for a response; firewall passage differs from a listening service. |
| 3.1P | Port exposure, SMTP support and software banners are not proof of exploitation. |
| 3.2C | Anonymous authentication and anonymous write permissions require different evidence. |
| 4.1P | SYSTEM access inherited the vulnerable service context; a separate escalation was not required. |
| 4.2D | Disabled antivirus prevents an evasion claim; starting token privilege needs clarification. |
| 5.1P | Promiscuous mode alone does not reveal all switched traffic; DNSSEC has validation/deployment conditions. |
| 5.2C | ARP baseline changes do not prove spoofing; the dnsspoof run did not establish successful redirection. |
| 5.3D | Injected packet capture does not establish execution or complete echo acknowledgement. |
| 6.1P | The slow HTTP attempt did not establish a connection; quantitative impact data are limited. |
| 6.2C | Curl 000 is not an HTTP status; ports 8000/8080 conflict; mitigation recovery was not measured. |
| 7.1P | A framework route does not automatically route every operating-system tool. |
| 7.2D | Legacy Silverlight policy, Flash policy and browser CORS are different mechanisms. |
| 8.1P | SQL login bypass is not a database dump; www-data is not root; challenge screenshots conflict. |
| 8.2C | POST alone does not prevent CSRF; upload acceptance is separate from execution. |
| 9.1P | Requested Android permissions do not prove runtime grants or unrestricted private-data access. |
| 9.2C | Menu numbering and the 2016 platform comparison are historical, version-bound observations. |
| 10.1P | Scan patterns do not alone prove hostile intent; cloud allocation is not customer ownership. |

## Better evidence for future work

For each finding retain the target/build, test time, relevant configuration, exact action, minimal output proving the result, observed identity and a separate impact statement. Capture failure evidence too. Availability tests need legitimate-client latency/errors and recovery measurements. Any remediation claim should include the change and a retest.

## Publication choices

Excluded the original full PDF, university task-sheet text, conversations, student identifier, identity-linked reconnaissance, passwords/hashes, APKs and generated executable payloads. The single debugger image was selected because it illustrates the investigation without publishing those materials. No broad claim that every hidden detail in the original PDF has been sanitised is made; the original is deliberately not distributed.
