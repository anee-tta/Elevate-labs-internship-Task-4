# Elevate-labs-internship-Task-4

A simple test to verify Windows Defender Firewall behavior by blocking inbound traffic on a specific port (Telnet, TCP 23).

### Objective

- Add a temporary rule to block inbound traffic on a port.
- Verify the block works.
- Remove the test rule and restore the original state.

### Environment

- OS: Windows (Defender Firewall).
- PowerShell (run as Administrator).
- Port tested: TCP 23 (Telnet).

### Steps

 1. Open Firewall.
 2. List current inbound rules.
 3. Create a test rule to block inbound TCP port 23.
 4. Test that the port is blocked on Powershell.
 5. Remove the test rule.
