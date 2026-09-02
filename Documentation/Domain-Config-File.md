# Domain Configuration File

## Domain Details
- Domain name: NMG.com
- Domain Controller name: NMG-DC01
- Static IP address: 10.0.0.160
- Subnet mask: 255.255.255.0
- Default gateway: 10.0.0.1
- Preferred DNS server: 10.0.0.160
- DHCP: Disabled
- Date completed: 28/08/2026

## Verification
Domain controller diagnostics (dcdiag) ran successfully with all tests passed, including:
- Schema partition tests
- Configuration partition tests
- NMG partition tests
- Enterprise tests on NMG.COM (LocatorCheck, Intersite)

All tests returned "passed", confirming the domain controller is healthy and fully operational.
